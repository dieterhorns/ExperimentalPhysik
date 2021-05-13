---
title: "Wellengleichung"
date: 2021-05-10T17:31:26+02:00
description: "Beispiel Seilwelle"
---
## Wellengleichung
Wir können die Seilwelle im Hinblick auf die zugrundeliegende
Bewegungsgleichung für ein kleines Seilstück der Länge $\Delta x$ betrachten.
Die Masse $m=\Delta x \mu$, wobei $\mu = \Delta m /\Delta x$ die Massenbelegung
ist (wir nehmen an, dass die Massenbelegung konstant ist).

Das Seil ist gespannt mit der Seilspannung $T$. Wenn das Seil ausgelenkt wird, 
erfährt das Seil eine Kraft in Richtung der Auslenkung $\Delta \zeta=\zeta(x+\Delta x)-\zeta(x)$
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

## Polarisation von transversalen Wellen
Für transversale Wellen ergeben sich zwei mögliche Schwingungsrichtungen. Bei der
Seilwelle können wir z.B. die Auslenkung in zwei senkrecht zueinander stehenden
Richtungen unterscheiden. Wir sprechen hier von linear polarisierten Wellen.

Wenn die Schwingungsrichtung zeitlich variiert, ist die Welle elliptisch polarisiert, bei gleicher Amplitude der beiden Schwingungsrichtungen sprechen wir von zirkulär
polarisierten Wellen. 




