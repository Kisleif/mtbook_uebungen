---
blogpost: true
date: Nov 23, 2023
category: Übung
tags: Fourier-Transformation, Sägezahn
---


# Fourier-Transformation Sägezahn

Gegeben sind die folgenden zwei Zeitfunktionen $x_1(t)$ und $x_2(t)$ in der Abbildung.  

```{figure} pictures/Ft_signal.png
:class: .dark-light
---
height: 100px
---
Sägezahnsignale
```


* Berechnen Sie die Spektralfunktion $X_1(f)$ von $x_1(t)$ mittels der Fourier-Transformation:

$$X(\omega) = \int_{-\infty}^{\infty} x(t) \mathrm e^{-j\omega t} dt$$

* Berechnen Sie aus $X_1(f)$ die Spektralfunktion $X_2(f)$ von $x_2(t)$ durch Anwendung der Rechenregeln der Fourier-Transformation. 
 
Hinweis: $\int x \mathrm e^{ax} = \frac{\mathrm e^{ax}}{a^2}(ax-1)$.



