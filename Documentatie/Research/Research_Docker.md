# Docker research

## Inhoud
- [Inleiding](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Research/Research_Docker.md#inleiding)
- [Wat is docker](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Research/Research_Docker.md#wat-is-docker)
- [Hoe werk docker](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Research/Research_Docker.md#hoe-werk-docker)
- [Hoe installeer je docker in jou projecten](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Research/Research_Docker.md#hoe-installeer-je-docker-in-jou-projecten)
- [Hoe voeg je automatiche testen toe](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Research/Research_Docker.md#hoe-voeg-je-automatisch-testen-toe)
- [Bronnen](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Research/Research_Docker.md#bronnen)

## Inleiding
Voor het leerdoel CI/CD van semester 3 te halen wou ik gebruik maken van docker. Voordat ik hier mee kon beginnen moest ik eerst onderzoek doen naar wat docker is, hoe het werkt en hoe ik het toevoeg aan mijn projecten. Ook wou ik wat Software quality toevoegen aan mijn projecten door het gebruiken van het automatisch testen en deployment van docker.

## Wat is docker
Docker is een open plantform voor het Ontwikkelen, leveren, en draaien van applicaties. Docker helpt je met het scheiden van je infrastructuur zodat je snel je producten kan leveren. Docker doet dit door jou applicaties in een geïsoleerde omgevingen genaamt containers te zetten. Deze containers kan een host dan gebruiken om jou applicaties te draaien.

## Hoe werk docker

### Containers
Containers zijn veiligen en geïsoleerde omgevingen waar alles in staat om jou applicatie te draaien. Containers werken door het procesisolatie en virtualisatiemogelijkheden van de linux kernel. Deze mogelijkheden zorgen ervoor dat meerdere applicatie componenten de zelfde werkkracht kunnen delen van een besturingssysteem. Dit heeft meerderen voordelen.
- Het systeem heeft minder werkkracht nodig.
- Minder werk voor developers omdat je de containers maar 1 keer hoeft te schrijven en dan kan je ze overal gebruiken.
- Containers gebruiken minder opslag.

### Docker architectuur
Docker werkt op een client-server architectuur. De Docker client praat met de Docker daemon. Deze daemon buid, draait en deelt jou Docker containers. De Docker client en daemon kunnen op het zelfde systeem draaien of je connect een docker cleint aan een online daemon. De client en daemon praten met elkaar via een REST API.
![architecture](https://user-images.githubusercontent.com/39116329/206179475-cbf5b0aa-6391-4c5e-8d8a-f2063c66ebb6.svg)


## Hoe installeer je docker in jou projecten

## Hoe voeg je automatisch testen toe

## Bronnen
- https://www.docker.com/
- https://docs.docker.com/get-started/overview/
- https://docs.docker.com/docker-hub/builds/automated-testing/
- https://www.ibm.com/cloud/learn/docker
