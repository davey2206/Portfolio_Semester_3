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
