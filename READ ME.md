## MOOC Kennisdeling 7 november 2019
___
### Introductie tot The Data Scientist's Toolbox
The Data Scientist’s Toolbox is een course die een goed begin opzet voor iemand die wilt beginnen met Data Science.
In de course wordt je uitgelegd hoe je je goed kunt gedragen binnen de community en hoe je er het beste in kunt vallen zonder al te veel af te wijken van de standaarden.

Je leert hoe mensen vragen stellen op forums en deze beantwoorden. Je leert dat als jij ergens vastloopt, dat er waarschijnlijk honderden, niet duizenden anderen ook zijn vastgelopen op dat punt, waardoor je altijd gebruik moet maken van je goeie vriend Google of forum archives als je met vragen zit. 

De course geeft aan hoe je bepaalde software download: R, Rstudio, R packages, Git en Git Bash. Git wordt veelal gebruikt om foldermanagement te doen, maar ook in de vorm van Github als versiebeheer. Hierbij kan je in een Command Line Interface (CLI) lokaal je Github repo bijhouden en zelfs bewerken (bestanden aanmaken/verwijderen). 

Aan de hand van Github kan je heel gemakkelijk aan versiebeheer doen, alleen of met meerderen, of je kunt toevoegingen geven aan een groter project. Veelal wordt daar Markdown gebruikt voor de documentatie, een manier om op een simpele manier tekst weer te geven zonder fancy tekstbestanden open te hebben. Herken je aan .md bestanden.

Tot slot de verschillende uitwerkingen (niet het goeie nederlandse woord sorry) waar je data science voor kunt gebruiken.
___
### Introductie tot Mastering Data Analysis in Excel

___
### Git Commands
Volgende commands komen naar voren:
- Git add . 	(toevoegen van bestanden)
- Git add –u	(updaten van bestandsnamen of verwijderde items)
- Git add –A 	(doet beide)
- Git commit –m “bericht” 	(voegt lokaal een opmerking toe aan repo)
- Git push 	(updaten van lokale commit naar github) 
- Git checkout –b naam 	(branche aanmaken, wanneer er teveel mensen in een repo zitten en je niet die versie wilt editen)
- Git branch 	(kijken in welke branche je zit)
- Git branche master 	(terug naar hoofd branch)
___
### Git Bash Commands
Met Git Bash kan je in de Command Line Interface (CLI) tussen mappen navigeren of deze aanmaken, aanpassen of verwijderen en zelfs programma’s opstarten

De volgende commands komen naar voren:
- pwd 	(zien waar je nu bent qua directories, zoals users/fern of users/fern/documenten/avans/project)
- clear 	(legen van de console, enkel tekst)
- ls 	(weergeven mappen en bestanden in de map waar je je nu bevindt)
- ls –a 	(geeft ook verborgen bestanden weer)
- ls –al 	(geeft extra informatie weer over de bestanden en mappen)
- cd x	(veranderen van map locatie, waar x de map is waar je heen wilt)
- cd 	(cd zonder toevoeging brengt je naar je home)
- cd ..	(cd met .. brengt je 1 map terug omhoog
- mkdir x 	(directory aanmaken, waar x de naam van de map is die je aanmaakt)
- touch 	(aanmaken van een leeg document)
- cp x	(kopiëren van een document)
- cp –r 	(kopiëren van mappen)
- rm 	(verwijderen van mappen en inhoud)
- mv	(verplaatsen of naam wijzigen)
- echo	(zegt gewoon wat je wilt dat het zegt: echo Hello World!
- date	(weergeeft de datum)
___
### Markdown (uitgelegd in Markdown)
- Headers kunnen gedaan worden met #, de meer # gebruikt worden de kleiner de header wordt
- Bullet lists met - , of
* Bullet lists met * 
- Lijnen onder tekst of headers met ___ of ---
- *Cursief*, **dikgedrukt** of ***allebei*** of ~~doorgestreept~~ ``code blok``
```
- *Cursief* **dikgedrukt** of ***allebei*** of ~~doorgestreept~~ ``code blok``
```
- Tabellen:
|kop 1 | kop 2 | kop 3 |
|-----------|-----------|-----------|
|tekst 1 | tekst 2 | tekst 3 |
|tekst 11 | tekst 22 | tekst 33|
```
|---|---|---|
|tekst 1 | tekst 2 | tekst 3|
|tekst 11| tekst 22| tekst 33|
```
___
### Soorten analyses
Descriptive
- Het beschrijven van de data set, je maakt nog geen beslissingen over de data. 
- Je geeft hier aan wat je ziet in de data zonder daar verder op in te gaan of verder op in te denken.
- Voorbeeld hiervan is weergave van een bevolking gesplitst in man en vrouw.

Exploratory
- Relaties vinden die je vooraf nog niet kende, maar nog niet zeggen dat ze volledig kloppen. Handig om in de toekomst verder in te spelen op de connectie.
- Wordt meestal niet als hoofdvraag gezien en ook liever niet gebruikt voor voorspellen en generaliseren. 
- Voorbeeld hiervan is kijken of verschillende delen van het brein oplichten (ahv foto’s van het brein) bij bepaalde events in het lichaam of van buitenaf. Enkel het kijken of er iets gebeurt, maar nog niet verder ingaan waarom iets gebeurt.

Inferential
- Het gebruiken van een studie of data van een kleine populatie naar een grote populatie.
- Gebruikt voor statistieken.
- Voorbeeld hiervan is vervuiling bij berekenen in heel Amerika op basis data uit ¼ van de provincies. 

Predictive
- Het gebruiken van data van x voor y. Belangrijk is hier dat wanneer x een voorspelling is van y, dat x niet gelijk y veroorzaakt.
- Het voorspellen op deze manier is heel lastig, al helemaal omdat het niet altijd accuraat is en niet waar hoeft te zijn.
- Een veel voorkomend voorbeeld hiervan is dat een supermarkt een vader benaderde dat haar dochter zwanger was terwijl hij dat nog niet wist.

Causal
- Het achterhalen van wat er gebeurt als je variabelen veranderd.
- Een gegeven voorbeeld hiervan is een studie naar hoe je lichaam reageert op het transplanteren van ontlasting tussen verschillende mensen, om zo de bacteriën in de dikke darm te beïnvloeden.

Mechanistic
- Inzicht krijgen in de exacte veranderingen van variabelen die leiden tot wijzigingen in andere variabelen voor individuele objecten.
___
### Handige functies
___
### Solver
Met de solver functionaliteit kan je gemakkelijk formules testen of automatisch laten uitrekenen. Door middel van een formule, een start bedrag en een hoeveelheid aan jaren kan je bijvoorbeeld uitrekenen hoeveel jaar het duurt om van €1000 naar €5000 te gaan met 7% rente per jaar. De solver rekent het precies uit tot in vele comma’s, wat exacter en sneller is dan het zelf uit te moeten rekenen.

Voorbeeld:
- Formule = D8*(1+C3)^C4
- 1000*(1+0,07)^10
- Met solver kan je een einddoel instellen voor y met als variabele het aantal jaren C4
- Dan vul je de juiste waarden in het pop up scherm
- En komt er 23,78 jaren uit

___
### Monty Hall


