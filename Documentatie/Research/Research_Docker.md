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
Docker is een open plantform voor het Ontwikkelen, leveren, en draaien van applicaties. Docker helpt je met het scheiden van je infrastructuur zodat je snel je producten kan leveren. Docker doet dit door jou applicaties in een geïsoleerde omgevingen genaamt containers te zetten. Deze containers kan een host dan gebruiken om jou applicaties te draaien. Je kan Docker voor meerderen dingen gebruiken:
- Snelle levering van jou applicaties.
- Het responsieve deployment en het schaalen van jou applicaties.
- Meer dingen draaien op de zelfde hardware.

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

voor dat je docker kan installeren in een van jou projecten moet je docker desktop downloaden en installeren. Hiermee kan je je Images en containers bijhouden en draaien. Het installeren van docker in jou project is anders per framework die je gebruikt voor mij moest ik het maken voor ASP.NET en Node.js.

### ASP.NET
een Image en een container aan te maken in ASP.net via Visual Studio 2022 is heel simple hier zijn de stappen die je moet doen.

- 1 Druk rechter muisknop op jou project
- 2 Druk op add en dan Docker Support

![image](https://user-images.githubusercontent.com/39116329/206902670-49e375ed-30c1-4805-a5ac-9d63d5aad9ee.png)

- 3 dit maakt automatisch een Dockerfile aan met alle commands die je nodig hebt

![image](https://user-images.githubusercontent.com/39116329/206902884-96408d56-8fc3-4ac1-8e1b-1f9f43370c62.png)

- 4 Hierna kan je hem publishe naar Docker Hub door deze stapen:

![image](https://user-images.githubusercontent.com/39116329/206902974-6afe250b-a955-4f21-be08-5458d7582e27.png)
![image](https://user-images.githubusercontent.com/39116329/206903049-1b75c3fd-11a6-4cc0-9a1c-5089c6cd9034.png)
![image](https://user-images.githubusercontent.com/39116329/206903079-ffb8b2c1-6a31-45f5-bfc7-c5d840fe98e1.png)
![image](https://user-images.githubusercontent.com/39116329/206903108-71c73bff-2c7d-4d44-ae51-542a0e3ee2ce.png)

Verder kan je nog Docker-compose toevoegen voor het toevegen van meerderen containers hier kom ik bij het MSSQL gedeelte op terug.

### Node.js

### MSSQL

## Hoe voeg je automatisch testen toe

## Bronnen
- https://www.docker.com/
- https://docs.docker.com/get-started/overview/
- https://docs.docker.com/docker-hub/builds/automated-testing/
- https://www.ibm.com/cloud/learn/docker
- https://learn.microsoft.com/en-us/aspnet/core/host-and-deploy/docker/building-net-docker-images?view=aspnetcore-6.0
- https://learn.microsoft.com/en-us/visualstudio/containers/overview?view=vs-2022
