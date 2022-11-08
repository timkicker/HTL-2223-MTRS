## Definition
Die **Übertragungsfunktion** beschreibt in der Regelungstechnik das **Verhältnis** vom **Ausgangssignal** zum **Eingangssignal** eines **dynamischen Systems**. Sie wird mit G(s) abgekürzt und im **Bildbereich** angegeben.

In der Praxis kann die Übertragungsfunktion ermittelt werden, indem ein System mit einem bekannten Eingangssignal beaufschlagt wird und gleichzeitig das Ausgangssignal aufgezeichnet wird.

Zum Beispiel können alle gängigen **Übertragungsglieder** aus der Regelungstechnik mit einer Übertragungsfunktion beschrieben werden.

### Aus Differenzialgleichung
Eine weitere Methode die Übertragungsfunktion eines Systems zu ermitteln ist, sie aus der **Differenzialgleichung** des Systems aufzustellen. Dafür wird die Differenzialgleichung aus dem Zeitbereich mittels [**Laplacetransformation**](https://studyflix.de/informatik/laplace-transformation-762) in den Bildbereich transformiert und anschließend das Verhältnis zwischen Ausgangs– und Eingangssignal gebildet. Dies wird weiter unten in diesem Artikel anhand eines Beispiels durchgeführt.

## Darstellungsformen
Grundsätzlich handelt es sich bei Übertragungsfunktionen in der Regelungstechnik um **gebrochen-rationale Funktionen** der Form
$$
G(s)=\frac{Zählerpolynom(s)}{Nennerpolynom(s)}
$$
Dabei gibt es verschiedene Möglichkeiten der Darstellung.

#### Pol-Nullstellendarstellung
Für die **Pol-Nullstellendarstellung** wird das Zähler- und Nennerpolynom **linearfaktorzerlegt**. Das bedeutet es werden die Nullstellen des jeweiligen Polynoms gefunden und das Polynom auf diese Weise umgeschrieben.
$$
G(s)=K*\frac{(s-sN1)*(s-sN2)...(s-sNn)}{(s-sP1)*(s-sP2)...(s-sPn)}
$$
Diese Darstellung kann beispielsweise dafür genutzt werden, um die **Reglerparameter** eines Reglers so zu bestimmen, dass seine Nullstellen die Polstellen der Regelstrecke aufheben und damit die Gesamtübertragungsfunktion vereinfachen.

Außerdem ist diese Form hilfreich, um den **Pol-Nullstellenplan** eines Systems aufzustellen und damit Aussagen über ihr Stabilitäts -und Schwingungsverhalten zu treffen.

#### Zeitkonstantendarstellung
Die **Zeitkonstantendarstellung** ist eine sehr häufig gewählte Darstellungsform, da die **Zeitkonstanten** eines Systems messtechnisch, beispielsweise durch die Impuls– oder Sprungantwort, ermittelt werden können.

Die Übertragungsfunktion wird dafür in folgende Form gebracht:
$$
G(s)=K*\frac{(Tz1s+1)*(Tz2s+1)...(Tzns+1)}{(TN1s+1)*(TN2s+1)...(TNns+1)}
$$
Die Zeitkonstantendarstellung kann beispielsweise zur schnellen Erstellung des [**Bodediagramms**](https://studyflix.de/informatik/bode-diagramm-816) genutzt werden.

#### Partialbruchdarstellung
Durch **Partialbruchzerlegung** kann die Übertragungsfunktion in die **Partialbruchdarstellung** umgewandelt werden. Die Pol-Nullstellendarstellung eignet sich dabei gut als Startpunkt, da hier bereits die Polstellen bestimmt wurden.

Die Partialbruchdarstellung eignet sich besonders gut zur **Rücktransformation** in den Zeitbereich, da jeder Partialbruch einzeln rücktransformiert und anschließend summiert werden kann. Außerdem lässt sich die **Laplacetransformierte** eines Partialbruches im Gegensatz zur gesamten Übertragungsfunktion häufig aus einer **Korrespondenztabelle** für die Laplacetransformation entnehmen.
$$
G(s)=\frac{A1}{s-sp1}+\frac{A2}{s-sp2}...+\frac{An}{s-spn}
$$
