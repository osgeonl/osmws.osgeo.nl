---
title: App - StreetComplete
---

# StreetComplete App

![Logo](../assets/images/streetcomplete-logo.png)

*"[StreetComplete](https://streetcomplete.app/?lang=nl) is een gemakkelijk te gebruiken bewerker/editor voor OpenStreetMap voor Android telefoons en tablets. 
Wordt gebruikt voor het in het veld in kaart brengen ("field surveying").*

*De app is speciaal gemaakt voor af-en-toe deelnemers en beginners omdat geen eerdere kennis over OpenStreetMap 
(zoals schema's voor taggen) vereist is om bij te dragen met de app. Verder is er iets van een spel ("gamification") en 
statistieken die tot doel hebben een introductie en proberen gebruikers te inspireren om dieper te duiken in de wereld van OpenStreetMap."*

Bron: [OSM Wiki](https://wiki.openstreetmap.org/wiki/NL:StreetComplete).

StreetComplete is oorspronkelijk gemaakt door [Tobias Zwick ](https://wiki.openstreetmap.org/wiki/User:Westnordost) en later doorontwikkeld met [vele mede-auteurs](https://github.com/streetcomplete/StreetComplete/graphs/contributors).

## Installeren

StreetComplete is alleen beschikbaar voor Android (via Google Play of F-Droid), volg 
de link hier:

* [StreetComplete Home](https://streetcomplete.app/?lang=nl)

## Documentatie

Er is niet echt een manual, de app wijst zichzelf ook, maar wel meerdere plekken met informatie, die 
we hier bijeenbrengen:
 
* [De README](https://github.com/streetcomplete/StreetComplete/blob/master/README.md)
* [Een FAQ](https://wiki.openstreetmap.org/wiki/StreetComplete/FAQ)
* [StreetComplete op OSM Wiki](https://wiki.openstreetmap.org/wiki/NL:StreetComplete)
* [SC Forum/QA op GitHub](https://github.com/streetcomplete/StreetComplete/discussions)

## Gebruiken

Zie allereerst de [README](https://github.com/streetcomplete/StreetComplete/blob/master/README.md), in Nederlands:

StreetComplete (SC) zoekt automatisch naar nabijgelegen plaatsen waar een aanvulling nodig is, een "quest", soort opdracht, geheten.
SC toont deze "quests" als markeringen op de kaart. Elk van deze opdrachten kan ter plaatse worden opgelost 
door een eenvoudige vraag te beantwoorden. Bijvoorbeeld, door op een markering te tikken, kan de vraag "Wat is de naam van deze weg?" 
worden weergegeven, met een tekstveld om deze te beantwoorden. Meer voorbeelden worden getoond in de onderstaande schermafbeeldingen.

<figure markdown>
![StreetComplete](../assets/images/streetcomplete-screenshots-1.jpg){ data-title="Streetcomplete Screenshots" data-description="Bron: https://github.com/streetcomplete/StreetComplete" }
<figcaption>Streetcomplete Screenshots - Bron: https://github.com/streetcomplete/StreetComplete</figcaption>
</figure>

Het antwoord van de gebruiker wordt automatisch verwerkt en rechtstreeks in de OSM-database geüpload. 
Bewerkingen worden uitgevoerd in zinvolle changesets met het OSM-account van de gebruiker. 
Aangezien de app bedoeld is om te worden gebruikt in het veld, kan deze ook offline (via Settings) worden gebruikt en gaat zuinig om met datagebruik.

Om de app gebruiksvriendelijk te maken, zijn de opdrachten beperkt tot die welke beantwoord kunnen worden door eenvoudige vragen te stellen.
Dit is de [lijst met mogelijke quests](https://wiki.openstreetmap.org/wiki/StreetComplete/Quests).

!!! tip

    Soms zie je een situatie in het veld die je niet direct in StreetComplete kan oplossen. Bijvoorbeeld een
    wandelpad is opgeheven of een gebouw is afgebroken.
    In dat geval kun je locatiegebonden Notes en zelfs foto's neerleggen en die vervolgens thuis met een OSM Editor zoals
    Id of JOSM oplossen. Vergeet daarna niet de Note te "resolven"!
    Hoe een Note maken? Binnen SC doe je een "long-push" met je vinger op de plek waar je de Note wilt neerleggen.
    Of je kunt in de "quest" ingeven "Other Answers...|Don't Know" en dan de Note maken.
    [Hier kun je de laatste Notes in NL zien](https://resultmaps.neis-one.org/osm-notes-country?c=Netherlands), maar ook in je User Profiel
    als je op openstreetmap.org bent ingelogd.
 
### Team Modus

Er is een Team Modus wanneer je bijvoorbeeld met meerderen door dezelfde straat loopt en je 
elkaar niet in de weg wil zitten, mogelijk gaan we die in de workshop proberen.
