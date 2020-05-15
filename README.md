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

- eine Seite mit Informationen zum Künstler mit einem Link zu dem weiterführenden Wikipedia-Artikel. 
- eine Seite mit einer einfachen Bildergalerie, die neben - oder untereinander mindestens zwei Kunstwerke aus dem Repertoire des Künstlers darstellt, und eine kurze Beschreibung zum jeweiligen Kunstwerk beinhaltet.
- eine Seite mit Informationen zur Epoche (auch hier können Sie mit Bildern arbeiten).

Die Informationen zu Ihrem Künstler und den Kunstwerken können Sie über das WikiArtEmotionSet und den weiterführenden Links abrufen, und in Ihre Seite integrieren.

Sie können sich bei der Gestaltung Ihrer Webseite an den Übungsaufgaben in der Vorlesung und Übung  orientieren. Spielen Sie mit verschiedenen Schriftarten für die Überschriften und Texte, um die Seite ansprechend zu gestalten. Verwenden Sie für die einzelnen Seiten semantische Elemente, wie z.B. _header_, _nav_, main und _footer_ (siehe https://www.w3schools.com/html/html5_semantic_elements.asp), um Ihren einzelnen HTML-Dokumenten Struktur zu verleihen. 

Sie finden unter https://homepages.uni-regensburg.de/~kom13409/WTSS2020/Home.html eine kleine HTML Seite, an der Sie sich orientieren können.



Die folgenden Tutorials sollen Sie bei der Erstellung Ihrer Webseite unterstützen:



_Seitenstrukturierung_:

Strukturieren Sie die Seite gemäß den Empfehlungen[^3] .

_Navigationsleiste_:

Verwenden Sie eine Navigationsleiste, um die Navigation zwischen den HTML-Dokumenten zu steuern[^4].

_Fonts_:

Verwenden Sie andere Schriftarten, um Ihre Seite ansprechend zu gestalten[^5][^6].

_Shadows_:

Hier lernen Sie Schatteneffekte kennen[^7].

_Intro_:

Hier finden Sie eine kleine Einführung in CSS[^8].

 



------

*Abgabekriterien:*

Laden Sie Ihre Antworten bis spätestens 31.5.2020 (23:59 Uhr) als zip-komprimierten Ordner auf GRIPS hoch.  Benennen Sie die einzelnen Dateien pro Aufgabe sinnvoll und verwenden Sie geeignete Formate:

- Aufgabe 1 und 2: Ein PDF-Dokument mit Ihrer Lösung
- Aufgabe 3: Das gesamte Projekt (HTML,CSS)

Der Name der Datei ergibt sich aus dem Präfix „SL_WT_SS20“, der Nr. der Studienleistung, ihrem Vor- und Nachnamen jeweils getrennt durch _ .

 

Beispiel: **SL_WT_SS20_1_Max_Mustermann.zip**

[^1]: https://docs.google.com/spreadsheets/d/19QDyny7b0CHnpotKPzwxMIK9_59uH4BZWEmqLupVPhQ/edit?usp=sharing
[^2]: http://saifmohammad.com/WebPages/wikiartemotions.html
[^3]: https://wiki.selfhtml.org/wiki/HTML/Tutorials/HTML5/Seitenstrukturierung
[^4]: https://www.w3schools.com/css/css_navbar.asp
[^5]: https://www.w3schools.com/css/css_font.asp
[^6]: https://www.w3schools.com/cssref/css_websafe_fonts.asp
[^7]: https://www.w3schools.com/css/css3_shadows_box.asp
[^8]: https://www.w3schools.com/css/css_intro.asp