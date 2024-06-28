---
blogpost: true
date: Nov 22, 2023
location: Zettel_7
category: Übung
tags: Messsystem, Hochpass, Übertragungsfunktion, DGL
---


# Passiver CR-Hochpass 1. Ordnung

In der Vorlesung wurde das Zeitverhalten der RC-Tiefpass-Schaltung erläutert. In dieser Aufgabe sollen die dort gebrachten Überlegungen auf ein CR-Hochpass-Messglied angewendet werden. Gegeben ist die Schaltung in der Abbildung.

```{figure} pictures/hochpass.png
:class: .dark-light
---
height: 200px
name: optional-label
---
Schaltbild eines CR-Hochpasses 1. Ordnung.

```


Geben Sie für die CR-Schaltung den komplexen Frequenzgang $\underline G(jf) = \frac{\underline U_a(f)}{U_e(f)}$ an (über DGL oder komplexe Impedanzen). Spalten Sie den Frequenzgang in seinen Realteil und Imaginärteil. Geben Sie den Amplitudengang $G(f) = |G(jf)|$ und Phasengang in Abhängigkeit von $f_g = 1/(2\pi R C)$ an. Welchen Wert hat der Amplitudengang für den Grenzfall $f = 0\,\mathrm{Hz}$ und $f = f_g$? Skizzieren Sie Amplituden- und Phasengang für folgende Fälle:

$$U_0 = 1\,\mathrm V$, $R = 0,16\,\mathrm{M\Omega}$ und $C = 1\,\mathrm{\upmu F}$$

$$U_0 = 1\,\mathrm V$, $R = 0,16\,\mathrm{M\Omega}$ und $C = 200\,\mathrm{nF}$$

Geben Sie die DGL an. Bestimmen Sie die Sprungantwort des Hochpass-Messgliedes für den Fall, dass sich die Eingangsspannung zur Zeit $t=0\,\mathrm s$ sprunghaft von $u_\mathrm e(t=0\,\mathrm s) = 0\,\mathrm V$ auf $u_\mathrm e(t>0\,\mathrm s) = U_0$ ändert. Nutzen Sie hierfür den für eine Sprunganregung typischen exponentiellen Ansatz, wobei $K_0$ und $\gamma$  Konstanten sind, die zu bestimmen sind:

$$ u_\mathrm a(t) = K_0 \cdot \mathrm e^{-\gamma t}$$

Skizzieren Sie die Sprungantworten für die angegebenen Fälle.


````{tip}
:class: dropdown
Hinweis zum Lösen der DGL: 
* Lösen Sie zuerst die homogene DGL (ohne Anregung, $u_\mathrm{e}(t)=0$). 
* Finden Sie die partikuläre Lösung für $t \rightarrow \infty$, wenn sich der Kondensator voll aufgeladen hat ($u_\mathrm a(t)$=?).
* Geben Sie den allgemeinen Lösungsansatz an (Summe aus homogener und partikulärer Lösung).
* Bestimmen Sie die Konstanten mithilfe der gegebenen Anfangsbedingungen. 

```