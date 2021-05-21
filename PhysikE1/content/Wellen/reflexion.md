---
title: "Reflexion und stehende Welle"
date: 2021-05-10T17:31:26+02:00
weight: 4
description: "Reflexion von Wellen, Überlagerung von Wellen"
---

## Reflexion am Beispiel Seilwelle
Wenn wir eine Seilwelle betrachten, die auf ein *fixiertes Ende* zuläuft, beobachten wir
   * eine reflektierte  (zurücklaufende Welle)
   * einen einlaufenden Wellenberg, der als Wellental (und umgekehrt) reflektiert
     wird.
Wenn das Ende *frei beweglich* ist, beobachten wir,
   * dass ein Wellenberg als Wellenberg reflektiert wird (bzw. ein Wellental als Wellental zurückläuft.

Wir sprechen im Falle eines festen Endes von einem _Phasensprung_ um $\pi$ bei
der Reflexion. 

## Überlagerung der Wellen
Die reflektierte Welle überlagert sich mit der einlaufenden Welle. Sind beide 
Enden der Seilwelle fixiert, bilden sich ggfs. _stehende Wellen_.

Die resultierende Seilwelle mit zwei fixierten Enden im Abstand
$L$ zueinander ist die Überlagerung der einlaufenden $\zeta_\mathrm{ein}$ und
reflektierten $\zeta_\mathrm{refl}$ Welle:
$$ \zeta(x,t) = \zeta_\mathrm{ein}(x,t) + \zeta_\mathrm{refl}(x,t).$$
Ist die Amplitude der einlaufenden und reflektierten Welle jeweils gleich groß,
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
reflektierten Welle betrachtet. Es kommt jedoch zu weiteren Reflexionen, die
sich überlagern. Das
Resultat ist eine _Überhöhung_ der Amplitude der Welle (ähnlich einer
Resonanz bei einer angeregten Schwingung). Schon eine geringe
Auslenkung bei der Anregung der Welle führt zu einem starken Ausschlag. 
