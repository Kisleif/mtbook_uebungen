---
blogpost: true
date: Nov 29, 2022
location: Zettel_8
category: Übung
tags: Faltung, Messsystem, Impuls, Sprung, Übertragungsfunktion
---


# Sprung- und Impulsantwort und Übertragungsfunktion


Die Sprungantwort eines LTI-Systems lautet

$$
g(t)=\left\{\begin{array}{cl}0&\textrm{für}\,\,t<0\\  2t&\textrm{für}\,\, 0 \leq t \leq T \\ 2T&\textrm{für}\,\, t > T\end{array}\right.
$$

1. Bestimmen und skizzieren Sie die Impulsantwort $h(t)$ des Systems. 
2. Wie lautet die Übertragungsfunktion $H(f)$ des Systems? Geben Sie $H(f)$ unter Verwendung der si-Funktion an.
3. Bestimmen Sie den Betrag $|H(f)|$ und die Phase $\varphi(f)$ von $H(f)$.
 
 ````{tip}
:class: dropdown
1. Der Impuls ist die Ableitung eines Sprungs. In einem LTI-System gilt, dass die Impulsantwort, $h(t)$, die Ableitung der Sprungantwort, $g(t)$, ist.
2. Die Übertragungsfunktion ist für eine Impulsanregung definiert. Transformiere folglich $h(t)$ in den Frequenzbereich und löse das Integral der Fourier (oder Laplace) Transformation: 

$$H(f) = \int_{-\infty}^{\infty} h(t) \mathrm e^{-j2\pi ft}dt = ... = 2T \mathrm{si}(\pi f T) \mathrm e^{-j\pi fT}$$

3. Überlegen Sie, was der Betrag einer komplexen e-Funktion ist. Die Funktion $|\mathrm{si}(...)|$ können Sie so stehen lassen. Für die Phase gilt die allgemeine Formel:

$$\varphi(f) = \arctan\left(\frac{Im(H)}{Re(H)}\right)$$
````