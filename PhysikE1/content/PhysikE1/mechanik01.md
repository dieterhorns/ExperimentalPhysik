---
title: "Schwingungen"
date: 2021-05-08T19:51:57+02:00
featured_image: '/images/gohugo-default-sample-hero-image.jpg'
description: "Periodische Systeme"
---
## Allgemeine Schwingungen
sind alle Vorgänge, die periodisch ablaufen. Für eine eindimensionale
Bewegung mit Periode $T$:
$ x(t+T) = x(t).$
## Harmonische Schwingungen
sind Schwingungen, die sich aus linearen Kraftgesetzen ergeben, wie z.B.:
\begin{equation} m\ddot{x} = -Dx. \end{equation}
## Beispiel Federpendel
Für ein reibungsfreies Federpendel mit Ruhelage $x=0$ ergibt sich für die Lösung
der Bewegungsgleichung
$$ x(t) = \hat x \sin(\omega t+\varphi),$$
und  damit für die _Kreisfrequenz_ $\omega$:
$$ \omega  = \sqrt{\frac{D}{m}}.$$
## Beispiel Fadenpendel
(wird auch mathematisches Pendel genannt). Wir befestigen eine Masse $m$ an
einen masselosen Faden der Länge $\ell$. Der Auslenkungswinkel $\vartheta$ zur
Ruheposition (senkrechtes Lot) soll hinreichend klein sein, so dass wir 
$\sin \vartheta \approx \vartheta$ ($\vartheta$ im Bogenmaß) annehmen dürfen. 
Die Auslenkung in der Horizontalen ist $x=\ell \sin\vartheta$ und
die rücktreibende Kraft in der Horizontalen $m\ddot x = -mg\sin\vartheta$, so dass
$$ m \ddot x = -\frac{mg}{\ell} x,$$
und damit ist das Problem äquivalent zu dem Federpendel für $D=mg/\ell$. Wir 
erkennen in beiden Fällen ein _lineares Kraftegesetz_. Die Kreisfrequenz 
$$\omega = \sqrt{\frac{g}{\ell}}.$$
## Gedämpfte Schwingungen
Die Reibungskraft $F_r = -k \dot{x}$ wirkt der Bewegungsrichtung entgegen und
im einfachsten Fall der _Newton'schen Reibung_ ist die Kraft proportional zur
Geschwindigkeit. Zusammen mit dem linearen Kraftgesetz ergibt sich die Bewegungsgleichung eines _gedämpften harmonischen Oszillators_:
$$ m\ddot x = -Dx - k \dot{x},$$
die wir umstellen zur Normalform 
$$ \ddot{x} + 2\gamma \dot{x} + \omega_0^2 x = 0.$$ 
Die Kreisfrequenz $\omega_0 = (D/m)^{1/2}$  ist uns schon vorher bei z.B. dem 
ungedämpften Federpendel begegnet. Der Dämpfungsterm $\gamma:= \frac{k}{2m}$
hat ebenfalls die Einheit einer Frequenz ($1/s$).


