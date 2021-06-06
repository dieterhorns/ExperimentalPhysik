---
title: "Schwingungen"
date: 2021-05-08T19:51:57+02:00
description: "Periodische Systeme"
weight: 10
---
## Allgemeine Definition 
*Schwingungen* sind alle Vorgänge, die *periodisch* ablaufen. Für eine eindimensionale
Bewegung mit Periode $P$:
$ x(t+P) = x(t).$
## Harmonische Schwingungen
sind Schwingungen, die sich aus *linearen Kraftgesetzen* ergeben, wie z.B.
das Hooke'sche Gesetz:
\begin{equation} m\ddot{x} = -Dx. \end{equation}
## Beispiel Federpendel
Für ein reibungsfreies Federpendel  mit Ruhelage $x=0$ ergibt sich für die Lösung
der Bewegungsgleichung
$$ x(t) = \hat x \sin(\omega t+\varphi),$$
und  damit für die _Kreisfrequenz_ $\omega$:
$$ \omega  = \sqrt{\frac{D}{m}}.$$
## Beispiel Fadenpendel
(wird auch mathematisches Pendel genannt). Wir befestigen eine Punktmasse $m$ an
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
in dem hier betrachteten Fall der _Newton'schen Reibung_ ist die 
Kraft proportional zur
Geschwindigkeit. Zusammen mit dem linearen Kraftgesetz ergibt sich die Bewegungsgleichung eines _gedämpften harmonischen Oszillators_:
$$ m\ddot x = -Dx - k \dot{x},$$
die wir umstellen zur Normalform 
$$ \ddot{x} + 2\gamma \dot{x} + \omega_0^2 x = 0,$$ 
mit der Kreisfrequenz 
$$\omega_0 = (D/m)^{1/2}$$ des ungedämpften Systems 
und dem  Dämpfungsterm $$\gamma:= \frac{k}{2m}.$$
Der Dämpfungsterm hat genau wie $\omega_0$ die Einheit einer Frequenz ($1/s$).

Wir wollen jetzt untersuchen, wie die Lösungen dieser Differenzialgleichung aussehen.
### Lösungen für gedämpfte Schwingungen.
Wir wählen $x(t) = A \exp(\lambda t)$ als Ansatz für die Lösung und erhalten
mit $\dot{x} = \lambda x$ und $\ddot{x} = \lambda^2 x$ 
$$ \lambda^2 + 2\gamma \lambda +\omega_0^2 = 0.$$
Damit erhalten wir zwei Lösungen für $\lambda$:
$$ \lambda_{1,2} = -\gamma\pm \sqrt{\gamma^2-\omega_0^2}.$$
Damit ist die allgemeine Lösung die Summe der beiden Lösungen:
$$ x(t) = A_1 \exp(\lambda_1 t) + A_2 \exp(\lambda_2 t)$$
und
$$ \dot{x}(t) = A_1~\lambda_1 \exp(\lambda_1 t) + A_2~\lambda_2 \exp(\lambda_2 t).$$

Mit den Anfangsbedingungen $x(t=0)=x_0$ und $\dot{x}(t=0)=v_0$ können wir
$A_1$ und $A_2$ ersetzen:
$$ x_0 = A_1 + A_2$$
$$ v_0 = A_1 \lambda_1 + A_2\lambda_2,$$
so dass 
$$ A_1 = \frac{v_0 - \lambda_2 x_0}{\lambda_1-\lambda_2},$$
$$ A_2 = -\frac{v_0 - \lambda_1 x_0}{\lambda_1 - \lambda_2}.$$

Um die Terme mit $\lambda_{1,2}$  etwas handlicher zu gestalten, definieren
wir $\delta:= \sqrt{\gamma^2-\omega_0^2}$. 
$$ x(t) = \frac{v_0 + \gamma x_0 +\delta x_0}{2\delta} e^{-\gamma~t}e^{\delta t}
         -\frac{v_0 + \gamma x_0 -\delta x_0}{2\delta} e^{-\gamma~t}e^{-\delta t}$$
bzw.
$$ x(t) = x_0 e^{-\gamma~t} 
       \left ( \frac{e^{\delta t}}{2} + 
                \left[ \gamma + \frac{v_0}{x_0}\right]\frac{e^{\delta t}}{2\delta}
              +\frac{e^{-\delta t}}{2} - 
                \left[ \gamma + \frac{v_0}{x_0}\right]\frac{e^{-\delta t}}{2\delta}
       \right)$$
und schließlich
$$ x(t) = x_0 e^{-\gamma t} \left( \frac{e^{\delta t} + e^{-\delta t}}{2} + \left[ \gamma + \frac{v_0}{x_0}\right]  
    \frac{e^{\delta t} - e^{-\delta t}}{2\delta} \right).$$


Je nach Stärke der Dämpfung $\gamma$ ergeben sich drei unterschiedliche Lösungstypen:
   * Schwach gedämpft  (**Schwingfall**): $\gamma^2 < \omega_0^2$, 
so dass $\lambda = -\gamma \pm i \sqrt{\omega_0^2-\gamma^2}$. 
$$ x(t) = x_0 e^{-\gamma t} \left(
     \cos(\omega t)  + \frac{\sin(\omega t)}{\omega}\left[ \gamma + \frac{v_0}{x_0}\right] \right)$$
     mit $\omega = \sqrt{\omega_0^2-\gamma^2}$ (die Frequenz $\omega$ wird mit zunehmender Dämpfung immer kleiner): 
   * Kritisch gedämpft (**aperiodischer Grenzfall**): $\gamma^2 = \omega_0^2$, 
      die Frequenz $\omega \rightarrow 0$,  
$$x(t) = x_0 e^{-\gamma t} \left( 1 + \left[\gamma + \frac{v_0}{x_0}\right]
       \left(\frac{e^{\delta~t} - e^{-\delta~t}}{2\delta}\right)_{\delta\rightarrow 0}\right).$$

 Der Grenzwert für $\delta\rightarrow 0$ ergibt sich aus der Regel von L'Hospital
mit 
$$\lim_{\delta\rightarrow 0} \frac{f(\delta)}{g(\delta)} = 
   \lim_{\delta\rightarrow0 } \frac{f'(\delta)}{g'(\delta)}.$$
 Mit $f(\delta) = \exp(\delta~t)-\exp(-\delta~t)$ und 
    $f'(\delta)=t \exp(\delta~t) + t\exp(-\delta~t)$. 
    $g'(\delta)= 2$ ist $f'(\delta=0)/g'(\delta=0)= t$:
$$ x(t) = x_0 e^{-\gamma t} \left( 1 + \left[\gamma + \frac{v_0}{x_0}\right ] t\right).$$
   * Starke Dämpfung (**Kriechfall**): $\gamma^2 > \omega_0^2$ und die Lösung
$$x(t) = x_0 e^{-\gamma t} \left( \cosh \omega t + \left[\gamma + \frac{v_0}{x_0}\right] \frac{\sinh \omega t}{\omega}\right).$$
### Qualitätsfaktor 
Häufig wird für einen Oszillator ein einheitenloser Qualitätsfaktor $Q$ definiert:
$$ Q :=  \frac{\omega_0}{2\gamma}.$$
Typische Qualitätsfaktoren liegen bei etwa 100 (einfaches Fadenpendel) und reichen
bis zu $10^{4}$ für elektrische Schwingkreise und Resonatoren. 

### Beispiel
Der $Q$-Faktor eines Fadenpendels lässt sich z.B. aus der Anzahl der Schwingungen
abschätzen bis die Amplitude der Schwingung auf $x_0/e$ absinkt:
$$A(t) = x_0 e^{-\gamma t} = x_0 e^{-\omega_0 t / (2 Q)},$$
für 
$$ \omega_0 t / (2Q) = 1$$
bzw. für $\omega_0\approx \omega = 2\pi/P$ bei der Periode $P$ folgt 
die Anzahl der Schwingungen:
$$ t/P = Q/\pi$$. 
Ist die Näherung $\omega_0\approx \omega$ angebracht? 
Hierzu betrachten wir
$$ \omega^2 = \omega_0^2-\gamma^2 = \omega_0^2\left( 1 - \frac{\gamma^2}{\omega_0^2}\right) = \omega_0^2\left( 1-\frac{1}{4Q^2}\right).$$
Als Reihe entwickelt $\sqrt{1-\epsilon^2} \approx 1-\frac{\epsilon^2}{2}$ ergibt sich für die relative Verschiebung der Frequenz:

$$ \frac{\Delta \omega}{\omega_0} = 1-\frac{\omega}{\omega_0} = -\frac{1}{8Q^2}.$$
Für einen Wert von $Q=10$ ist die relative Abweichung der Frequenz lediglich $0,1~$\%.

### Zum Nachdenken
   * Die höchsten $Q$-Werte liegen bei etwa $10^{11}$. Wie lange dauert es hier, bis
die Schwingungsamplitude auf $1/e$ des ursprünglichen Wertes abfallen.
   * Wie sieht die Energiebilanz beim ungedämpften Pendel aus? 
   * Wie sieht die Energiebilanz beim angeregten Pendel aus? 
