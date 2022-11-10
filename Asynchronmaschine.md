# Aufbau

[Erklärungsvideo](https://www.youtube.com/watch?v=zKvnDy_8Mps)

**Rotor:** Der Rotor kann aus Eisen oder aus geblechten Eisen bestehen. In den Nuten befindet sich oft ALU da es den Strom gut leitet und eingießbar ist und Stirnseitig kurzgeschlossen ist. Kupfer wäre besser kann aber nicht eingegossen werden.

**Stator:** Im Stator sind die drei Wicklungen des Drehstromes R, S und T.

# Berechnung

**Drehzahl n:**

$$
\begin{split}
n&=\frac{f\cdot60}{p}\quad\left|\ \begin{matrix*}[l]
n\text{ ... Drehzahl in 1/min}\\
f\text{ ... Netz frequenz in Hz (Synchron 50Hz)}\\
p\text{ ... Polpaarzahl}
\end{matrix*}\right. \\\\
n&=\left\{\begin{matrix*}[l]
p=1:3000\\
p=2:1500\\
p=3:1000\\
p=4:750\\
\quad\vdots
\end{matrix*} \right.
\end{split}
$$
**Schlupf s:**
$$
\begin{split}
s&=\frac{{n_s}-{n}}{n_s}\quad\left|\ \begin{matrix*}[l]
n_s\text{ ... Synchrone Drehzahl in 1/min}\\
n\text{ ... Derzeitige Drehzahl in 1/min}\\
\end{matrix*}\right. \\\\
\end{split}
$$

**Blindleistung S, Winkel eta, Leistung P:**
$$
\begin{split}

P=3*P_{w}\\
S=\sqrt{3}*U_{Dreieck}*I\\
\eta=arccos(\frac{P}{S})
\end{split}
$$
# Problem Anlaufen
Im Zeitpunkt t=0 wechseln sich die Pole des Magnetfeldes, jedoch Steht der Rotor noch

## Lösung 1: Wechseln Stern-Dreieck
Im Anlauf wird die Spannung reduziert in dem man die Wicklungen in Stern verschaltet. Nach dem Hochlaufen wird dann automatisch auf Dreieck umgeschalten.

![](Pasted%20image%2020221110181236.png)

Stern... Gut für Anlaufen
Dreieck... Gut für Berieb

## Lösung 2: Frequenzumrichter
Mit einem Frequenzumrichter kann der Anlassstrom auf der höhe des Nennstromes gehalten werden.


## Lösung 3: Hochstabläufer
Der Hochstabläufer besitzt besonders tiefe Nuten, durch welche beim anlaufen weniger Strom gezogen wird, da sich der Läuferwiderstand durch den Skineffekt erhöht. Geleichzeitig wird die ungünstige Phasenverschiebung des Läuferstromes verbessert also mit einer stärkeren Wirkkomponente versehen Dh. das Anlaufmoment wird verbessert.

![](Pasted%20image%2020221110181416.png)

## Lösung 4: Schleifringläufer
Beim Schleifringläufer wird anstatt dem Alu-Käfig eine Wicklung eingebaut und über drei Schleifringe auf den Klemmkasten des Motors geführt. Im Hochlaufvorgang werden nun ohmsche Widerstände zugeschalten. Dadurch wird wie beim Hochstabläufer der Anlaufstrom reduziert und das Anlaufmoment verbessert.

--> Einschaltstrom verkleinern

![](Pasted%20image%2020221110181550.png)