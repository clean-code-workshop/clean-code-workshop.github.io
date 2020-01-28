## 1. Benodigheden workshop
- Chrome / Safari / Firefox browser
- GitHub account, heeft u dat dat nog niet maak dan [hier](https://github.com/join?source=header-home) een account  aan.

## 2. Zet twee public repositories met code in je GitHub account
Je kan zelf een nieuwe repository maken, in de workshop maken we een [fork](https://help.github.com/articles/fork-a-repo/) van twee public repos.

- [https://github.com/clean_code_workshop/training-assignments-simple](https://github.com/clean_code_workshop/training-assignments-simple)
- [https://github.com/clean_code_workshop/learnakka](https://github.com/clean_code_workshop/learnakka)

## 3. Installeer BetterCodeHub
- Ga naar [BetterCodeHub.com](https://BetterCodeHub.com)
- Login met je GitHub account, accepteer de public 'scopes'
- Je wordt welkom geheten op de my Repository page 

## 4. Eerste analyses
- druk op de Play knop van een van de repositories, daarna de ander, gebruik het not analysed filter om de repos te zien.
- de analyse zal starten en uw eerste rapport opent, blader door het rapport, zie de overall score en de guidelines.
- ga naar terug naar my repositories page en start de andere analyse

## 5. Aanzetten Push en Pull Request integratie -- CI/CD integratie
Push en Pull request intergratie van BetterCodeHub zorgt ervoor dat de analyses gedraaid zullen worden bij elke 'commit' op de code. Daarmee wordt BetterCodeHub direct een vooledig onderdeel van de CI/CD pipeline.
- Ga naar de my repos page en druk op beide cards op het Pull request icoon links onder.
- Omdat BetterCodeHub voor deze actie schrijfrechten nodig heeft in de repo krijgt u nu een additionele 'scope' vraag, accepteer ook deze.
- De melding volgt dat Push en Pull request is enabled
- Controleer de webhook door in GitHub.com/uwaccount/learnakka te kijken onder Settings > Webhooks.
- Het groene vinkje in GitHub geeft aan dat de webhook actief is.

## 6. Eerste Issue maken met BetterCodeHub
- [Issues](https://guides.github.com/features/issues/) zijn een de GutHub manier om taken, verbeteringen en bugs vast te leggen. (Een andere tool op dit gebied is Jira, hiermee heeft GitHub intergraties.)
- We gaan voor Learnakka de mogelijkheid om issues te maken activeren.
- Ga daarvoor in de repo Settings > Options > Features en vink Issues aan.
- Ga daarna in BetterCodeHub.com naar de analyse van repository LearnAkka. Open Guideline 1: 'Short units of code' zoek naar HelloWorld.java, klik erop zodat de code getoond wordt en klik in de rechter bovenhoek op create issue.
- Het issue wordt voorbereid in GitHub, u kunt het issue verrijken met meta-data en natuurlijk editen en saven!
- Het assignen van mensen die het issue moeten gaan fixen valt buiten de workshop, u gaat het issue namelijk zelf oplossen ;-)


## 7. Hello World issue oplossen dmv een Pull Request in GitHub
- Nadat het Issue aangemaakt is blijven we in GitHub.com en gaan in de browser de code van LearnAkka editten.
- Zoek in het <>code tabblad via [find file] naar learnakka/gigi/src/main/java/com/learnakka/HelloWorld.java
- Klik op de file en gebruik de edit file functie (pen icoon naast de prullenbak) 
- Verwijder een stukje code door specifiek de regels 7 tot en met 17 te deleten.
- In de commit changes onder in de pagina kiest u Create a new branch, verander eventueel de naam en druk [propose file change]
- Er opent een Pull request waar u informatie aan kan toevoegen, druk op Create Pull Request
- Als de webhook van #5 goed is aangezet dan zal BetterCodeHub gaan draaien 
- Na een kleine minuut zal in de Pull request een 'All checks have passed' sectie verschijnen
- Klik op Show All Checks 
- Bekijk het commentaar dat BetterCodeHub daar heeft geschreven...
- Klik op details en inspecteer het analyse rapport
- U ziet dat de guideline Write Short Units nu compliant is geworden, (het pijltje omhoog en de groene vink)
- Klik op de guideline en zie dat de HelloWorld.java candidate nu 22 lines of code lang is.
- Hoewel deze file een iets langer is dan de ideale 15, is de guideline nu wel gehaald.
- Druk op merge pull request en uw verbetering zal in de code base verwerkt worden
- Ga naar BetterCodeHub en bekijk de score van Learnakka.

## 8. Van een 9 naar een 10!
- Na stap 7 heeft uw code nu 9 van de 10 guidelines.
- Bekijk de guideline Write Code Once, deze is rood en nog niet niet compliant
- klik in het vakje voor 29 lines .. en merk op dat de voorspelling van het nieuwe profiel zal resulteren in een groene guideline
- Klik op de naam van de candidate en creeer een tweede GitHub issue
- zoek weer naar de file om nu de duplicatie volledig weg te halen
- doe dit door ook de regel 18 - 35 te deleten
- maak weer een branch en een Pull Request en zie de nieuwe score

## 9. Toon de score dmv een badge!
Nu de learnakka op alle guidelines compliant is gaan we een trotse badge plaatsen.
- Ga hiervoor naar BetterCodeHub, naar de my repos page en druk op het gear icon van Learnakka
- kopier uit de settings dialog het stukje code bij 'Grab your badge for markdown'
- Ga naar de readme.md van Learnakka op GitHub, plaats de file in edit mode en voeg uw eigen de code toe.
- Hier kan je direct op master committen ;-)
- bekijk uw trotse badge

## 10. Tutorial 2

- [How to build a modern CI pipeline DevOps Tutorial](https://medium.com/bettercode/how-to-build-a-modern-ci-cd-pipeline-5faa01891a5b)









