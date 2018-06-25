## Benodigheden workshop
- Chrome / Safari / Firefox browser
- GitHub account, heb je dat nog niet maak dan [hier](https://github.com/join?source=header-home) een account  aan.

## Zet 2 public repositories met code in je GitHub account
Je kan natuurlijk zelf een nieuwe repository maken, in de workshop maken we een [fork](https://help.github.com/articles/fork-a-repo/) van twee public repos.

- [https://github.com/SSC-ICT-demo/training-assignments-simple](https://github.com/SSC-ICT-demo/training-assignments-simple)
- [https://github.com/SSC-ICT-demo/learnakka](https://github.com/SSC-ICT-demo/learnakka)

## Installeer BetterCodeHub
- Ga naar BetterCodeHub.com 
- Login met je GitHub account, accepteer de 'scopes'
- Je wordt welkom geheten op de my Repository page 


## Eerste 2 analyses
- druk op de Play knop van een van de repositories, daarna de ander
- de analyse zal starten en uw eerste rapport opent, blader door het rapport, zie de overall score en de guidelines.
- ga naar terug naar my repositories page en start de andere analyse

## Aanzetten Push en Pull Request integratie -- CI/CD integratie
Push en Pull request intergratie van BetterCodeHub zorgt ervoor dat de analyses gedraaid zullen worden bij elke 'commit' op de code. Als dit aangezet is dat is BetterCodeHub onderdeel van de CI/CD pipeline
- Ga naar de my repos page en druk op beide cards op het Pull request icoon links onder
- Omdat BetterCodeHub voor deze actie schrijfrechten nodig heeft in de repo krijgt u nu een additionele 'scope' vraag, accepteer ook deze.
- De melding volgt dat Push en Pull request is enabled
- Controleer de webhook door in GitHub.com/uwaccount te bekijken onder Settings > 

## Hello World Issue maken met BetterCodeHub
- [Issues](https://guides.github.com/features/issues/) zijn een prima manier om taken, verbeteringen en bugs in GitHub vast te leggen.
- Ga naar beide repos en enable de mogelijkheid om issues te maken. Ga daarvoor in de repo Settings > Options > Features en vink Issues aan.
- Ga daarna in BetterCodeHub.com naar de analyse van repository LearnAkka. Open Guideline 1: Short units of code en maak een issue van de candidate HelloWorld.java


## Hello World issue refactoren in GitHub
- Nadat het Issue aangemaakt is gaan we nu naar GitHub en gaan in de browser de code editten.
- Zoek in <> code tabblad via [find file] naar learnakka/gigi/src/main/java/com/learnakka/HelloWorld.java
- Klik op de file en gebruik de edit file functie (icoon naast de prullenbak) 
- Verwijder de extra duplicatie door de regels 7 - 35 te deleten.



