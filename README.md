---
title: Studienleistung 1
author: Martin Kocur
documentclass: scrartcl
classoption:
  - a4paper
header-includes: |
    \usepackage{german} 
    \usepackage[a4paper,left=2.5cm, right=2.5cm,top=2.5cm, bottom=3cm]{geometry}
    \usepackage{fancyhdr}
    \pagestyle{fancy}
    \fancyhf{}
    \rhead{Webtechnologien}
    \lhead{SL1}
    \fancypagestyle{plain}{
      \fancyhf{}
      \rhead{Webtechnologien}
      \lhead{SL1}}


---

## Aufgabe 1: Kommunikation im Internet (1 Punkt)

Beschreiben und skizzieren Sie die grundlegende Funktionsweise der Kommunikation mittels Paketen zwischen einzelnen Punkten in einem Netzwerk (100 bis 150 Wörter). 

## Aufgabe 2: Das Document Object Model (1 Punkt)

In der Vorlesung haben Sie das Document Object Model (DOM) kennengelernt.  Erläutern Sie das DOM anhand eines Beispiels (100 bis 150 Wörter).

## Aufgabe 3: Erstellen einer einfachen HTML-Seite (8 Punkte)

In dieser Aufgabe sollen Sie eine einfache HTML-Seite erstellen. Verwenden Sie dafür HTML, um den Inhalt zu definieren und zu strukturieren, und CSS, um die Seiten zu designen.  

Ihre HTML-Seite soll Informationen über einen Künstler zur Verfügung stellen. Suchen Sie sich dafür einen Künstler aus dem [WikiArtEmotionSet](https://docs.google.com/spreadsheets/d/19QDyny7b0CHnpotKPzwxMIK9_59uH4BZWEmqLupVPhQ/edit?usp=sharing)[^1] aus, das eine Sammlung von Kunstwerken/Bildern und Sentiment/Emotions-Annotationen enthält. Mehr Informationen zum Datensatz des WikiArtEmotionSets erhalten Sie unter [_The WikiArt Emotions Dataset_](http://saifmohammad.com/WebPages/wikiartemotions.html)[^2].

Die Webseite soll mindestens über drei einzelne Seiten verfügen, zu denen Sie jederzeit navigieren können. Jede Seite soll unterschiedliche Informationen darstellen:

- eine Seite mit Informationen zum Künstler mit einem Link zu dem weiterführendem Wikipedia-Artikel. 
- eine Seite mit einer einfachen Bildergalerie, die neben - oder untereinander mindestens zwei Kunstwerke aus dem Repertoire des Künstlers darstellt.
- eine Seite mit Informationen zur Epoche.

Die Informationen zu Ihrem Künstler und den Kunstwerken können Sie über das WikiArtEmotionSet und den weiterführenden Links abrufen, und in Ihre Seite integrieren.

Sie können sich bei der Gestaltung Ihrer Webseite an den Übungsaufgaben in der Vorlesung und Übung  orientieren. Spielen Sie mit verschiedenen Schriftarten für die Überschriften und Texte, um die Seite ansprechend zu gestalten. Verwenden Sie für die einzelnen Seiten semantische Elemente, wie z.B. _header_, _nav_, _section_ und _footer_ (siehe https://www.w3schools.com/html/html5_semantic_elements.asp), um Ihren einzelnen HTML-Dokumenten Struktur zu verleihen. 

Sie können sich an folgendem Screenshot orientieren und sich von der Struktur der HTML Seite inspirieren lassen.

![Beispiel für eine einfache HTML - Seite mit einem Header, einer Navigationsbar und dem Hauptinhalt](Home.PNG){ height=10cm }



------

*Abgabekriterien:*

Laden Sie Ihre Antworten bis spätestens 31.5.2020 (23:59 Uhr) als zip-komprimierten Ordner auf GRIPS hoch.  Benennen Sie die einzelnen Dateien pro Aufgabe sinnvoll und verwenden Sie geeignete Formate:

- Aufgabe 1 und 2: Ein PDF-Dokument mit Ihrer Lösung
- Aufgabe 3: Das gesamte HTML-Projekt

Der Name der Datei ergibt sich aus dem Präfix „SL_WT_SS20“, der Nr. der Studienleistung, ihrem Vor- und Nachnamen jeweils getrennt durch _ .

 

Beispiel: **SL_WT_SS20_2_Max_Mustermann.zip**

[^1]: https://docs.google.com/spreadsheets/d/19QDyny7b0CHnpotKPzwxMIK9_59uH4BZWEmqLupVPhQ/edit?usp=sharing
[^2]: http://saifmohammad.com/WebPages/wikiartemotions.html