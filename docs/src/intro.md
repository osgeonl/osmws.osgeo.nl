---
title: Intro - OSM Basics
---

# OSM Basics

Hierin leggen we de basis principes van OSM uit.

## Historie

OpenStreetMap is opgericht in 2004 door [Steve Coast](https://stevecoast.com/) lees meer in de [History_of_OpenStreetMap](https://wiki.openstreetmap.org/wiki/History_of_OpenStreetMap)

## De OpenStreetMap Website Exploreren

[Start OSM op LearnOSM](https://learnosm.org/nl_NL/beginner/start-osm/)

## Het OSM Data Model

Zie [Understanding OSM Data](https://wiki.openstreetmap.org/wiki/Beginners_Guide_1.3)

Binnen het OSM data model staan geometrieën centraal. 
Denk aan punten, lijnen, vlakken, en combinaties daarvan.

Deze geometrieën worden **Elements**, Elementen genoemd.
Aan elk 
Element worden eigenschappen, sommigen noemen dit metadata, 
toegekend in de vorm van **Tags**.

De Elementen in OSM terminologie zijn:

* **[Node](https://wiki.openstreetmap.org/wiki/Node)** (lees: punten)
* **[Way](https://wiki.openstreetmap.org/wiki/Way)** (lees: lijnen)
* **[Closed Way](https://wiki.openstreetmap.org/wiki/Way#Closed_way)** en **[Area](https://wiki.openstreetmap.org/wiki/Way#Area)** (lees: open en gevulde vlakken, polygonen)
* **[Relation](https://wiki.openstreetmap.org/wiki/Relation)**, combinaties van Elementen bijv Wandelroutes, laten we hier buiten beschouwing
* Elk Element heeft een **[uniek 64-bit integer Id](https://wiki.openstreetmap.org/wiki/64-bit_Identifiers)**

In plaats van modellen en schemas met attributen, 
zoals in GML, gebruikt OSM **Tagging**:

* Elk Element (zie boven) wordt beschreven met een of meer **Tags**
* Een Tag is een `key=value` paar
* Bijvoorbeeld voor een Way: `highway=residential` of een parkeerplaats (Closed Way) `amenity=parking`
* Er is binnen OSM, via de [Wiki](https://wiki.openstreetmap.org/wiki/Tags), "ongoing" consensus over een set te gebruiken Tags
* Sommige OSM Editors, bijv ID, gebruiken presets voor Tags om de gebruiker te faciliteren 
* Zie [uitgebreide uitleg](https://wiki.openstreetmap.org/wiki/Tags)
* OSM kent impliciet, door tagging, [Map Features](https://wiki.openstreetmap.org/wiki/Map_features)

!!! tip

    De website/app TagInfo op [taginfo.openstreetmap.org](https://taginfo.openstreetmap.org/) geeft veel informatie over gebruik van tags.
    De tags die voor Nederland worden gebruikt vind je op [taginfo.geofabrik.de/europe/netherlands](https://taginfo.geofabrik.de/europe/netherlands)
    Specifieke tagging conventies voor NL: [Wiki NL:Kaartelementen](https://wiki.openstreetmap.org/wiki/NL:Kaartelementen)
    Iedere tag, een key, of key=value, is op de OSM Wiki te vinden, bijv [amenity=hospital](https://wiki.openstreetmap.org/wiki/Tag:amenity%3Dhospital)

## Account Aanmaken

We vragen deelnemers tevoren (via email) om dit te doen ivm tijd.
Registratie gaat eenvoudig via [www.openstreetmap.org/user/new](https://www.openstreetmap.org/user/new).
Je hoeft niet perse je eigen naam te gebruiken als username, ook wel "OSM-handle" genoemd.
Deze kan overigens later aangepast. Ook je home locatie hoeft niet perse op je huis.
Ook dat is later aan te passen.

## iD Editor

Dit is de editor die standaard op openstreetmap.org beschikbaar is.
Wanneer je [inlogt daar](https://www.openstreetmap.org/login) zie je links boven een 'Edit' knop. Deze brengt je
in de iD Editor. De achtergrondkaart zal dan ook wijzigen, meestal naar de meest
gedetailleerde luchtfoto's. In Nederland is dat de PDOK Luchtfoto met 8cm resolutie.

We behandelen alleen de iD basics.

!!! tip

    Je kunt een eigen achtergrondkaart invoegen in iD bijv uit PDOK. Ga naar lagen en dan "Custom.."
    In een form kun je een symbolische URL invoegen bijv een laag uit Top10NL, 
    bijv hier de laag Top10NL Wegdeel, je kunt deze copy-pasten:
    https://service.pdok.nl/brt/top10nl/wms/v1_0?SERVICE=WMS&VERSION=1.3.0&REQUEST=GetMap&FORMAT=image/png&TRANSPARENT=true&LAYERS=wegdeel&CRS={proj}&STYLES=&WIDTH={width}&HEIGHT={height}&BBOX={bbox}

## Community

* [OSM Forum](https://community.openstreetmap.org)
* [NL Community op OSM Forum](https://community.openstreetmap.org/c/communities/nl/43)
* [NL Landings Pagina op OSM Wiki](https://wiki.openstreetmap.org/wiki/NL:Nederland)
* BAG-import methodiek en conventies
* NL-Bijeenkomsten
* Internationaal: SOTM - [EU-versie, 10-12 November, 2023 in Antwerpen!](https://stateofthemap.eu/)
* Meer? Discord? NL Telegram groep?

!!! tip

    Met je OSM Account heb je automatisch toegang tot het OSM Forum.

## Meer info

* [OSM Wiki](https://wiki.openstreetmap.org/)
* [Start OSM op LearnOSM](https://learnosm.org/nl_NL/beginner/start-osm/) (de Engelse versie is wat meer uptodate)

**Door naar de [Smart App EveryDoor](apps/everydoor.md)!**
