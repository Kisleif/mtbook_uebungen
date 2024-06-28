---
blogpost: true
date: Nov 29, 2023
category: Übung
location: Zettel_9
tags: Systematisch, Stromrichtig, Spannungsrichtig, Messabweichung, Elektronik
---


# Systematische Messabweichung
Zwei unbekannte Widerstände $R$ im $\mathrm{k\Omega}$-Bereich werden mit zwei Messschaltungen bestimmt:

```{figure} pictures/strom_spannungsrichtig.png
:class: .dark-light
---
height: 150px
name: optional-label
---
Schaltungen zur Bestimmung von Widerständen nach $R = U/I$

```

* Welches Schaltbild stellt die stromrichtige und welche die spannungsrichtige Schaltung dar?
* Berechnen Sie für beide Fälle den unkorrigierten und korrigierten Widerstandswert. Bei welcher Schaltung ist der relative Fehler kleiner? Benutzen Sie folgende Wert: einen Strom von $I = 2{,}4\mathrm{mA}$, eine Spannung von $U=10\mathrm V$ und Innenwiderstände von $R_{A}=4\Omega$ und $R_{V}= 10\mathrm{k}\Omega$.
* Für welche Grenzwerte von $R$ sollte man strom- bzw. spannungsrichtig messen? Setzen Sie erneut $R_{A} = 4\,\mathrm \Omega$ und $R_{V} = 10\,\mathrm{k\Omega}$.


````{tip}
:class: dropdown
* Schaltung 1 (korrigiert):

$$U = R_KI = R_K\cdot (I-I_V)$$

$$I_V = U / R_{V}$$

$$\Rightarrow R_K = ... = 7{,}14\,\mathrm{k\Omega} $$

$$\frac{\Delta R}{R} = \frac{\Delta I}{I} = ... = -41\%$$

* Schaltung 2 (korrigiert):

$$U = R_KI $$

$$R_K = R - R_{A}$$

$$\Rightarrow R_K = ... = 4{,}162\,\mathrm{k\Omega} $$

$$\frac{\Delta R}{R} = ... = 0{,}09\%$$

* Schreiben Sie die Formeln für $R$ auf, indem Sie die Reihen- bzw. Parallelschaltung mit $R_A$ und $R_V$ berücksichtigen, und setzen Sie diese beiden Gleichungen gleich. Formen Sie dann nach $R$ um:

$$R = \frac{R_A}{2} \pm \sqrt{\frac{R_A^2}{4} + R_V R_A} \approx 320\,\Omega$$
````

