---
title: "Kinetische Gastheorie"
date: 2021-06-24T20:48:15+02:00
weight: 20
---
## Kinetische Gastheorie
Die Zustandsgrößen Druck ($p$) und Temperatur ($T$)  haben wir bislang
_makroskopisch_ definiert ohne dabei über einen Zusammenhang zu den zugrundeliegenden
_mikroskopischen_ Eigenschaften des Gases nachzudenken. Wir können einen unmittelbaren
Zusammenhang herstellen, indem wir für das ideale Gas annehmen, dass es aus Molekülen
(bzw. Atomen) besteht, die untereinander und mit der Wand elastisch stoßen können. Die
Ausdehnung der Moleküle kann zunächst vernachlässigt werden. Da es keine weiteren
Austauschkräfte zwischen den Molekülen im idealen Gas gibt, kann es auch keine Phasenübergänge
geben. 

## Druck, Temperatur
Die Moleküle der Masse $m$ bewegen sich ungeordnet in alle Richtungen in einem würfelförmigen 
Volumen $V=L^3$. Betrachten wir zunächst die 
Geschwindigkeitskomponente $v_x$, dann werden die Moleküle nach einer endlichen Zeit
$t=L/v_x$ das Volumen des Würfels durchqueren und elastisch an der Wand bei $x=L$ stoßen.
Bei dem elastischen Stoß wird der Impuls $2 m v_x$ übertragen. Die mittlere Zeit zwischen zwei
Stößen ist $\Delta t = 2t = 2L/v_x$, so dass der Impulsübertrag pro Zeit pro Molekül:
$$ F_x = \frac{2 m v_x}{2L/v_x} = \frac{m}{L} v_x^2.$$
Wenn wir in dem Volumen $N$ Moleküle haben, ist die Gesamtkraft gegeben durch die Summe
der Kräfte der einzelnen Moleküle $F_i$:
$$ F_x = \sum F_i = \frac{m}{L} \sum v_{x,i}^2 = \frac{m}{L} N \frac{1}{N} \sum v_{x,i}^2,$$
wobei im letzten Schritt das mittlere Geschwindigkeitsquadrat $\langle v_x^2\rangle$  eingeführt wird:
$$ \langle v_x^2\rangle = \frac{1}{N} \sum\limits_{i=1}^{N} v_{x,i}^2:$$
$$ F_x = \frac{N}{L} m \langle v_x^2 \rangle.$$

Für eine isotrope Geschwindigkeitsverteilung sind die mittleren Geschwindigkeitsquadrate
der drei Raumrichtungen alle gleich groß:
$$\langle v_x^2\rangle = \langle v_y^2\rangle = \langle v_z^2 \rangle = \frac{1}{3} \langle v^2\rangle.$$
Die Gleichheit ergibt sich aus dem Zusammenhang $v^2 = v_x^2 + v_y^2 + v_z^2$.

Mit dem Zusammenhang $p=F/A$ und $AL=V$:
$$ p = \frac{F}{A} = \frac{N}{3LA} m \langle v^2\rangle = \frac{2N}{3} \frac{m}{2} \langle v^2 \rangle$$
ergibt sich sofort die Zustandsgleichung des idealen Gases $pV = N k_B T$:
\begin{equation}
 p V = \frac{2}{3} N \langle E_\mathrm{kin}\rangle = N k_B T,
\end{equation}
wobei
$$ \langle E_\mathrm{kin} \rangle = \frac{m}{2} \langle v^2\rangle = \frac{3}{2} k_B T.$$

   1. Temperatur ist ein Maß für die mittlere kinetische Energie der zugrundeliegenden Bewegung der Moleküle.
   2. Die mittlere kinetische Energie ist $k_BT/2$ pro _Freiheitsgrad_: In unserem Beispiel ist die Zahl der 
      Freiheitsgrade $f=3$ für die drei Raumrichtungen. Weitere Freiheitsgrade ergeben sich z.B. durch Anregung 
      von Rotationsbewegungen oder auch elastischen Schwingungen bei mehratomigen Molekülen.
   3. Bei Gasen mit unterschiedlichen Molekülen ist die mittlere kinetische Energie für alle Sorten identisch.
      Aufgrund der unterschiedlichen Masse sind die Geschwindigkeiten jedoch entsprechend unterschiedlich!
   4. Thermodynamisches Gleichgewicht bzw. gleiche Temperaturen entspricht Gleichheit der kinetischen Energie.
      

## Geschwindigkeitsverteilung
Bei einer gegebenen Temperatur $T$ und Masse der Moleküle $m$ ist die mittlere quadratische Geschwindigkeit
$$ \langle v^2 \rangle = \frac{3 k T }{m},$$
bzw. die Quadratwurzel hieraus (_root mean square_ oder _RMS_):
$$ \sqrt{\langle v^2\rangle } = \sqrt{\frac{3 k T}{m}}.$$

Die mittlere Geschwindigkeit ist 
Wie sieht jedoch die Verteilung der Geschwindigkeiten aus?

Ohne Ableitung ergibt sich die **Maxwell-Boltzmann Geschwindigkeitsverteilung** für ein isotropes Gas (alle
Richtungen sind gleich wahrscheinlich):

$$ dN = N_0 4\pi v^2 dv e^{-\frac{mv^2}{2 kT}}, $$
mit der Normierung  
$$ N_0 = n~N_A \left(\frac{m}{2\pi kT}\right)^{3/2},$$
so dass sich bei der Integration 
$$ \int dN = 4\pi \int\limits_0^\infty dv v^2 N_0 e^{-\frac{mv^2}{2kT}}  = n N_A$$
die Gesamtzahl der Teilchen für ein Gas aus $N=nN_A$ Molekülen ergibt.

## Boltzmann-Verteilung 
Wir können die (massenabhängige) Geschwindigkeitsverteilung auch in eine Verteilung der kinetischen Energie umschreiben. 
Mit 
$$ E_\mathrm{kin} = \frac{m}{2} v^2 = \frac{3}{2} kT,$$
ist 
$$\frac{dE_\mathrm{kin}}{dv} = mv\qquad dE_\mathrm{kin} = mv dv,$$
so dass 
$$ dN =  n N_A \frac{2}{\sqrt{\pi}} \left( \frac{1}{kT}\right)^{3/2} \sqrt{E_\mathrm{kin}} \exp\left( -\frac{E_\mathrm{kin}}{kT}\right) dE_\mathrm{kin}.$$
Wenn wir das Verhältnis der Moleküle mit Energie $E_\mathrm{kin}>E_0$ zu allen Molekülen $nN_A$ anschauen, integrieren wir die
Verteilungsfunktion der kinetischen Energie auf und erhalten 
$$ \frac{N(E_\mathrm{kin}>E_0)}{nN_A} = \frac{2}{\sqrt{\pi}} \sqrt{\frac{E_0}{kT}} \exp\left(-\frac{E_0}{kT}\right).$$
Diese charakteristische Reduktion der Anzahl der Moleküle mit einem exponentiellen Term $\exp(-E/kT)$ ist ein Beispiel der __Boltzmann-Verteilung__
für Gleichgewichtszustände.



