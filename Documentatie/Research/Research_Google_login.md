# implementeer Google OAuth

## inhoud
- [Inleiding](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Research/Research_Google_login.md#inleiding)
- [Wat is Google OAuth](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Research/Research_Google_login.md#wat-is-google-oauth)
- [Voordelen en nadelen van Google OAuth](https://github.com/davey2206/Portfolio_Semester_3/blob/main/Documentatie/Research/Research_Google_login.md#voordelen-en-nadelen-van-google-oauth)
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

Google OAuth kan op meederen manieren werken dit ligt aan de soort app die je wilt gebruiken. voor mijn project gebruik ik een web app gemaakt in asp.net en deze werkt als volgt. 

![authorization-code](https://user-images.githubusercontent.com/39116329/203999336-b9f4633b-48e7-4dea-94b6-38642dde830e.png)

## Hoe implementeer je Google OAuth

## Bronnen
- https://developers.google.com/identity/protocols/oauth2
- https://developers.google.com/identity/gsi/web/guides/overview
- https://learn.microsoft.com/en-us/aspnet/core/security/authentication/social/google-logins?view=aspnetcore-7.0
- https://fusebit.io/blog/google-oauth/?utm_source=www.google.com&utm_medium=referral&utm_campaign=none
- https://www.tsts.com/blog/pros-cons-of-using-facebook-or-google-for-logins/
- https://stfalcon.com/en/blog/post/oauth-2.0
