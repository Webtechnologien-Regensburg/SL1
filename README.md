---
title: Studienleistung 1
author: Alexander Bazo und Jakob Fehle
documentclass: scrartcl
classoption:
  - a4paper
header-includes: |
    \usepackage{german}
	\usepackage{xcolor} 
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

# Eine erste Webseite mit HTML & CSS

Auf der Webseite [https://www.wikiart.org/](wikiart.org) finden Sie zahlreiche zahlreiche Kunstwerke unterschiedlicher Epochen und Stilrichtungen. Die Seite bietet neben vielen lizenzfrei nutzbaren Abbildungen auch biographische Informationen zu den jeweiligen Künstlern und Künstlerinnen. Entwerfen Sie auf Basis dieser Inhalte eine Webseite, mit der Sie eine der Stilrichtung und deren bedeutendsten Vertreter vorstellen. **Suchen Sie sich dazu eine Richtung (z.B. den *Impressionismus*) aus, und erstellen Sie mit Hilfe von HTML und CSS eine Webseite, die die folgenden Anforderungen erfüllt:**

- Auf einer Startseite präsentieren Sie **allgemeine Informationen zur Stilrichtungen** sowie eine **Liste bedeutender Vertreter und Vertreterinnen**
- Für vier besonders wichtige Künstler oder Künstlerinnen erstellen Sie separate Unterseite, die aus den Listeneinträgen heraus verlinkt sind
- Zu den übrigen Künstlern und Künstlerinnen verlinken Sie in der Liste die jeweiligen Artikel der Wikipedia
- Auf den Unterseiten präsentieren Sie die wichtigsten biographischen Informationen sowie eine Auswahl aus mindestens fünf wichtigen Werken zu denen neben dem Werk als Bild (`img`-Tag) auch Informationen zum Titel, Entstehungsjahr und Medium aufgeführt sind

Bei der Strukturierung und Gestaltung Ihrer Seite können Sie sich z.B. an diesem Beispiel Orientieren.

![Überblicksseite zur Stilrichtung Impressionismus][example-website-main.png]
![Detailseite zur Künstlerin Mary Cassat][example-website-sub.png]

## Mögliche Erweiterungen

Nutzen Sie diese Aufgabe auch, um sich über die geforderten Punkte hinaus mit der Verwendung von HTML & CSS vertraut zu machen. Überlegen Sie sich z.B., wie Sie die (farbliche) Gestaltung der Seite an das inhaltliche Thema anpassen können. Nutzen Sie die Möglichkeiten zur typographischen Gestaltung der angezeigten Texte aus. Verwenden Sie im CSS auch *state*-Selektoren, um z.B. Elemente beim *hovern* hervorzuheben, um die Nutzer und Nutzerinnen auf Interaktionsmöglichkeiten hinzuweisen.

## Weitere Hinweise

- Im WikiArt-Projekt sind zu jedem Künstler bzw. jeder Künstlerin auch die zugehörigen Wikipediartikel verlinkt
- Der Dienst [Google Web Fonts](https://fonts.google.com/) erlaubt das einfache Einbinden und Verwenden zusätzlicher Schriftarten
- Auf der Webseite [coolors.co](https://coolors.co/) können Sie sehr einfach Farbschemen zur graphischen Gestaltung Ihrer Webseite erstellen
- Adobe bietet [ein Tool](https://color.adobe.com/de/create/image) an, über das Sie Farbschemen aus existierenden Bildern, z.B. Gemälden extrahieren können
- Wenn Sie die *Flexbox* zur Gestaltung Ihrer Seite verwenden wollen, finden Sie [hier](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) eine gute Übersicht über deren Verwendung
- Im *Mozilla Developer Network* finden Sie eine Sammlung von [CSS-Rezepten](https://developer.mozilla.org/en-US/docs/Web/CSS/Layout_cookbook) für einige häufige Aufgaben

## Abgabe

Laden Sie Ihre Antworten **bis spätestens 21.5.2021 (23:59 Uhr) als zip-komprimierten Ordner auf GRIPS hoch**. Benennen Sie die einzelnen Dateien sinnvoll und verwenden Sie geeignete Formate.Der Name der Datei ergibt sich aus dem Präfix „SL_WT_SS21“, der Nr. der Studienleistung, ihrem Vor- und Nachnamen jeweils getrennt durch _ (Beispiel: `SL_WT_SS21_1_Max_Mustermann.zip`).