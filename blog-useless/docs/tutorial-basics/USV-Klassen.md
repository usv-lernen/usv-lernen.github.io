---
sidebar_position: 2
---

### USV-Klassen:

Da sich im Laufe der Zeit der Anspruch an eine USV geändert hat unterscheiden wir deshalb in 3 verschiedenen USV Klassen. 

- VFI Voltage and Frequency (Dauerwandler oder Online-USV)
- VI Voltage Independet (Netzinteraktive USV oder Line-Interactive)
- VFD Voltage and Frequency (Standby- bzw. Offline-USV)

---

### VFI Voltage and Frequency (Dauerwandler oder Online-USV) (Klasse 1)

VFI Voltage and Frequency (Dauerwandler oder Online-USV) auch als Dauerwandler oder Online-USV bezeichnet. Das Ziel einer Online-USV ist es keine Verzögerung also Umschaltzeit zu haben.

Im Normalen Betrieb läuft der gesamte Strom durch die USV auch wenn sie nicht benutzt wird, und lädt ggf. den Akku auf. Sobald wir einen Ausfall haben schaltet die USV sich ein und man hat fast keine Verzögerung, zumindest so das die Systeme es nicht merken.

Die Spannung und Frequenz werden bei der Online-USV vom Wechselrichter erzeugt.

Der Wechselrichter wandelt den Gleichstrom in Wechselstrom um. Dann entnimmt die Stromversorgung von der Wechselstrom Quelle und lädt den Akku auf. 

Während des Stromausfalls erhält der Wechselrichter die Versorgung aus der Batterie und versorgt die elektrischen Geräte mit Strom.

Quelle: [https://illustrationprize.com/70-difference-between-ups-amp-inverter](https://illustrationprize.com/70-difference-between-ups-amp-inverter.html)

---

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0a5c2394-f617-4252-b4c2-435a8f066a29/Untitled.png](https://imgur.com/KZ6WnQe.png)

Quelle: [https://www.elektronik-kompendium.de/sites/grd/0812171](https://www.elektronik-kompendium.de/sites/grd/0812171.htm)

---

**Vorteile**

✅ Unempfindlich gegen einseitige Spannungs & Frequenzschwankungen

✅ Einfacher Aufbau

✅ Geringe Kosten

**Nachteile**

⚠️ Umschaltlücke von wenigen Millisekunden

⚠️ Verbraucher wird durch ungefilterte Spannung versorgt.

Quelle: [https://www.akkuteam.de/produkte-leistungen/usv-vergleich](https://www.akkuteam.de/produkte-leistungen/usv-vergleich/)/




### VI – Voltage Independent form Mains Supply (Klasse 2)

Auch: Line-Interactive oder netzinteraktive USV ist dies die zweite Klasse von USV

![Untitled](https://imgur.com/v84g8Tq.png)

Der Wechselrichter ist mit dem Ausgang der USV verbunden. Wie der Darstellung zu entnehmen ist, fließt im Normalbetrieb Strom für die Batterie über den Wechselrichter, während im Falle eines Netzausfalles (in Orange) die Batterie zur Versorgung der angeschlossenen Verbraucher dient. Des Weiteren schützt die netzinteraktive USV auch vor Netzstörungen wie Schwankungen der Netzspannung durch den vor die Verbraucher geschalteten Spannungsregler Verbindung des Wechselrichters. Somit ist diese USV sogar für Umgebungen mit Netzstörungen geeignet.

Geeignet für: TK-Anlagen, Netzwerke oder einzelne Computersysteme

Nicht geeignet für: Hochsensible Systeme

Wirkungsgrad: 95 bis 98%

Umschaltzeit: 2-4 ms

### VFD – Voltage and Frequency Dependent form Mains Supply (Klasse 3)

Auch: Standby- oder Offline- USV, 3. Klasse von USV

![Untitled](https://imgur.com/Xm6IECN.png)

Dies ist die einfachste Form der USV, welche einen Netzausfall abfangen kann. Anders als die Klassen 1 und 2 kann diese jedoch nicht vor Schwankungen der Netzspannungen oder –frequenzen schützen. Fällt die Stromspannung ab, wird die Versorgung mittels eines elektromechanischen Relais umgestellt auf Wechselrichter und Batterie. Auf diese Weise wird sowohl bei einem Stromausfall als auch bei Über- oder Unterspannung auf Batteriebetrieb umgestellt werden.

Geeignet für: Kleinstverbraucher, einzelne Computer

Nicht geeignet für: Hochsensible Systeme, Computersysteme oder Netzwerke

Wirkungsgrad: 95%

Umschaltzeit: 4-10 ms

## Übersicht der verschiedenen USV-Klassen.

![Untitled](https://imgur.com/wc4vm7v.png)

**Quellen**:

[https://www.thomas-krenn.com/de/wiki/USV_Grundlagen](https://www.thomas-krenn.com/de/wiki/USV_Grundlagen)

[https://www.reichelt.de/reicheltpedia/index.php/Unterbrechungsfreie_Stromversorgung](https://www.reichelt.de/reicheltpedia/index.php/Unterbrechungsfreie_Stromversorgung)

[http://www.mtm.at/downloads/usv-klassifizierung-nach-iec-62040-3.pdf](http://www.mtm.at/downloads/usv-klassifizierung-nach-iec-62040-3.pdf)