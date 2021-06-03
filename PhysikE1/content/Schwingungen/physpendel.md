---
title: "Physikalisches Pendel"
date: 2021-05-10T17:31:26+02:00
weight: 11
description: "Schwerependel"
---
## Allgemeine Schwerependel
sind beliebig geformte starre Körper, die um eine fixierte Achse aufgrund des
wirkenden Drehmoments periodische Schwingungen ausführen. Wir betrachten
zunächst die Drehmomentsgleichung für einen Körper der Masse $m$, der am Punkt
$A$ aufgehängt ist. Die Verbindungslinie vom Punkt $A$ zum Schwerpunkt $S$ ist
$s=\overline{AS}$.  Dann ergibt sich bei einer Auslenkung des Pendels  um einen Winkel
$\theta$ ein rückstellendes Drehmoment $M=-mgs~\sin\theta$: 
$$ I_A \ddot\theta = -mgs \sin\theta.$$
Das Trägheitsmoment $I_A$ ist das Trägheitsmoment für die Rotationsachse im Punkt $A$.
Für hinreichend kleine Winkel reduziert sich $\sin \theta \approx \theta$:
$$ \ddot \theta = -\frac{mgs}{I_A} \theta.$$
Auch hier ist die Lösung eine [harmonische Schwingung]({{<relref "schwingungen">}}), so dass 
$$ \theta(t) = \hat \theta \sin(\omega t + \varphi),$$
mit 
$$ \omega = \sqrt{\frac{mgs}{I_A}}.$$

## Beispiel Ringpendel
Ein Ring mit Radius $R$ und Masse $m$ wird an einem Punkt im Abstand $R$ zum Mittelpunkt
aufgehängt. Wie groß ist die Kreisfrequenz $\omega$?

Hierzu berechnen wir das Trägheitsmoment mit Hilfe des Steinerschen Satzes. Das Trägheitsmoment für die
Rotation um den Mittelpunkt ist $I_M = mR^2$. Wenn wir die Drehachse um $R$ verschieben, ergibt sich
$I_A=2mR^2$. Für die Winkelfrequenz ist dann
$$ \omega = \sqrt{ \frac{mgR}{2mR^2} } = \sqrt{ \frac{g}{2R} }.$$
Es ergibt sich also, dass das Ringpendel mit der gleichen Frequenz schwingt wie ein Fadenpendel der Länge $2R$!
Natürlich müssen wir uns gleich experimentell davon überzeugen, dass das stimmt!

Im allgemeinen lässt sich ein jedes physikalische Pendel durch ein Fadenpendel der _reduzierten Pendellänge_  $\ell_r$
ersetzen:
$$ \omega = \sqrt{\frac{g}{\ell}} = \sqrt{\frac{mgs}{I_A}},$$
so dass 
$$ \ell_r = \frac{I_A}{m~s}.$$
Mit dem Steiner'schen Satz ist $I_A = I_s + ms^2$ und damit 
$$ \ell_r = s + \frac{I_s}{ms}>s.$$

## Reversionspendel
Ein nicht-ideales Pendel ist *immer* ein physikalisches Pendel. Um z.B.
aus der Schwingungsperiode auf die Schwerebeschleunigung zu schließen,
ist eine genaue Kenntnis des Trägheitsmoments $I_A$ für den gegebenen 
Aufhängepunkt des Pendels nötig. Experimentell ist die Messung 
des Trägheitsmoments jedoch aufwändig und mit zu großen Unsicherheiten 
versehen. 

Stattdessen verwenden wir einen zweiten Aufhängepunkt $B$ in der Verlängerung
von $r=\overline{AS}$ mit der gleichen reduzierten Pendellänge (also gleicher
Schwingungsdauer)

$$ \ell_r = \frac{I_A}{ms} = s +  \frac{I_s}{ms}$$
bzw.
$$ \ell_r =  \frac{I_B}{ms} = r + \frac{I_s}{mr}.$$
Umformen der beiden Gleichungen ergibt
$$ \ell_r ms = ms^2 + I_s,$$
$$ \ell_r mr = mr^2 + I_s.$$
Subtraktion der beiden Gleichungen:
$$ \ell_r (s-r) = s^2-r^2 = (s-r)(s+r),$$
wodurch sich ergibt, dass 
$$ \ell_r = s+r.$$

Im praktischen Versuch lässt sich durch Messung der Punkte $A$ und $B$ mit
gleicher Periode durch den Abstand der beiden Punkte die reduzierte Pendellänge
und damit die Schwerebeschleunigung messen ohne das Trägheitsmoment des Pendels zu
kennen!

