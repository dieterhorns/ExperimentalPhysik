---
title: "Physikalisches Pendel"
date: 2021-05-10T17:31:26+02:00
description: "Schwerependel"
---
## Allgmeine Schwerependel
sind beliebig geformte starre Körper, die um eine fixierte Achse aufgrund des
wirkenden Drehmoments periodische Schwingungen ausführen. Wir betrachten
zunächst die Drehmomentsgleichung für einen Körper der Masse $m$, der am Punkt
$A$ aufgehängt ist. Die Verbindungslinie vom Punkt $A$ zum Schwerpunkt $S$ ist
$s=\bar{AS}$.  Dann ergibt sich bei einer Auslenkung des Pendels  um einen Winkel
$\theta$ ein rückstellendes Drehmoment $M=-mgs~\sin\theta$: 
$$ I_A \ddot\theta = -mgs \sin\theta.$$
Das Trägheitsmoment $I_A$ ist das Trägheitsmoment für die Rotationsachse im Punkt $A$.
Für hinreichend kleine Winkel reduziert sich $\sin \theta \approx \theta$:
$$ \ddot \theta = -\frac{mgs}{I_A} \theta.$$
Auch hier ist die Lösung eine harmonische Schwingung, so dass 
$$ \theta(t) = \hat \theta \sin(\omega t + \varphi),$$
mit 
$$ \omega = \sqrt{\frac{mgs}{I_A}}.$$

## Beispiel Ringpendel
Ein kreisförmiger Ring mit Radius $R$ und Masse $m$ wird an einem Punkt im Abstand $R$ zum Mittelpunkt
aufgehängt. Wie groß ist die Kreisfrequenz $\omega$?

Hierzu berechnen wir das Trägheitsmoment mit Hilfe des Steinerschen Satzes. Das Trägheitsmoment für die
Rotation um den Mittelpunkt ist $I_M = mR^2$. Wenn wir die Drehachse um $R$ verschieben, ergibt sich
$I_A=2mR^2$. Für die Winkelfrequenz ist dann
$$ \omega = \sqrt{ \frac{mgR}{2mR^2} } = \sqrt{ \frac{g}{2R} }.$$
Es ergibt sich also, dass das Ringpendel mit der gleichen Frequenz schwingt wie ein Fadenpendel der Länge $2R$!
Natürlich müssen wir uns gleich experimentell davon überzeugen, dass das stimmt!

## Reversionspendel
