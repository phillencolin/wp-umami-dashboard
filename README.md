# WP Umami Dashboard

Zeigt deine [Umami Analytics](https://umami.is) Statistiken direkt im WordPress-Backend an – ohne Tracking-Skript, ohne Datenweitergabe, direkt via API.

> Dieses Plugin wurde vollständig per Vibe-Coding entwickelt. Details zur Architektur für KI-Agenten findest du in [AGENTS.md](AGENTS.md).

## Features

- Analytics-Seite im WP-Backend mit Zeitraumauswahl
- Dashboard-Widget mit Kurzübersicht
- Charts: Besucher/Aufrufe, Geräte, Browser, Betriebssysteme, Quellen, Top-Seiten, Länder, Events
- Modulares Chart-System – neue Charts einfach als JS-Datei hinzufügen
- Anpassbare Farben via CSS Custom Properties
- Passwort-Verschlüsselung (AES-256)
- Rollenbasierte Zugriffskontrolle
- Auto-Updates direkt über das WP-Dashboard via GitHub Releases

## Voraussetzungen

- WordPress 5.0+
- PHP 7.4+
- Laufende Umami-Instanz mit API-Zugang

## Installation

1. Neueste Version unter [Releases](https://github.com/phillencolin/wp-umami-dashboard/releases) herunterladen
2. ZIP im WP-Backend unter Plugins → Installieren → Plugin hochladen installieren
3. Plugin aktivieren
4. Unter Einstellungen → Umami Dashboard: URL, Benutzername und Passwort der Umami-Instanz eintragen

## Sprache

Das Plugin ist auf Deutsch. Wer eine andere Sprache bevorzugt, kann die Texte schnell per KI übersetzen lassen.

## Lizenz

GPL v2 or later
