---
layout: chapter
title: Rollen in het Ecosysteem
part: Deel II - Het Ecosysteem
prev_chapter: /03-ecosysteem-ontwikkeling
next_chapter: /05-governance-modellen
---

In een open source ecosysteem voor overheids-software zijn er verschillende rollen en functies te onderscheiden. Verschillende aspecten van software-ontwikkeling kunnen hierbij door verschillende partijen worden opgepakt. Dit in contrast met vendor-software, waar al deze taken vaak bij één partij liggen.

## Ontwikkelingsrollen

### Hoofdaannemer
De hoofdaannemer krijgt opdracht een bepaalde tool of oplossing te realiseren. Er worden budget- en planningsafspraken gemaakt met de opdrachtgever. De eerste keuze die moet worden gemaakt is of er wordt begonnen vanuit een bestaande open source tool, of dat er "from scratch" wordt gestart. Vervolgens kan op verschillende manieren invulling gegeven worden aan het ontwikkeltraject. In het paper "Open Source Ecosysteem" [5] suggereert ICTU een interessante optie, namelijk micro-funding voor kleine stukjes functionaliteit.

## Infrastructuur en Technische Rollen

### Infrastructuur
Een digitale dienst of toepassing draait op een infrastructuur. Bij het Datalab van de gemeente Amsterdam is er gekozen om een infrastructuur in te richten voor het ontsluiten, analyseren en gebruiken van (open) data uit de stad. Deze infrastructuur heet Datapunt en is gebaseerd op open stack. [6] Momenteel worden er stappen gezet om Datapunt geschikt te maken voor het beheren van open source applicaties. Een goede infrastructuur opzetten met hoge service level is niet eenvoudig en vereist veel initieel werk en onderhoud. Het valt daarom aan te raden om dit centraal op te zetten. Hiervoor wordt gekeken naar VNG, maar de Nederlandse overheid heeft met ODC-Noord een datacenter dat openstack aanbiedt. Het verdient de aanbeveling om te kijken of daarvan gebruik kan worden gemaakt. Hierbij kan ook de technologie en kennis die is ontwikkeld bij het opzetten van Datapunt worden aangewend. Andere zaken waaraan gedacht kan worden is bijvoorbeeld een Rancher omgeving voor Docker en VPS beheer, orchestratie, en iets van KONG of API-Umbrella voor diensten die samenhangen met API hosting (rate limiting, authenticatie, load balancing, etc.)

### DevOps
In opdracht van de aanbieder installeert en configureert een door de aanbieder aangestuurd devOps team de software, regelt de infrastructuur en voert monitoring en onderhoudswerkzaamheden uit. Ze registreren ook domeinnamen en SSL certificaten voor beveiligde verbinding. Daarnaast zorgen ze voor backups en het beheer van de infrastructuur.

## Kwaliteitsborging

### Functioneel testen
Alvorens de applicatie te gaan gebruiken, is het verstandig om deze grondig te testen. Dit gebeurt onder leiding van de product owner, welke representatieve groepen betrekt en een test schema opstelt.

### PEN/Hack test
White hat hackers proberen de applicatie op van allerhande manieren te hacken, om beveiligingsproblemen in kaart te brengen. Naar aanleiding van dit rapport kunnen aanpassingen worden gedaan om de beveiligingsproblemen te verhelpen.

## Beheer en Ondersteuning

### Functioneel en gebruikersbeheer
Het aanmaken van gebruikers en toekennen van rechten, waarbij ook controleprocessen worden gevolgd voor het vaststellen van identiteit en autorisaties vanuit de organisatie, maar ook het controleren van de logs en in de gaten houden of er dingen mis gaan. Run-time configuratie (soms grijs gebied met devOps: in de applicatie vs in de code/database).

### Implementatie en ondersteuning
De software moet vervolgens ook nog in processen worden ingepast. Vaak gaat dit hand in hand met kleine maatwerk aanpassingen. Daarnaast is er een behoefte aan het kunnen stellen van vragen en het krijgen van uitleg over het gebruik van de software.

## Onderzoek en Innovatie

### Samen onderzoeken
Gezien zowel de technologie als de organisaties nog volop in ontwikkeling zijn, en het ernaar uitziet dat dit nog wel even zo blijft, is het belangrijk om samen te testen en verkennen wat werkt, wat wenselijk is, welke ambities er zijn, en wie wat waar kan bijdragen. Verschillende partijen kunnen op termijn een rol spelen, maar zijn nog niet altijd in staat om die rol per direct te vervullen. Daarnaast is het een puzzel om binnen dit groeiende en zich ontwikkelende ecosysteem van open source dienstverleners te bepalen hoe de taken te verdelen, de samenhang te vinden en de samenwerking te bevorderen