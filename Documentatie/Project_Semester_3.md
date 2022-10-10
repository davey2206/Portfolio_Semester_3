Project MijnCV.nl

Het idee voor mijn project dit semester is een website waar je een online cv op kan zoeken en een online cv aanmaken. Ook kan je de inhoud van de cv makkelijk aanpassen en je kan de lay-out met een paar opties aanpassen.

# Front-end project.
Het front-end project wordt de plek waar mensen cv`s kunnen opzoeken en bekijken. Mensen kunnen hier ook via een link een specifieke cv door sturen.

Het front-end project ga ik maken in de VueJS framework.

# Backend project.
Het backend project wordt de plek waar mensen een cv kunnen aanmaken en aanpassen. Mensen kunnen hun cv aanpassen door een paar verschillende dingen te doen.

Dingen die ze kunnen doen:

- Een lay-out kiezen uit een paar opties.
- De kleuren van de lay-out aanpassen.
- Teksten aanpassen.
- Plaatjes toevoegen als de lay-out het toelaat.

Het backend project ga ik maken het asp.net framework.

# API-project.
Het front-end project en het backend project gaan werken via een API-project. Waarbij het front-end project alleen dingen ophaalt en het backend project dingen kan opsturen die dan worden opgeslagen via de API in een database.

Dit API-project ga ik maken in .net.


# User stories

**US1:**  Als een bezoeker wil ik een cv kunnen opzoeken zo dat ik een cv kan bekijken.

**Acceptatiecriteria:**

- Een cv kunnen opzoeken.
- Cv`s kunnen bekijken.

**US2:**   Als een gebruiker wil ik een cv kunnen delen met anderen zodat ik deze makkelijk kan door sturen naar een werkgever.

**Acceptatiecriteria:**

- De link van de cv kunnen delen (momenteel alleen via de link van de browser).

**US3:**   Als een gebruiker wil ik een cv kunnen aanmaken zodat ik een online cv heb.

**Acceptatiecriteria:**

- Aanmaken van een cv.
  - Gegevens die je moet invullen tijdens het aanmaken
    - Naam van de cv
    - Email wordt automatisch ingevuld (zelfde als login)
- Per pagina secties kunnen toevoegen.
  - Gegevens die je kunt invullen (mogelijk per lay-out anders)
    - Lay-out kiezen
    - Titel (verplicht).
    - Paragraaf (niet verplicht).
    - Image (niet verplicht).
    - Positie (verplicht).
- Eerste versie 1 lay-out

**US4:**   Als een gebruiker wil ik mijn cv kunnen aanpassen zodat ik nieuwe informatie kan toevoegen of oude informatie kan aanpassen.

**Acceptatiecriteria:**

- Per pagina secties kunnen bewerken
  - Gegevens die je kunt (mogelijk per lay-out anders)
    - Lay-out kiezen
    - Titel
    - Paragraaf
    - Image
    - Positie



**US5:** als een gebruiker wil ik kunnen in logen zodat ik bij MijnCv controle panel kan

- Kunnen inloggen/registreren via google.
## Extra stories

**US6:**   Als een gebruiker wil ik de lay-out van mijn cv kunnen aanpassen zodat ik mijn cv unieke kan maken.

**Acceptatiecriteria:**

- Kleuren kunnen aanpassen (per lay-out anders welke secties je de kleuren kan aanpassen)

**US7:**   Als een gebruiker wil ik mijn cv kunnen uitprinten of kunnen opslaan als pdf zodat ik deze kan opsturen naar een werkgevers die geen online cv`s ontvangen.

**Acceptatiecriteria:**

- Website naar een pdf-bestand kunnen omzetten (vanuit de pdf-reader kan je printen).


# Ontwerpen

## Front-end project

![Start_Page drawio](https://user-images.githubusercontent.com/39116329/194814239-b69d076b-8088-4df8-bc4c-35dd7779649d.png)
![Home_page_cv drawio](https://user-images.githubusercontent.com/39116329/194814242-a0daa3c4-d9c0-43ac-a52d-4070282092ed.png)
![Menu](https://user-images.githubusercontent.com/39116329/194814243-67850d07-d0c6-4b42-b018-2b80f6df7c2e.png)

## Database ontwerp

![Database_Ontwerp](https://user-images.githubusercontent.com/39116329/194814199-476c230a-e0aa-4082-9735-1d0ef58a2e27.png)
