---
title: "Resonanzen"
date: 2021-05-08T19:51:57+02:00
featured_image: '/images/gohugo-default-sample-hero-image.jpg'
description: "Angeregte Schwingungen"
---
## Periodische Anregung
Wir ergänzen eine periodisch anregende Kraft $F(t)=F(t+T)$,
mit der Periode $T=2\pi/\omega$, so dass 
wir eine inhomogene Differenzialgleichung erhalten
$$ \ddot{x} + 2\gamma \dot{x} + \omega_0^2 x = \frac{F(t)}{m}.$$

Wir nehmen einen schwach gedämpften Fall an ($\gamma<\omega_0$).
Nach einem Einschwingvorgang wird  das System mit der 
anregenden Kreisfrequenz $\omega_A$ oszillieren.  Während des Einschwingens
werden durch die Dämpfung Schwingungen mit der (freien) Frequenz 
$\sqrt{\omega_0^2-\gamma^2}$ 
über eine charakteristische Zeit $1/\gamma$ gedämpft, so dass 
nach einer Zeit $t \gamma \gg 1$ lediglich die anregende Frequenz
beiträgt. 

Die resultierende Amplitude $\hat x(\omega)$ und Phasenwinkel 
$\varphi(\omega)$ der Bewegung 
$x(t) = |\hat x| \sin(\omega_A t - \varphi)$ zeigt ein spektakuläres Verhalten bei 
der Resonanzfreqzen $\omega_A=\omega_r\approx \omega_0$: die sogenannte _Resonanz_

## Resonanz
Wir nehmen für die Lösung den Realteil von 
$$ x(t) = \hat x \exp(i \omega_A t)$$
an und nehmen eine harmonische Anregung als den Realteil von
$$ F(t) = \hat F \exp(i \omega t)$$
an,
so dass sich nach Einsetzen für die inhomogene Gleichung ergibt:
$$ -\omega_A^2 \hat x \exp(i\omega_A t) + 2\gamma i \omega_A \hat x \exp(i\omega_A t)
+\omega_0^2 \hat x \exp(i\omega_A t) = \frac{F}{m} \exp (i\omega_A t).$$
Jetzt können wir nach $\hat x$ auflösen
$$ \hat x = \frac{\hat F}{m}\frac{1}{\omega_0^2-\omega_A^2 + 2\gamma \omega_A i}.$$
Uns interessiert der Betrag 
$$|\hat x| = \sqrt{Re(\hat x)^2+Im(\hat x)^2},$$ 
wobei $Re(z)$ und $Im(z)$ der Real- und Imaginärteil der komplexen Zahl $z$ 
ist.
Wir ergänzen daher:
$$ \frac{1}{(\omega_0^2 - \omega_A^2) + 2\gamma \omega_A  i}
   \frac{(\omega_0^2-\omega_A^2) - 2\gamma\omega_A i}{(\omega_0^2-\omega_A^2) - 2\gamma\omega_A i} $$
$$   = \frac{\omega_0^2 - \omega_A^2}{(\omega_0^2 - \omega_A^2)^2 + 4 \gamma^2\omega_A^2} - \frac{2\gamma \omega_A i}{(\omega_0^2 - \omega_A^2)^2 + 4 \gamma^2\omega_A^2}.$$
und erhalten 
$$|\hat x| = \frac{\hat F}{m\sqrt{(\omega_0^2-\omega_A^2)^2+4\gamma^2\omega_A^2}}.$$
Der relative Phasenwinkel der Bewegung $x(t)$ ergibt sich aus dem Phasenwinkel
von $x(t) = |\hat x| \exp(i(\omega_A t-\varphi)):$  
(Aufgrund der Konvention für den Phasenwinkel wird hier ein negatives Vorzeichen benötigt):
$$ \tan \varphi = -\frac{Im(\hat x)}{Re(\hat x)} = 
\frac{2\gamma \omega_A}{\omega_0^2-\omega_A^2}.$$

Die maximale Amplitude wird erreicht, wenn der Term 
$$(\omega_0^2-\omega_A^2)^2 + 4\gamma^2\omega_A^2$$ minimal wird. 
Ableiten $d/d\omega_A$ und identisch null
setzen für die gesuchte Resonanzfrequenz $\omega_r$ ergibt: 
$$ 2(\omega_0^2-\omega_r^2)(-2\omega_r) + 8 \gamma^2\omega_r=0,$$
mit der Lösung
$$ \omega_r = \sqrt{\omega_0^2 - 2 \gamma^2}.$$

Analyse der Resonanzkurve:
   * $\omega_A \rightarrow 0$: $\varphi\rightarrow 0$, $|\hat x| = \frac{\hat F}{m\omega_0}$. 
   * $\omega_A = \omega_r<\omega_0$: Resonanzamplitude 
    $$|\hat x|_{r} = \frac{\hat F}{2m\gamma\sqrt{(\omega_0^2-\gamma^2)}}$$
   * (ohne Beweis): Die Amplitude fällt auf $|\hat x|_{r}/\sqrt{2}$ an
den Grenzen des  Frequenzintervalls $\omega_r \pm \gamma$ ab. 
 Die resultierende Breite der Resonanz von $2\gamma$ wird
auch als *Güte* oder *Q-Faktor*  bezeichnet (siehe auch [gedämpfte Schwingung]({{< relref "/schwingungen/schwingungen" >}} "gedaempfte Schwingungen") )
   * $\omega_A = \omega_0$: $\varphi =  \pi/2$. 
   * $\omega_A \rightarrow \infty$: $\varphi \rightarrow \pi$, $|\hat x| \rightarrow 0$. 

