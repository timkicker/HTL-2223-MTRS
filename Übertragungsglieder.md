# I-Glied ("Integrier-Glied")
Das I-Glied, oder auch Integrierglied genannt, kommt in der Regelungstechnik zum Einsatz und ist eine Form des Übertragungsglieds, welches ein integrales Übertragungsverhalten zeigt. Das heißt soviel wie, dass die Amplitudenänderung der Eingangsgröße bestimmt die Änderungsgeschwindigkeit der Ausgangsgröße.

Das I-Glied ist eine Form des Übertragungsglieds mit integralem Übertragungsverhalten.

## Integrierbeiwert
Das allgemeine Strukturglied eines I-Glieds sieht so aus:
![](Pasted%20image%2020221108171311.png)

Das K oben links ist dabei ein Kennwert des I-Glieds, der Integrierbeiwert. Er ist eine Konstante. Sind die Einheiten der Ein- und Ausgangsgrößen des I- Glieds gleich, so verwendet man statt K, den Kehrwert 1/K.

An dieser Stelle können wir wieder an unser Beispiel anknüpfen. Sehen wir uns den Pool dafür einmal genauer an: Er besitzt eine Querschnittsfläche, die sich natürlich nicht verändert. Mit diesen Informationen erhalten wir jetzt unseren Kennwert: 1/K, wobei wir für K unsere gleichbleibende Querschnittsfläche einsetzen. Üblicherweise werden solche Konstanten, Parameter und Proportionalitätsfaktoren auch bei anderen Übertragungsgliedern immer über den Kästchen notiert.

# P-Glied ("Proportional-Glied")
Stell dir vor, du hast einen Swimmingpool im Garten und bemerkst, dass sich der Pool nicht so schnell füllt wie vergangenen Sommer. Offensichtlich ist er irgendwo beschädigt, sodass Wasser ins Erdreich abfließt. Jetzt müssen wir unser Beispiel in einer passenden Form um diesen Umstand erweitern. In diesem Fall ist es ein negativer Zufluss an Wasser, oder auch Abfluss, den wir als qab(t) bezeichnen. Während unser Schlauch nun für einen Zufluss sorgt, fließt gleichzeitig Wasser durch das Loch ab.

Um den Abfluss mathematisch zu beschreiben, nehmen wir vereinfachend an, dass dieser einen proportionalen Einfluss auf unser System hat. Deshalb benötigen wir an dieser Stelle auch einen Proportionalitätsfaktor. Du ahnst sicherlich schon, dass wir uns langsam der Funktion des P-Glieds nähern.

Wie Dir sicher bereits aus der Mathematik bekannt ist, steht „proportional“ dafür, dass die Änderung einer Größe an die Änderung einer anderen Größe durch einen bestimmten Faktor, den Proportionalitätsfaktor, gekoppelt ist. So auch hier. Denn obwohl Wasser durch das Loch abfließt, steigt die Füllstandshöhe trotzdem noch an, da ja mehr Wasser hinein- als hinausfließt. Für diese Beeinflussung unseres Systems verwenden wir ein sogenanntes Proportionalglied, kurz P-Glied. Die Ausgangsgröße ist beim P-Glied proportional zum Wert ihrer konstanten Eingangsgröße

Das Ausgangssignal des P-Glieds nimmt den K-fachen Wert des Eingangs ohne zeitliche Verzögerung, also sofort, an. Somit beschreibt der Faktor K die Verstärkung des Eingangssignals. Auch das P-Glied als Übertragungsglied lässt sich anhand seiner Übergangsfunktion abbilden. Das Strukturbild eines P-Glieds im Blockschaltbild sieht damit so aus:

![](Pasted%20image%2020221108170107.png)

# D-Glied
Diese Art der Übertragungsglieder bestimmt ihren Ausgang überwiegend anhand der Veränderungen ihrer Eingangsgröße. Anders formuliert: Die Ausgangsgröße ist der zeitlichen Änderung der Eingangsgröße proportional!

