---
title: "Gekoppelte Pendel"
date: 2020-05-08T20:10:57+02:00
featured_image: '/images/gohugo-default-sample-hero-image.jpg'
description: "Systeme von Pendeln"
---
Wenn wir zwei horizontale Federpendel mit jeweils gleicher
Masse $m$ und  Federkonstante $D$ durch eine
dritte Feder mit Federkonstante $D_0$ verbinden, erhalten wir ein gekoppeltes
System von Pendeln. Die Auslenkungen $x_1$ und $x_2$ um die jeweilige
Ruhelage der Federpendel ergeben sich mit
den Bewegungsgleichungen
$$ \ddot x_1 + \frac{D}{m}x_1 + \frac{D_0}{m} (x_1-x_2)=0,$$
$$ \ddot x_2 + \frac{D}{m}x_2 + \frac{D_0}{m} (x_2-x_1)=0$$ 
ein System von zwei gekoppelten Differenzialgleichungen. 
Die Lösung dieses Systems ergibt sich aus der Linearkombination der beiden 
_Normalschwingungen_: 
   * $x_1-x_2=0$: Beide Massen bewegen sich jeweils in die selbe Richtung,
     die Kopplungsfeder wird weder gestreckt noch gestaucht:
    $$x_1(t)=x_2(t) = A\sin(\omega t + \alpha),$$
    mit $\omega = (D/m)^{1/2}$. 
   * $x_1+x_2=0$: Beide Massen bewegen sich jeweils in entgegengesetzte Richtungen
     und haben denselben Abstand zur Ruheposition.
     $$ \ddot x_1 + (D  +2D_0) \frac{x_1}{m} = 0.$$
    $$ x_1 (t) = -x_2(t) = B \sin (\Omega t +\beta),$$
 mit $\Omega = \sqrt{(D+2D_0)/m}>\omega$. 
Die allgemeine Lösung für $x_1(t)$ und $x_2(t)$ ergibt sich aus den 
Linearkombinationen der beiden Normalschwingungen:
$$ x_1(t) = A \sin (\omega t + \alpha) + B\sin(\Omega t + \beta),$$
$$ x_2(t) = A \sin (\omega t + \alpha) - B\sin(\Omega t + \beta).$$
Die vier freien Parameter $(A,B, \alpha, \beta)$ ergeben sich aus den 
Anfangsbedingungen für $x_1(0), x_2(0)$ und $\dot{x}_1(0)$, $\dot{x}_2(0)$.

Als Beispiel setzen wir $x_1(0)=A_0$, $x_2(0)=0$ und $\dot{x}_1(0)=\dot{x}_2(0)=0$,
dann ergibt sich 
$$ A \sin(\alpha) + B\sin(\beta) = A_0,$$
$$ A \sin(\alpha) - B\sin(\beta) = 0.$$
Wenn wir die beiden Gleichungen addieren (subtrahieren) erhalten wir
$$ A_0 = 2A\sin\alpha,$$
bzw. 
$$ A_0 = 2B\sin\beta.$$
Analog gehen wir mit den Geschwindigkeiten vor
$$ A\omega \cos(\alpha) + B\Omega \cos\beta = 0, $$
$$ A\omega \cos(\alpha) - B\Omega \cos\beta = 0.$$
$$ 2A\omega \cos(\alpha) = 0,$$
bzw.
$$ 2B\Omega \cos\beta = 0.$$
Damit ist $\alpha=\beta= \pi/2$ und $A_0 = 2A = 2B$ und wir erhalten 
für die Lösung:
$$ x_1(t) = \frac{A_0}{2} (\cos\omega t +\cos\Omega t),$$
$$ x_2(t) = \frac{A_0}{2} (\cos\omega t -\cos\Omega t).$$
Mit den Additionstheoremen für $\sin$ und $\cos$ 
lassen sich die Lösungen auch schreiben als
$$ x_1(t) = A_0 \cos\left(\frac{\omega -\Omega}{2} t\right) \cos\left(\frac{\omega+\Omega}{2}t \right),$$
$$ x_2(t) = -A_0 \sin\left(\frac{\omega -\Omega}{2} t\right) \sin\left(\frac{\omega+\Omega}{2}t \right).$$
Die gekoppelte Bewegung wird durch zwei Frequenzen beschrieben. Eine kleine
Frequenz $\Omega-\omega$ und eine hohe Frequenz $\omega + \Omega$. Die beiden
Pendel sind jeweils bei beiden Frequenzen um den Phasenwinkel $\pi/2$ in der
Bewegung zueinander verschoben. 
