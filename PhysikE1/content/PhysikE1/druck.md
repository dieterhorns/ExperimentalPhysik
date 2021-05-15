---
title: "Druck"
date: 2021-05-14T18:35:37+02:00
---
## Flüssigkeit
Im Vergleich zu den elastischen Änderungen eines Festkörpers und der 
Kompressibilität von Gasen, verhalten sich Flüssigkeiten deutlich anders:
   * Das Schermodul einer Flüssigkeit $G\approx 0$: Experimentell beobachten wir, dass die
Flüssigkeit in einem rotierenden Gefäß eine Paraboloid-Form annimmt.
   * Eine Flüssigkeit ist (nahezu) inkompressibel.

## Statischer Druck
Wenn wir mit einem Stempel eine Kraft $F$ senkrecht auf eine Oberfläche $A$ einer Flüssigkeit ausüben, entspricht
das einem _statischen Druck_ $p$:
$$ p:= \frac{F}{A}.$$
Die Kraft ist hier keine vektorielle Größe, weil es sich immer um die Normalkomponente der Kraft handelt. 
Die Einheit für Druck ist das _Pascal_ [Pa=N~m$^{-2}$]. 

Der statische Druck in einer ruhenden Flüssigkeit ist überall gleich groß. Experiment Wasserigel.

Warum ist der Druck überall gleich groß? Betrachten wir ein Volumenelement $dV$ in einer ruhenden Flüssigkeit, so muss die
Summe der wirkenden Kräfte verschwinden (ansonsten würde das Volumenelement nicht in Ruhe verharren). 
Nehmen wir an, dass Volumenelement spannt den Bereich von $x$ nach $x+dx$, $y$ nach $y+dy$ und $z$ nach $z+dz$ auf.
Dann können wir davon ausgehen, dass komponentenweise die Kraft auf den gegenüberliegenden Seiten gleich groß und 
entgegengesetzt zueinander sein müssen. In $x$-Richtung muss z.B. gelten:
$$F_x = p(x,y,z)dydz - p(x+dx,y,z) dydz = 0$$
$$ 0 = p(x,y,z)dydz - \left(p(x,y,z) + \frac{\partial p}{\partial x} dx\right) dydz$$
$$ 0 = -\frac{\partial p}{\partial x} dV. $$
Analog lassen sich Gleichungen für $F_y$ und $F_z$ aufstellen, so dass für den Vektor der  Kraft $\mathbf{F}$ gilt:
$$\mathbf{F} = - \mathbf{\nabla} \cdot p dV = - \left(\frac{\partial p}{\partial x}\mathbf{e}_x 
                                                 +\frac{\partial p}{\partial y}\mathbf{e}_y
                                                 +\frac{\partial p}{\partial z}\mathbf{e}_z\right) dV .$$
Die geforderte Kräftefreiheit $\mathbf{F} = 0$
im statischen Fall  entspricht der Bedingung, dass  die partiellen Ableitungen von $p$ verschwinden, also $p=$konst.

Anwendung: Hydraulische Presse. Wir betrachten zwei Stempel mit unterschiedlichen Flächen $A_1$ und $A_2$. 
Wenn die Kraft $F_1$ auf den Stempel mit Fläche $A_1$ wirkt, ist der Druck in der ruhenden Flüssigkeit $p=F_1~A_1$. 
Das bedeutet für den zweiten Stempel, dass mit 
$$ F_1 A_1 = F_2 A_2,$$
die Kraft $F_2$ 
$$ F_2 = F_1 \frac{A_1}{A_2}.$$
bei geeigneter Wahl des Verhältnis $A_1/A_2\gg 1$ deutlich größer als die Kraft $F_1$ sein kann. Diesem Effekt liegt
die Inkompressibilität von Flüssigkeiten zugrunde und
wird für hydraulische Pressen, Wagenheber etc. benutzt.  

Auch wenn die Kraft $F_1$ klein ist, wird die geleistete Arbeit an den beiden Stempeln gleich groß sein.
 Die Reduzierung der Kraft wird durch einen entsprechend längeren Weg $d_2>d_1$ 
kompensiert - das ergibt sich aus der Bedingung, dass die Volumina gleich groß sein müssen: 
$$ d_1 A_1 =  d_2 A_2,$$
so dass $F_1 d_1 = F_2 d_2$ gilt.



## Schweredruck
Befindet sich die Flüssigkeit in einem Schwerefeld, wirkt auf jedes Volumenelement eine Schwerekraft
$$\mathbf{F}= \rho \mathbf{g} dV,$$
wobei $\rho$ die Massendichte der Flüssigkeit ist. Um zu gewährleisten, dass die Flüssigkeit in 
Ruhe verharrt, muss der Druck in der Flüssigkeit variieren: 

 Hieraus ergibt sich, dass 
$$\rho \mathbf{g}~dV = -(\mathbf{\nabla}\cdot p) dV$$ 
und der Gradient 
$$\mathbf{\nabla}\cdot p = - \rho \mathbf{g}$$
sein muss. 

Wie sieht unter Einfluss der Schwerebeschleunigung $\mathbf{g}=-g\mathbf{e}_z$
der Druck in einer Flüssigkeit aus?  Nehmen wir an, dass die Flüssigkeit,
mit der Dichte $\rho$ sich in einem zylindrischen Gefäß mit Radius
$R$, befüllt bis zu der Höhe $h$ befindet. Die Position $z=0$ befindet sich auf
der Höhe des Gefäßbodens, der Füllstand liegt bei $z=h$.

Wir können annehmen, dass $p=p(z)$ nur von der $z$-Koordinate abhängt, deswegen
benötigen wir nur eine Lösung für $p(z)$ aus
$$ \frac{d p}{dz} = - \rho~g.$$
Mit Separation der Variablen 
$$ dp = - \rho g dz.$$
Wir können beide Seiten unter Einbehaltung der Randbedingung $p(h)=p_{atm}$
lösen
$$\int\limits_{p(z)}^{p_{atm}}dp' = - \int\limits_{z}^{h} dz' \rho g.$$
In unserem Fall ist $\rho$ und $g$ für den betrachteten Bereich konstant, so dass
$$p_{atm}- p(z)  = - \rho g (h-z), $$
bzw.
$$p(z) = p_{atmo} + \rho g (h-z).$$
Die Lösung zeigt das erwartete Verhalten: für $z=h$ ist $p=p_{atm}$. Der Druck steigt
dann linear mit der Tiefe an und erreicht für $z=0$ am Gefäßboden den höchsten Wert 
$p(0) = p_{atm}+ \rho g h$.

Experiment: Wir öffnen seitliche Löcher in einem Wassergefäß und beobachten das ausströmende Wasser in verschiedenen
Höhen. 

  * Der atmosphärische Druck ist auf Meeresniveau  $p_{atm}=101325$ Pa  (Normaldruck).
  * Der Schweredruck $\rho g h$ für Wasser nimmt pro Meter um $\Delta p / \Delta z \approx 98100$ Pa/m zu, so 
dass in einer Tiefe von etwa 10,4~m der Druck der Wassersäule gleich groß dem atmosphärischen Druck wird.
  * Die Größe des Drucks hängt nicht von der Wassermenge oder der Form des Gefäßes ab sondern lediglich von der Höhe!
