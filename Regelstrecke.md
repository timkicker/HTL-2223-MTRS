# Übersicht

## Definition Regelstrecke

Als **Regelstrecke** wird der Teil eines **Regelkreises** bezeichnet, der durch einen **Regler** beeinflusst werden soll.

Der **Eingang** des **[Regelkreises](./Regelkreis.md)** ist dabei die **Stellgröße** y(t) und ihr **Ausgang** die **Regelgröße** x(t). Der **Einfluss** der Stellgröße auf die Regelgröße ist dabei im **Bildbereich** über die **Übertragungsfunktion** **G(s)** der **Regelstrecke** gegeben.

Grundsätzlich wird zwischen zwei Arten von **Regelstrecken** unterschieden: den Regelstrecken **mit** und **ohne** **Ausgleich**.

![](./Images/Pasted%20image%2020221107095208.png)

## Übertragungsfunktion

Die **Übertragungsfunktion** einer Regelstrecke stellt das **Verhältnis** von ihrem **Ausgang** zu ihrem **Eingang** im Bildbereich dar und wird mit G(s) bezeichnet. Die **Übertragungsfunktion** beschreibt also das Verhältnis X(s) / Y(s) der Regelgröße x zur **Stellgröße** y.

In der Regel handelt es sich bei G(s) um eine gebrochen-rationale Funktion mit einem Polynom im Zähler und im Nenner. Die Pol- und Nullstellen dieser Polynome geben darüber Auskunft, um was für eine Art von Regelstrecke es sich handelt.

G(s) = Zählerpolynom(s) / Nennerpolynom (s)