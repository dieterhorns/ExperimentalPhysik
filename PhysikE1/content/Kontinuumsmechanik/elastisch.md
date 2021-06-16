---
title: "Elastische Verformungen"
date: 2021-05-13T10:22:16+02:00
weight: 8
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
Weise, d.h. die _relative_ Längenänderung $\epsilon:=\Delta L/L$ ist proportional zur
Zugspannung $\sigma$ mit der Proportionalitätskonstante $1/E$, das sogenannte
*Elastizitätsmodul*. 

$$ \epsilon = \frac{\Delta L}{L} = \frac{1}{E} \sigma.$$
Das Elastizitätsmodul $E$ ist eine Materialkonstante und
trägt die Einheit Kraft/Fläche $[\mathrm{N}~\mathrm{m}^{-2}$]. Wir geben hier einige
typische Werte für $E$ an (je größer $E$, desto geringer ist die Längendehnung):

| Material | El.Modul $E$  | Streckgrenze | $\rho$       |  $v_s$              |  $\mu$ |
|----------|---------------|--------------|--------------|---------------------|--------|
|          | [GPa]         |  [MPa]       | [$10^3$ kg m$^{-3}$]| [km s$^{-1}]$ |        |
| Kupfer   | 110           | 200          |  9           | 3,5                 | 0,35   |
|Aluminium |  70           |  40          | 2,7          | 5,1                 | 0,35   |
| Baustahl | 210           | 300          | 8            | 5,0                 | 0,28   |
| Nylon    |  3            |              |              |                     |        |
| Keramik  |               |              |              |                     |        |
<caption> 
Für eine weitergehende Tabelle der Materialeigenschaften von Metallen: 
<a href="https://www.electrical-contacts-wiki.com/index.php/Physikalische_Eigenschaften_der_wichtigsten_Metalle">[1]</a>
</caption>


### Zusammenhang $E$ und Federkonstante $D$

Aus dem Elastizitätsmodul lässt sich auch die Federkonstante berechnen.
Das lineare Kraftgesetz für die rücktreibende Kraft $F = -Dx$ entspricht
hierbei der negativen Zugspannung:
$$ \frac{F}{E~A} = \frac{\Delta L}{L},$$
$$ F = \frac{E~A}{L} \Delta L,$$
somit ist $D=E \frac{A}{L}$. 

### Zusammenhang $E$ und $v_s$

Die Schallgeschwindigkeit $v_s$ in einem Festkörper 
der Massendichte $\rho$ ergibt  sich
(ohne Herleitung)  zu
$$ v_s = \sqrt{\frac{E}{\rho}}.$$

Bei bekannter Geschwindigkeit ergibt sich die Frequenz $\nu$ des  Grundtons einer Metallstange
der Länge $L$, die wir
mit einem Hammer von der Seite anschlagen zu 
$$ \nu = \frac{v_s}{\lambda} = \frac{v_s}{2 L}.$$
Ein Kupferstab hat eine deutlich niedrigere Frequenz als ein Stahlstab gleicher Länge.

Aus der Messung der Frequenz des Grundtons bei bekannter Länge und Massendichte lässt sich also auch
das Elastizitätsmodul bestimmen.

### Streckgrenze, Fließbereich
Im linearen Bereich ist die relative Ausdehnung proportional zur Zugspannung. 
Wenn wir die Zugspannung wieder auf 0 reduzieren, kehrt das System zurück zu dem 
ursprünglichen Zustand $\Delta L=0$. Ist die Zugspannung größer als die
sogenannte _Streckgrenze_, ändert sich das Verhalten:
  *  die Ausdehnung $\Delta L$ ist nicht mehr linear  zur Zugspannung
  *  wenn wir die Zugspannung auf 0 reduzieren, bleibt $\Delta L>0$.
Die übliche Konvention für die Streckgrenze ist eine Abweichung von 
$\Delta L/L = 0,002$. 

Wenn die Zugspannung weiter anwächst, vergrößert sich die Länge nicht-linear bis
die sogenannte Fließgrenze überschritten wird. Jetzt reicht schon eine reduzierte
Zugspannung aus, um den Körper weiter zu dehnen: es bildet sich  eine Einschnürung, so
dass bei gleicher Kraft die Zugspannung an dieser Stelle zunimmt bis es zum Bruch kommt.

Bei Federstahl kommt es bei einer relativen Längenänderung von etwa $0,06$ zum Bruch. 

{{< figure src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/64/Spgs-Dehnungs-Kurve_Dehngrenze.svg/480px-Spgs-Dehnungs-Kurve_Dehngrenze.svg.png" caption="Abbildung Wikipedia, schematisches Diagramm mit Zugspannung $\sigma$ vs. rel. Längenänderung $\epsilon=\Delta L/L$" link="https://de.wikipedia.org/wiki/Elastizit%C3%A4tsgrenze#Flie%C3%9Fgrenze">}}


## Querkontraktion: Poissonzahl $\mu$ 
Bei einer relativen Längenänderung $\Delta L /L$ wird ein Körper quer zur Längenänderung kontrahieren. 
Der lineare Zusammenhang zwischen Querkontraktion und Längenänderung 
$$\frac{\Delta d}{d} = -\mu \frac{\Delta L}{L}$$
ist materialspezifisch. Die einheitenlose Konstante $\mu$ wird _Poissonzahl_ $\mu$ genannt.

Für Metalle ist $\mu\approx 0,3$, für Käse und Gummi ist $\mu \approx 0,5$. Kork hat $\mu \approx 0$. Aufgrund
dieser Eigenschaft können wir überhaupt einen Korken in eine Flasche drücken.



## Kompressionsmodul $K$
Für einen Körper mit einer Zugspannung $-\sigma$ in einer Richtung ergibt sich das neue Volumen zu

$$ V' = (L+\Delta L) ( d - \Delta d)^2 \approx (L + \Delta L) d^2(1 - 2\frac{\Delta d}{d})\approx L d^2  ( 1 + \frac{\Delta L}{L} - 2 \frac{\Delta d}{d}),$$
so dass 
$$ \frac{\Delta V}{V} = \epsilon(1-2\mu).$$

Hieraus ergibt sich sofort, dass $\mu < 0,5$ gelten muss, damit bei einer Dehnung durch Zugspannung das Volumen abnimmt. 





##  Schermodul $G$ 
 Das Schermodul
     ist die Proportionalitätskonstante zwischen dem Schubwinkel $\gamma$ und der Scherspannung $\tau$:
$$ \tan\gamma = \frac{1}{G} \tau,$$
wobei $\tau=F/A$ eine Spannung ist, die sich aus der tangential ansetzenden Kraft $F$  pro Flächenelement $A$ ergibt.
Für kleine Schubwinkel ist $\tan\gamma \approx \gamma$. 

 Das Schermodul ist auch als Torsionsmodul bekannt. Für einen Draht der Länge $L$ und Radius $R$ lässt sich der Zusammenhang herstellen
zwischen dem für ein Torsionspendel wirkenden rückstellenden Drehmoment bei einem Torsionswinkel $\alpha$:

$$ M = I\ddot \alpha = -\kappa \alpha.$$
Die Konstante $\kappa$  (_Richtmoment_)  ergibt sich aus dem materialspezifischen Schermodul und der Geometrie des Drahtes (Länge und Radius).
Bei einer Verdrehung des Drahtes um den Winkel $\alpha\ll 1$ ergibt sich ein Scherungswinkel $\gamma$ 
$$ \gamma = \alpha \frac{r}{L} = \frac{\tau}{G} $$
im Abstand $r$ zur Mittellinie des Drahtes ($r\ll L$).

Die Scherspannung $\tau=dF/dA$ ist für das zylindrische Flächenelement $dA = r d\phi dr$.  Das resultierende Drehmoment $dM$ für die Kraft $dF$ ist
$$ dM = r dF = r \tau dA = r^2 \tau d\phi dr = \frac{r^3 \alpha G}{L} d\phi dr   $$
Um das Gesamtdrehmoment zu bestimmen, integrieren wir über $\phi$ und $r$ in den Grenzen $0,2\pi$ und $0,R$:
$$ M = \frac{R^4 \pi  G}{2 L} \alpha.$$
Der Vergleich ergibt dann für $\kappa$:
$$ \kappa = \frac{\pi R^4 G}{2 L}.$$

Aus der Messung der Pendelperiode eines Torsionspendels
$$ P = 2\pi \sqrt{\frac{I}{\kappa}}$$
lässt sich bei bekanntem Trägheitsmoment $I$ und bekannter Geometrie das Richtmoment $\kappa$ und damit das Schermodul $G$ vermessen.

## Fortgeschrittenes Thema
### Zusammenhang Elastizitätsmodul und Bindungsenergie
Warum unterscheiden sich die Werte für das Elastizitätsmodul für unterschiedliche Materialien? Auf atomarer Ebene lässt sich das 
zumindest qualitativ auf die Bindungsenergie $U_0$ der Atome zurückführen. Eine einfache Betrachtung hierzu:

 Wir nehmen an, dass es die Bindungsenergie $U=U(r)$  nur vom Abstand abhängt. Der atomare Abstand sei $r_0$, dann ist die Spannung pro
Atom 
$$ \sigma = \frac{F}{r_0^2}.$$
Die relative Dehnung ist
$$ \epsilon = \frac{r-r_0}{r_0},$$
wobei die rücktreibende Kraft durch die Ableitung der Bindungsenergie $U(r)$ gegeben ist:
$$ F = \frac{dU}{dr}.$$

Das $E$-Modul ist gegeben durch $\sigma = E \epsilon$ bzw.
 $$ E = \frac{d\sigma}{d\epsilon} = \frac{d \sigma}{dr} \left(\frac{d\epsilon}{dr}\right)^{-1} = 
\frac{d\sigma}{dr}\frac{1}{r_0}.$$
$$ E = \frac{1}{r_0}\frac{d}{dr} \frac{dU}{dr} = \frac{1}{r_0} \frac{d^2 U}{dr^2}.$$ 
Für ein allgemeines Potenzial der Form
$$ U(r) = -\frac{A}{r^n} + \frac{B}{r^m}$$
mit $U(r_0)=U_0<0$ lässt sich zeigen:
$$ E =-U_0 \frac{n~m}{r_0^3}.$$
Die Bindungsenergie $-U_0$ ist  positiv und sollte in etwa proportional zur Schmelzwärme $k_B~T_s$ 
sein. Der Term $r_0^3$ ist das atomare Volumen, so dass sich für die meisten Materialien (nicht jedoch für
Elastomere) ergibt
$$ E\propto T_s/r_0^3$$. 



