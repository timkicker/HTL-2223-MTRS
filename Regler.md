
## Arten

### P-Regler

Siehe P-Glied ([[Übertragungsglieder]])

"Bei dem P Regler handelt es sich um einen stätigen Regler mit bleibender Regeldifferenz"
Der P Regler besteht aus einem P Glied und weist damit auch identische Eigenschaften dazu auf. Die Stellgröße ist entsprechend proportional zur **Regeldifferenz**.

Mathematisch lässt sich dieser Zusammenhang im Zeitbereich wie folgt darstellen:
$$
y(t) = Kp*e(t)
$$
y(t) beschreibt hier die **Stellgröße** und e(t) die **Regeldifferenz**, also die Differenz des Sollwerts der Regelgröße und ihrem Istwert.

Kp wird als **Proportionalitätsfaktor** bezeichnet. Er gibt an wie stark die Regeldifferenz verstärkt wird. Je größer der Proportionalitätsfaktor desto geringer die Regeldifferenz. Auf diesen Zusammenhang wird weiter unten genauer eingegangen.

Mit Hilfe der [**Laplacetransformation**](https://studyflix.de/informatik/laplace-transformation-762) lässt sich daraus die **[[Übertragungsfunktion]]** bilden:

### PI-Regler
Siehe P, I-Glied ([[Übertragungsglieder]])
Der PI Regler setzt sich aus den Anteilen des **P-** und **I- Gliedes** zusammen und entspricht damit einem **PI Glied**.

*Blockschaltbild:*
![](Pasted%20image%2020221108172554.png)

### PID-Regler

