# Individual

## Project Architecture

Mijn project is gemaakt op een Distributed software architectuur manier. Het project bestaat uit 4 applicaties, 1 database en een connectie met google OAuth 2.0.
2 applicaties zijn ASP.NET WEB API's deze hebben de volgende services:
- Section service: met deze service kan je de secties van een cv ophalen, aanmaken en bijwerken die op een pagina komen te staan
- Page service: met deze service kan je pagina's voor een cv ophalen, aanmaken en bijwerken.
- User service: met deze service kan je een user ophalen, aanmaken en bijwerken.
- Statistics service: met deze service kan je de views van een cv ophalen en bijwerken.

1 applicatie is gemaakt in ASP.NET MVC WEB APP. op deze applicatie kan de gebruiker een cv aanmaken en bijhouden. Ook kan de gebruiker hier de statistieken van hun cv hier zien. In deze applicatie moet de gebruiker inloggen voor dat hij deze kan gebruiken dit wordt gedaan via Google OAuth 2.0.

Ik voor ASP.NET gekozen omdat:
- ASP.NET web API is snel en makkelijk om op tezeten.
- ASP.NET web API is makkelijk uitbreidbaar.
- ASP.NET heeft een groten community die er mee werk dus je kan snel problemen oplossen.
- Met ASP.NET en XUnit kan je makkelijk unit testen op zetten.

De laatste applicatie is gemaakt in VueJS samen met Vue Router voor een single page web applicatie.

Ik heb voor Vuejs gekozen omdat:
- VueJS is Snel te leren en makkelijk te begrijpen.
- Door het gebruiken van VueJS components kan ik mijn verschillende layouts makkelijk aanroepen.
- VueJS heeft makkelijk te gebruiken for loops zodat ik mijn cv paginas automatisch kon opbouwen.

![Project_Ar drawio (1)](https://user-images.githubusercontent.com/39116329/212539524-0ba0375f-422c-4334-847f-0a975ed85a9d.png)


## Database design
### V1
![Database_Ontwerp](https://user-images.githubusercontent.com/39116329/201663979-c2f817f6-7d04-468c-9bfb-8bc1eed8cdc3.png)

### V2
![database design drawio](https://user-images.githubusercontent.com/39116329/212539307-e3d0b4d7-e5da-4891-b129-ff14636b41a1.png)


## Use case
![Use_case drawio](https://user-images.githubusercontent.com/39116329/203010235-20f8795d-c0d9-42a8-9363-4030c5d06be6.png)

# Group

## Project Architecture

Voor het groepsproject werken wij met 3 applicaties en 1 database. Hiervan zijn 2 applicaties een React.js project en 1 een ASP.NET Core web API project. 

We hebben voor React.js gekozen omdat:
- React is flexibel en kan voor veel verschillende applicaties worden gebruikt.
- In React kan je snel een werkende applicatie maken.
- Sammen met Material UI of vergelijkbaren extensies kan je snel en makkelijk een mooien applicatie maken.

We hebben voor ASP.NET Core web API gekozen omdat:
- ASP.NET web API is snel en makkelijk om op tezeten.
- ASP.NET web API is makkelijk uitbreidbaar.
- ASP.NET heeft een groten community die er mee werk dus je kan snel problemen oplossen.
- Met ASP.NET en XUnit kan je makkelijk unit testen op zetten.

Ook werken wij met Google OAuth 2.0 voor het inloggen van onze gebruiker. hiermee hoeven zij zelf geen inlog systeem te maken en is het makkelijker en veiliger voor onze gebruikers om in teloggen.

![image](https://user-images.githubusercontent.com/39116329/210232487-2b62aa64-be0b-4848-bae8-af9d132ed847.png)

## Database design
### V1

Hieronder zie je de eerste versie van ons database design. Ik had deze gemaakt gebaseerd op de eerste User Storys die wij moesten maken.

![ClassDiagram_Proftaak drawio](https://user-images.githubusercontent.com/39116329/212298669-7ae51f74-277f-494c-bbf9-458d526a57c3.png)

We moesten een User kunnen opslaan:
- Hiervoor had ik een tabel aan gemaakt met een ID en een SubID. Hiervoor hoefte wij alleen de SubID opteslaan van het Google account van de gebruiker.

Een gebruiker moest ook een auto kunnen toevoegen en zijn account.
- Hiervoor had ik de auto tabel toegevoegd hier kan een gebruiker het kenteken zijn auto opslaan.
- Ook kan een gebruiker meerderen auto hebben omdat somige gezinnen meerder autos hebben.
- Ook kan een auto meerderen gebruikers hebben om de zelfde reden.

We hadden Garages nodig waar een gebruiker kon parkeren.
- Hiervoor had ik de Garage tabel toegevoedt.
- Een gerage moest een openings en sluitings tijd hebben.
- Een gerage moest kunnen bijhouden of hij vol is.
- Een gerage had een naam.
- Een gerage had een prijs per uur.

Een gebruiker moest kunnen parkeren en een berekende prijs kunnen betalen.
- Hiervoor had ik de Parking tabel toegevoedt
- Deze hielt de aankomst en vertrek tijd bij.
- Ook hielt hij de berekende prijs de ge gebruiker moet betalen bij.
- Een parking hoorde bij een Garage en had een Auto die er op kon staan.

### V2

Hieronder zie je de 2e versie van ons database design. ik had de 2e versie gemaakt na de feedback van de stakeholders. deze versie is gebasseert op het hele geplende project inplaats van alleen de user storys waar we mee bezig waren. hierdoor hoefde we niet de heletijd de database aan tepassen.

![image](https://user-images.githubusercontent.com/39116329/202904190-f3a9cce1-eede-49f4-b2d8-78f2c61ff508.png)

#### Aanpassingen van V1 naar V2:

Parking tabel is nu verdeel over 3 tabelen:
- Reservations tabel deze houd bij wanneer een gebruiker in een garage is / wanneer hij verwacht is.
- Space tabel zijn alle plaatse die in een gerage zitten.
- Receipt is voor de berekende bon van de gebruiker.

De User tabel
- heeft een role kolom gekregen om te kunnen zien of het een admin of gebruiker is.

Gerage tabel
- Freespace is weg gehaalt en wordt nu berekent me de space tabel
- Price is opgesplits in NormalPrice en MaxPrice

Nieuw tabel Pricing
- Met deze tabel kunnen we speciale prijsen bij houden van een gerage.
- deze hebben een start en eind tijd en een prijs per uur.

Verder zijn alle prijsen veranderd naar Decimal inplaats van double. Dit heb ik gedaan omdat doubles niet heel accuraat zijn bijvoorbeeld een 1.1 kan in een double 1.09999999 worden. Dit wil je natuurlijk niet hebben als het gaat om prijzen hiervoor heb ik kort onderzoek gedaan naar wat het beeste is om te gebruiken hier kwam uit dat Decimal het nauwkeurigste waren voor de prijzen van onze applicatie. maar zelfs Decimal kan afrond problemmen krijgen bij bedragen boven de miljoenen. Omdat wij niet zoon hogen prijzen hoeven bij te houden is Decimal de beste optie voor ons.

### V3

Hieronder zie je de 3e en laatste versie van ons database design. Deze is gemaakt omdat er nog een paar kleine dingen miste in de vorge versie.

![ClassDiagram_Proftaak (1) drawio](https://user-images.githubusercontent.com/39116329/212302957-7e065f73-15ea-4b70-8bfa-a67bd63ec165.png)

#### Aanpassingen van V2 naar V3:

nieuwen tabelen
- Role tabel: in deze tabel zitten alle role die een user kan zijn.
- SpaceType tabel: in deze tabel zitten verschillende soorten parkeer pleken.
- SpaceStatus tabel: in deze tabek zitten alle statusen die een parkeer plek kan hebben

Pricing tabel
- nieuwe kolom Recurring: deze houd bij of een prijs elke week moet herhalen.

Space tabel
- Row kolom: houd de rij van de plek bij.
- TypeID kolom: deze houd het type van de plek bij via de SpaceType tabel.
- StatusID kolom: deze houd de status van de plek bij bia de SpaceStatus tabel.

User tabel
- Role kolom naar RoleID hiermee gebruikt de user de role van de Role tabel.

Reservations tabel
- nieuwe kolom Payment_Id deze kolom wordt door Mollie gebruikt om de betaling te maken.

