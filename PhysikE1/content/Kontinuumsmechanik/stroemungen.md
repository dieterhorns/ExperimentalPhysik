---
title: "Strömungen"
date: 2021-05-17T22:46:20+02:00
description: "dynamische Systeme"
weight: 20
---
Strömungen lassen sich gut beschreiben, wenn einige Bedingungen erfüllt sind:
   1. Scherspannungen sind vernachlässigbar, dh. es gibt nur wenig __innere Reibung__.
   2. Inkompressibilität (Dichte bleibt konstant).
   3. Stationäre Strömung (d.h. Geschwindigkeit eines Volumenelementes ist nur vom Ort aber
      nicht von der Zeit abhängig. 

## Kontinuität
Wir betrachten jetzt ein dynamisches System: ein durchströmtes Rohr. Die Flüssigkeit sei ideal, also 
reibungsfrei. Das Rohr habe am Anfang eine Querschnittsfläche $A_1$ und die (inkompressible) Flüssigkeit 
der Dichte $\rho$ durchströmt diesen Querschnitt mit der Geschwindigkeit $v_1$. Das Rohrende 
habe den Querschnitt $A_2$. Der Höhenunterschied der beiden Rohrenden sei $h$. 

Wir können davon ausgehen, dass die Flüssigkeitsmenge, die pro Zeiteinheit das Rohr durchströmt entlang des Rohres 
überall gleich sein muss. Es muss also für die Rohrenden gelten:

$$\rho_1 A_1 v_1 = \rho_2 A_2 v_2.$$
Im Falle einer inkompressiblen Flüssigkeit können wir $\rho_1 = \rho_2 = \rho$ als konstant annehmen, so dass (unabhängig von
der Dichte):
$$A_1 v_1 = A_2 v_2 $$
gilt. An einer Verengung des Rohres erhöht sich die Strömgeschwindigkeit, an einer Stelle mit einem größeren Querschnitt reduziert 
sich die Geschwindigkeit. 

## Energieerhaltung und Bernoulli-Gleichung

Wir können das durchströmte Rohr  energetisch analysieren. Die kinetische Energie pro Volumenelement ergibt sich 
zu $\rho/2 v_1^2$ bzw. $\rho/2 v_2^2$, der Unterschied der potenziellen Energie pro Volumenelement ist $\rho g h$ für das obere Rohrende.
Zusätzlich müssen wir berücksichtigen, dass ein vorhandener Druck $p_1$ bzw. $p_2$ an den Rohrenden 
anliegt, der Arbeit an der Flüssigkeit verrichtet $p dV = dW$. Wir dürfen verlangen, dass die Energie erhalten bleibt, die
Summe der drei Komponenten (Druck, kinetische Energie, potenzielle Energie  - jeweils pro Volumeneinheit) konstant sein muss:

$$ p_1 + \frac{rho}{2} v_1^2 + \rho g h_1 = p_2 \frac{rho}{2} v_2^2 + \rho g (h_1 + h).$$ 

Diese Gleichung ist als _Bernoulli-Gleichung_ bekannt. 

### Beispiel-Experimente
   1. Strandball im Luftstrom: Zum einen schwebt der Ball aufgrund der 
      Verwirbelung oberhalb des Balls  - zum anderen wird der Ball in die
      Ruheposition in der Mitte der Strömung zurückgeführt, weil das Strömungsprofil
	die höchste Geschwindigkeit der Luftströmung in der Mitte das Maximum erreicht.
   1. Ball in einem Trichter: Ein Ball in einem Trichter wird durch die Strömung
  nicht wie naiv zu erwarten wäre aus dem Trichter herausgedrückt sondern 
  aufgrund der schnellen Strömung zwischen Ball und Trichterwand durch den höheren
statischen Luftdruck festgedrückt.
   1. Kanaleffekt: Schiffe, die durch einen Kanal fahren, können bei 
   zu schneller Fahrt durch den Unterdruck an das Ufer gedrückt werden.
   1. Zerstäuber: Durch das Zusammendrücken eines Gummiballs wird eine Strömung über
die Öffnung eines Gefäßes gelenkt. Hierbei wird durch eine Verengung die Strömung
in einen kleineren Querschnitt geführt und dadurch die Geschwindigkeit erhöht.
Der höhere äußere Druck drückt die Flüssigkeit in den Luftstrom. 

## Anwendung: Prandtl'sches Staurohr


     

