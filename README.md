# Pokédex

Eine interaktive Pokédex-Webanwendung, die Pokémon-Daten von der [PokéAPI](https://pokeapi.co/) abruft und übersichtlich darstellt.

## Features

- **Pokémon-Karten** – Anzeige von Name, ID, Bild und Typen für jedes Pokémon
- **Suchfunktion** – Pokémon nach Name filtern (ab 3 Buchstaben)
- **Mehr laden** – Weitere Pokémon per Klick nachladen
- **Detailansicht** – Dialog mit drei Tabs:
  - *About* – Größe, Gewicht, Fähigkeiten und Typen
  - *Stats* – HP, Angriff, Verteidigung und Geschwindigkeit als Balkendiagramm
  - *Evo Chain* – Evolutionskette mit Bildern
- **Navigation** – Zwischen Pokémon in der Detailansicht blättern
- **Typ-basiertes Farbschema** – Karten und Dialoge werden je nach Pokémon-Typ eingefärbt
- **Ladeanimation** – Skeleton-Loading beim ersten Laden der Seite

## Technologien

- HTML
- CSS
- JavaScript (Vanilla)
- [PokéAPI](https://pokeapi.co/)

## Starten

1. Repository klonen:
   ```bash
   git clone https://github.com/janbrauner2502/pokedex.git
   ```
2. `index.html` im Browser öffnen – es wird kein Build-Schritt oder Server benötigt.

## Projektstruktur

```
├── index.html          # Haupt-HTML-Seite
├── scripts/
│   ├── script.js       # API-Aufrufe, Datenverarbeitung und Suchlogik
│   ├── template.js     # HTML-Templates für Karten und Dialoge
│   └── dialog.js       # Dialog-/Overlay-Steuerung
├── style/
│   ├── style.css       # Allgemeines Layout und Karten-Styling
│   ├── color.css       # Typ-basierte Farben
│   ├── dialog.css      # Dialog-Styling
│   ├── font.css        # Schriftarten
│   └── load.css        # Ladeanimationen
├── assets/
│   ├── fonts/          # Schriftdateien
│   └── icons/          # Icons und Typ-Symbole
└── LICENSE             # MIT-Lizenz
```

## Lizenz

Dieses Projekt steht unter der [MIT-Lizenz](LICENSE).
