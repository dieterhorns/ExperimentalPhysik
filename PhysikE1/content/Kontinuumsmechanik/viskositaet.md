---
title: "Viskosität"
date: 2021-05-21T08:04:37+02:00
weight: 22
---
## Viskosität und innere Reibung in Flüssigkeiten
Flüssigkeiten haften an Oberflächen (siehe auch Oberflächeneffekte). Es ist also eine Kraft nötig, um eine
Oberfläche relativ zu einer Flüssigkeit bzw. eine Flüssigkeit relativ zu einer Oberfläche mit
konstanter Geschwindigkeit zu bewegen. 
Die nötige Kraft wird proportional zu der Größe der Oberfläche $A$ sein. Für unterschiedliche Flüssigkeiten
ist aufgrund Stoffeigenschaften bzw. Bindungsenergien ein unterschiedliches Verhalten zu erwarten - wir charakterisieren
die Zähigkeit der Flüssigkeit mit einer Stoffkonstante, die **dynamische Viskosität** $\eta$. 

Innerhalb der Flüssigkeit können wir erwarten, dass die anziehenden Kräfte der Molekülbindungenl
 einer Relativbewegung von benachbarten 
Volumenelementen entgegenwirkt. Die Molekülbindungen sind bei Flüssigkeiten der
wesentliche Grund für die __innere Reibung__. Es kommt hierbei also weniger auf die Geschwindigkeit an sondern vielmehr auf die
Geschwindigkeitsänderung innerhalb des Fluids. Wir fassen für die innere Reibungskraft $F$ zusammen:

$$ F = \eta  A \left| \frac{dv}{dz}\right|,$$
wobei $dv/dz$ die Änderung der Geschwindigkeit senkrecht zu der Fließbewegung ist. Die Stoffkonstante 
**dynamische Viskosität** $\eta$
trägt die Einheit Pa~s. 

Wir können die Kraft/Fläche auch als Scherspannung zusammenfassen und erhalten
das __Newton'sche Reibungsgesetz__:
$$ \tau = \frac{F}{A} = \eta \left| \frac{dv}{dz}\right|.$$
Im einfachsten Fall einer _Newton'schen_ Flüssigkeit ist $\eta$ konstant. 
Auf den ersten Blick scheint die Scherspannung $\tau$ bei Flüssigkeiten ähnlich wie bei der Verformung eines Festkörpers 
zu wirken. Die wesentlichen Unterschiede sind jedoch:
   * Festkörper: Die Scherspannung ist proportional zur Verformung (der Scherung).
   * Flüssigkeit: Die Scherspannung ist proportional zum Geschwindigkeitsgefälle.
   * Festkörper: Die Scherung ist elastisch, dh. ein Festkörper kehrt zurück in die ursprüngliche Form.
   * Flüssigkeit: Die Verformung der Wassermoleküle ist nicht-elastisch.


Die dynamische Viskosität ändert sich deutlich bei Änderungen der Temperatur, weil hier die
molekulare Bindungsenergie hauptsächlich die innere Reibung bedingt.  Mit zunehmender Temperatur lockert sich die
molekulare Bindung und die Viskosität wird mit zunehmender Temperatur sinken (Beispiel: Teer, Schmierfette, Olivenöl im Kühlschrank).  

In Gasen ist die Viskosität deutlich kleiner 
als in Flüssigkeiten und auf die Stöße der Gasatome untereinander zurückzuführen.  Mit zunehmender Temperatur wird der Impulsübertrag
durch elastsische Stöße größer und die Viskosität steigt an $\eta \propto \sqrt{T}$. 


| Material | $\eta$ [mPa~s] |
|----------|----------------|
|Wasser    | $1,00$        |
|Blut      | $3\ldots 25$   |
|Öl        | $100$          |
|Honig     | $10^4$         |
|Benzol    | $0,65$         |
|Ethanol   | $1,2$          |
|Glyzerin  | $1480$         |
|Schweröl  | $660$          |
|Glas      | $10^{22}$      |
|Quecksilber| $1,55$        |
|Luft ($10^{5}$~Pa) | $1,8\times 10^{-2}$ |
|Helium ($10^{5}$~Pa) | $1,9\times 10^{-2}$ |
<caption>
Zusammenstellung von dynamischen Viskositäten $\eta$.
</caption>

## Newton'sche und nicht-Newton'sche Flüssigkeiten
Suspensionen wie z.B. Blut oder Maisstärke/Wasser-Gemische haben die Eigenschaft, dass bei großen Geschwindigkeitsunterschieden ($dv/dz$)
die Viskosität deutlich größer ist als bei kleinen Werten von $dv/dz$ (dilatantes Fluid). Eine Bingham-Flüssigkeit fängt erst oberhalb einer
bestimmten Scherspannung $\tau$ an zu fließen (Beispiel: Ketchup, Wandfarbe, Hefeteig).
{{<figure src="https://upload.wikimedia.org/wikipedia/commons/c/c4/Scherspannung_Nichtnewtonscher_Fluide_linear.png?classes=shadow&width=600px" 
   caption="Unterschiedliche dynamische Viskositäten als Funktion der Schergeschwindigkeit $\dot \gamma=dv/dz$ (Abb.: Dietmar Haba)">}}

### Beispiel für eine nicht-Newton'sche Flüssigkeit für zu Hause
Rühren Sie etwas feine Maisstärke (zum Binden von Saucen) mit Wasser an. Sie werden merken, dass sie bei langsamen Rührbewegungen
kaum Widerstand verspüren. Versuchen Sie jedoch ruckartig den Löffel zu bewegen, erscheint die Flüssigkeit fest zu sein. 

