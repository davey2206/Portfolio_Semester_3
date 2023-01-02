# Learing Outcomes

| Outcome                         | Description                                                                                                                        |
| ------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| [Web application](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Learning_Outcomes.md#web-application) | You design and build user-friendly, full-stack web applications.                                                                   |
| [Software quality](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Learning_Outcomes.md#software-quality) | You use software tooling and methodology that continuously monitors and improve the software quality during software development.  |
| [Agile method](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Learning_Outcomes.md#agile-method) | You choose and implement the most suitable agile software development method for your software project. |
| [CI/CD](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Learning_Outcomes.md#cicd) | You design and implement a (semi)automated software release process that matches the needs of the project context. |
| [Cultural differences and ethics](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Learning_Outcomes.md#cultural-differences-and-ethics) | You recognize and take into account cultural differences between project stakeholders and ethical aspects in software development. |
| [Requirements and design](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Learning_Outcomes.md#requirements-and-design) | You analyze (non-functional) requirements, elaborate (architectural) designs and validate them using multiple types of test techniques.|
| [Business processes](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Learning_Outcomes.md#business-processes) | You analyze and describe simple business processes that are related to your project.|
| [Professional](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Learning_Outcomes.md#professional) | You act in a professional manner during software development and learning. |

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Web application

Voor mijn individueel project heb ik een product gemaakt waarmee je een online cv kan aanmaken, bijhouden en bekijken. Dit project is gemaakt via een Distributed software architectuur. 

(Plaatje van architectuur)

En bestaat dus uit 4 applicaties.

- [front-end application made in vuejs](https://github.com/davey2206/MijnCV)
- [CMS application made in asp.net mvc](https://github.com/davey2206/MijnCV_CMS)
- [API application made in asp.net web api](https://github.com/davey2206/MijnCV_API)
- [API application made in asp.net web api user services](https://github.com/davey2206/MijnCV_User_Service)

Voor het Groepsproject moesten wij een web app maken om het parkeren bij een parkeer plaats te digitaliseren / automatiseren. 

Voor dit project heb ik grotendeels gewerkt aan de backend / API. Verder heb ik gewerkt aan front-end en backend van de bonnen pagina’s. Ook ben ik de Git master van het project en ben ik Scrum master geweest.

- [front-end application made in reactjs](https://github.com/davey2206/proftaak_s3_front-end)
- [API application made in asp.net web api](https://github.com/davey2206/Proftaak_S3_API)
- [front-end CMS application made in reactjs](https://github.com/ParKings-inc/ParKings.CMS.UI.React)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Software quality

#### Individual project

Voor het bijhouden van mijn software quality in mijn individueel Project voor ik testen uit gebaseerd op de acceptatiecriteria van mijn user stories. Ook heb ik Github actions toegevoegd aan mijn projecten die deze testen automatisch uitvoeren. Via Github actions wordt mijn project ook de gestuurd naar Sonarcloud hier kan ik belangrijke informatie zien over mijn projecten die mij helpen problemen verhelpen. 

![image](https://user-images.githubusercontent.com/39116329/208443794-3ad908ec-3b05-4c68-a9d3-4b57ed974a01.png)

#### Group project

Voor het groepsproject werken wij met code reviews en branch protection voor onze software quality. Hiermee kan niet zomaar iemand iets in de dev en master branches doen zonder dat de code eerst wordt na gekeken daar anderen mensen van de groep.

Ook blijf ik op te hoogten van nieuwen software technieken door onderzoek te blijven doen.
- [Google OAuth Research](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Research/Research_Google_login.md)
- [Docker Research](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Research/Research_Docker.md)
- [UX Research](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Research/UX_Research.md) 

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Agile method

Door het werken op een agile manier blijven wij flexibel zodat wij kunnen blijven focussen op wat op dat moment het belangrijks is. Zo blijft het project altijd verbeteren en kan het project makkelijk aangepast worden.

Bij ons groepsproject werken wij via de scrum methode hierbij hebben wij een scrum master die elke ochtend een stand up doet en elke middag een stand down zodat iedereen weet waar we mee bezig zijn en op welke punten we moeten focussen. Ook hebben wij elke sprint een oplevering bij de stakeholders en hierna een retrospective. Hiermee weten wij of we de goeden kant opgaan en waar we de komende sprint aan moeten werken.

Via de scrum methode werk je via User Stories die dan bij elke retrospective, stand up  en strand down worden besproken.

- [Individual Project](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/UserStories/UserStories_Individual_Project.md)
- [Group Project](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/UserStories/UserStories_Group_Project.md)

Voor het groepsproject houden wij onze user stories bij via jira en bij mijn individueel hou ik deze bij via Github projects.

![image](https://user-images.githubusercontent.com/39116329/208300196-d9845829-e3be-4843-a700-3bd6de33f1d9.png)
- [Git Projects Board](https://github.com/users/davey2206/projects/1/views/1)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

### CI/CD

Voor CI/CD van mijn project werk ik met Github Actions. Zodra ik een push doe naar de Github worden deze Actions uitgevoerd. De Actions builden de applicatie, voeren de testen uit, sturen een analyse door naar Sonarcloud en maken een docker image aan die naar mijn docker hub repositorie worden gestuurd.

![image](https://user-images.githubusercontent.com/39116329/210232013-e3c614b6-0acd-44a3-88ae-4b7fe86b880e.png)

Ook heb ik onderzoek gedaan naar docker om te leren wat het is en hoe ik het toevoeg aan mijn projecten.

- [Docker Research](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Research/Research_Docker.md)

Projecten met actions:
- [front-end application made in vuejs](https://github.com/davey2206/MijnCV)
- [CMS application made in asp.net mvc](https://github.com/davey2206/MijnCV_CMS)
- [API application made in asp.net web api](https://github.com/davey2206/MijnCV_API)
- [API application made in asp.net web api user services](https://github.com/davey2206/MijnCV_User_Service)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Cultural differences and ethics

Bij ons groeps project hebben wij te maken met kentekens en Google account informatie van onze gebruikers. Wij moeten met deze informatie op een ethische manier omgaan. Hiervoor slaan wij alleen de Google Subid op en hashen wij de kentekens van de gebruikers zodat niemand hier bij kan. Ook bij mijn eigen project ga ik op deze manier om met de Google informatie van mijn gebruikers.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Requirements and design

Bij ons groepsproject en ook bij mijn eigen project werken wij met user stories om de Requirements van de projecten bij te houden.

- [Individual Project](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/UserStories/UserStories_Individual_Project.md)
- [Group Project](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/UserStories/UserStories_Group_Project.md)

Ook hebben wij user vriendelijke ontwerpen gemaakt zodat iedereen makkelijk de app kan gebruiken. Hiervoor heb ik onderzoek gedaan naar UX design.

Designs:
- [Technical Designs](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Ontwerpen/Technical_design.md)
- [UI Designs](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Ontwerpen/UX.md)
- [UX Research](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Research/UX_Research.md) 

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Business processes

Voor business heb ik een paar business processen gemaakt. Voor het groepsproject heb ik het proces gemaakt van het parkeren zonder onze app en met onze app. Voor mijn eigen project heb ik het proces gemaakt voor het maken van een online cv zonder mijn app en met mijn app.

- [Business process model](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Ontwerpen/Business_Process.md)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Professional

Door middel van onderzoek naar onderwerpen die ik nodig heb voor mijn projecten blijf ik op te hoogten van de nieuwen technieken in de industrie. Hierdoor kan ik op een professionele manier over de onderwerpen praten tegen mijn groepsgenoten en stakeholders en zo kan ik bewusten beslissingen maken over het project.

- [Google OAuth Research](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Research/Research_Google_login.md)
- [Docker Research](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Research/Research_Docker.md)
- [UX Research](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Research/UX_Research.md) 
