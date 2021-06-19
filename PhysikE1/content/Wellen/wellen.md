---
title: "Wellen"
date: 2021-05-10T17:31:26+02:00
weight: 2
description: "Wellenphänomene"
---
## Allgemeine Wellen
Aus der Beobachtung von Phänomenen in der Natur ist uns allen der
Begriff der Welle vertraut. Wir kennen z.B. Wasserwellen und Seilwellen. 

Im Unterschied zu einer Schwingung, breitet sich eine Welle im Raum aus. 
Bei der Seilwelle können wir feststellen, dass die
Auslenkung (_Elongation_)  des Seils $\zeta$ mit zunehmender Zeit 
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
Im einfachsten Fall ist die Ausbreitungsgeschwindigkeit 
$$v = \frac{\omega}{k} = \nu\lambda $$
zeitlich und räumlich konstant ($\omega=2\pi \nu$). 

Im allgemeinen ergeben sich jedoch 
kompliziertere _Dispersionsrelationen_ wenn z.B. die Ausbreitungsgeschwindigkeit
oder die Wellenlänge räumlich variieren.

   * Alle Funktionen $\zeta(x-vt)$ beschreiben eindimensionale Wellen, die sich
entlang der _positiven_ $x$-Richtung ausbreiten. 
   * Alle Funktionen $\zeta(x+vt)$ beschreiben eindimensionale Wellen, die sich 
entlang der _negativen_ $x$-Richtung ausbreiten.
   * Die Funktion $\zeta(x)$ gibt hierbei die Form der Welle an.
   * Harmonische Wellen sind von der Form 
  $$\zeta(x,t)=\zeta_0 \sin(k(x\pm vt)) = \zeta_0 \sin(kx\pm\omega t).$$
   * Wellen lassen sich als Überlagerung von harmonischen 
Wellen darstellen
  $$ \zeta(x,t) = \sum_i \zeta_i \sin(k_ix - \omega t).$$
   * Die Auslenkung der Seilwelle ist ein Beispiel einer *transversalen* Welle (Schwingungsrichtung senkrecht zur Ausbreitungsrichtung)
   * Die Dichteänderung von Schallwellen ist ein Beispiel für 
     eine *longitudinale* Welle (Schwingungsrichtung parallel zur Ausbreitungsrichtung)
   * Wellen, die  sich in Richtung des Wellenvektors  
  $\mathbf{k}=k_x \mathbf{e}_x+k_y\mathbf{e}_y+k_z\mathbf{e}_z$ ausbreiten:  
  $$ \zeta(\mathbf{k}\cdot  \mathbf{r} \pm \omega t)$$
