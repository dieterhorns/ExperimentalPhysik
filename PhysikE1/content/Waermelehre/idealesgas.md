---
title: "Ideales Gas"
date: 2021-06-27T15:45:37+02:00
weight: 24
---
## Zustandsgrößen
Das ideale Gas wird mit drei Zustandsgrößen beschrieben: $p$, $V$, $T$ mit dem
Zusammenhang der Zustandsgleichung:
\begin{equation}
 pV = N k_B T,
\end{equation}
wobei $N$ die Anzahl der Moleküle im Gas sind und $k_B$ die Boltzmannkonstante
$$ k_B = 1,38\times 10^{-24} \frac{J}{K}.$$

## Stoffmengen
Die Anzahl der Moleküle (immer synonym zu Atomen zu verstehen) in einem Gas 
lässt sich auch als Zahl der Mole $n$ angeben mit der Avogadro-Konstante $N_A$:
$$ N_A = 6,022 \times 10^{23} \frac{\mathrm{g}}{\mathrm{u}~\mathrm{mol}}.$$
Hierbei ist $\mathrm{u} = 1,66\times 10^{-27} ~\mathrm{kg}$ die _atomare
Masseneinheit_. 

Beispiele:
   * $n=1$ mol Kohlenstoff $^{12}C$ entspricht  12 g.
   * $n=1$ mol Sauerstoff $O_2$ entspricht 32 g.


## Universale Gaskonstante $R$
Neben der Boltzmannkonstante $k_B$ ist auch die _universelle Gaskonstante_ $R=k_B N_A$
im Gebrauch:
$$ R = 8,31 \frac{\mathrm{J}}{\mathrm{mol}~\mathrm{K}},$$
so dass die Zustandsgleichung sich ergibt zu
$$ pV = n R T,$$
mit $n$ als Stoffmenge (ein Einheiten von mol). 


## Universales Gasvolumen 
Bei _Normalbedingungen_ ($p=1013~\mathrm{hPa}=1~\mathrm{atm}$ und $T=273,15~\mathrm{K}$) ergibt sich für das 
Volumen der Stoffmenge $n=1$ eines idealen Gases
$$ V = \frac{RT}{p} = 22,4~\mathrm{l/mol}.$$
Dieses _universelle Gasvolumen_ oder auch _molares Volumen_ bei Normalbedingungen ist unabhängig von der Gassorte
bzw. der Masse der Moleküle.  

## Barometrische Höhenformel
Wir können unter der Näherung einer isothermen Atmosphäre den Druckverlauf in der Erdatmosphäre bestimmen.
Ansatz: 
$$ pV = n RT,$$
im hydrostatischen Gleichgewicht, d.h.
$$ \frac{dp}{dz} = - \rho~g,$$
wobei $\rho$ im Gegensatz zu einer Flüssigkeit nicht als konstant angenommen werden darf. Das atmosphärische Gas 
ist kompressibel. Die Massendichte bestimmt sich aus der molaren Masse $m$ zu 
$$\rho = \frac{m}{RT} p,$$
so dass
$$ \frac{dp}{dz} = - \frac{mg}{RT} p$$
zu lösen ist - z.B. durch Separation der Variablen:
$$ \frac{dp}{p} = -\frac{mg}{RT} dz.$$
Integrieren von $z=0$ (Meereshöhe) zur Höhe $h$  mit den Randbedingungen,
dass $p(0) = p_0=1~\mathrm{atm}$ und $p(h)$ der gesuchte Druck in der Höhe $h$ ist:
$$\int\limits_{p_0}^{p(h)} \frac{d\tilde p}{\tilde p} = -\frac{mg}{RT} \int\limits_{0}^h dz.$$
$$ \ln \frac{p(h)}{p_0} = -\frac{mg}{RT} h,$$
ergibt 
$$ p(h) = p_0 \exp\left( -\frac{h}{h_0} \right),$$
mit 
$$ \frac{1}{h_0} = \frac{mg}{RT}.$$
Wir nehmen für die Atmosphäre die Normalbedingung an und eine Zusammensetzung $80~\\%$ Stickstoff ($N_2$) und 
$20~\\%$ Sauerstoff ($O_2$), so dass das mittlere molare Gewicht 
$$ \langle m \rangle = 0,8\cdot 28~\mathrm{g/mol} + 0,2\cdot 32~\mathrm{g/mol} = 28,8~\mathrm{g/mol}.$$
Damit wird die exponentielle Abklinglänge 
$$ h_0 \approx 8038~\mathrm{m},$$
also in etwa die Höhe der höchsten Berge und in etwa der Höhe der Troposphäre ($h=10~\mathrm{km}$).

