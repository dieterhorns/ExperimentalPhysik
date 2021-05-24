---
title: "Hagen-Poisseuille Gesetz"
date: 2021-05-24T20:46:25+02:00
weight: 25
---
## Laminare, viskose Strömung im Rohr
Eine Newton'sche Flüssigkeit mit dynamischer Viskosität $\eta$ durchströmt 
ein Rohr der Länge $L$ mit Radius $R$. Der Druckunterschied zwischen den
beiden Rohrenden sei $\Delta p$ und die beiden Rohrenden befinden sich
auf gleicher Höhe.

Wir wollen jetzt bestimmen
   * wie das Geschwindigkeitsprofil der Strömung im Rohr ausschaut und
   * wie die Flüssigkeitsmenge pro Zeiteinheit von dem Rohrquerschnitt abhängt.

Die Strömung soll laminar (also wirbelfrei) und stationär sein (d.h. die Geschwindigkeit, mit der sich
das Fluid bewegt sich an einem festen Ort mit einer zeitlich konstanten Geschwindigkeit. 


Wir gehen davon aus, dass die Geschwindigkeit in der Rohrmitte $v(0)$ maximal ist und
am Rand $v(R)=0$ ist. Es bildet sich ein Geschwindigkeitsprofil aus $v(r)$, so dass
die innere Reibung gerade gleich groß der Kraft ist, die aufgrund des Druckunterschieds
$\Delta p$ auf ein Volumenelemnt wirkt:

$$ \Delta p \pi r^2  = -\eta 2\pi r L \frac{dv}{dr},$$
die DGL lässt sich via Separation der Variablen lösen. Wir formen zunächst um:
$$ \Delta p r dr     = -\eta 2 L dv$$
und integrieren dann auf beiden Seiten:
$$ \Delta p \int\limits_R^r r' dr' = -\eta 2 L \int\limits_{0}^{v(r)} dv',$$
so dass 
$$ \frac{\Delta p}{2} (r^2 - R^2) = - \eta 2 L v(r)$$
und damit erhalten wir ein parabelförmiges Profil mit dem Apex in der 
Mittellinie des Rohres. Dort erreicht die Geschwindigkeit das Maximum 
$$ v_\mathrm{max} = v(0) = \frac{\Delta p}{4 L \eta } R^2,$$
bzw
$$ v(r) = \frac{\Delta p}{4 L \eta} (R^2-r^2).$$

Jetzt bleibt noch zu klären, welches Volumen der Strömung pro Zeiteinheit
durch das Rohr hindurchfließt:  gesucht ist der Volumenstrom $\dot{V}$: 

Dazu integrieren wir die Geschwindigkeit über die Querschnittsfläche:


$$\dot V  = 2\pi \int\limits_{0}^{R} dr r v(r) = \frac{\pi \Delta p}{2L\eta} \frac{R^4}{2} - \frac{R^4}{4} = \frac{\pi \Delta p}{8 L \eta} R^4.$$

Der Volumenstrom hängt also dramatisch vom Radius des Rohres ab. 


