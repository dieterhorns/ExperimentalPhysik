---
title: "Temperatur"
date: 2021-06-24T19:03:17+02:00
weight: 18
---
## Temperaturmessung
Die Wahrnehmung von _warm_ und _kalt_ ist durch die Nerven in der Haut möglich (Thermozeption). Sogenannte 
_Kälterezeptoren_ erzeugen bei gleichbleibender Temperatur eine konstante Rate von Nervenpulsen (10-40 Pulse/s),
die bei Änderung der Temperatur wechselt. Bei sehr hohen Temperaturen kommt ein Schmerzempfinden hinzu. 

Die Messung einer Temperatur (Thermometrie) beruht auf temperaturabhängige Effekte:
   1. rel. Längenänderung  $\Delta L/L\propto \Delta T$,
   1. rel. Volumenänderung $\Delta V/V \propto \Delta T$,
   1. Schallgeschwindigkeit in einem Gas $\propto \sqrt{T}$,
   1. Änderung des Brechungsindex in einem Gas,
   1. Johnson-Rauschen der Leitungselektronen,
   1. Doppler-Verbreiterung von spektralen Linien, 
   1. Änderung der Leitfähigkeit für elektrischen Strom in Leitern.
   1. spektrale Eigenschaft der abgegebenen Strahlung.


## Temperaturskala
Eine Temperaturmessung geht einher mit einer Temperaturskala, die eine Kalibrierung der Temperaturmessung
auch für verschiedene Messmethoden ermöglicht. 
Temperaturskalen, die zur Zeit gebräuchlich sind:
   1. Skala nach Celsius: $t=0^\circ$ C ist der Gefrierpunkt von Wasser, $t=100^\circ$C ist der Siedepunkt von Wasser bei Normalbedingungen.
     Die Celsius-Skala ist nach einer Revision an die absolute (Kelvin)-Skala gekoppelt
   1. Skala nach Fahrenheit: nur noch im angloamerikanischen Bereich in Gebrauch. Mittlerweile auch über die Celsius-Skala an die absolute Temperatur gekoppelt.
   1. Absolute Temperatur $T$ in Kelvin (K) ist die SI-Basiseinheit für Temperatur. Diese Skala ist in gleich große Einheiten unterteilt wie das Grad Celsius, so dass
    ein Temperaturunterschied von $\Delta T= 1$ K einem Temperaturunterschied von  $\Delta t=1^\circ$C entspricht. 

Die absolute Temperatur $T$ ist hierbei über den absoluten Nullpunkt $T=0$ und den Tripelpunkt von Wasser definiert ($1 K$ entspricht dem 273,16ten Teil
der Temperatur des Tripelpunktes). In der Praxis sind die Temperaturmessungen in den verschiedenen Messbereichen an weiteren Fixpunkten (z.B. Phasenübergänge) 
festgelegt. [PTB-Referenz](https://oar.ptb.de/files/download/57d6a26aa4949dd13c3c9878)

## Wärmeausdehnung
Ein Festkörper (z.B. ein Messingstab, eine Eisenbahnschiene etc.) zeigt bei zunehmender Temperatur $\Delta T$ eine relative Längenänderung, die proportional
zur Temperaturänderung ist:
$$ L(T+\Delta T) = L(T) (1+\alpha \Delta T),$$
bzw. mit $\Delta L = L(T+\Delta T)-L(T)$:
$$ \frac{\Delta L}{L} = \alpha \Delta T,$$
 wobei $\alpha$ der lineare Ausdehnungskoeffizient in Einheiten $\mathrm{K}^{-1}$ ist.

Die Ausdehnung findet bei isotropen Festkörpern in alle Raumdimensionen statt, so dass die Volumenänderung  sich zu 
$$ V(T+\Delta T) = V (1+\alpha \Delta T)^3 \approx V (1+3\alpha \Delta T) = V (1+\gamma \Delta T)$$
bzw. mit $\Delta V = V(T+\Delta T)-V(T)$
$$ \frac{\Delta V}{V} = \gamma \Delta T$$
wobei  $\gamma = 3\alpha$  ergibt.

Die Werte von $\alpha$ (in Einheiten K$^{-1}$) liegen bei Metallen bei etwa $\alpha\approx 1\ldots 3\times 10^{-5}$ K$^{-1}$. 
Spezielle Legierungen wie z.B. Invar (Eisen-Nickel Legierung, entdeckt von Charles Guillaume, Nobelpreis der Physik 1920) haben 
einen deutlich reduzierten Wärmeausdehnungskoeffizienten von $\alpha \approx 2\times 10^{-6}~$K$^{-1}$. 

Weiterhin zeigen Quartz (0,4 ppm/K), Pyrex (3 ppm/K) und Marmor (2 ppm/K) geringe Wärmeausdehnungskoeffizienten. 


## Quecksilberthermometer


## Bimetallthermometer
