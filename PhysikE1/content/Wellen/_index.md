---
title: Wellen
Featured_image: "/images/battle_rope.jpg"
weight: 30
---
## Überblick 
### Wellengleichung
Lineare und ungedämpfte ein-dimensionale Wellen mit Elongation $\zeta(x,t)$
sind Lösungen der _Wellengleichung_:
$$ \frac{\partial^2 \zeta}{\partial t^2} = v^2 \frac{\partial^2 \zeta}{\partial x^2}.$$

Harmonische Wellen:
$$ \zeta(x,t) = \zeta_m \cos (\omega t - kx + \varphi),$$
mit der Wellenzahl 
$$ k = \frac{2\pi}{\lambda},$$
der Ausbreitungsgeschwindigkeit 
$$ v = \frac{\omega}{k} = \nu \lambda,$$
Wellenlänge $\lambda$ und Kreisfrequenz $\omega$ bzw. Frequenz $\nu=2\pi \omega.$

### Polarisation
Wellen können transversal (z.B. Seilwelle) oder longitudinal (z.B. Schallwelle)
sein. Transversale Wellen können linear oder elliptisch polarisiert sein.

### Ausbreitungsgeschwindigkeit 
Die Ausbreitungsgeschwindigkeit $v$ einer Welle hängt von der Art der Welle ab:

   * Transversale Seilwelle (Spannung $T$, Längenmassendichte $\mu$):
     $$ v = \sqrt{\frac{T}{\mu}} = \sqrt{\frac{\sigma}{\rho}}.$$
   * Schallwelle in idealem Gas (Adiabatenindex $\kappa$, Druck $p$, 
     Massendichte $\rho$):
     $$ v = \sqrt{\kappa \frac{p}{\rho}}$$
   * Transversalwellen in Festkörpern  mit Schermodul $G$:
     $$ v = \sqrt{\frac{G}{\rho}}.$$
   * Longitudinalwelle in dünnen Stäben mit Elastizitätsmodul $E$:
     $$ v = \sqrt{\frac{E}{\rho}}.$$
   * Schwerewellen Flüssigkeit (Tiefe $d$, Schwerebeschleunigung $g$):
     $$ v = \sqrt{\frac{g\lambda}{2\pi} \tanh \left(\frac{2\pi d}{\lambda}\right)}$$
     mit den Näherungen $d\ll \lambda$:
     $$ v\approx \sqrt{g d}$$
     und $d\gg \lambda \rightarrow \tanh\rightarrow 1$:
     $$ v\approx \sqrt{\frac{ g\lambda}{2\pi}}.$$
