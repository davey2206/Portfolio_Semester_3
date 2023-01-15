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

![Project_Ar drawio (1)](https://user-images.githubusercontent.com/39116329/212539590-d395ca04-68a9-4788-a2de-d432a2c38d36.png)


En bestaat dus uit 4 applicaties.

- [front-end application made in vuejs](https://github.com/davey2206/MijnCV)
- [CMS application made in asp.net mvc](https://github.com/davey2206/MijnCV_CMS)
- [API application made in asp.net web api (Section service/ Pages service)](https://github.com/davey2206/MijnCV_API)
- [API application made in asp.net web api (User service/ Statistics service)](https://github.com/davey2206/MijnCV_User_Service)

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
- [API application made in asp.net web api (Section service/ Pages service)](https://github.com/davey2206/MijnCV_API)
- [API application made in asp.net web api (User service/ Statistics service)](https://github.com/davey2206/MijnCV_User_Service)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Cultural differences and ethics

Om op een ethisch manier te werken bij ons groepsproject hebben wij Ethische ontwikkelingsprincipes toegepast

#### Een applicatie moet voor iedereen werken

Om te zorgen dat iedereen onze applicatie kan gebruiken doen wij de volgende dingen:
- Onze applicatie volgt een goed UX design zodat iedereen de applicatie kan begrijpen en gebruiken. 
- Ook maken wij gebruik van Google login zodat iedereen gemakkelijk een account kan aanmaken en kan inlogen.

#### Een applicatie moet overall werken

Om te zorgen dat onze applicatie overall werkt doen wij de volgende dingen:
- Onze applicatie zijn gemaakt met ReactJS, Material UI en bootstrap hiermee maken wij onze applicatie responsief zodat je hem overal kan gebruiken.
- Ook wordt de data in onze app realtime geupdate en hebben wij onze applicatie a one page web app gemaakt zodat je nooit de pagina hoeft te vernieuwen.

#### Een applicatie moet de privé en veiligheid van de gebruiker respecteren

Bij onze applicatie hebben wij te maken met privé data van onze gebruiker en moeten gebruiker veilig kunnen inlogen hiervoor doen wij een paar dingen:
- We maken gebruik van Google OAuth 2.0 zodat wij zelf geen data hoeven opteslaan behalve de Google SubID.
- Door het gebruiken van Google OAuth is het inlogen voor de gebruiker ook veiliger als dat wij zelf een systeem zouden maken.
- Verder hebben wij te maken met kentekens van de gebruiker deze worden door ons systeem gehashed zodat we de gebruiker informatie privé en veilig houden.

Verder heb ik nog onderzoek gedaan naar cultuur veschillen in softwareontwikkeling.

- [Culturele verschillen in softwareontwikkeling](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Research/Cultural_differences.md)


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Requirements and design

Bij ons groepsproject en ook bij mijn eigen project werken wij met user stories om de Requirements van de projecten bij te houden.

- [Individual Project User Stories](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/UserStories/UserStories_Individual_Project.md)
- [Group Project User Stories](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/UserStories/UserStories_Group_Project.md)

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
