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
Für ein einfaches Federpendel mit Ruhelage $x=0$ ergibt sich für die Lösung
der Bewegungsgleichung
$$ x(t) = \hat x \sin(\omega t+\varphi),$$
und  damit für die _Kreisfrequenz_ $\omega$:
$$ \omega  = \sqrt{\frac{D}{m}}.$$
## Beispiel Fadenpendel
(wird auch mathematisches Pendel genannt). Wir befestigen eine Masse $m$ an
einen masselosen Faden der Länge $\ell$. Der Auslenkungswinkel $\vartheta$ zur 
Horizontalen soll hinreichend klein sein, so dass wir 
$\sin \vartheta \approx \vartheta$ ($\vartheta$ im Bogenmaß) annehmen dürfen. 
Die Auslenkung in der Horizontalen ist $x=\ell \sin\vartheta$ und
die rücktreibende Kraft in der Horizontalen $m\ddot x = -mg\sin\vartheta$, so dass
$$ m \ddot x = -\frac{mg}{\ell} x,$$
und damit ist das Problem äquivalent zu dem Federpendel für $D=mg/\ell$. Wir 
erkennen in beiden Fällen ein _lineares Kraftegesetz_. Die Kreisfrequenz 
$$\omega = \sqrt{\frac{g}{\ell}}.$


