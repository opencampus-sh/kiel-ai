# Woche 2 - Grafische Darstellung von Daten

### Diese Woche werden wir...

folgende Themen behandeln:

* Darstellung von unterschiedlichen Datenstrukturen&#x20;
* Besprechung der Übungsaufgaben der vergangenen Woche
* Import von Daten
* Struktur der Funktionen in ggplot
* Erstellen eines Balkendiagramms

### Lernressourcen

{% file src="../.gitbook/assets/230425_Grafische Darstellung von Daten (1).pdf" %}

* Kapitel 1 des Kurses [Introduction to Data Visualization with ggplot2](https://campus.datacamp.com/courses/data-visualization-with-ggplot2-1) bei datacamp
* [R-Notebook](https://github.com/opencampus-sh/einfuehrung-in-data-science-und-ml/blob/main/Beispiele%20zu%20Diagrammen%20aus%20Woche%202.Rmd) mit Beispielen für grafische Abbildungen
* Video zur [Selektion von Zeilen und Spalten in R](https://vimeo.com/822158843?share=copy) (9 Minuten)
* Video zur [Selektion mit Booleschen Vektoren](https://vimeo.com/822446585?share=copy) (5 Minuten)
* Video zu [Skalentypen](https://vimeo.com/822451187?share=copy) (2,5 Minuten)
* Video zum [Anlegen von RStudio-Projekten](https://vimeo.com/822451090?share=copy) (2 Minuten)

### Bis zur nächsten Woche solltet Ihr...

* [x] Schaut Euch bitte folgendes Video (4 Minuten) an, um die Relevanz von Konfidenz-Intervallen zu verstehen: [https://www.youtube.com/watch?v=tFWsuO9f74o](https://www.youtube.com/watch?v=tFWsuO9f74o)\

* [x] Legt ein R-Studio-Projekt-Verzeichnis an und speichere dort die Dateien „kiwo.csv“, „umsatzdaten\_gekuerzt.csv“ und „wetter.csv“ aus [diesem Github-Repository](https://github.com/opencampus-sh/einfuehrung-in-data-science-und-ml).\

*   [x] Erstellt ein R-Notebook, das

    * den Datensatz "umsatzdaten\_gekuerzt.csv" importiert
    * mit Hilfe eines Balkendiagramms über alle Warengruppen hinweg den Zusammenhang der durschnittlichen Umsätze je Wochentag darstellt

    Benutzt für den Beginn des Programms wenn Ihr möchtet [diesen Programmcode](https://github.com/opencampus-sh/einfuehrung-in-data-science-und-ml/blob/main/starthilfe.Rmd) als Starthilfe.\

* [x] Fügt in einem zweiten Schritt zusätzlich Konfidenzintervalle der Umsätze je Wochentag hinzu. Lese Dir dazu das in der [R Graph Gallery („barplot with error bars“)](https://www.r-graph-gallery.com/4-barplot-with-error-bar.html) dargestellte Vorgehen durch und passe es auf den Datensatz mit den Umsatzdaten an.\

* [x] Als zusätzliche (optionale) Aufgabe könnt Ihr versuchen, die Umsätze je Wochentag getrennt nach Warengruppe darzustellen (ein eigenes Balkendiagramm je Warengruppe), um einen genaueren Einblick in die Daten zu erhalten.\

*   [x] Installiert bitte die Versionierungssoftware "git" auf Eurem Rechner: [https://git-scm.com/downloads](https://git-scm.com/downloads)\
    Um zu kontrollieren, ob die Installation von Git auch korrekt von RStudio erkannt wurde, kannst Du in RStudio (nach Neustart von RStudio) unter _Tools_ > _Version Control_ gehen und dort _git_ als Version Control System für Dein Projekt auswählen (siehe auch Screenshots unten am Ende). Achte dabei darauf, dass Dein Projekt auch geöffnet ist - Du erkennst es an der Anzeige oben rechts.\
    Falls _git_ dort nicht auswählbar sein sollte, gehe in RStudio zu _Tools_ > _Global Options_ > _Git/SVN_ und überprüfe, ob in dem Eingabefeld zu „Git executable“ der richtige Verweis eingetragen ist. Der Verweis sollte eine der folgenden Formen haben:

    Mac und Linux: **/usr/bin/git**\

* [x] Als Einführung in die Versionierung mit git absolviert bitte das Kapitel "Basic Workflow" des Kurses [Introduction to Git](https://learn.datacamp.com/courses/introduction-to-git-for-data-science) bei Datacamp.\


Die Aufgaben sind noch einmal recht arbeitsintensiv, daher fangt am besten rechtzeitig vor dem Termin in der nächsten Woche damit an.

![Auswählen der Einstellungen für die Versionierung des aktuellen Projektes](<../.gitbook/assets/Selection of Version Control.png>)

![Auswählen der Software für die Versionierung des aktuellen Projektes](<../.gitbook/assets/grafik (1) (1).png>)
