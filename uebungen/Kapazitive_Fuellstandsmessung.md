---
blogpost: true
date: Nov 15, 2023
location: Probeklausur
category: Übung
tags: Mittelwert, Vertrauensintervall, Standardabweichung, Fehlerfortpflanzung
---


# Kapazitive Füllstandsmessung

Bei der kapazitiven Füllstandsmessung nutzt man die Tatsache aus, dass Flüssigkeiten eine relative Dielektrizitätskonstante $\epsilon_r$ größer als eins besitzen. Als Messgrößenumformer kommt daher ein Kondensator zum Einsatz, der durch die Behälterwand und eine Stabelektrode gebildet wird (siehe Abbildung).

Wird der dargestellte Behälter mit Flüssigkeit befüllt, so nimmt gleichzeitig die Kapazität des Kondensators zu. Es existiert ein eindeutiger Zusammenhang zwischen der Gesamtkapazität $C_G$ und der Füllhöhe $h$, welcher als Berechnungsgrundlage für die Auswertung herangezogen werden kann.
Die zu bestimmende Füllhöhe $h$ ergibt sich gemäß folgendem formelmäßigen Zusammenhang:

$$h = \frac{H}{\epsilon_r - 1} \cdot \left( \frac{C_G-C_K}{C_E} -1 \right)$$

Hierin steht $H$ für die maximale Füllhöhe des Behälters, $\epsilon_r$ für die relative Dielektrizitätskonstante des Füllmediums, $C_G$ für die variable Gesamtkapazität des Behälters bei jeweiliger Befüllung, $C_K$ für den konstanten Anteil der Kapazität, welcher vorwiegend aus der Kapazität zwischen Sonde und Deckel sowie Sonde und Boden gebildet wird, und $C_E$ für die über die Höhe $H$ gemessene Kapazität des leeren Behälters.

```{figure} pictures/fuellstandsmessung.png
:class: .dark-light
---
height: 150px
name: optional-label
---
Füllstandsmessung.

```


Im Folgenden soll die Füllhöhe $h$ des Behälters auf der Grundlage von Messergebnissen für die Größen $H$, $\epsilon_r$, $C_G$, $C_K$ und $C_E$ einschließlich der wahrscheinlichen Abweichungsgrenzen ermittelt werden. Die maximale Füllhöhe $H$ wird vom Hersteller des Behälters mit einem Nennwert von $H = 5000\mathrm{mm}$ angegeben. Das Konfidenzintervall der maximalen Füllhöhe $H$ gibt der Hersteller mit $\pm 0{,}05 \%$ vom Nennwert bei einer Aussagewahrscheinlichkeit von $P=95\%$ und sehr großen Stichprobenumfang $n$ an. Als Füllmedium des Behälters wird Wasser eingesetzt, welches unter den herrschenden Umgebungsbedingungen eine relative Dielektrizitätskonstante von $\epsilon_r = 80$ aufweist. Dieser Wert kann als exakt angesehen werden. Die Kapazität $C_K$ wird vom Hersteller des Behälters mit $C_K = 40\mathrm{pF}$ angegeben. Dieser Wert kann als exakt angesehen werden. Die Kapazität $C_E$ wurden im Vorfeld experimentell in $n = 25$ Versuchen bestimmt. Das ermittelte Messergebnis beträgt $C_E = 240\mathrm{pF} \pm 1\mathrm{pF}$ bei $P = 99\%$. Die Gesamtkapazität $C_G$ wird im Zuge der Versuchsdurchführung mit insgesamt $n = 9$ Einzelmessungen ermittelt. Die dabei erhaltenen Einzelmesswerte sind in folgender Tabelle zusammengefasst.

| $i$ |  1  |  2  |  3  |  4  |  5  |
|-----|-----|-----|-----|-----|-----|
| $C_G /\mathrm{pF}$ | 3335 | 3405 | 3349 | 3381 | 3417 |


Berechnen Sie die gesuchte Füllhöhe $h$ des Behälters und geben Sie das vollständige Messergebnis mit einer Aussagewahrscheinlichkeit von $P = 95\%$ an!

*Hinweis: Für alle Messgrößen kann eine Normalverteilung vorausgesetzt werden.*


![png](pictures/p-quantile.png)
