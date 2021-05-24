---
title: "Viskose Reibung"
date: 2021-05-21T18:58:18+02:00
weight: 23
---
## Reibungskräfte bei Bewegung in einer Flüssigkeit 
Ein Körper, der sich mit der Geschwindigkeit $\mathbf{v}$ durch eine Flüssigkeit bewegt, erfährt eine Reibungskraft der folgenden Form

$$ \mathbf{F}_r = - (k_1 v + k_2 v^2) \mathbf{\hat{v}},$$
wobei $\mathbf{\hat{v}}$ der Einheitsvektor der Geschwindigkeit ist. 
Der erste Term repräsentiert den __viskosen Widerstand__ und der zweite Term  den __Druckwiderstand__ (__Wirbelwiderstand__). 

Für den Spezialfall einer Kugel mit Radius $r$ ist
$$ |\mathbf{F}_r| = C_1 r v + C_2 r^2 v^2,$$
wobei $C_1$ proportional zur Viskosität ist und $C_2$ proportional zu der Dichte des Mediums ist. 

### Kritische Geschwindigkeit $v_\mathrm{krit.}$
Für die kritische Geschwindigkeit gilt:
$$ C_1 r v_\mathrm{krit} = C_2 r^2 v_\mathrm{krit}^2,$$ 
bzw.
$$ v_\mathrm{krit} = \frac{1}{r} \frac{C_1}{C_2} \propto \frac{1}{r}.$$


### Endgeschwindigkeit
Für eine Kugel, die in einem Medium frei fällt, ergibt sich eine maximale Geschwindigkeit
$v_\mathrm{term}$  
(terminal velocity) , bei der 

$$mg = F_r = C_1rv_\mathrm{term} + C_2 r^2 v^2_\mathrm{term}$$
gilt. Diese maximale Geschwindigkeit wird z.B. für Regentropfen erreicht und sorgt dafür, dass
wir einen Regenfall unbeschadet überstehen (ohne die Reibungskräfte würden Regentropfen eine unangenehm hohe
kinetische Energie haben). 


#### Viskoser Widerstand dominiert
Für $v\ll v_\mathrm{krit}$ dominiert der viskose Reibungsterm, so dass
$$ mg = \frac{4}{3} \rho r^3 = C_1 v_\mathrm{term} r,$$
und damit
$$ v_\mathrm{term}= \frac{4}{3} \frac{\rho}{C_1} r^2 \propto r^2.$$


#### Druckreibung dominiert
Für $v\gg v_\mathrm{krit}$ dominiert die Druckreibung, so dass
$$ mg = \frac{4}{3} \rho r^3 = C_2 v_\mathrm{term}^2 r^2,$$
und damit
$$ v_\mathrm{term} = \sqrt{\frac{4}{3} \frac{\rho}{C_2} r }\propto r^{1/2}.$$

#### Numerisches Beispiel
Das numerische Beispiel können Sie via python notebook selbst ausführen
und mit den Parametern spielen. 

Versuchen Sie zum Beispiel folgende Frage zu lösen: Anstatt den Ball fallen zu
lassen, werfen Sie den Ball senkrecht mit einer Geschwindigkeit $v_0$ nach oben. Vergleichen Sie
die Zeit, die der Ball benötigt, um den höchsten Punkt zu erreichen mit der Zeit, die der Ball dann
benötigt, um den Ausgangspunkt wieder zu erreichen? Fliegt der Ball länger/kürzer/gleich lang?

Sie können das Problem auch durch Nachdenken lösen.

{{< gist dieterhorns a2c8edb5c0240c5a87ace94ff46d9d14 >}}








