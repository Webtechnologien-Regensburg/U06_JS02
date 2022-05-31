---
title: JavaScript
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

Absolvieren Sie das Tutorial "A First Splash" der _Mozilla Developer Guides_ unter https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/A_first_splash. Implementieren Sie das  _Number Guessing Game_ mit Hilfe des Tutorials.  Wenn Sie das Spiel fertiggestellt haben, beherrschen Sie die grundlegenden Kenntnisse zu Funktionen, Schleifen, Operatoren und Bedingungen in JS!

## Aufgabe 2: Kalender

Erstellen Sie in dieser Aufgabe einen Jahreskalender, in welchem  alle Tage/Monate des Jahres 2021 wahrheitsgetreu visualisiert werden. Die Ausgangslage stellt [\textcolor{blue}{folgendes Projekt}](https://elearning.uni-regensburg.de/mod/resource/view.php?id=1801878) dar. Hierbei werden bereits die zwölf Monate des Jahres zur Auswahl angezeigt. Durch Anklicken einer Monatsplakette sollen nun dynamisch und mit Hilfe von JavaScript die jeweiligen Tage des ausgewählten Monats erstellt und unterhalb der Auswahl angezeigt werden. 

Bedenken Sie, dass die Monate eine unterschiedliche Länge haben können. Speichern Sie daher die spezifische Länge jedes Monats in einem Array ab und lesen diese Information an gegebener Stelle wieder aus. 

Zusätzlich sollen Sie den ausgewählten Monat sowie alle Sonntage des Monats einfärben. Auch die Information, an welcher Stelle der erste Sonntag eines Monats auftritt, können Sie in einem Array abspeichern und an gegebener Stelle wieder auslesen. Alle weiteren Sonntage des Monats können dann errechnet werden.

Sie müssen hierfür folgende Funktionalitäten umsetzen:

1. Eine Funktion zur Erstellung der Visualisierung eines Monatstages (z.B. Zahl zw. 01 u. 31 sowie Abkürzung für den Wochentag).</li>
2. Eine Schleife zur Erstellung aller Monatstage für den ausgewählten Monat.</li>
3. Eine Funktion, welche das Klick-Event auf einen Monat abfängt und die Erstellung der Monatstage anstößt.</li>
4. Eine CSS-Klasse, welche den ausgewählten Monat farblich hervorhebt. </li>
5. Eine CSS-Klasse, welche jeden Sonntag des Monats farblich hervorhebt.</li>



Vergessen Sie nicht ihre JavaScript-Datei in die HTML-Datei einzubinden. Das Setzen der CSS-Klasse für eine individuelle Einfärbung der Sonntage kann entweder in einer eigenen Schleife oder während der Erstellung von (2) erfolgen. 

------

*Abgabekriterien:*

Laden Sie Ihre Antworten bis spätestens 06.06.2020 (23:59 Uhr) als zip-komprimierten Ordner auf GRIPS hoch. Benennen Sie die einzelnen Dateien pro Aufgabe sinnvoll und verwenden Sie geeignete Formate:

- Aufgabe 2: Ihr Kalender-Projekt (HTML, JS, CSS)

Der Name der Datei ergibt sich aus dem Präfix „Übung_WT_SS22“, der Nr. des Übungsblattes, ihrem Vor- und Nachnamen jeweils getrennt durch _ .

 

Beispiel: **Übung_WT_SS22_6_Max_Mustermann.zip**

