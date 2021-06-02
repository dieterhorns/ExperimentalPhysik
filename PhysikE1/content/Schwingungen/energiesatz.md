---
title: "Energiesatz"
date: 2021-05-25T08:51:47+02:00
---
### Fortgeschrittenes Thema
## Energiesatz, harmonische Schwingungen
Wir haben bislang die Bewegungsgleichungen
über die wirkenden Kräfte aufgeschrieben. Das ist
bei den meisten Systemen (Pendel) ein anschaulicher und 
gleichzeitig zielführender Ansatz.

Die Analyse der Kräfte ist jedoch oft nicht nötig, um zum Beispiel
die Periode eines Systems zu bestimmen. 

## Beispielhaft: Kugel auf Bahn
Wenn wir eine Kugel auf einer bogenförmigen Bahn
zum Rollen bringen, beobachten wir ein periodisches Hin- und 
Herbewegen. Wenn wir die Periode ausrechnen wollen, merken wir recht schnell, dass
das System auch in der Kleinwinkelnäherung nicht ganz einfach zu betrachten ist, weil
es zur Überlagerung der Roll- und Translationsbewegung kommt. Wie können wir die 
Periode berechnen?

## Ansatz Energieerhaltung
Wir können für das reibungsfreie System ansetzen, dass die Summe der kinetischen und potenziellen
Energie zeitlich erhalten ist, also

$$ \dot E_\mathrm{tot} = 0 = \dot E_\mathrm{kin} + \dot E_\mathrm{pot}.$$
Wenn es uns gelingt, die Energie als Funktion der kinetischen Variablen aufzuschreiben, 
erhalten wir dann die gesuchte Bewegungsgleichung mit dem Ansatz der Energieerhaltung ohne
die Kräfte betrachten zu müssen.

## Beispiel Schlitten auf Kreisbogen
Wir nehmen an, dass ein reibungsfreier Schlitten der Masse $m$ (z.B. auf einer 
Luftkissenschiene) auf einer Unterlage, die einem Kreisbogen mit 
Krümmungsradius $R$ folgt, 
in Bewegung versetzt wird. Der
Schlitten wird aufgrund der Schwerebeschleunigung um den tiefstgelegenen
Punkt der Unterlage hin-und her schwingen. 

Wie groß ist die Periode dieser Schwingung?

Wir betrachten die kinetische Energie (hier gibt es keine Rollbewegung) des Systems:
$$ E_\mathrm{kin} = \frac{m}{2} v^2 = \frac{m}{2} (\dot \theta R)^2,$$
wobei wir jetzt die Bahngeschwindigkeit $v= \dot\theta R$ ersetzen. Der Winkel $\theta$ sei der
Auslenkungswinkel des Schlittens aus der Ruheposition.

Die potenzielle Energie des Schlittens $E_\mathrm{pot}$ bei einer Auslenkung
$\theta$ ergibt sich aus dem Höhenunterschied zur Ruheposition 
$h=R(1-\cos\theta)$ und somit
$$ E_\mathrm{pot} = mgh = mgR(1-\cos\theta).$$
Für kleine Winkel $\theta \ll 1$ (Winkel im Bogenmaß) ist 
$$ \cos \theta = 1-\frac{\theta^2}{2}+\mathcal{O}(\theta^4).$$
Die Näherung ist selbst für einen Winkel von $10^\circ$ bzw. $\pi/18$ 
im Bogenmaß immer noch ausreichend genau: $\cos(10^\circ)=0,98481$ und
die Näherung $1-(\pi/18)^2/2 = 0,98477$, also eine relative Abweichung von $0,04~$\%.

In dieser _Kleinwinkelnäherung_ ist die potenzielle Energie
$$ E_\mathrm{pot} = mgR\frac{\theta^2}{2}$$

Die Gesamtenergie $E_\mathrm{tot} = E_\mathrm{kin}+E_\mathrm{pot}$ ist erhalten, dh.
die zeitliche Ableitung muss verschwinden
$$ 0 = \frac{d}{dt} \left (\frac{m}{2} \dot\theta^2 R^2 + \frac{m}{2} gR \theta^2 \right).$$
Bei der Ableitung wenden wir die Kettenregel an, also 
$$\frac{d (\dot \theta)^2}{dt} =  2 \dot \theta \ddot \theta $$
und erhalten
$$ 0  = \frac{m}{2} R^2 \left(2\ddot{\theta}\dot \theta + 2 \frac{g}{R} \dot{\theta}\theta \right).$$
Durch Umstellen erhalten wir eine Differenzialgleichung, die als Lösung eine harmonische Schwingung hat:
$$ \ddot\theta = - \frac{g}{2R}\theta,$$
$$ \theta(t) = \hat\theta \sin(\omega t+\varphi).$$ 
Die Kreisfrequenz 
$$\omega = \sqrt{\frac{g}{2R}},$$
bzw. 
$$  P = \frac{2\pi}{\omega} = 2\pi\sqrt{\frac{2R}{g}},$$
wir erkennen die Periode des Fadenpendels mit $\ell = 2R$ wieder!

## Beispiel Kugel auf Kreisbogen
Wenn wir etwas Reibung zulassen, fängt eine Kugel mit Radius $r$ auf einer Kugelbahn an zu rollen (schlupffrei). 
Jetzt müssen wir beim Energiesatz auch die kinetische Rotationsenergie berücksichtigen (unter Vernachlässigung
der Reibungswärme):
$$ E_\mathrm{kin} = \frac{m}{2} v^2 + \frac{I}{2}\Omega^2.$$
Um sicherzustellen, dass wir die Winkelgeschwindigkeit der Rotation $\Omega$ nicht mit 
der Kreisfrequenz $\omega$ verwechseln, verwenden wir hier unterschiedliche Buchstaben.
Wenn die Kugel ohne Schlupf rollt, ist weiterhin $\Omega r = \dot \theta R.$
$$ E_\mathrm{kin} = \frac{m}{2} \dot\theta^2 R^2 + \frac{I}{2} \frac{R^2}{r^2} \dot\theta^2.$$
Für das Trägheitsmoment einer Vollkugel mit Masse $m$ und Radius $r$ gilt $I=2/5~mr^2$, so dass
$$ E_\mathrm{kin} = \frac{m}{2} \dot \theta^2 R^2 + \frac{2/5~mr^2}{2} \frac{R^2}{r^2} \dot \theta^2.$$
Wir kürzen und fassen Terme zusammen
$$ E_\mathrm{kin} = \frac{m}{2} \dot \theta^2 R^2 \left(1 + \frac{2}{5}\right)= \frac{7}{5} \frac{m}{2} \dot \theta^2 R^2 .$$

