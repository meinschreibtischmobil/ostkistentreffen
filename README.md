# 🛵 Ostkisten Mischöl-Rechner

Eine mobile Web-App für 2-Takt-Mischöl-Berechnung – optimiert für Simson, MZ, Trabant & Co.

**Live:** [meinschreibtischmobil.github.io/ostkisten-mischoelrechner](https://meinschreibtischmobil.github.io/ostkisten-mischoelrechner)

---

## Features

- **KI-Zapfsäulenerkennung** – Foto der Zapfsäule → Liter werden automatisch erkannt
- **KI-Tacholesung** – Tacho fotografieren → Kilometerstand wird ausgelesen
- **Verbrauchsrechner** – Automatische L/100km Berechnung zwischen zwei Tankstopps
- **Mischungsverhältnisse** – 1:50, 1:33 oder frei wählbar
- **Tankhistorie** – bis zu 20 Einträge mit Kilometerstand & Verbrauch (localStorage)
- **PWA** – als App auf dem Home-Screen speicherbar (iOS & Android)
- **IFA-Garage-Design** – Retro-Werkstatt-Optik mit Oswald-Schrift

## Technik

- Einzelne HTML-Datei, kein Build-Prozess
- Claude Sonnet API (KI-Bilderkennung)
- Open-Meteo, Overpass API
- Google Fonts (Oswald, Roboto Condensed)

## Installation auf dem iPhone

1. Seite im Safari öffnen
2. Teilen → „Zum Home-Bildschirm"
3. Fertig – läuft wie eine native App

---

*Design inspiriert von [thomas-ifa-garage.de](https://thomas-ifa-garage.de)*
