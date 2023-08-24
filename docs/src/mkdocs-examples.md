---
title: Voorbeelden mkdocs formatting
---

Dit is bedoeld voor de editors van deze workshop, bevat verschillende
format-constructies voor Markdown en mkdocs.

# Quoting

Indentatie

    Een basis workshop OSM Mapping. Leer de OSM basics, werken met de ID-editor, 
    maak kennis met de OSM-NL community. 
    Maar vooral met recente slimme OSM surveyor apps zoals 
    StreetComplete en EveryDoor gaan we naar buiten! Kijken wat in 
    Middelburg ontbreekt en op de kaart zetten! Indien tijd over: hoe 
    werken met de Overpass APIs om data uit OSM te halen, in QGIS bijvoorbeeld, 
    en/of werken met de advanced JOSM Editor.

# Formatting

Oefeningen

!!! question "Example exercise"

    A section marked like this indicates that you can try out the exercise.

Tips en tricks in de tekst:

!!! tip

    Tips share additional help on how to best achieve tasks

Examples are indicated as follows:

Code
``` {.html linenums="1"}
<html>
    <head>
        <title>This is an HTML sample</title>
    </head>
</html>
```

Configuration
``` {.yaml linenums="1"}
my-collection:
    type: collection
    title: my cool collection title
    description: my cool collection description
```

Snippets which need to be typed in a on a terminal/console are indicated as:

<div class="termy">
```bash
echo 'Hello world'
```
</div>


# Plaatjes

Plaatjes zijn "Lightbox-enabled", dus door te klikken op plaatje te vergroten, 
bijv als "slide" te gebruiken.

<figure markdown>
![Architecture](assets/images/testplaatje.jpg){ data-title="testplaatje" data-description="dit is een testplaatje" }
<figcaption>Voorbeeld Caption</figcaption>
</figure>

# Embed Video

Voorbeeld OpenStreetMap tutorial, adding building in Id-Editor:

![type:video](https://www.youtube.com/embed/E1YJV6I_rhY)

