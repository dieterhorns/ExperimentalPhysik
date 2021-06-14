---
title: "Oberflächen"
date: 2021-06-14T17:19:19+02:00
---
## Oberflächenspannung
An der Oberfläche (bzw. Grenzschicht) einer Flüssigkeit fehlen die benachbarten 
Atome/Moleküle. Die Atome sind dort weniger stark gebunden. Um die Oberfläche
zu _vergrößern_, muss die Bindungsenergie der entsprechenden 
neuen Oberflächenatome reduziert werden.

Die Energie $\Delta W$  pro Fläche  $\Delta A$ ist die Oberflächenergie $\epsilon$:
$$ \epsilon = \frac{\Delta W}{\Delta A}.$$

Die Kraft, die nötig ist, um die Oberflächenergie zu vergrößern (Experiment:
Metallbügel der Seitenlänge $L$ in Seife eingetaucht) ergibt sich aus der 
Änderung der Oberfläche um $\Delta A$: 

$$ \Delta W = F \Delta s = \epsilon \Delta A = \epsilon 2 L \Delta s,$$
so dass
$$ \epsilon = \frac{F}{2L}.$$
wobei im Falle von Seifenblasen/ Seifenlamellen die Oberfläche eine Vorder- und Rückseite hat (deswegen
ist der Faktor 2 nötig).

Die sich ergebende Kraft pro Längeneinheit 
$$ \sigma := \frac{F}{2L} = \epsilon$$
wird **Oberflächenspannung** genannt und ist gleich der Energie pro Fläche.
            
### Demoexperiment: Kleine/Große Seifenblase
Wenn wir zwei Seifenblasen über einen Schlauch/Strohhalm miteinander 
verbinden, stellen wir fest, dass überraschenderweise die kleine Seifenblase von der großen
Seifenblase aufgesaugt wird. 

Erklärung:
Im Gleichgewicht ist eine isolierte Seifenblase so groß, dass der innere Druck
abhängig vom Radiue ein wenig
höher ist als der atmosphärische (äußere) Druck.
 Der nötige Überdruck $p(R)$ ist 
 gegeben durch die 
Oberflächenspannung, so dass die Änderung des Radius $\Delta R$ eine
Änderung der Oberfläche $\Delta A$ ergibt. Hierzu ist die Kraft 
$F=4\pi R^2 p$ nötig::
$$ F \Delta R = 4\pi R^2 p  \Delta R=   \epsilon \Delta A $$
Die Änderung der Oberfläche $\Delta A$ bei Änderung des Radius $\Delta R$: 
$$ \Delta A = 2 \frac{dA}{dR} \Delta R $$
(Faktor 2: es sind zwei Oberflächen: die Innen- und die Außenseite), so  dass 
mit 
$$\frac{dA}{dR} = 8 \pi R:$$
$$  \epsilon 16 \pi R \Delta R = p 4\pi R^2 \Delta R,$$
und damit ist der Überdruck
$$ p = \frac{4\epsilon}{R} \propto \frac{1}{R}.$$

Jetzt wird deutlich, warum die kleinere Blase einen höheren Druck im Inneren hat 
als die größere Blase. Durch den Druckausgleich zwischen den beiden Blasen verringert
sich der Radius der kleinen Blase weiter, so dass der Prozess mit zunehmender
Schnelligkeit abläuft, bis die kleinere Blase verschwunden ist.

### Demoexperiment Minimalflächen
Seifenwasserlamellen bilden Minimalflächen, so dass lokal der Flächeninhalt bei einer gegebenen Randlinie minimiert wird.

Beispiele für einfache Minimalflächen:
   * Ring: es bildet sich eine plane Fläche, die auch bei Störungen wieder in die plane Form zurückkehrt.
   * Ring im Ring: Wenn wir in die plane Fläche eine Schlaufe einbringen, bildet sich ein perfekt kreisförmiges Loch.
   * Zwei parallele Ringe: Die resultierende Form ist der Katenoid (rotierte Kettenlinie) 
   * Spirallinie: Wendelfläche (Helikoid)

Die Eigenschaft von Seifenlamellen, die Oberflächenenergien zu minimieren führt zu Oberflächen, die die Eigenschaften 
von Minimalflächen haben (siehe z.B. Drahtrahmen in Würfelform in Seifenwasser).

