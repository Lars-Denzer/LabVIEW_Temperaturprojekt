### 🚨 check_threshold.vi

Dieses Modul überprüft, ob ein Temperaturwert (oder dessen Durchschnitt) definierte Schwellen überschreitet.

Funktion:
- Vergleicht den aktuellen Tageswert mit einem **oberen Grenzwert**
- Berechnet zusätzlich den **Durchschnittswert über N Tage** und prüft, ob dieser ebenfalls eine eigene Schwelle übersteigt

Eingänge:
- Temperaturwerte (Array)
- Anzahl Tage für Mittelwert
- Zwei Schwellenwerte (Tages- und Durchschnittsgrenze)

Ausgänge:
- Boolean-Flags für **Tageswarnung** und **Durchschnittswarnung**
- Temperaturanzeige für aktuelle Werte

✅ Anwendungszweck:
- Alarmfunktion bei Überhitzung
- Kontrolllogik für Heiz-/Kühlsysteme
- Ergänzung zur reinen Rohdatensimulation
