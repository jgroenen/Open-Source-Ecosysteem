---
layout: chapter
title: Software Ontwikkeling in een Open Source Ecosysteem
part: Deel II - Het Ecosysteem
prev_chapter: /02-open-source-principes
next_chapter: /04-rollen-ecosysteem
---

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

### Innovatie en nieuwe ontwikkeling

Indien er geen geschikte tools beschikbaar zijn, of nog niet duidelijk is wat er precies nodig is, dan kan er ook "from scratch" iets ontwikkeld worden. Daarbij is het belangrijk om te bepalen welke programmeertaal, technieken en infrastructuur gebruikt moeten worden, om te zorgen voor maximale onderhoudbaarheid. Daarnaast moet er gekozen worden voor een ontwikkelmethode, zoals Agile of Design Thinking.

#### Product eigenaarschap

De wensen van gemeenten moeten ergens binnenkomen en vervolgens vertaald worden naar features of "user stories" voor ontwikkeling. Vervolgens moeten er beslissingen genomen worden over welke wijzigingen wel of niet worden geaccepteerd in de code, wat de focus is van de ontwikkeling. De aannemer wijst een producteigenaar aan. Deze kan al dan niet inspraakmogelijkheden organiseren en daarvoor regels opstellen. In de software-wereld bestaat het gezegde: "a camel is a horse designed by committee". Het is noodzakelijk om iemand aan te wijzen, één product owner, die uiteindelijk de eindverantwoordelijkheid heeft.

### Kwaliteitscontrole

De code moet ergens worden opgeslagen en daar worden onderhouden. Aan te raden is om hiervoor Github te gebruiken, de de facto standaard voor open source community projecten. Vervolgens moet de kwaliteit van de ontwikkelde code gecontroleerd worden en gecheckt op functionaliteit, leesbaarheid, veiligheid en ook of er aan juridische eisen zoals bijvoorbeeld privacy moet worden voldaan. Gezien het open source code betreft, ligt de verantwoordelijkheid voor problemen bij gebruik geheel bij de aanbieder van de applicatie. Dat wil dus zeggen dat deze kwaliteitscontrole erg belangrijk is voor die aanbieder, en deze dus vertrouwen moet hebben in het gebruikte protocol en controlemechanisme. Om dit proces enigszins te kunnen beheersen wordt er gewerkt in een 'fork' van een bestaande repository. Periodiek kan er in beide richtingen uitwisseling plaatsvinden. De ontwikkelaars kunnen via een 'pull request' functionele blokken toevoegen aan de oorspronkelijke repository, en nieuwe functionaliteit of bug-fixes in die oorspronkelijke repository kunnen worden samengevoegd met de fork waarin ontwikkeld wordt. Derden kunnen via hetzelfde mechanisme ook direct bijdragen aan deze fork.

### Promotie van hergebruik en samenwerking

Een andere taak is het promoten van gebruik van de beschikbare oplossingen. Dan gaat het enerzijds om het vergroten van het gebruik door gemeenten die dat nog niet van plan waren, anderzijds door het aanprijzen van deze oplossing bij gemeenten die iets dergelijks zoeken. Het overkoepelende belang van het open source ecosysteem uitdragen, en de noodzakelijke gedragsregels blijven aanstippen. Actief samenwerking opzoeken, plannen delen, hergebruik stimuleren, actief participeren in open source projecten, actief doorontwikkelen van oplossingen... Deze cultuur in in de context van digitale overheidsdienstverlening en dienstverleners nog niet vanzelfsprekend.

### Cultuur en technieken

Om te zorgen dat er een cultuur ontstaat onder de dienstverleners en ontwikkelaars, en levende standaarden en best practices gedeeld worden, zijn meetups cruciaal. Zo leren de ontwikkelaars elkaar en elkaars projecten kennen. Dit zorgt voor meer vertrouwen, meer samenwerking, meer hergebruik van code, en convergentie van technieken. Code for NL is in 2017 begonnen met maandelijkse meetups, in samenwerking met onder meer ICTU, Waag, Datalab Amsterdam, gemeente Haarlem, en de interesse vanuit gemeenten om deel te nemen groeit. Daarnaast is er een Slack kanaal geopend voor vragen en discussies in de tussentijd: http://praatmee.codefor.nl

### Maatwerk en flexibiliteit

Het is in het belang van alle gemeenten dat zoveel mogelijk gebruik wordt gemaakt van dezelfde tools, maar ook dat er ruimte is voor eigen inbreng en specifieke wensen. Voor een deel is dit technisch op te lossen door voor een modulaire opzet te kiezen in de software. Voor een ander deel is het een belangenafweging. Hierin moet een middenweg gevonden worden. De rol voor het promoten van gedeelde oplossingen, en en het beoordelen van algemene dan wel specifieke wensen zou bij de VNG kunnen liggen.. Gemeenten met specifieke wensen die extra maatwerk vergen kunnen hun eigen devops/service team inrichten om een fork te maken met de noodzakelijke aanpassingen, en deze up-to-date te houden met de originele repository. Vaak is het wenselijk om nog wat dingen aan te passen in de applicatie. Denk hierbij aan vertaling van de teksten binnen de applicatie naar het Nederlands, het net anders inrichten van ingebouwde processen, of eenvoudigweg het aanpassen van de visuele stijl van de applicatie en het gebruiken van een ander logo. In sommige applicaties is dit configureerbaar, dat wil zeggen: in te stellen in de applicatie na de installatie. Dit wordt vaak aangeduid met "functioneel beheer". In andere gevallen moet een programmeur hiervoor dingen aanpassen in de code. Bij open source software ligt dit vaak dicht tegen elkaar aan. Als je besluit aanpassingen aan de software te gaan maken, dan is het belangrijk om te bepalen of je wilt dat de software gekoppeld blijft aan de oorspronkelijke software (die vaak ook doorontwikkelt wordt). Als je namelijk teveel wijzigingen maakt, zonder daarbij rekening te houden met de ontwikkelingen in de oorspronkelijke code, dan drijft je eigen variant af. Het kan dan gebeuren dat de twee versies op een bepaald moment niet meer compatibel zijn, en je geen profijt meer hebt van updates aan de oorspronkelijke code. Oplossingen hiervoor zijn tijdige "pull requests", waarbij je vraagt of jouw veranderingen mogen worden opgenomen in de oorspronkelijke code, of een modulaire opzet, waarbij extra functionaliteit los staat van de oorspronkelijke code en er via gedocumenteerd open protocollen en standaarden aan kan worden gekoppeld.