---
blogpost: true
date: Nov 22, 2023
location: Zettel_7
category: Übung
tags: Faltung, Rechteck
---

# Grafische Faltung

Ein System habe die Impulsantwort 

$$h(t) = 2{,}5 A \cdot \mathrm{rect}\left(\frac{t-1{,}5t_0}{t_0}\right) +  A \cdot \mathrm{rect}\left(\frac{t-3t_0}{2t_0}\right) +  2 A \cdot \mathrm{rect}\left(\frac{t-5{,}5t_0}{3t_0}\right).$$

Die Rechteckfunktion ist wiefolgt definiert:

$$
\operatorname{rect}(t) = \Pi(t) = \begin{cases}
0           & \text{wenn } |t| > \frac{1}{2} \\[3pt]
\frac{1}{2} & \text{wenn } |t| = \frac{1}{2} \\[3pt]
1           & \text{wenn } |t| < \frac{1}{2}
\end{cases}
$$

Eine Rechteckfunktion, die bei $t_0$ zentriert ist und eine Dauer von $T$ hat, wird ausgedrückt durch

$$\operatorname{rect}\left(\frac{t-t_0}{T} \right)$$

ausgedrückt.

Am Eingang des Systems liegt das Signal $x(t)$ aus der folgenden Abbildung an. 


```{figure} pictures/xt.png
:class: .dark-light
---
height: 300px
name: optional-label
---
Eingangssignal $x(t)$.

```

* Skizzieren Sie die Impulsantwort $h(t)$. Stellen Sie die Formel für $x(t)$ auf. 
* Stellen Sie das Faltungsintegral $y(t) = h(t) * x(t)$ auf. 
* Berechnen Sie es mithilfe der grafischen Faltung.


```{button-link} https://kisleif.github.io/mtbook/_website/_images/grafischeFaltung.pdf
:color: primary
Download der Anleitung zur Grafischen Faltung.
```


