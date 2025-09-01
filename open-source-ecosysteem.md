## Public Tech, een introductie

De samenleving digitaliseert in rap tempo. In steeds meer branches worden diensten zoveel mogelijk online aangeboden. Veranderende verwachtingen van de consument zorgen ervoor dat ook de overheid hierin niet achter kan blijven.

Bij verschillende overheden wordt dan ook geëxperimenteerd met het aanbieden van nieuwe digitale diensten. De software die hiervoor nodig is wordt in de meeste gevallen speciaal voor de overheid ontwikkeld en beheerd, veelal door private partijen. En alhoewel deze publieke voorzieningen worden betaald met publiek geld zijn het vaak black boxes, waarvan het intellectueel eigendom in handen komt van de ontwikkelaar.

Hierdoor zijn overheden voor wijzigingen aan de software volledig afhankelijk van de bereidheid van de leverancier om de aanpassingen door te voeren, en van diens planning en beprijzing. Overstappen naar een andere leverancier is kostbaar, of zelfs onmogelijk, omdat processen afgestemd zijn op en data gevangen zit in het systeem; de zogenaamde vendor lock-in.

In toenemende mate is er interesse in het ontwikkelen en gebruiken van open source software; code die controleerbaar is, die in samenwerking tot stand komt, en die vervolgens door iedereen aanpasbaar en herbruikbaar is.

Naast een verminderde afhankelijkheid van specifieke ICT-leveranciers, biedt open source ontwikkeling ook kansen voor het aanleggen van een gezamenlijke "bibliotheek" aan publieke code. Code die betaald is door iedereen, en die dus ook beschikbaar voor iedereen.

Dit kan zorgen voor lagere ontwikkelkosten, omdat het hergebruik van (deel)oplossingen mogelijk maakt, de kans op fouten verminderd, en leidt tot convergentie van gebruikte technieken. Dit laatste maakt ook een gedeelde infrastructuur en gezamenlijk beheer mogelijk.

Daarnaast biedt een open source ecosysteem de samenleving nieuwe mogelijkheden om hun relatie met de overheid vorm te geven. Meekijken is niet alleen mogelijk, het wordt actief aangemoedigd. Dat maakt discussies mogelijk over de regels die in software worden gegoten, en over de manier waarop informatie wordt bewerkt en opgeslagen. Ook stelt het de groeiende community van software-developers in staat de publieke digitale diensten van de overheid mee vorm te geven en te verbeteren, of zelf de maatwerk applicaties te creëren waar de overheid niet aan toekomt.

Dit kan een motor zijn voor de digitale transformatie van de overheid en de samenleving.

## Verschillende Rollen en Functies

In een open source ecosysteem voor overheids-software zijn er verschillende rollen en functies te onderscheiden. Verschillende aspecten van software-ontwikkeling kunnen hierbij door verschillende partijen worden opgepakt. Dit in contrast met vendor-software, waar al deze taken vaak bij één partij liggen.

### Hoofdaannemer

De hoofdaannemer krijgt opdracht een bepaalde tool of oplossing te realiseren. Er worden budget- en planningsafspraken gemaakt met de opdrachtgever. De eerste keuze die moet worden gemaakt is of er wordt begonnen vanuit een bestaande open source tool, of dat er “from scratch” wordt gestart. Vervolgens kan op verschillende manieren invulling gegeven worden aan het ontwikkeltraject. In het paper “Open Source Ecosysteem” \[5\] suggereert ICTU een interessante optie, namelijk micro-funding voor kleine stukjes functionaliteit.

### Beschikbare oplossingen en projecten

Om beter hergebruik van bestaande software mogelijk te maken, is het belangrijk dat er hiervan een actueel overzicht is. Dit overzicht moet regelmatig worden bijgewerkt. Op dit moment gebeurt dat sporadisch in projecten als E-DEM en D-CENT, maar dit zijn indexeringen achteraf. Beter zou het zijn om ook zicht te hebben op lopende ontwikkeltrajecten en voornemens, zodat samenwerkingen kunnen worden aangegaan en vanaf het begin van projecten open source kan worden samengewerkt. Voor het vinden van beschikbare tools is een groot aantal online zoekmachines en overzichten beschikbaar. Enkele voorbeelden zijn:

 - D-CENT https://dcentproject.eu/
 - OGP Toolbox https://ogptoolbox.org/
 - Code for America Civic Tech Project Search http://brigade.codeforamerica.org/
 - Joinup https://joinup.ec.europa.eu
 - Transparencee Tools https://transparencee.org/scaling/
 - Digital Social Innovation https://digitalsocial.eu/
 - Participedia https://www.participedia.net/
 - Clarity Marketplace https://clarity-csa.eu/portfolio-classic-3cols
 - Github and Government https://government.github.com/
 
 Veel van deze catalogi zijn ontstaan in een project, en worden daarom niet actief onderhouden. Veel van de beschikbare informatie technisch, op de software gericht in plaats van op de use case, en bovendien alleen in het Engels beschikbaar. Het zou goed zijn om een actuele centrale vraagbaak te hebben voor dit soort informatie.

## Innovatie, ontwikkeling van nieuwe toepassingen

Indien er geen geschikte tools beschikbaar zijn, of nog niet duidelijk is wat er precies nodig is, dan kan er ook “from scratch” iets ontwikkeld worden. Daarbij is het belangrijk om te bepalen welke programmeertaal, technieken en infrastructuur gebruikt moeten worden, om te zorgen voor maximale onderhoudbaarheid. Daarnaast moet er gekozen worden voor een ontwikkelmethode, zoals Agile of Design Thinking. Product eigenaarschap De wensen van gemeenten moeten ergens binnenkomen en vervolgens vertaald worden naar features of “user stories” voor ontwikkeling. Vervolgens moeten er beslissingen genomen worden over welke wijzigingen wel of niet worden geaccepteerd in de code, wat de focus is van de ontwikkeling. De aannemer wijst een producteigenaar aan. Deze kan al dan niet inspraakmogelijkheden organiseren en daarvoor regels opstellen. In de software-wereld bestaat het gezegde: “a camel is a horse designed by committee”. Het is noodzakelijk om iemand aan te wijzen, één product owner, die uiteindelijk de eindverantwoordelijkheid heeft.

## Kwaliteitscontrole op de code

De code moet ergens worden opgeslagen en daar worden onderhouden. Aan te raden is om hiervoor Github te gebruiken, de de facto standaard voor open source community projecten. Vervolgens moet de kwaliteit van de ontwikkelde code gecontroleerd worden en gecheckt op functionaliteit, leesbaarheid, veiligheid en ook of er aan juridische eisen zoals bijvoorbeeld privacy moet worden voldaan. Gezien het open source code betreft, ligt de verantwoordelijkheid voor problemen bij gebruik geheel bij de aanbieder van de applicatie. Dat wil dus zeggen dat deze kwaliteitscontrole erg belangrijk is voor die aanbieder, en deze dus vertrouwen moet hebben in het gebruikte protocol en controlemechanisme. Om dit proces enigszins te kunnen beheersen wordt er gewerkt in een ‘fork’ van een bestaande repository. Periodiek kan er in beide richtingen uitwisseling plaatsvinden. De ontwikkelaars kunnen via een ‘pull request’ functionele blokken toevoegen aan de oorspronkelijke repository, en nieuwe functionaliteit of bug-fixes in die oorspronkelijke repository kunnen worden samengevoegd met de fork waarin ontwikkeld wordt. Derden kunnen via hetzelfde mechanisme ook direct bijdragen aan deze fork.

### Promotie van hergebruik, gezamenlijk gebruik en samenwerking

Een andere taak is het promoten van gebruik van de beschikbare oplossingen. Dan gaat het enerzijds om het vergroten van het gebruik door gemeenten die dat nog niet van plan waren, anderzijds door het aanprijzen van deze oplossing bij gemeenten die iets dergelijks zoeken. Het overkoepelende belang van het open source ecosysteem uitdragen, en de noodzakelijke gedragsregels blijven aanstippen. Actief samenwerking opzoeken, plannen delen, hergebruik stimuleren, actief participeren in open source projecten, actief doorontwikkelen van oplossingen... Deze cultuur in in de context van digitale overheidsdienstverlening en dienstverleners nog niet vanzelfsprekend.

### Afstemming van cultuur, best practices en technieken

Om te zorgen dat er een cultuur ontstaat onder de dienstverleners en ontwikkelaars, en levende standaarden en best practices gedeeld worden, zijn meetups cruciaal. Zo leren de ontwikkelaars elkaar en elkaars projecten kennen. Dit zorgt voor meer vertrouwen, meer samenwerking, meer hergebruik van code, en convergentie van technieken. Code for NL is in 2017 begonnen met maandelijkse meetups, in samenwerking met onder meer ICTU, Waag, Datalab Amsterdam, gemeente Haarlem, en de interesse vanuit gemeenten om deel te nemen groeit. Daarnaast is er een Slack kanaal geopend voor vragen en discussies in de tussentijd: http://praatmee.codefor.nl

### Infrastructuur

Een digitale dienst of toepassing draait op een infrastructuur. Bij het Datalab van de gemeente Amsterdam is er gekozen om een infrastructuur in te richten voor het ontsluiten, analyseren en gebruiken van (open) data uit de stad. Deze infrastructuur heet Datapunt en is gebaseerd op open stack. \[6\] Momenteel worden er stappen gezet om Datapunt geschikt te maken voor het beheren van open source applicaties. Een goede infrastructuur opzetten met hoge service level is niet eenvoudig en vereist veel initieel werk en onderhoud. Het valt daarom aan te raden om dit centraal op te zetten. Hiervoor wordt gekeken naar VNG, maar de Nederlandse overheid heeft met ODC-Noord een datacenter dat openstack aanbiedt. Het verdient de aanbeveling om te kijken of daarvan gebruik kan worden gemaakt. Hierbij kan ook de technologie en kennis die is ontwikkeld bij het opzetten van Datapunt worden aangewend. Andere zaken waaraan gedacht kan worden is bijvoorbeeld een Rancher omgeving voor Docker en VPS beheer, orchestratie, en iets van KONG of API-Umbrella voor diensten die samenhangen met API hosting (rate limiting, authenticatie, load balancing, etc.)

### Ruimte voor maatwerk

Het is in het belang van alle gemeenten dat zoveel mogelijk gebruik wordt gemaakt van dezelfde tools, maar ook dat er ruimte is voor eigen inbreng en specifieke wensen. Voor een deel is dit technisch op te lossen door voor een modulaire opzet te kiezen in de software. Voor een ander deel is het een belangenafweging. Hierin moet een middenweg gevonden worden. De rol voor het promoten van gedeelde oplossingen, en en het beoordelen van algemene dan wel specifieke wensen zou bij de VNG kunnen liggen.. Gemeenten met specifieke wensen die extra maatwerk vergen kunnen hun eigen devops/service team inrichten om een fork te maken met de noodzakelijke aanpassingen, en deze up-to-date te houden met de originele repository. Vaak is het wenselijk om nog wat dingen aan te passen in de applicatie. Denk hierbij aan vertaling van de teksten binnen de applicatie naar het Nederlands, het net anders inrichten van ingebouwde processen, of eenvoudigweg het aanpassen van de visuele stijl van de applicatie en het gebruiken van een ander logo. In sommige applicaties is dit configureerbaar, dat wil zeggen: in te stellen in de applicatie na de installatie. Dit wordt vaak aangeduid met “functioneel beheer”. In andere gevallen moet een programmeur hiervoor dingen aanpassen in de code. Bij open source software ligt dit vaak dicht tegen elkaar aan. Als je besluit aanpassingen aan de software te gaan maken, dan is het belangrijk om te bepalen of je wilt dat de software gekoppeld blijft aan de oorspronkelijke software (die vaak ook doorontwikkelt wordt). Als je namelijk teveel wijzigingen maakt, zonder daarbij rekening te houden met de ontwikkelingen in de oorspronkelijke code, dan drijft je eigen variant af. Het kan dan gebeuren dat de twee versies op een bepaald moment niet meer compatibel zijn, en je geen profijt meer hebt van updates aan de oorspronkelijke code. Oplossingen hiervoor zijn tijdige “pull requests”, waarbij je vraagt of jouw veranderingen mogen worden opgenomen in de oorspronkelijke code, of een modulaire opzet, waarbij extra functionaliteit los staat van de oorspronkelijke code en er via gedocumenteerd open protocollen en standaarden aan kan worden gekoppeld.

### Aanbieder

Om een applicatie vervolgens echt te kunnen inzetten, is er een aanbieder nodig. De aanbieder neemt verantwoordelijkheid voor de veiligheid en beschikbaarheid van de applicatie, en maakt hierover afspraken met de afnemer in de vorm van een Service Level Agreement. Er zijn verschillende manieren om dit organisatorisch in te richten.

#### INTERNE MANAGED HOSTING (ICT AFDELING)

De traditionele manier om software te implementeren in de organisatie is een ICT afdeling. Deze afdeling beheert toepassingen op verzoek van de operations. Het voordeel is dat er veel controlemechanismen zijn binnen de organisatie, bijvoorbeeld op het gebied van service level, privacy en security. Een nadeel kan zijn dat deze afdeling vaak vastzit aan een bepaalde (vaak verouderde) infrastructuur, die zich niet leent voor het hosten van moderne web applicaties, en al helemaal niet voor meer experimentele toepassingen. Door eerdere oorzaken, van budgettaire aard of door legacy code is de werkwijze vaak minder flexibel. In het geval van Datapunt Amsterdam is ervoor gekozen om een nieuwe interne aanbieder op te zetten, naast de traditionele ICT organisatie, die minder bureaucratisch is ingericht en meer vrijheid heeft met betrekking tot de keuze voor technieken en andere manieren van werken. Dit heeft op nationaal niveau navolging gekregen vanuit VNG (common ground), waarbij gekeken wordt of er op een agile manier nieuwe toepassingen kunnen worden gebouwd, in eerste instantie buiten de bestaande ICT-organisaties om. Een toekomstige mogelijkheid is om Datapunt-achtige aanbieders niet alleen diensten aan te laten bieden aan hun eigen organisatie, maar ook aan andere gemeenten. Dit zou een ecosysteem opleveren waarin gemeenten elkaars applicaties afnemen (“as a Service”), in plaats van deze te moeten kopiëren of beleggen bij een centrale partij als VNG.

#### INTERNE SERVICE TEAMS

In plaats van een algemene interne hostingpartij, kunnen er ook interne service teams ontstaan, die zelf zorg dragen voor hun digitale diensten. Deze manier van denken komt uit de Digital Transformation en heeft als voordeel dat de verantwoordelijkheid voor de business en voor de software bij één en hetzelfde team liggen. Dit team kan hierdoor volledig zelfstandig bepalen hoe ze hun software en processen intern inrichten voor hun domein, terwijl ze naar buiten toe alleen afgerekend worden op hun kwaliteit van dienstverlening. In Amsterdam wordt op dit moment geëxperimenteerd met Open Stad, een afdeling die zich volledig richt op het aanbieden van digitale participatietools.

#### EXTERNE MANAGED HOSTING (WEB DEVELOPMENT BUREAU)

Een andere optie is om een web development bureau in de hand te nemen en deze verantwoordelijk te maken voor het installeren, onderhouden en beheren van de web applicatie. Het voordeel hiervan is dat er ruime keus aan is. Het nadeel is dat er een situatie ontstaat waarbij iedere gemeente telkens weer moet zoeken naar een geschikt bureau en dat deze bureaus bij het implementeren van de software telkens weer dezelfde oplossingen gaan maken voor veel voorkomende problemen, zonder deze met elkaar te delen. Ook is er vaak weinig zicht op de interne processen van de bureaus, wat bepaalde veiligheidsrisico’s met zich mee kan brengen. Belangrijk is het om bij de keuze voor een web development bureau duidelijk vast te leggen dat de data eigendom is van de gemeente, dat deze eenvoudig te exporteren moet zijn, dat de software-wijzigingen open source moeten worden gepubliceerd, en dat er open standaarden worden gehanteerd. Daarnaast is het belangrijk om een audit te doen, waarbij gecontroleerd wordt hoe en waar de data wordt opgeslagen en hoe de servers beveiligd zijn. Ook moet worden bepaald wie applicatiebeheer en support verzorgd. Waarschijnlijk is het wenselijk dat gebruikers zich bij de gemeentelijke dienst melden en niet bij het ingeschakelde bureau, alhoewel dit natuurlijk varieert met het soort dienst en de doelgroep ervan.

#### STICHTING MET SPECIFIEK DOEL

Voor veelgebruikte oplossingen is het een optie om een stichting op te richten voor het aanbieden en beheren van deze oplossing. Een voorbeeld hiervan is Pleio, een open source discussieplatform voor overheden. De Stichting Pleio \[7\] draagt zorg voor de doorontwikkeling, het aanbieden en beheren van de software “as a Service”. Het voordeel is dat er heel specifiek kan worden gefocust op het doorontwikkelen van de service en de software en dat alle capaciteit daarvoor wordt ingezet. Nadeel kan zijn dat er een kritieke massa aan lange termijn commitment moet zijn van gemeenten en een stabiele stroom inkomsten om dit stabiel op te zetten.

#### SPECIFIEKE COÖPERATIE OF VERENIGING

Om de gemeenten meer invloed te geven op hoe de aanbieder zich ontwikkeld, kan in plaats van een stichting ook worden gekozen voor een coöperatie of vereniging. Voordeel is hierbij dat er kan worden besloten door de leden welke koers moet worden gevolgd. Nadeel kan zijn dat er veel management overhead geïntroduceerd wordt, waardoor er veel tijd en geld gaat zitten in vergaderen over ontwikkeling, in plaats van ontwikkeling zelf.

#### ALGEMENE STICHTINGEN

Een andere optie is om het beheer neer te leggen bij een algemene stichting die meerdere applicaties onderhoud en aanbiedt. Zo wil Stichting ICTU, de ICT uitvoeringsorganisatie voor de overheid, graag een aantal toepassingen in beheer nemen. Voordeel hiervan is dat dit snel kan worden opgetuigd. Het nadeel kan zijn dat er intern wordt bepaald waar ontwikkel- en service capaciteit wordt ingezet, en het dus kan zijn dat sommige applicaties niet heel actief worden doorontwikkeld. Ook andere diensten kunnen in algemene stichtingen worden ondergebracht. Zo is recent de Foundation for Public Code opgericht, om een portfolio aan open source applicaties voor steden te gaan beheren. Stichting Code for NL is opgericht om een actief netwerk op te bouwen en te onderhouden van open source developers en designers die zich inzetten voor een betere digitale overheid. De Stichting Open Source en Overheid zet zich in voor een minder afhankelijke positie van de overheid ten aanzien van softwarebedrijven. VNG Gemeenten zijn al verenigd in de VNG. Binnen VNG zou een afdeling kunnen ontstaan die zich bezighoudt met het ontwikkelen en aanbieden van open source applicaties aan gemeenten. Een goed voorbeeld van hoe dat eruit kan zien is 6AIKA: 6 Finse steden hebben gezamenlijk een development team opgezet dat zich bezighoudt met het ontwikkelen van toepassingen en deze beschikbaar maken en ondersteunen. Zie https://dev.hel.fi

#### ALGEMENE COÖPERATIE OF VERENIGING

Niet alleen gemeenten hebben behoefte aan infrastructuur en beheer van open source oplossingen. Ook veel kleine marktpartijen in het open source ecosysteem zouden graag gebruik maken van dergelijke diensten. Zo kunnen ze zich namelijk richten op het ontwikkelen van maatwerkoplossingen in processen. Een samenwerking tussen overheid en marktpartijen in een vereniging of coöperatie kan een interessante optie zijn als basis voor een levendig open source ecosysteem.

#### STARTUPS

Er zijn ook startups die e-participatietools as a Service aanbieden. Hierbij gaat het doorgaans om closed source oplossingen. In bepaalde situaties kan dit een snelle en relatief eenvoudige manier zijn om hiermee te experimenteren. Daarbij is het wel belangrijk om te bespreken wat er met de data gebeurt, en om bepaalde controlemechanismen in te bouwen, zodat er niet gesjoemeld kan worden met bijvoorbeeld de uitslagen van een stemming. Misschien is aandeelhouderschap hiervoor een manier. In het algemeen verdienen closed-source oplossingen, uit oogpunt van transparantie en vendor lock-in, niet de voorkeur.

### devOps

In opdracht van de aanbieder installeert en configureert een door de aanbieder aangestuurd devOps team de software, regelt de infrastructuur en voert monitoring en onderhoudswerkzaamheden uit. Ze registreren ook domeinnamen en SSL certificaten voor beveiligde verbinding. Daarnaast zorgen ze voor backups en het beheer van de infrastructuur.

### Functioneel testen

Alvorens de applicatie te gaan gebruiken, is het verstandig om deze grondig te testen. Dit gebeurt onder leiding van de product owner, welke representatieve groepen betrekt en een test schema opstelt.

### PEN/Hack test

White hat hackers proberen de applicatie op van allerhande manieren te hacken, om beveiligingsproblemen in kaart te brengen. Naar aanleiding van dit rapport kunnen aanpassingen worden gedaan om de beveiligingsproblemen te verhelpen.

### Functioneel en gebruikersbeheer

Het aanmaken van gebruikers en toekennen van rechten, waarbij ook controleprocessen worden gevolgd voor het vaststellen van identiteit en autorisaties vanuit de organisatie, maar ook het controleren van de logs en in de gaten houden of er dingen mis gaan. Run-time configuratie (soms grijs gebied met devOps: in de applicatie vs in de code/database).

### Implementatie en ondersteuning

De software moet vervolgens ook nog in processen worden ingepast. Vaak gaat dit hand in hand met kleine maatwerk aanpassingen. Daarnaast is er een behoefte aan het kunnen stellen van vragen en het krijgen van uitleg over het gebruik van de software.

### Samen onderzoeken

Gezien zowel de technologie als de organisaties nog volop in ontwikkeling zijn, en het ernaar uitziet dat dit nog wel even zo blijft, is het belangrijk om samen te testen en verkennen wat werkt, wat wenselijk is, welke ambities er zijn, en wie wat waar kan bijdragen. Verschillende partijen kunnen op termijn een rol spelen, maar zijn nog niet altijd in staat om die rol per direct te vervullen. Daarnaast is het een puzzel om binnen dit groeiende en zich ontwikkelende ecosysteem van open source dienstverleners te bepalen hoe de taken te verdelen, de samenhang te vinden en de samenwerking te bevorderen

## Open Source mentaliteit

Om van open source een succes te maken, is een bepaalde houding nodig.

### 1\. SAMENWERKEN

Door nauw (inter)nationaal samen te werken in projecten worden krijgen de oplossingen meer schaal, worden ze modulair (voor maatwerk), worden best practices gedeeld en convergeren technieken. Dit zorgt voor betere herbruikbaarheid van zowel de oplossingen als de infrastructuur en goedkoper beheer.

### 2\. DELEN VAN CODE, KENNIS, ERVARING

Door te delen wat er precies gedaan is, wat de resultaten waren, zowel de positieve als de fouten die gemaakt zijn, zorg je voor convergentie van technieken, ontwikkeling van de kennis, en een positieve cultuur van samen delen en samen experimenteren.

### 3\. DURF TE VRAGEN (MAAR PROBEER HET EERST EVEN ZELF UIT TE ZOEKEN)

Niemand weet alles. Een vraag kan voorkomen dat je tijd verspilt aan de verkeerde dingen doen of dingen verkeerd doen. Beantwoord daarom ook vragen van anderen, en moedig mensen aan om ze te stellen.

### 4\. DURF TE -FALEN- LEREN

Niet alles kan altijd goed gaan. Zorg voor een veilige omgeving, waarin fouten niet worden verstopt, maar gevierd. Dit zorgt ervoor dat ze snel boven tafel komen, en ervan kan worden geleerd.

### 5\. HERGEBRUIKEN

Zoveel mogelijk doorontwikkelen wat er is, in plaats van telkens opnieuw beginnen. Dit zorgt voor een actieve community rondom open source projecten, in plaats van een enorme veelheid aan verlaten applicaties. Dit zorgt ervoor dat er een kritieke massa is voor doorontwikkeling, waardoor projecten blijven leven en beheer eenvoudiger wordt.

### 6\. OPEN (WEB) STANDAARDEN

Gebruik waar mogelijk open (web) standaarden, in plaats van eigen standaarden bedenken. Dit zorgt voor begrijpelijke code en betere herbruikbaarheid. Open web standaarden zijn over lange tijd ontstaan uit internationale consensus. Het is onwaarschijnlijk dat de standaarden die je zelf verzint hetzelfde draagvlak gaan krijgen.

### 7\. BOTTOM-UP

Volg en doe mee, in plaats van proberen te sturen. Bijsturen kun je doen door middel van inzet en initiatief. Volg zoveel mogelijk de gangbare werkwijze. Volg de coding standards van een project.

### 8\. EAT YOUR OWN DOGFOOD EN SCRATCH YOUR OWN ITCH

Gebruik je eigen code, en draag bij aan projecten waar je gebruik van maakt.

### 9\. KUDO'S

Geef kudo's aan bijdragers, steel geen ideeen, maar geef credit where credit's due.

## Ontwikkelingen in Nederland

Er zijn op dit moment enkele relevante ontwikkelingen gaande op het gebied van e-participatie tools in Nederland, die mede bepalen welke richting de governance op zal gaan.

ARGU (https://argu.co) is een jong discussieplatform As A Service. De (commerciële) onderneming is verantwoordelijk voor technologie, beheer en ontwikkeling. Simpel uit te rollen, maar over data eigenaarschap en -portabiliteit is op de site niets te vinden (op het moment van schrijven zijn de ‘terms of use’ en ‘privacy’ pagina’s niet beschikbaar).

Stichting Pleio (https://www.pleio.nl) ontwikkelt en beheert open source online kennisdelingsplatform As A Service, speciaal voor overheidsorganisaties en bestuurslagen binnen de overheid. Tot nu toe niet ingezet als deliberatieplatform met burgers.

Ideeënvijver is een open source tool voor het pitchen van ideeën en het daarop stemmen. Vanuit Code for NL fellowships bij de gemeente Eindhoven ontwikkeld en onder beheer bij Code For NL. (https://e52.nl/tag/ideeenvijver/)

Your Priorities (https://www.yrpri.org/) is een in IJsland en Estland zeer succesvol open source deliberatie platform. Het is beschikbaar in het Nederlands, en een nl proefversie is uit te proberen op https://e-dem.nl. Ook op e-dem.nl is een Nederlandstalige versie van Consul (http://consulproject.org) te vinden, een open source platform dat met succes ingezet wordt in Madrid.

De Stichting ICTU organiseert software-development voor de overheid, waarbij marktpartijen worden aangehaakt om te bouwen. ICTU is voornemens om een rol te spelen in het beheer van open source tools op het gebied van participatieve democratie.

Stichting Code for NL organiseert maandelijks bijeenkomsten voor open source developers en designers (en andere geïnteresseerden) die werkenbij of voor de overheid, om kennis en ervaring uit te wisselen, resultaten te delen en samenwerkingen te promoten. Een overzicht van use cases van digitale tools bij overheden op clarity.codefor.nl

Open Stad is een doorontwikkeling van Open Stadsdeel, dat op zijn beurt een doorontwikkeling is van Stem van West. Deze applicaties wordt gehost vanuit Datapunt Amsterdam, is open source en heeft zich als Stem van West als interessante, door de overheid gestuurde ontwikkeling gemanifesteerd.. Informatie: https://www.amsterdam.nl/bestuur-organisatie/geef-mening/openstad-online/

Datalab Amsterdam ontwikkelt de afdeling “innovatieve toepassingen” open source procesapplicaties voor uitvoerende ambtenaren. Deze maatwerkapplicaties worden beheerd en gehost door Datapunt Amsterdam, de nieuwe infrastructuur voor data services, data-toepassingen en in-house ontwikkelde open source web applicaties van de gemeente Amsterdam. Doorontwikkeling en ondersteuning door oorspronkelijke team. (lange termijn betrokkenheid) Amsterdam neemt hiermee het voortouw, in de hoop dat andere (grote) gemeenten en VNG spoedig zullen volgen en de (open source) samenwerking zullen opzoeken. (https://data.amsterdam.nl)

Het zeer nieuwe Nederlandse initiatief Foundation for Public Code richt zich op het beheer en de sustainable inzet van open source publieke code en publieke digitale infrastructuur. (http://publiccode.net).

Stichting Open Source en Overheid (https://oseno.nl) zet zich in om de Nederlandse overheid minder afhankelijk te maken van software-leveranciers.

## Aandachtspunten

- Open source ecosysteem kan alleen bestaan als er proactief samengewerkt wordt.
- Het beheer van open source broncode is iets totaal anders dan het beheer van draaiende open source applicaties.
- Open source software is pas waardevol als er een organisatie is die er een bepaalde service level aan toevoegt.
- Open source software is niet gratis; in plaats van licentiekosten dient rekening te worden gehouden met kosten voor (door)ontwikkeling.
- Code open source maken is niet een laatste stap, maar een eerste stap. Het gaat niet om open source code, maar om open source samenwerking.
- Zorg zoveel mogelijk voor een modulaire opzet in open source projecten, zodat maatwerk mogelijk blijft, terwijl nog wel kan worden samengewerkt aan de co-re-functionaliteiten
- Lange termijn betrokkenheid van en verantwoordelijkheidsgevoel bij programmeurs gaan hand in hand.
- Leesbare code, gangbare volwassen talen en technieken, eenvoudige architectuur en andere best practices zorgen voor een maximale onderhoudbaarheid (“bus factor”, zie https://en.wikipedia.org/wiki/Bus\_factor).

## Open vragen

- Hoe zorg je voor de democratische controleerbaarheid die essentieel is voor e-participatietools?
- Hoe align je de motivaties van bedrijven met de motivaties van overheid en het publiek belang?
- Op welke manier kunnen bedrijven, non-profits en overheid samen een beheerorganisatie vormen?
- Kunnen we een systeem van micro funding bedenken in combinatie met een pool (“zwerm”) van open source ontwikkelaars, om een constante ontwikkelcapaciteit te realiseren?
- Er is veel bereidheid om digitale services toe te voegen voor een ecosysteem van open source applicaties. Hoe maken we hiervoor een marktplaats?
- Welke organisaties willen welke rol precies vervullen? Hoe combineer je die ambities in één ecosysteem?