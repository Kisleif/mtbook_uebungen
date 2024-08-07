---
blogpost: true
date: Oct 01, 2023
location: Übungszettel
category: Übung
tags: Dreieck, Sägezahn, Rechteck, Fourier-Reihe, Audio-Technik, Signal, Aliasing, Abtastung
---

# Synthesizer- und Audio-Technik: Warum klingt Dreieckswelle leise und kläglich?

Am 29.09.2011 hat Globoflexia online folgendes Problem gepostet:

> Hallo Synth-Community,
> 
> vor kurzem habe ich begonnen, mich mit meinem Arturia Microbrute in das riesige Feld der Klangsynthese einzuarbeiten. Beim Herumprobieren habe ich etwas Seltsames bemerkt und hoffe auf eure Hilfe:
> 
> Wenn ich meinen Oszillator eine reine Dreieckswelle ausgeben lasse (ohne Filter oder ähnliches), dann scheint die Lautstärke ab einer gewissen Frequenz stark abzufallen. Töne knapp oberhalb von ca. 600 Hz, z.B. das c'' (523 Hz), klingen noch schön laut und satt, aber wenn ich dann ein f'' (698 Hz) spiele, scheinen dem Ton einige Komponenten zu fehlen und er klingt nur noch sehr leise und kläglich. Dieser Effekt tritt nicht auf, wenn ich eine andere Wellenform wie z.B. Sägezahn verwende.
> 
> Der Microbrute ist an einen mittelguten Stereoanlagen-Verstärker angeschlossen, an dem normale Boxen hängen. Auch wenn ich Aktiv-Kopfhörer direkt an den Microbrute anschließe, tritt der Effekt bei der Dreieckswelle auf.
> 
> Kommt jemandem dieser Effekt bekannt vor? Wie kann ich das lösen? Wie kann ich der Sache weiter nachgehen?
> 
> Vielen Dank für eure Hilfe!

1. **Analyse der Obertonstruktur:**

* Vergleichen Sie die Amplituden der Obertöne (höhere Harmonische der Grundfrequenz) von Dreieckswellen, Sägezahnwellen und Rechteckwellen. 
* Beschreiben Sie, welche Obertöne (Frequenzen) jede dieser Wellenformen enthält und wie die Amplituden der Obertöne gedämpft werden.

Gegebene Parameter: Grundfrequenz: $100\,\mathrm{Hz}$

2. **Verstehen der Klangunterschiede:**

  * Erklären Sie, warum eine Dreieckswelle bei höheren Frequenzen leiser und dumpfer klingt im Vergleich zu Sägezahn- oder Rechteckwellen.
  * Geben Sie eine Erklärung basierend auf der Obertonstruktur und der Dämpfung der Amplituden.

3. **Praktische Anwendung:**

  * Sie bemerken, dass ein Dreieckssignal bei einer Frequenz von $700\,\mathrm{Hz}$ sehr leise und kläglich klingt, während das gleiche Signal bei $500\,\mathrm{Hz}$ laut und satt klingt. Erklären Sie diesen Effekt und geben Sie an, welche Harmonischen in beiden Fällen vorhanden sind und wie ihre Amplituden gedämpft werden.

Gegeben: Frequenzen: $500\,\mathrm{Hz}$ und $700\,\mathrm{Hz}$


4. **Berechnung der Abtastrate:**

  * Berechnen Sie die notwendige Abtastrate, um ein Dreieckssignal mit einer Grundfrequenz von $1\,\mathrm{kHz}$ korrekt zu digitalisieren, ohne dass Aliasing bei Audiofrequenzen auftritt.
  * Geben Sie eine Erklärung, warum diese Abtastrate gewählt werden muss und wie das Abtasttheorem nach Shannon angewendet wird.

