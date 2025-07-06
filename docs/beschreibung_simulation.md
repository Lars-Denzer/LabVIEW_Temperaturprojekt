### 📈 simulate_temperature.vi

Dieses Modul erzeugt simulierte Temperaturdaten zur Verwendung in Messsystemen, Visualisierungen oder Testläufen.

Die Temperatur wird als Kombination aus:
- einem festen **Basiswert** (z. B. 22 °C),
- einer sinusförmigen **Tagesmodulation** (z. B. ±5 °C),
- sowie einem **Zufallsrauschen** simuliert.

Formel:
```text
Temperatur = Basiswert + Schwankung * sin(t) + Rauschfaktor * Zufall

Das VI gibt einen Rohwert aus und stellt diesen in einem Waveform Chart grafisch dar. Es kann als eigenständiger Simulationsbaustein oder als SubVI in komplexere Systeme integriert werden.

✅ Anwendungszweck:

    Testumgebungen ohne echte Sensorhardware

    Schulung & Demonstration

    Basis für Schwellenwertüberwachung und Mittelwertbildung
