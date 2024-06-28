---
blogpost: true
date: Nov 29, 2023
category: Übung
location: Zettel_9
tags: Widerstand, Elektronik, Operationsverstärker
---

# Verstärkerschaltung

Gegeben sei die in der Abbildung dargestellte Verstärkerschaltung mit $R_1 = 1\,\mathrm{k\Omega}$, $R_3 = R_1 || R_2$, wobei der Operationsverstärker eine Temperaturempfindlichkeit von $|U_\mathrm{OS} / \Delta \vartheta | = 2{,}5\mathrm{\mu V / K}$ hat. 

```{figure} pictures/OS.png
:class: .dark-light
---
height: 150px
---
Verstärkerschaltung mit Operationsverstärker.

```

* Berechnen Sie die Widerstände für eine Verstärkung von 40dB.

````{tip}
:class: dropdown
40dB ist als Verstärkungsfaktor gegeben, d.h. es gilt $k = 40\,\mathrm{dB}$. Welcher Verstärkung entspricht dies in nicht-dB Einheiten? Zur Umrechnung benutzen Sie $v = 20\cdot \log k$. Außerdem können Sie die Verstärkung in Abhängigkeit von den Widerständen $R_1$ und $R_2$ angeben ($k = R_2/R_1$). 
````

* Wie groß darf die Spannung am Eingang maximal werden, wenn die Ausgangsspannung auf 12V begrenzt ist?

````{tip}
:class: dropdown
Für die Verstärkung gilt allgemein: $k = U_a / U_e$...

````

* Der Verstärker soll in einem Temperaturbereich von $20^\circ\mathrm C$ bis $80^\circ\mathrm C$ zum Einsatz kommen. Ermitteln Sie den kleinstmöglichen Messbereich, bei dem der Offsetfehler höchstens 1\% vom Messbereichsendwert ausmacht. 

````{tip}
:class: dropdown
Wie groß ist das gewünschte Temperaturintervall $\Delta \vartheta$? Was für einen maximale Abweichung (in $\mu \mathrm V$) begehen Sie für die angegebene Temperaturempfindlichkeit $|U_\mathrm{OS} / \Delta \vartheta | = 2{,}5\mathrm{\mu V / K}$? Was bedeutet dies für die Abweichung bei Ausgangsspannung, $\Delta U_a = k \cdot \Delta U_e$? Diese Abweichung gegenüber dem Ausgangsmessbereich soll kleiner sein als 1%, also $\Delta U_a / U_{a,\mathrm{min.Messbereich}} < 1%$...
````