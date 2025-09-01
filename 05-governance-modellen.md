---
layout: chapter
title: Governance Modellen voor Open Source Dienstverlening
part: Deel III - Governance en Organisatie
prev_chapter: /04-rollen-ecosysteem
next_chapter: /06-nederlandse-praktijk
---

Om een applicatie vervolgens echt te kunnen inzetten, is er een aanbieder nodig. De aanbieder neemt verantwoordelijkheid voor de veiligheid en beschikbaarheid van de applicatie, en maakt hierover afspraken met de afnemer in de vorm van een Service Level Agreement. Er zijn verschillende manieren om dit organisatorisch in te richten.

## Interne Modellen

### Interne managed hosting (ICT afdeling)
De traditionele manier om software te implementeren in de organisatie is een ICT afdeling. Deze afdeling beheert toepassingen op verzoek van de operations. Het voordeel is dat er veel controlemechanismen zijn binnen de organisatie, bijvoorbeeld op het gebied van service level, privacy en security. Een nadeel kan zijn dat deze afdeling vaak vastzit aan een bepaalde (vaak verouderde) infrastructuur, die zich niet leent voor het hosten van moderne web applicaties, en al helemaal niet voor meer experimentele toepassingen. Door eerdere oorzaken, van budgettaire aard of door legacy code is de werkwijze vaak minder flexibel. In het geval van Datapunt Amsterdam is ervoor gekozen om een nieuwe interne aanbieder op te zetten, naast de traditionele ICT organisatie, die minder bureaucratisch is ingericht en meer vrijheid heeft met betrekking tot de keuze voor technieken en andere manieren van werken. Dit heeft op nationaal niveau navolging gekregen vanuit VNG (common ground), waarbij gekeken wordt of er op een agile manier nieuwe toepassingen kunnen worden gebouwd, in eerste instantie buiten de bestaande ICT-organisaties om. Een toekomstige mogelijkheid is om Datapunt-achtige aanbieders niet alleen diensten aan te laten bieden aan hun eigen organisatie, maar ook aan andere gemeenten. Dit zou een ecosysteem opleveren waarin gemeenten elkaars applicaties afnemen ("as a Service"), in plaats van deze te moeten kopiëren of beleggen bij een centrale partij als VNG.

### Interne service teams
In plaats van een algemene interne hostingpartij, kunnen er ook interne service teams ontstaan, die zelf zorg dragen voor hun digitale diensten. Deze manier van denken komt uit de Digital Transformation en heeft als voordeel dat de verantwoordelijkheid voor de business en voor de software bij één en hetzelfde team liggen. Dit team kan hierdoor volledig zelfstandig bepalen hoe ze hun software en processen intern inrichten voor hun domein, terwijl ze naar buiten toe alleen afgerekend worden op hun kwaliteit van dienstverlening. In Amsterdam wordt op dit moment geëxperimenteerd met Open Stad, een afdeling die zich volledig richt op het aanbieden van digitale participatietools.

## Externe Modellen

### Externe managed hosting (web development bureau)
Een andere optie is om een web development bureau in de hand te nemen en deze verantwoordelijk te maken voor het installeren, onderhouden en beheren van de web applicatie. Het voordeel hiervan is dat er ruime keus aan is. Het nadeel is dat er een situatie ontstaat waarbij iedere gemeente telkens weer moet zoeken naar een geschikt bureau en dat deze bureaus bij het implementeren van de software telkens weer dezelfde oplossingen gaan maken voor veel voorkomende problemen, zonder deze met elkaar te delen. Ook is er vaak weinig zicht op de interne processen van de bureaus, wat bepaalde veiligheidsrisico's met zich mee kan brengen. Belangrijk is het om bij de keuze voor een web development bureau duidelijk vast te leggen dat de data eigendom is van de gemeente, dat deze eenvoudig te exporteren moet zijn, dat de software-wijzigingen open source moeten worden gepubliceerd, en dat er open standaarden worden gehanteerd. Daarnaast is het belangrijk om een audit te doen, waarbij gecontroleerd wordt hoe en waar de data wordt opgeslagen en hoe de servers beveiligd zijn. Ook moet worden bepaald wie applicatiebeheer en support verzorgd. Waarschijnlijk is het wenselijk dat gebruikers zich bij de gemeentelijke dienst melden en niet bij het ingeschakelde bureau, alhoewel dit natuurlijk varieert met het soort dienst en de doelgroep ervan.

### Startups
Er zijn ook startups die e-participatietools as a Service aanbieden. Hierbij gaat het doorgaans om closed source oplossingen. In bepaalde situaties kan dit een snelle en relatief eenvoudige manier zijn om hiermee te experimenteren. Daarbij is het wel belangrijk om te bespreken wat er met de data gebeurt, en om bepaalde controlemechanismen in te bouwen, zodat er niet gesjoemeld kan worden met bijvoorbeeld de uitslagen van een stemming. Misschien is aandeelhouderschap hiervoor een manier. In het algemeen verdienen closed-source oplossingen, uit oogpunt van transparantie en vendor lock-in, niet de voorkeur.

## Collectieve Modellen

### Stichting met specifiek doel
Voor veelgebruikte oplossingen is het een optie om een stichting op te richten voor het aanbieden en beheren van deze oplossing. Een voorbeeld hiervan is Pleio, een open source discussieplatform voor overheden. De Stichting Pleio [7] draagt zorg voor de doorontwikkeling, het aanbieden en beheren van de software "as a Service". Het voordeel is dat er heel specifiek kan worden gefocust op het doorontwikkelen van de service en de software en dat alle capaciteit daarvoor wordt ingezet. Nadeel kan zijn dat er een kritieke massa aan lange termijn commitment moet zijn van gemeenten en een stabiele stroom inkomsten om dit stabiel op te zetten.

### Specifieke coöperatie of vereniging
Om de gemeenten meer invloed te geven op hoe de aanbieder zich ontwikkeld, kan in plaats van een stichting ook worden gekozen voor een coöperatie of vereniging. Voordeel is hierbij dat er kan worden besloten door de leden welke koers moet worden gevolgd. Nadeel kan zijn dat er veel management overhead geïntroduceerd wordt, waardoor er veel tijd en geld gaat zitten in vergaderen over ontwikkeling, in plaats van ontwikkeling zelf.

### Algemene stichtingen
Een andere optie is om het beheer neer te leggen bij een algemene stichting die meerdere applicaties onderhoud en aanbiedt. Zo wil Stichting ICTU, de ICT uitvoeringsorganisatie voor de overheid, graag een aantal toepassingen in beheer nemen. Voordeel hiervan is dat dit snel kan worden opgetuigd. Het nadeel kan zijn dat er intern wordt bepaald waar ontwikkel- en service capaciteit wordt ingezet, en het dus kan zijn dat sommige applicaties niet heel actief worden doorontwikkeld. Ook andere diensten kunnen in algemene stichtingen worden ondergebracht. Zo is recent de Foundation for Public Code opgericht, om een portfolio aan open source applicaties voor steden te gaan beheren. Stichting Code for NL is opgericht om een actief netwerk op te bouwen en te onderhouden van open source developers en designers die zich inzetten voor een betere digitale overheid. De Stichting Open Source en Overheid zet zich in voor een minder afhankelijke positie van de overheid ten aanzien van softwarebedrijven.

### VNG Model
Gemeenten zijn al verenigd in de VNG. Binnen VNG zou een afdeling kunnen ontstaan die zich bezighoudt met het ontwikkelen en aanbieden van open source applicaties aan gemeenten. Een goed voorbeeld van hoe dat eruit kan zien is 6AIKA: 6 Finse steden hebben gezamenlijk een development team opgezet dat zich bezighoudt met het ontwikkelen van toepassingen en deze beschikbaar maken en ondersteunen. Zie https://dev.hel.fi

### Algemene coöperatie of vereniging
Niet alleen gemeenten hebben behoefte aan infrastructuur en beheer van open source oplossingen. Ook veel kleine marktpartijen in het open source ecosysteem zouden graag gebruik maken van dergelijke diensten. Zo kunnen ze zich namelijk richten op het ontwikkelen van maatwerkoplossingen in processen. Een samenwerking tussen overheid en marktpartijen in een vereniging of coöperatie kan een interessante optie zijn als basis voor een levendig open source ecosysteem.