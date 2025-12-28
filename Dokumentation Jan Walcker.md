<div align="center">

# Signalverarbeitung 2

## Projektdokumentation

<div align="right">

**Datum:** 28.12.2025
</div>

# Student Information

|                   |                                 |
|-------------------|---------------------------------|
| Name              | Jan Walcker                     |
| Matrikelnummer    | 22759                           |
| Studiengang       | Software engineering Bachelor   |
| Kurs              | SV2                             |
| Betreuer          | Marc Nauendorf                  |
| Akademisches Jahr | 2025/2026                       |
</div>

# Task 1
## 1
**Berechnung:** Berechnen Sie zuerst die theoretische Resonanzfrequenz f₀ mit der Formel von Folie 5 und den gegebenen Werten.

$$
f_0 = \frac{1}{2 \pi \sqrt{L C}}
$$

$$
f_0 = \frac{1}{2 \pi \sqrt{(10 \cdot 10^{-3} \, \text{H}) \cdot (100 \cdot 10^{-9} \, \text{F})}}
$$

$$
f_0 \approx 5032.92 \, \text{Hz}
$$


## 2
**Simulation:** Bauen Sie die Schaltung auf. Finden Sie im Simulator die Frequenz, bei der der Strom I maximal ist. (Tipp: Verwenden Sie einen "Slider" für die Frequenz und beobachten Sie die Helligkeit/Geschwindigkeit der fließenden Punkte).

![Task 1 GIF](https://raw.githubusercontent.com/SpongebobSquarepants35/SV2/main/HDGifs/Task1SV2HD.gif)

## 3
**Dokumentation:** Notieren Sie die Frequenz, die Sie im Simulator gemessen haben.

| Rechenwert  | Messwert | Folie 7     |
|:-----------:|:--------:|:-----------:|
| ~5032.92 Hz | 5 kHz    | 1300 Hz     |

## 4
**Vergleich:** Vergleichen Sie Ihren Rechenwert (aus 1.), Ihren Messwert (aus 3.) und den Wert auf Folie 7. Was stellen Sie fest?

Der berechnete Wert entspricht unter Berücksichtigung kleiner Messabweichungen weitgehend dem simuliert ermittelten Wert.
Der auf Folie 7 angegebene Wert ist jedoch deutlich geringer. Dies ist auf die etwa zehnfach höhere Induktivität sowie die erhöhte Kapazität in dem dort dargestellten Beispiel zurückzuführen.
Da die Impedanz im Nenner der Resonanzformel steht, führt dies zu einer entsprechend deutlich niedrigeren Resonanzfrequenz.

# Task 2
## 1
Finden Sie eine Methode in der Simulationssoftware, um den Frequenzgang des Stroms sichtbar zu machen. (Tipp: Die Spannung am Widerstand R ist proportional zum Strom I).

## 2
Stellen Sie den Widerstand R so ein, dass Sie ihn interaktiv verändern können (z.B. mit einem Schieberegler).

## 3
**Dokumentieren** Sie durch ein GIF, wie sich die Form der Resonanzkurve (die "Peak-Form") ändert, wenn Sie R von einem sehr kleinen Wert (z.B. 5 Ω) zu einem großen Wert (z.B. 300 Ω) ändern.

![Task2 GIF](https://raw.githubusercontent.com/SpongebobSquarepants35/SV2/main/HDGifs/Task2SV2HD.gif)

## 4
**Erklären** Sie den Zusammenhang, den Sie beobachten:
- Was passiert mit der **Höhe** des Peaks?
  - Je höher der Widerstand ist, desto niedriger ist die Höhe des Peaks.
- Was passiert mit der **Breite** des Peaks?
  - Je höher der Widerstand ist, desto schmaler wird die Breite des Peaks.
- Was bedeutet das für die **Güte Q** und die **Bandbreite** der Schaltung (vgl. Folie 9)?
  - Wenn der Widerstand sinkt, wird die Güte höher und die Bandbreite schmaler. 
    Bei steigendem Widerstand, steigt auch die Bandbreite und die Güte sinkt.

# Task 3
## 1
**Bauen** Sie beide Schaltungen im Simulator auf.

## 2
**Berechnen** Sie zuerst die erwartete Resonanzfrequenz f₀ (Thomsonsche Formel).

$$
f_0 = \frac{1}{2 \pi \sqrt{L C}}
$$

$$
f_0 = \frac{1}{2 \pi \sqrt{(1 \cdot 10^{-3} \, \text{H}) \cdot (10 \cdot 10^{-9} \, \text{F})}}
$$

$$
f_0 \approx 50329.21 \, \text{Hz}
$$

## 3
**Simulieren** Sie den Frequenzgang der Ausgangsspannung für beide Schaltungen (z.B. in einem Bereich von 15 kHz bis 30 kHz).

## 4
**Dokumentieren** Sie Ihre Ergebnisse durch GIFs, die den Frequenzgang beider Schaltungen zeigen.
 ![Task3 GIF](https://raw.githubusercontent.com/SpongebobSquarepants35/SV2/main/HDGifs/Task3SV2LongHD.gif)