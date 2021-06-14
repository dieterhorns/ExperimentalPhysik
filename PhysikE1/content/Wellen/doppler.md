---
title: "Dopplereffekt"
date: 2021-05-10T17:31:26+02:00
weight: 11
description: "Bewegter Sender, bewegter Empfänger, Anwendungen"
---

## Beobachtung des Doppler-Effekts
Wir kennen das Phänomen einer scheinbaren Veränderung der Tonhöhe
von z.B. dem Martinshorn der Feuerwehr bei relativer Bewegung von Sender und
Empfänger zueinander.  Wir betrachten im Folgenden den einfachsten Fall eines
Senders und Empfängers die sich entlang der Verbindungslinie relativ zueinander bewegen. 

Wir nehmen weiterhin an, dass das Medium in Ruhe ist.

Experiment: Bewegte Stimmgabel. Mikrofon. Plastikrohr. 
### Bewegter Sender
Die Frequenz $\nu$ und die Ausbreitungsgeschwindigkeit 
der Schallwelle $c$ des bewegten Senders (Geschwindigkeit $v$)  
bleibt konstant. Die Abfolge der Wellenzüge (Wellenlänge) wird
jedoch durch die relative Bewegung während der Emission für den 
ruhenden Empfänger verkürzt. Nehmen wir
an, dass die Wellenlänge $\lambda = c/\nu$ in Ruhe wahrgenommen wird. 
Während der Periode $P=1/\nu$  bewegt sich der Sender um die Wegstrecke
$\Delta x = Pv = v/\nu$. Die wahrgenommene Wellenlänge $\lambda'$, also die 
Abfolge von zwei Wellenzügen ist gegeben durch $\lambda' = \lambda - \Delta x.$
Die resultierende wahrgenommene Frequenz $\nu'=c/\lambda'$:
$$ \nu' = \frac{c}{\lambda - v/\nu}= \frac{c}{\frac{c}{\nu} - \frac{v}{\nu}} 
  = \nu \frac{1}{1-\frac{v}{c}}\approx \nu (1+\frac{v}{c}).$$

Für den Fall, dass $v\ge c$ gilt, ergibt sich die interessante Situation, dass
der Sender sich schneller bewegt als die Ausbreitungsgeschwindigkeit der 
Wellen. In diesem Fall bildet sich eine Wellenfront aus, der sogenannte Mach-Kegel.
Die Wellenfront entspricht der Überlagerung aller Wellen, die entlang der
Bahnkurve des Körpers abgegeben wurden. Für Schallwellen
entsteht eine nicht-lineare Schockwelle, die als lauter Knall (_Überschallknall_)
wahrgenommen wird (bei ausgedehnten Objekten ergeben sich auch mehrere Mach-Kegel).

Der Öffnungswinkel des Mach-Kegels ergibt sich aus der Mach-Zahl $\mathcal{M}=v/c$:
$$ \sin \theta = \frac{1}{\mathcal{M}}=\frac{c}{v}.$$

## Bewegter Empfänger
Der Abstand der Wellenfronten $\lambda$ ist konstant, aber die Zeit, die ein bewegter
Beobachter zwischen zwei Wellenfronten wahrnimmt, verkürzt sich, weil die
Geschwindigkeit sich vergrößert:
$$c' = c + v$$
und damit ist 
$$\nu' = \frac{c'}{\lambda} = \frac{c+v}{\lambda} = \nu\left(1+\frac{v}{c}\right).$$

## Allgemeiner Fall
Im allgemeinen können sich sowohl Sender ${v}_S$ 
als auch Empfänger bewegen ${v}_E$. 
$$ \nu' = \nu \frac{1+v_S/c}{1-v_E/c}.$$
## Anwendungen
   * Dopplereffekt in der Medizin: Bei Ultraschalluntersuchungen kann die Frequenzverschiebung bei der Reflexion an z.B. Blut in Adern benutzt werden, um deren 
Fließgeschwindigkeit zu bestimmen.
   * Dopplereffekt in der Astrophysik: In stellaren Systemen kommen häufig Doppelsterne vor, sogenannte Binärsysteme. Die Sterne bewegen sich hierbei periodisch auf den Beobachter zu und vom Beobachter weg. Da elektromagnetische Wellen genau so wie akustische Wellen einen Dopplereffekt zeigen, verschieben sich die beobachteten Frequenzen 
von Spektrallinien periodisch. 
  

