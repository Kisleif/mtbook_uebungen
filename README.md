#  [Übungspool](https://kisleif.github.io/mtbook/_website/uebungen/index.html) der Messtechnik der HSU

In diesem Repository werden alle Übungsaufgaben der Messtechnik als Markdown (.md) Dateien gesichert. 
Dies sind die Quelldateien, woraus später die HTML Webseite kompiliert wird.

## Issues nutzen!!!
Bevor ihr eine Aufgabe korrigiert, erstellt erst ein Issue, mit dem Titel der Aufgabe, und assigned es entsprechend. So umgehen wird das Problem, dass mehrere Leute die gleiche Aufgabe korrigieren. 

## Aufgaben korrigieren und neue erstellen
Dies geht bereits ohne Klonen des Repositories direkt im Browser:
Ihr möchtet eine Aufgabe korrigieren? Wann sucht die dazugehörige .md Datei raus und editiert sie im Browser (oder dem geklonten Repository auf eurem Rechner).
Ihr möchtet eine neue Aufgabe hinzufügen? Dann erstellt eine neue .md Datei im Hauptordner im Browser (oder dem geklonten Repository auf eurem Rechner).
Solltet ihr im Repository auf eurem Rechner arbeiten, vergesst nicht im Anschluss zu committen and pushen. 

## Aufgaben als HTML kompilieren
Dafür müsst ihr dieses Repository auf eurem PC klonen. 
Navigiert im Terminal in den Hauptordner (mtbook_uebungen) und führt folgenden Terminal-Befehl aus: `ablog build`.
Danach findet ihr die HTML Datein jeder einzelnen ÜBungsaufgabe im Unterordner `_website`. Klickt diese einfach an (z.B. `index.html`).

Bei Fehlern/Errors versucht `ablog clean` mit anschließendem `ablog build`.

Ihr könnt diesen Ordner auch pushen. 

## Upload der Aufgaben in den Online Pool 
KSI wird die Übungen online stellen, welche aus diesem Repository mittels `ablog build` erstellt werden. Hier für eine kurze Nachricht an KSI schreiben. Sie wird dann neue HTMLs generieren und im  [Übungspool](https://kisleif.github.io/mtbook/_website/uebungen/index.html) veröffentlichen. 


