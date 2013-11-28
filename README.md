Koaltionsvertrag 2013 - Enhanced Edition
----------------------------------------

Für die Darstellung im Web angepasste und durch Verlinkungen und Quellenangaben erweitere
Version des Koalitionsvertrages von CDU/CSU und SPD. Keine offizielle Quelle!

### Helft mit bei der Kontextualisierung

Der Koalitionsvertrag ist gespickt mit einer Vielzahl von Fachbegriffen und er enthält
zahlreiche Hinweise auf Institutionen, Förderprogramme, usw.. Mit Eurer Hilfe würde ich
hier in einem ersten Schritt gerne mehr Kontext schaffen durch die Verlinkung mit
Originalquellen und Hintergrundartikeln.

**Für Folgendes bietet sich dieses im Speziellen an:**

* Verlinkung von Institutionen, Verbänden u.ä. (z.B. [EZB](https://www.ecb.europa.eu/ecb/html/index.de.html), [Fraunhofer-Gesellschaft](http://www.fraunhofer.de/))
* Verlinkung von Programmen, Initiativen u.ä. (z.B. [Bundesverkehrswegeplan](http://www.bmvbs.de/DE/VerkehrUndMobilitaet/Verkehrspolitik/Verkehrsinfrastruktur/Bundesverkehrswegeplan/bundesverkehrswegeplan_node.html))
* Verlinkung von Fachbegriffen, i.d.R. sinnvoll zu Wikipedia (z.B. [Crowdfunding](http://de.wikipedia.org/wiki/Crowdfunding), [Wohnungsbauprämie](http://de.wikipedia.org/wiki/Wohnungsbaupr%C3%A4mie))
* Verlinkung von Gesetzestexten (z.B. [Artikel 7 EUV](http://dejure.org/gesetze/EU/7.html))

[Hier](http://holgerd77.github.io/koalitionsvertrag/1_wachstum/1_1_wirtschaft.html#tourismus) 
könnt Ihr sehen, wie eine Verlinkung im Koalitionsvertragstext aussieht.


Ihr könnt auch andere Dinge verlinken, aber bitte verzichtet auf Links zu 
bewertenden Quellen ("Warum Vorhaben XY eine doofe Idee ist") oder Meinungsartikeln.

### Schritt-für-Schritt Anleitung

Hier eine Anleitung zum Einfügen eines Links (am obigen Beispiel):

1. Erstelle einen ``Fork``, also eine Kopie dieses Repositories. Klicke hierfür auf den
   Fork-Button oben rechts auf dieser Seite. Du brauchst hierfür einen Account bei GitHub.
   Du solltest Dich nun in Deiner Kopie des Koalitionsvertrags-Repositories befinden.
2. Suche die Datei, in der Du einen Link einfügen möchtest. Es gibt für jedes Hauptkapitel
   einen Ordner (z.b. ``1_wachstum``) und für jedes Unterkapitel eine Datei 
   (z.B. ``1_1_wirtschaft.rst``). Klicke auf die entsprechende Datei.
3. Um eine Datei zu bearbeiten, klicke auf ``Edit`` oben rechts im Fenster. Suche die 
   Textstelle, wo Du einen Link einfügen möchtest.
4. Ersetze die entsprechenden Wörter mit dem Link in Form von folgender Syntax:

```
vorher: Deutsche Zentrale für Tourismus (DZT)
```   
```
nachher: `Deutsche Zentrale für Tourismus (DZT) <http://www.germany.travel>`_
```

5. Achte hier vor allem auf auf die Wahl des korrekten - schräggestellten -  Anführungszeichens,
   im Zweifel kopiere das Anführungszeichen aus diesem Beispiel. 
6. Überprüfe sowohl die korrekte Anzeige als auch die Funktionalität des Links
   mit der Preview-Funktion oben links.
7. Wenn alles funktioniert, gehe auf ``Commit Changes`` ganz unten auf der Seite.
8. Gehe zur Hauptseite Deines geforkten Repositories und klicke ``Pull Request`` oben 
   rechts über der Ordneransicht. Klicke auf ``Click to create a pull request for this comparison``.
   Schaue Dir ggf. den Quelltext noch einmal an. Wenn Dir etwas komisch vorkommt, breche hier ab
   und frage noch mal nach. Ansonsten schicke den Pull Request mit ``Send pull request``.
9. Fertig! Ich schaue in regelmäßigen Abständen über die Pull Requests drüber, integriere Sie
   ins Hauptrepository und erstelle eine neue Version der generierten Webseiten.


### Kontakt
[@HolgerD77](https://twitter.com/holgerd77)


### Page Creation Process
This document was created using the following tools:
* [Python Sphinx](http://sphinx-doc.org/) for document creation
* [PDFMiner](http://www.unixuser.org/~euske/python/pdfminer/) for PDF parsing

Chapters/text is in reStructuredText Format, using GitHub Pages for page
hosting (see gh-pages Branch) by following the following tutorial article
for connecting Sphinx and GitHub Pages:
* http://lucasbardella.com/report/hosting-your-sphinx-docs-in-github/

