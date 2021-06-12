---
title: "Energietransport"
date: 2021-06-12T21:11:49+02:00
---
## Leistung
Eine Welle überträgt Energie. Bei der Seilwelle wird z.B. bei der Auslenkung eines
Seilelements Arbeit geleistet. Bei der Rückkehr in die Ruheposition wird wiederum
Arbeit an einem benachbarten Seilelement geleistet. 

Die rücktreibende Kraft beim Seil hatten wir bereits bei der 
[Wellengleichung]({{< ref "wellen/wellengleichung" >}})
kennengelernt
$$ F = -T \frac{\partial \zeta}{\partial x}.$$
Die Rate, mit der Arbeit durch diese Kraft geleistet wird ergibt sich als Leistung aus
$$ P= F v = -T \frac{\partial \zeta}{\partial x} \frac{\partial \zeta}{\partial t}.$$

Für eine harmonische Seilwelle ergibt sich mit
$$ \zeta = \zeta_0 \sin(kx-\omega t),$$
$$ \frac{\partial \zeta}{\partial t} = -\omega \zeta_0 \cos(kx - \omega t),$$
$$ \frac{\partial \zeta}{\partial x} = k \zeta_0 \cos(kx - \omega t),$$
$$ P = T k \omega \zeta_0^2 \cos^2(kx-\omega t).$$
Wir kennen den Zusammenhang $v=\omega/k = \sqrt{T/\mu}$ und ersetzen $k=\omega \sqrt{\mu/T}$:
$$ P = \sqrt{T\mu} \omega^2 \zeta_0^2 \cos^2(kx-\omega t).$$
Als letztes mitteln wir den $\cos^2(t)$ über die Zeit $\langle \cos^2(t)\rangle = 1/2$:
$$ \langle P \rangle = \frac{\sqrt{T\mu}}{2} \omega^2 \zeta_0^2.$$

Wir finden die für Wellen typische Eigenschaft, **dass die übertragene Leistung quadratisch
mit der Frequenz und der Amplitude ansteigt**.

