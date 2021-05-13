---
title: "Elastische Verformungen"
date: 2021-05-13T10:22:16+02:00
description: "Spannungen, Elastizität"
---
## Zugspannung und Elastizitätsmodul
Ein Festkörper mit Querschnittsfläche $A$ wird mit einer Kraft
$F$ belastet, die senkrecht zur Oberfläche wirkt. Die Kraft pro 
Flächeneinheit wird *Zugspannung* $\sigma$ genannt:
$$ \sigma = \frac{F}{A}.$$

Die Zugspannung ist _keine_ vektorielle Größe - wir betrachten nur
die Kraft, die senkrecht auf der Oberfläche wirkt (die 
Komponente parallel zur Fläche erzeugt eine Schubspannung. . 

In Experimenten zeigt sich, dass z.B. ein Kupferdraht, an dem wir ein Gewicht befestigen 
seine Länge ändert. Bei kleinen Zugspannungen geschieht dies in einer linearen
Weise, d.h. die _relative_ Längenänderung $\Delta L/L$ ist proportional zur
Zugspannung $\sigma$ mit der Proportionalitätskonstante $1/E$, das sogenannte
*Elastizitätsmodul*. 

$$ \frac{\Delta L}{L} = \frac{1}{E} \sigma.$$
Das Elastizitätsmodul $E$ ist eine Materialkonstante und
trägt die Einheit Kraft/Fläche $[\mathrm{N}~\mathrm{m}^{-2}$]. Wir geben hier einige
typische Werte für $E$ an (je größer $E$, desto geringer ist die Längendehnung):

{{<table "f6 bb striped--moon-gray:nth-child(odd)">}}
| Material | El.Modul $E$  | Streckgrenze |
|----------|---------|--------------|
|          | [GPa]   |  [MPa]       |
| Kupfer   | 128     | 200          |
| Baustahl | 210     | 300          |
| Nylon    | 2.6     | 80           |
{{</table>}}

Aus dem Elastizitätsmodul lässt sich auch die Federkonstante berechnen.
Das lineare Kraftgesetz für die rücktreibende Kraft $F = -Dx$ entspricht
hierbei der negativen Zugspannung:
$$ \frac{F}{E~A} = \frac{\Delta L}{L},$$
$$ F = \frac{E~A}{L} \Delta L,$$
somit ist $D=E \frac{A}{L}$. 

## Streckgrenze, Fließbereich
Im linearen Bereich ist die relative Ausdehnung proportional zur Zugspannung. 
Wenn wir die Zugspannung wieder auf 0 reduzieren, kehrt das System zurück zu dem 
ursprünglichen Zustand $\Delta L=0$. Ist die Zugspannung größer als die
sogenannte _Streckgrenze_, ändert sich das Verhalten:
  *  die Ausdehnung $\Delta L$ ist nicht mehr linear  zur Zugspannung
  *  wenn wir die Zugspannung auf 0 reduzieren, bleibt $\Delta L>0$.
Die übliche Konvention für die Streckgrenze ist eine Abweichung von 
$\Delta L/L = 0,2~\%$. 

Wenn die Zugspannung weiter anwächst, vergrößert sich die Länge nicht-linear bis
die sogenannte Fließgrenze überschritten wird. Jetzt reicht schon eine reduzierte
Zugspannung aus, um den Körper weiter zu dehnen bis schließlich eine Einschnürung
auftritt und es zum Riss kommt.

{{< figure src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/64/Spgs-Dehnungs-Kurve_Dehngrenze.svg/480px-Spgs-Dehnungs-Kurve_Dehngrenze.svg.png" caption="Abbildung Wikipedia, schematisches Diagramm mit Zugspannung vs. rel. Längenänderung" link="https://de.wikipedia.org/wiki/Elastizit%C3%A4tsgrenze#Flie%C3%9Fgrenze">}}




## Kompressionsmodul, Schermodul
