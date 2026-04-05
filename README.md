# Meine Betaflight Presets

Persönliche Preset-Sammlung für einheitliche Drohnen-Konfiguration.

## Enthaltene Presets

| Preset | Beschreibung |
|--------|--------------|
| **Mein OSD Layout** | Komplettes OSD-Layout mit allen Element-Positionen (HD-optimiert) |
| **Meine Modes** | Switch-Belegung: ARM, ANGLE, HORIZON, PREARM, BEEPER, TURTLE |
| **Meine Rates** | Actual Rates mit 550°/s, 50% Expo, angepasste Throttle-Kurve |

## Installation

### 1. Repository auf GitHub hochladen

1. Erstelle ein neues Repository auf [github.com](https://github.com/new)
2. Nenne es z.B. `betaflight-presets`
3. Lade alle Dateien aus diesem Ordner hoch

### 2. Im Betaflight Configurator einrichten

1. Öffne den **Betaflight Configurator**
2. Gehe zum **Presets**-Tab
3. Klicke auf das **Zahnrad-Symbol** (Preset Sources)
4. Füge eine neue Quelle hinzu:
   ```
   https://raw.githubusercontent.com/DEIN-USERNAME/betaflight-presets/main/index.json
   ```
5. Speichern und Presets neu laden

### 3. Presets anwenden

1. Drohne verbinden
2. Presets-Tab öffnen
3. Deine Preset-Quelle auswählen
4. Gewünschtes Preset auswählen (OSD, Modes, oder Rates)
5. "Pick" klicken und anwenden
6. **Save** nicht vergessen!

## Ordnerstruktur

```
betaflight-presets/
├── index.json              # Preset-Index für Betaflight
├── README.md               # Diese Anleitung
└── presets/
    ├── osd/
    │   └── mein-osd-layout.txt
    ├── modes/
    │   └── meine-modes.txt
    └── rates/
        └── meine-rates.txt
```

## Mode-Belegung

| Kanal | Funktion | Range |
|-------|----------|-------|
| AUX1 | ARM | 1700-2100 |
| AUX2 | ANGLE | 1325-1725 |
| AUX2 | HORIZON | 1700-2100 |
| AUX3 | TURTLE | 1700-2100 |
| AUX4 | PREARM | 1700-2100 |
| AUX5 | BEEPER | 900-1800 |

## Rates Übersicht

- **Typ:** Actual Rates
- **Max Rate:** 550°/s (alle Achsen)
- **Center Sensitivity:** 100°/s
- **Expo:** 50%
- **Throttle Mid:** 35%
- **Throttle Expo:** 40%
