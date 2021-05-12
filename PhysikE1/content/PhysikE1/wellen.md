---
title: "Wellen"
date: 2021-05-10T17:31:26+02:00
description: "Wellenphänomene"
---
## Allgemeine Wellen
Aus der Beobachtung von Phänomenen in der Natur ist uns allen der
Begriff der Welle vertraut. Wir kennen z.B. Wasserwellen und Seilwellen. 

Eine Welle breitet sich aus. Bei der Seilwelle können wir feststellen, dass die
Auslenkung des Seils $\zeta$ mit zunehmender Zeit 
entlang des Seils fortschreitet, so dass 
$$ \zeta = \zeta(x,t)$$
eine Funktion der Position entlang des Seils $x$ und der Zeit $t$ ist. Wir
erkennen aber auch, dass $x$ und $t$ nicht unabhängig voneinander sind. 

Für einen festen Zeitpunkt $t$ folgt $\zeta(x,t)$ einer bestimmten Form, die
sich für einen späteren Zeitpunkt $t+\Delta t$ entlang des Seils um $\Delta x>0$
in positiver x-Richtung weiterbewegt hat, 
wobei jedoch die Form erhalten bleibt (ohne Dämpfungseffekte):

$$ \zeta(x,t+\Delta t) = \zeta(x-vt),$$
wobei wir mit $v=\Delta x/\Delta t$ die Ausbreitungsgeschwindigkeit der Welle 
betrachten. 


   * Alle Funktionen $f(x-vt)$ beschreiben eindimensionale Wellen, die sich
entlang der positiven $x$-Richtung ausbreiten. 
   * Alle Funktionen $f(x+vt)$ beschreiben eindimensionale Wellen, die sich 
entlang der negativen $x$-Richtung ausbreiten.
   * Die Funktion $f(x)$ gibt hierbei die Form der Welle an.
   * Harmonische Wellen sind von der Form $f(x-vt)=f_0 \sin(x-vt)$. 

## Wellengleichung
Wir können die Seilwelle im Hinblick auf die zugrundeliegende
Bewegungsgleichung für ein kleines Seilstück der Länge $\Delta x$ betrachten.
Die Masse $m=\Delta x \mu$, wobei $\mu = \Delta m /\Delta x$ die Massenbelegung
ist (wir nehmen an, dass die Massenbelegung konstant ist).

Das Seil ist gespannt mit der Seilspannung $T$. Wenn das Seil ausgelenkt wird, 
erfährt das Seil eine Kraft in Richtung der Auslenkung $\Delta \zeta$
$$ \mu \Delta x  \frac{\partial^2 \zeta}{\partial t^2} = - T \frac{\Delta \zeta}{\Delta x}.$$
Wenn wir jetzt durch $\Delta x$ teilen und $\Delta x \rightarrow 0$ annehmen,
ergibt sich
$$ \frac{\partial^2 \zeta}{\partial t^2} = -\frac{T}{\mu} \frac{\partial^2 \zeta}{\partial x^2}.$$
Diese partielle Differenzialgleichung zweiter Ordnung ist ein Beispiel für die
**Wellengleichung**. Von den Einheiten der Ausdrücke ist zu erkennen, dass der
Term $T/\mu$ eine quadrierte Geschwindigkeit ist. Wir können mit unserer bekannten
Lösung der Form $\zeta(x-vt)$ zeigen, dass
$$ v = \sqrt{\frac{T}{\mu}$$
die Ausbreitungsgeschwindigkeit einer Seilwelle mit Seilspannung $T$ und Massenbelegung (Masse/Länge) $\mu$ ist.



