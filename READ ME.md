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
Dit is een vrij onhandig gekozen course, helaas. Ik had er verwachtingen bij dat ik wat meer met echt data aan de slag kon gaan en daar vervolgens formules op af kon gooien. Helaas was dit dus niet het geval en was het merendeel vrij wiskundig, iets wiskundiger dan ik had gedacht. Hierdoor snapte ik van een groot deel van de course eigenlijk vrij weinig. Het was ook algebra in plaats van wiskunde, dus net een tandje hoger nog dan wat je normaal gebruikt. Al met al heb ik wel alle toetsen gehaald, met moeite en meerdere keren proberen. De course werd aan de hand van filmpjes gegeven met elke week 2 of 3 quizes, waarvan alleen de laatste meetelt voor een punt. Voor bijna elk probleem is een spreadsheet gemaakt en de tests worden aan de hand van deze spreadsheets gegeven en uitgevoerd. 


Ik snap het nut wel in van de course, maar voor 40 uur is het te weinig om het te kunnen gebruiken, met alles opzoeken wat dat nou precies is.
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
De basis van Excel is natuurlijk de hoeveelheid formules die ze hebben, de course begint gelukkig makkelijk met het gebruik van average, min, max, correl en stdev, die je gewoon uit kan voeren en dan zie je het antwoord. Later in de course komen er moeilijkere formules voorbij die je aan de hand van log moet samenstellen en eigenlijk zonder Excel te lastig zijn om uit te rekenen. Een belangrijk onderdeel is natuurlijk het visualiseren van de data die je hebt, hiervoor is charting een van de belangrijkste en bekendste functies van Excel. Voor elke soort data is er wel een soort grafiek aanwezig. Tot slot kan je door middel van een ` (naast de 1) een formule in de cel weergeven zonder deze uit te voeren, een soort codeblock eigenlijk.
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
### Confusion Matrix
Een belangrijk onderdeel van data analysis is dat je aan de hand van oude informatie voorspellingen kan doen voor de toekomst. Om dit uit te leggen kan je de confusion matrix gebruiken. Er zijn hier 2 dingen die meetellen, wat is er voorspelt en wat is waarheid met elk van de twee dat deze positief of negatief kan zijn. Hiermee kan je achteraf zien of een voorspelling uitkwam. Gaf je aan dat de uitkomst van coin flip geen munt zou zijn, dan zou je True Negative scoren. Bij correct gokken van wel munt zou er True Positive uitkomen. Bij wel munt maar gokken voor geen munt, zou er False Positive uitkomen en bij wel munt gokken waar geen munt uitkomt False Negative. 

Op grote schaal kan je de confusion matrix bijvoorbeeld toepassen bij het achterhalen van kanker bij mensen, waardoor er bijvoorbeeld bespaard kan worden op de kosten van de tests naar of iemand het heeft.
___
### Monty Hall
Het Monty Hall probleem komt voort uit het Amerikaanse tv programma Let's make a deal, hierbij mogen deelnemers een van de drie deuren kiezen die voor hen staan. Een van deze deuren heeft een prijs en twee dus niet. De deelnemer kiest eerst een deur, bijv deur A. Vervolgens vertelt de presentator dat hij 1 deur openmaakt, waar niet de prijs achter zit, maar dit is niet jouw deur. Dus deur B gaat open, A en C zijn nog dicht. Vervolgens krijg je de kans om te mogen switchen. Blijf je bij je keus van deur A of stap je over naar deur C.

Begin van het spel is er een 1/3 kans om te winnen omdat je verder geen kennis hebt over de deuren. De presentator elimineert een van de deuren waar niets achter zit, dit kan nooit jouw deur zijn. Het is niet raar dat gedacht wordt dat de kans nu 50/50 is, omdat het gaat over 2 deuren. Echter is de kans nog steeds 1/3 dat de prijs achter deur 1 zit. De kans van de geopende deur verplaatst zich naar de nog niet geopende deur, dus wordt 2/3. 

Het gaat erom dat de deur die open gaat, precies uitgekozen is, want 2 deuren mogen niet geopend worden, degene die gekozen is en degene die de prijs heeft. De kans is groter dat de deur die gekozen is niet de prijs heeft dan wel, dus moet er in dat geval altijd de andere lege deur geopend worden. 

Voor meer info:
https://www.coursera.org/learn/analytics-excel/lecture/ibNmv/the-monty-hall-problem


