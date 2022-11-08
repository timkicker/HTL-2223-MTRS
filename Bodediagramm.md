# Bodediagramm

## Definition
Das BODE-Diagramm stellt den Frequenzgang G(jw) eines Systems über die Kreisfrequenz ω grafisch dar. Dabei gliedert sich dieser in zwei Teile: in den Amplitudenverlauf A(w) und den Phasenverlauf phi(w)  
Üblicherweise verwendet man eine logarithmische Skala. Die Amplitude trägt man in Dezibel auf:

$$
Adb(w)=20*logA(w)
$$

![](./Images/Pasted%20image%2020221107104722.png)

## Beispiel
Für unser Beispiel wählen wir das Blockschaltbild G1, das aus drei Blöcken besteht. Jeder Block besitzt eine [Übertragungsfunktion](./Übertragungsfunktion.md) G. Um unser Diagramm zu zeichnen, müssen wir daraus aber erst einmal eine gemeinsame Übertragungsfunktion basteln. Da wir hier eine Rückkopplung in der Parallelschaltung haben, müssen wir diese erst auflösen. Dafür verwenden wir die Beziehung für solch eine Rückkopplungsschaltung:

[*Videoerklärung*](https://studyflix.de/informatik/bode-diagramm-816)

![](./Images/Pasted%20image%2020221107104920.png)

### Rechnung:

![](./Images/Pasted%20image%2020221107105037.png)

### Zeichnung
Diese Informationen können wir jetzt grafisch in das Diagramm übertragen. Zunächst zeichnen wir alle drei Übertragungsglieder einzeln ein: erst das P-Glied, dann das erste PT1-Glied und schließlich das zweite PT1-Glied.  
Um eine einzige Kurve zu erhalten, die alle drei beinhaltet, können wir diese aufaddieren. Bis ω=2 folgt die Kurve dem P-Glied, danach fällt sie mit einer Steigung von -20 Db pro Dekade. Dekade steht für eine 10-er Einheit, da wir uns hier in der logarithmischen Skala befinden. Ab ω= 200 muss die Kurve dem zweitem PT1-Glied folgen und nochmal mit einer Steigung von -20 Db pro Dekade fallen. So ergibt sich schließlich eine Steigung von -40 db pro Dekade.

![](./Images/Pasted%20image%2020221107105153.png)

Nun müssen wir uns noch dem zweiten Diagrammteil widmen, der den Phasenverlauf ϕ(ω) beschreibt.  
Für das P-Glied, zeichnest Du konstant entlang der Null-Grad-Linie, da für dieses Übertragungsglied keine Steigung vorliegt. Das erste PT1-Glied hatte für den Amplitudenverlauf zuvor eine negative Steigung von minus 20 Dezibel pro Dekade. In diesem Diagrammteil zeichnen wir dafür bis zu Omega gleich 20 ebenfalls entlang der Null-Grad-Linie. Danach zeichnen wir nach unten, bis zur minus 45 Grad- Linie. Geschnitten wird die 45 Grad-Linie bei Omega gleich 200. Für das zweite PT1-Glied beginnen wir ebenfalls bei Null Grad und begeben uns wieder in den negativen Bereich, da wir hier zuvor eine negative Steigung von minus 20 Dezibel ermittelt haben. Unseren Schnittpunkt mit der minus 45 Grad-Linie bekommen wir wieder, indem wir uns an unseren Wert für Omega 2 erinnern. Dieser beträgt 2.  
Um die drei einzelnen Funktionen der Übertragungsglieder im Phasenverlauf in eine gemeinsame zu verpacken, addieren wir sie wieder auf. Du siehst, dass sich die Werte für Omega an den Wendepunkten der Gesamtfunktion befinden

![](./Images/Pasted%20image%2020221107105221.png)