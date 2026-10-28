# Finanzen Tracker

Mobile Portfolio- & Net-Worth-Tracker-App als **eine einzige HTML-Datei** – optimiert für die Nutzung am Handy (Android + Chrome).

## Features
- **Übersicht**: Gesamt-Net-Worth (Depot + Cash), Verlaufskurve (1M–Max), Depotwert, Einzahlungen, Wertzuwachs, TWRR-Rendite (zeitgewichtete Rendite), annualisierte Rendite, Diversifikation
- **Positionen**: Bestände mit Live-Kursen, G/V absolut & %, Tagesveränderung; Detailansicht mit Kurschart, Benchmark-Vergleich (MSCI World / S&P 500), Dividendenhistorie, realisierten Gewinnen
- **Buchungen**: Käufe, Verkäufe, Dividenden, Ein-/Auszahlungen, Gebühren; Ticker-Suche nach Name (z. B. „Apple" → AAPL) mit automatischem Kurs-Laden; Sparpläne mit 1-Tap-Ausführung zum Tageskurs
- **Vergleich**: bis zu 7 Wertpapiere + eigenes Portfolio, normalisiert (Start = 100)
- **Backup**: 4 rotierende interne Sicherungskopien mit Auto-Restore, Backup-Datei exportieren/teilen (Cloud), Import, 7-Tage-Erinnerung

## Kurse
Yahoo Finance (ca. 15 Min. verzögert), Fremdwährungen werden automatisch in EUR umgerechnet, 6-Stunden-Cache, CORS-Proxys mit Fallback – kein eigener Server nötig.

## Datenschutz
Alle Daten liegen ausschließlich lokal im Browser (localStorage). Es werden keinerlei persönliche Daten übertragen oder gespeichert.

## Nutzung (Android)
1. `finanzen-tracker.html` herunterladen (Rechtsklick → Speichern unter / am Handy über die GitHub-App)
2. In Chrome öffnen (nicht in der Dateien-Vorschau)
3. Chrome-Menü (⋮) → „Zum Startbildschirm hinzufügen" → App-Icon
4. Unter „Mehr" → „Beispieldaten laden" zum Ausprobieren

## Wichtig
Regelmäßig „Mehr" → „Backup-Datei speichern" bzw. „Backup teilen" nutzen und in deine Cloud (Drive/Dropbox) legen – localStorage kann beim Leeren von Browserdaten verloren gehen.
