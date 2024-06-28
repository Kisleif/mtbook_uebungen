---
blogpost: true
date: Nov 29, 2023
category: Übung
location: Zettel_9
tags: Messabweichung, Leistung, Gleichspannung, Elektronik
---


# Leistungsmessung bei Gleichspannung

Wir wollen die rein durch die jeweilige Anschaltung entstehenden Messabweichungen einer Leistungsmessung bei Gleichstrom an einem Beispiel aufzeigen. Hierzu nehmen wir einen handelsüblichen Gleichstrommotor als Verbraucher an, der laut Datenblatt bei Speisung mit $24\,\mathrm V$ Gleichspannung einen Nennstrom von $3{,}0\,\mathrm A$ verbraucht.

* Welcher Leistungsaufnahme entspricht dies? 
* Wie groß ist offensichtlicherweise der Innenwiderstand (konkret ist das hier der Wicklungswiderstand der Spulen im Motor)?

````{tip}
:class: dropdown
* $P = UI = ... = 72\,\mathrm W$
* $R = U/I = ... = 8\,\mathrm\Omega$
````

* Wir wollen diesen Motor nun auch exakt mit $24\,\mathrm V$ Gleichspannung z.B. an einem Netzteil betreiben und verwenden zur Leistungsbestimmung einen Spannungsmesseingang mit $1\,\mathrm{M\Omega}$ Innenwiderstand sowie einen Strommesseingang mit $1\,\mathrm{\Omega}$ Innenwiderstand. Mit welcher Messabweichung ist bei stromrichtiger bzw. spannungsrichtiger Anschaltung zu rechnen?

````{tip}
:class: dropdown
$$P = UI = I\cdot (U + I\cdot R_{iA}) = UI + I^2\cdot R_{iA} \Rightarrow \Delta P = ... = 9\,\mathrm W$$

$$P = UI = U\cdot (I + U / R_{iV}) = UI + U^2/R_{iV} \Rightarrow \Delta P = ... = 5{,}76\cdot 10^{-4}\,\mathrm W $$
````


* Wie groß ist die Messabweichung bei Verwendung eines qualitativ eher nicht so hochwertigen Strommesseingangs mit $10\,\mathrm{\Omega}$ Innenwiderstand bei einer stromrichtigen Schaltung?
