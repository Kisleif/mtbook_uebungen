---
blogpost: true
date: Nov 01, 2023
location: Zettel_5
category: Übung
tags: Fourierreihe, Sägezahn
---


# Fourierreihe einer Sägezahn-Spannung

Bestimmen Sie die komplexe und die reelle Fourier-Reihe für die gegebene Sägezahn-Spannung. Wie lauten die Koeffizienten für $k = 1,2,3,4,5$? Skizzieren Sie das Betragsspektrum.

```{figure} pictures/functions2.png
:class: .dark-light
---
height: 100px
---
Sägezahnsignal

```


````{admonition} Formeln für die rellen Fourier-Reihen
:class: dropdown

Die reelle Darstellungsform benutzt Sinus- und Cosinusfunktionen um $x(t)$ in einer Reihe zu entwickeln:

$$x(t) = x_0 + \sum_{k=1}^{\infty} a_k \cos(2\pi k f_0 t) + \sum_{k=1}^{\infty} b_k \sin(2\pi k f_0 t)$$

Der Mittelwert (Gleichanteil) $x_0$ und die Koeffizienten, $a_k$ und $b_k$ berechnen sich durch die Integrale:

$$x_0 = \frac{1}{T} \int_{-T/2}^{T/2} x(t) dt$$

$$a_k = \frac{2}{T}  \int_{-T/2}^{T/2} x(t) \cos(2\pi k f_0 t) dt $$

$$b_k = \frac{2}{T}  \int_{-T/2}^{T/2} x(t) \sin(2\pi k f_0 t) dt $$
````

````{admonition} Formeln für die komplexe Fourier-Reihen
:class: dropdown

Die komplexe Darstellung der Fourierreihe ist insbesondere in der Elektrotechnik weit verbreitet und lautet:

$$x(t) = \sum_{k=-\infty}^{\infty} \underline{c}_k \mathrm e^{j 2\pi k f_0 t}$$

Die imaginäre Einheit ist hierbei durch $j$ bezeichnet. 
Für $k=0$ erhalten wir wieder den Mittelwert $x_0$ und die zugehörigen Koeffizienten, jetzt mit $c_k$ bezeichnet, berechnen sich mittels:

$$\underline {c}_k = \frac{1}{T}  \int_{-T/2}^{T/2} x(t) \mathrm e^{- j 2\pi k f_0 t} dt $$

Die komplexen Koeffizienten verhalten sich zueinander komplex konjugiert: $\underline{c}_{-k} = \underline{c}^*_{k}$. 
Die komplexen Koeffizienten können in die reellen Koeffizienten umgeformt werden und andersherum:

$$a_k = \underline{c}_{k} + \underline{c}_{-k} \qquad b_k = j (\underline{c}_{k} - \underline{c}_{-k})$$

$$\underline c_k = \frac{1}{2} (a_k - j b_k) \qquad \underline c_{-k} = \frac{1}{2} (a_k + j b_k)$$

````





