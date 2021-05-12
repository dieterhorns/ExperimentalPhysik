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

Ein Sonderfall sind harmonische Wellen mit 
$$\zeta(x,t) =  \zeta_0 \sin(k(x-vt)),$$
wobei  die _Wellenzahl k_ 
$$ k:= \frac{2\pi}{\lambda} $$
mit der _Wellenlänge_ $\lambda$ verknüpft ist. Die Wellenlänge
gibt an, wie groß der Abstand von zwei Maxima (res. Minima) zueinander ist, wenn 
wir die Welle zu einem festen Zeitpunkt anschauen. 

An einem festen Ort oszilliert z.B. ein kleines Seilstück   mit einer Kreisfrequenz
$$ \omega = k~v,$$
Im einfachsten Fall ist die Geschwindigkeit 
$$v = \frac{\omega}{k} = \nu\lambda $$
zeitlich und räumlich konstant ($\omega=2\pi \nu$). 
Im allgemeinen ergeben sich jedoch 
kompliziertere _Dispersionsrelationen_ wenn z.B. die Ausbreitungsgeschwindigkeit
oder die Wellenlänge variieren.


   * Alle Funktionen $\zeta(x-vt)$ beschreiben eindimensionale Wellen, die sich
entlang der positiven $x$-Richtung ausbreiten. 
   * Alle Funktionen $\zeta(x+vt)$ beschreiben eindimensionale Wellen, die sich 
entlang der negativen $x$-Richtung ausbreiten.
   * Die Funktion $\zeta(x)$ gibt hierbei die Form der Welle an.
   * Harmonische Wellen sind von der Form 
  $$\zeta(x,t)=\zeta_0 \sin(k(x\pm vt)) = \zeta_0 \sin(kx\pm\omega t).$$
   * Wellen lassen sich als Überlagerung von harmonischen 
Wellen darstellen
  $$ \zeta(x,t) = \sum_i \zeta_i \sin(k_ix - \omega t).$$

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
$$ v = \sqrt{\frac{T}{\mu}}$$
die Ausbreitungsgeschwindigkeit einer Seilwelle mit Seilspannung $T$ und Massenbelegung (Masse/Länge) $\mu$ ist.


## Reflexion einer Welle
Wenn wir eine Seilwelle betrachten, die auf ein fixiertes Ende zuläuft, beobachten wir
   * eine reflektierte  (zurücklaufende Welle)
   * einen einlaufenden Wellenberg, der als Wellental (und umgekehrt) reflektiert
     wird.
Wenn das Ende frei bewegelich ist, beobachten wir, dass ein Wellenberg als Wellenberg reflektiert wird (bzw. ein Wellental als Wellental zurückläuft.

Wir sprechen im Falle eines festen Endes von einem _Phasensprung_ um $\pi$ bei
der Reflektion. 

Die reflektierte Welle überlagert sich mit der einlaufenden Welle. Sind beide 
Enden der Seilwelle fixiert, bilden sich ggfs. _stehende Wellen_.

Die resultierende Seilwelle mit zwei fixierten Enden im Abstand
$L$ zueinander ist die Überlagerung der einlaufenden $\zeta_\mathrm{ein}$ und
reflektierten $\zeta_\mathrm{refl}$ Welle:
$$ \zeta(x,t) = \zeta_\mathrm{ein}(x,t) + \zeta_\mathrm{refl}(x,t).$$
Ist die Amplitude der einlaufenden und reflektierten Welle jeweils gleich groß 
ergibt sich 
$$ \zeta(x,t) = \zeta_0 (\sin (kx - \omega t) + \sin(kx+\omega t)).$$
Mit dem Additionstheorem ist
$$ \zeta(x,t) = \zeta_0 (\sin kx \cos \omega t - \sin\omega t \cos kx
                       + \sin kx \cos \omega t + \sin\omega t \cos kx),$$
$$ \zeta(x,t) = 2 \zeta_0 \sin kx \cos \omega t.$$
Wir haben zusätzlich die Bedingung zu erfüllen, dass für die Punkte $x=0$
und $x=L$ gelten muss $\zeta(0,t)=\zeta(L,t)=0$. Damit gibt es nur Lösungen mit
$kL = \pi, 2\pi, 3\pi, 4\pi, 5\pi, \ldots$. Die möglichen Wellenlängen für
diese Lösungen sind $\lambda = 2L, L, 2/3 L, L/2, 2/5~L, \ldots, 2~L/n$, mit
$n={1,2,3,\ldots}$.  
 
Die stehende Welle hat die interessante Eigenschaft, dass sie stationär ist, d.h.
die Position der $n$ Bäuche und $n+1$ Knoten ändert sich zeitlich nicht. 

Wir haben im bisherigen Beispiel nur die Überlagerung der einlaufenden und
reflektierten Welle betrachtet. Es kommt jedoch zu weiteren Reflexionen. Das
Resultat ist eine _Überhöhung_ der Amplitude der Welle. Schon eine geringe
Auslenkung bei der Anregung der Welle führt zu einem starken Ausschlag. 
