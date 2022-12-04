# implementeer Google OAuth

## inhoud
- [Inleiding](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Research/Research_Google_login.md#inleiding)
- [Wat is Google OAuth](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Research/Research_Google_login.md#wat-is-google-oauth)
- [Voordelen en nadelen van OAuth](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Research/Research_Google_login.md#voordelen-en-nadelen-van-oauth)
- [Hoe implementeer je Google OAuth](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Research/Research_Google_login.md#hoe-implementeer-je-google-oauth)
- [Bronnen](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Research/Research_Google_login.md#bronnen)

## Inleiding

Voor mijn project van dit semester wou ik kunnen inlogen op mijn app met een Google account. hiervoor wou ik Google's OAuth microservice voor gebruiken. 
Door het gebruiken van deze service hoef ik zelf geen login te maken. Hiermee bespaar ik tijd en maak ik mijn app veiliger voor de gebruikers. Voordat ik kon beginnen met het implementeer van Google OAuth moest ik gaan onderzoeken wat Google OAuth precies is, wat de voor en na delen zijn van het gebruiken van Google OAuth.

## Wat is Google OAuth

OAuth is een internet standaart waarmee je kan inlogen met je Google, Facebook, Microsoft, enz account op een anderen websites bijvoorbeeld je eigen website.
OAuth geeft de maker van een website de kans om de gegevens van de gebruiker te gebruiken zonder dat de website het wachtwoord van de gebruiker weet.
Hiermee hou je de informatie van de gebruiker veilig en hoef je deze nergens op te slaan.

## Voordelen en nadelen van OAuth

### Voordelen voor de gebruiker
- De gebruiker hoeft minder wachtwoorden te onthounden.
- De gebruiker kan sneller een account aanmaken.
- informatie kan worden ge deelt tussen jou eigen accounts

### Nadelen voor de gebruiker
- Je hebt maar 1 wachtwoord voor meerderen websites inplaats van 1 per website. Hiermee breek je een van de regels om je accounts veilig te houden. Waardoor als je op 1 website wordt gehackt kan alles worden gehackt.
- Je data kan worden gedeelt op manieren die je niet door hebt.

### Voordelen voor de developer
- Je kan het gebruiken voor bijna alle applicaties.
- Redelijk simpel te implementeren met veel informatie en voorbeelden.
- Het is populair en veel groten bedrijfen gebruiken het.
- capaciteit voor veel gebruikers

### Nadelen voor de developer
- Er is geen overeenkomende formaat van de data tussen bedrijven die OAuth gebruiken.
- Als de Token wordt gestolen door een hacker heeft hij een tijdje toegang tot de data.

## Hoe werkt Google OAuth

Google OAuth kan op meederen manieren werken dit ligt aan de soort app die je wilt gebruiken. Voor mijn project gebruik ik een web app gemaakt in asp.net en deze werkt als volgt. Als een gebruiker wil inlogen redirect mijn app hun naar een Google URL. Via deze URL geeft mijn app informatie door over wat voor soort toegang wordt gevraagt. Google verwerkt te gegevens en laat de gebruiker inloggen en stuurt een authorization code terug. Met deze code kan mijn app een token aanvragen die ik dan weer kan gebruiken om toegang te krijgen bij een Gooogle API

![authorization-code](https://user-images.githubusercontent.com/39116329/203999336-b9f4633b-48e7-4dea-94b6-38642dde830e.png)

## Hoe implementeer je Google OAuth

### Google OAuth Credentials aanvragen
Voor het gebruiken van Google OAuth moet je eerst bij Google Credentials aanvragen. Dit doe je door de voglende stappen: 
1. Maak een Project aan in google cloud.
2. Ga naar APIs & services.
3. Ga naar de tap Credentials.
4. Druk op Create Credentials en dan OAuth client ID.
5. Vul hier de gegevens van jou app in en druk op create.

Met deze Credentials krijg je 2 codes

1. Client ID
2. Client Secret

Deze codes heb je nodig voor het implementeren van de Google OAuth in jou applicatie.

### implementeren in ASP.net

Om Google OAuth te implementeren in asp.net moet je een project aanmaken met Authenication type: individual accounts. deze kan je installen bij het aanmaken van een applicatie.

![image](https://user-images.githubusercontent.com/39116329/205499542-14f73396-c852-4740-93d5-e9e60b31e114.png)

Deze Authenication type kan je ook later toevoegen door de template via de console te installeren in jou applicatie. Als je dit doet moet je wel uitkijken dat hij de HomeController, Hove Views en layout files van jou project vervangt. Heb hier dus een backup van.

Installeer via NuGet de authentication package van google.

![image](https://user-images.githubusercontent.com/39116329/205501074-91c1d31b-4e39-4745-bd4c-2638c7b64a65.png)

Hierna kun je de secrets die je van Google hebt ontvangen toevoegen aan jou project. dit doe je via de command line met deze commands:
1. dotnet user-secrets set “Authentication:Google:ClientId” “client-id”
2. dotnet user-secrets set “Authentication:Google:ClientSecret” “client-secret”

Deze commands voegt deze line code toe aan je secrets.json

![image](https://user-images.githubusercontent.com/39116329/205500462-0ec7799b-f6e7-4292-9eca-410f77c4adf2.png)

Verder moet je nog in je Program.cs deze regels code toevoegen en ASP.net doet de rest.

![image](https://user-images.githubusercontent.com/39116329/205501339-a5c9ef16-65fe-4541-88bc-a3c68cd3f992.png)

Nu kun je inlogen met je Google Account en de login pagina kan je later nog veranderen naar wat je nodig hebt.

![image](https://user-images.githubusercontent.com/39116329/205501428-e67dbe22-2cfc-47ca-b08d-d0d584ac374b.png)
![image](https://user-images.githubusercontent.com/39116329/205501443-e7fdfd26-6714-4aee-a187-d9143753bf9a.png)


## Bronnen
- https://developers.google.com/identity/protocols/oauth2
- https://blog.matrixpost.net/using-googles-oauth-2-0-api-for-an-asp-net-core-web-app
- https://learn.microsoft.com/en-us/aspnet/core/security/authentication/social/google-logins?view=aspnetcore-7.0
- https://fusebit.io/blog/google-oauth/?utm_source=www.google.com&utm_medium=referral&utm_campaign=none
- https://www.tsts.com/blog/pros-cons-of-using-facebook-or-google-for-logins/
- https://stfalcon.com/en/blog/post/oauth-2.0
