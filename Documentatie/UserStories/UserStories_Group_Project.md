# User stories group project

## User story 1 : Een parkeergarage bezoeker kan zichzelf identificeren.
### Omschrijving

Als parkeergarage bezoeker wil ik mijzelf bij de poort kunnen identificeren zodat de poort voor mij geopend kan worden.

### Acceptatiecriteria

- Een parkeergarage bezoeker kan zich identificeren door de benodigde identificatiegegevens in te voeren
  - Deze identificatiegegevens bestaan uit:
    - User ID 0auth google (naam & e-mailadres) (automatisch)
    - Kenteken voertuig (De gebruiker kan meerdere voertuigen aan zijn account toevoegen)
    - locatie/parkeergarage
      - Een parkeergarage bezoeker kan aangeven bij welke garage hij of zij staat door de garage te selecteren in een drop down.
- Na een succesvolle identificatie gaat de poort open
- Na een onsuccesvolle identificatie blijft de poort gesloten en krijgt de bezoeker de kans om opnieuw zich proberen te identificeren

### Definition of ready

Werkomgeving is opgezet, architectuur is uit geplanned.

### Definition of done

Alle acceptatiecriteria punten zijn functioneel.

------------------------------------------------------------------------------------------------------------------------------------------------------------

## User story 2 : Een parkeergarage bezoeker kan inzien hoeveel vrije plaatsen er zijn.
### Omschrijving

Als parkeergarage bezoeker wil ik een overzicht zien met beschikbare plaatsen zodat ik kan zien hoeveel vrije plaatsen er zijn.

### Acceptatiecriteria

- De parkeergarage bezoeker moet het totaal aantal plaatsen kunnen zien.
- De parkeergarage bezoeker moet het totaal aantal beschikbare plaatsen kunnen zien.

### Definition of ready

x

### Definition of done

Alle acceptatiecriteria punten zijn functioneel.

------------------------------------------------------------------------------------------------------------------------------------------------------------

## User story 3 : Een parkeergarage bezoeker kan parkeerinformatie in zien.
### Omschrijving

Als parkeergarage bezoeker wil ik mijn parkeerinformatie (parkeertijd, kosten, etc) kunnen inzien zodat ik bewust wordt van de bijbehorende informatie van mijn bezoek.

### Acceptatiecriteria

- De parkeergarage bezoeker kan de berekende parkeertijd inzien.
- De parkeergarage bezoeker kan het huidige parkeertarief inzien.
- De parkeergarage bezoeker kan de berekende betaalkosten inzien.
- De parkeergarage bezoeker kan zijn of haar aankomsttijd inzien.
- De parkeergarage bezoeker kan zijn of haar vertrektijd inzien.
- De parkeergarage bezoeker kan zijn of haar geschiedenis inzien. (1 week)


### Definition of ready

x

### Definition of done

Alle acceptatiecriteria punten zijn functioneel.

------------------------------------------------------------------------------------------------------------------------------------------------------------

## User story 4 : Een parkeergarage bezoeker kan betaalkosten inzien en betalen.
### Omschrijving

Als parkeergarage bezoeker wil ik mijn betaalkosten kunnen inzien en betalen zodat ik bewust ben van hoe duur mijn bezoek was en uit de parkeergarage gelaten kan worden.

### Acceptatiecriteria

- De bezoeker krijgt de te betalen kosten te zien aan het eind van zijn/haar bezoek.
  - Het systeem houd rekening met verschillende tarieven op verschillende tijden.
  - Tenzij een tariefverandering van te voren gedefinieerd was betalen geparkeerde autos nog het oude tarief.
  - Het systeem houd rekening met de maximum dag prijs van een garage
- De bezoeker krijgt te zien hoelang hij/zij heeft geparkeerd.
- De bezoeker kan betalen via mollie.
- De bezoeker betaalt het bedrag waardoor de slagboom omhoog gaat.


### Definition of ready

x

### Definition of done

Alle acceptatiecriteria punten zijn functioneel.

------------------------------------------------------------------------------------------------------------------------------------------------------------

## User story 5 : Een parkeergarages bezoekers benodigde persoonlijke gegevens worden opgeslagen
### Omschrijving

Als parkeergarage bezoeker wil ik dat mijn [persoonlijke] gegevens opgeslagen worden zodat ik deze niet later opnieuw in hoef te vullen.

### Acceptatiecriteria

- De parkeergarage bezoeker kan zijn gegevens invullen/worden opgehaald.
  - UserId(geregeld door 0auth)
  - Kentekens (een persoon kan meerdere autos hebben)
- Het systeem controleert of dat deze gegevens geschikt zijn.(0auth/scanner)
- De parkeergarage bezoekersgegevens (kenteken) worden opgeslagen. (kenteken koppeling aan SubID)


### Definition of ready

Werkomgeving is opgezet, architectuur is uit geplanned.

### Definition of done

Alle acceptatiecriteria punten zijn functioneel.

------------------------------------------------------------------------------------------------------------------------------------------------------------

## User story 6 : Een parkeergarage bezoeker kan overzicht van zijn of haar reserveringen inzien
### Omschrijving

Als parkeergarage bezoeker wil al mijn reservering kunnen inzien zodat ik weet welke reserveringen ik gemaakt heb

### Acceptatiecriteria

- Er is een overzichtspagina met de bezoekers zijn of haar reserveringen

### Definition of ready

x

### Definition of done

Alle acceptatiecriteria punten zijn functioneel

------------------------------------------------------------------------------------------------------------------------------------------------------------

## User story 7 : 
### Omschrijving



### Acceptatiecriteria



### Definition of ready



### Definition of done



------------------------------------------------------------------------------------------------------------------------------------------------------------

## User story  : 
### Omschrijving



### Acceptatiecriteria



### Definition of ready



### Definition of done



------------------------------------------------------------------------------------------------------------------------------------------------------------

## User story  : 
### Omschrijving



### Acceptatiecriteria



### Definition of ready



### Definition of done



------------------------------------------------------------------------------------------------------------------------------------------------------------

## User story  : 
### Omschrijving



### Acceptatiecriteria



### Definition of ready



### Definition of done



------------------------------------------------------------------------------------------------------------------------------------------------------------

## User story  : 
### Omschrijving



### Acceptatiecriteria



### Definition of ready



### Definition of done



------------------------------------------------------------------------------------------------------------------------------------------------------------

## User story  : 
### Omschrijving



### Acceptatiecriteria



### Definition of ready



### Definition of done



------------------------------------------------------------------------------------------------------------------------------------------------------------
