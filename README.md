---
title: JS und Responsive Design
author: Martin Kocur
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
    \lhead{Übungsblatt}
    \fancypagestyle{plain}{
      \fancyhf{}
      \rhead{Webtechnologien}
      \lhead{Übungsblatt}}





---


# 06 | JavaScript_02

## Aufgabe 1: JS Mozilla Developer Guides

Absolvieren Sie das Tutorial "A First Splash" der _Mozilla Developer Guides_ unter https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/A_first_splash. Implementieren Sie das  _Number Guessing Game_ mit Hilfe des Tutorials.  Wenn Sie das Spiel fertiggestellt haben, beherrschen Sie die grundlegenden Kenntnisse zu Funktionen, Schleifen, Operatoren und Bedingungen in JS! :)

## Aufgabe 2: Responsive Bildergallerie

Erstellen Sie in dieser Aufgabe eine kleine Bildergalerie mit 4 Bildern, die sich an die Bildschirmgröße anpasst.  Ihre Seite soll aus einem einfachen Header (über die gesamte Breite) mit einer Überschrift und einer Navigationsleiste mit drei Optionen (die Links können sie "leer" lassen) bestehen. Zusätzlich dazu soll Ihr HTML-Dokument über einen Hauptteil verfügen, der 4 verschiedene Bilder beinhaltet und diese auf folgende Weise darstellt:

- Für Screens mit einer Breite bis zu 576 Pixel sollen die Inhalte des Headers sowie die einzelnen Bilder untereinander dargestellt werden und die gesamte Breite des Screens füllen.
-  Für Screens bis zu 768 Pixel sollen die Optionen der Navigationsleiste nebeneinander dargestellt werden.
-  Für Screens bis 992 Pixel sollen jeweils zwei Bilder nebeneinander dargestellt werden.
-  Für Screens ab 992 Pixel  sollen alle vier Bilder nebeneinander dargestellt werden.

Verwenden Sie das Framework [\textcolor{blue}{Bootstrap 4}](https://getbootstrap.com/docs/4.5/getting-started/introduction/), um die Aufgabe zu lösen. Bootstrap ist ein open-source Framework, das Sie dabei unterstützt responsive Webseiten zu gestalten. Binden Sie die   [\textcolor{blue}{hier}](https://homepages.uni-regensburg.de/~kom13409/WTSS2020/U06/bootstrap.min.css) zur Verfügung gestellte CSS-Datei in Ihr HTML Dokument ein, um die responsiven Elemente von Bootstrap zu nutzen. Sie können den Inhalt kopieren und in eine CSS-Datei einfügen. Sie können darüber hinaus eine zusätzliche CSS-Datei definieren, die sie neben der Bootstrap-CSS in ihr Dokument einbinden können. 

Halten Sie sich an das _Grid-System_ von Bootstrap, mit dem Sie  Ihr HTML Dokument strukturieren können. Mehr Informationen zum Grid System finden Sie [\textcolor{blue}{hier}](https://getbootstrap.com/docs/4.0/layout/grid/) und [\textcolor{blue}{hier}](https://www.w3schools.com/bootstrap4/bootstrap_grid_basic.asp). Verwenden Sie die Entwicklertools Ihres Browsers, um in die responsive Darstellung zu wechseln und zu überprüfen, ob sich Ihre Seite an die Bildschirmgröße anpasst.



Zusätzlich sollen Ihnen die nachfolgenden Quellen dabei helfen, die Seite  mit Hilfe von Bootstrap zu gestalten:

- Allgemeine Informationen zu Bootstrap sind [\textcolor{blue}{hier}](https://www.w3schools.com/bootstrap4/default.asp) zu finden.
- Eine Überblick über die Bildschirmgrößen und den jeweiligen Breakpoints finden Sie [\textcolor{blue}{hier}](https://getbootstrap.com/docs/4.5/layout/overview/)
- Mehr Informationen zu Navbars in Bootstrap erhalten Sie [\textcolor{blue}{hier}](https://www.w3schools.com/bootstrap4/bootstrap_navbar.asp).
- Mehr zu responsiven Bildern in Bootstrap können Sie  [\textcolor{blue}{hier}](https://getbootstrap.com/docs/4.5/content/images/) nachlesen. 
- Sie können gerne Bilder aus dem [\textcolor{blue}{WikiArtEmotionSet}](https://docs.google.com/spreadsheets/d/19QDyny7b0CHnpotKPzwxMIK9_59uH4BZWEmqLupVPhQ/edit?usp=sharing) verwenden, um die Bildergalerie zu gestalten.



[\textcolor{blue}{Hier}](https://homepages.uni-regensburg.de/~kom13409/WTSS2020/U06/Gallery.html) finden Sie eine HTML-Seite, an der Sie sich orientieren können.



------

*Abgabekriterien:*

Laden Sie Ihre Antworten bis spätestens 22.06.2020 (23:59 Uhr) als zip-komprimierten Ordner auf GRIPS hoch.  Für dieses Übungsblatt haben Sie zwei Wochen Zeit. Benennen Sie die einzelnen Dateien pro Aufgabe sinnvoll und verwenden Sie geeignete Formate:

- Aufgabe 1: Ihr Number Guessing Game (HTML, JS, CSS)

- Aufgabe 2: Ihre responsive Bildergallerie (HTML, JS, CSS)

Der Name der Datei ergibt sich aus dem Präfix „Übung_WT_SS20“, der Nr. des Übungsblattes, ihrem Vor- und Nachnamen jeweils getrennt durch _ .

 

Beispiel: **Übung_WT_SS20_6_Max_Mustermann.zip**

