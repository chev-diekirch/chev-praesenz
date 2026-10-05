# CHEV Präsenz

Anwesenheits-App für die Trainer des **CHEV Handball Diekirch**. Die Trainer tragen nach jedem Training und Spiel am Handy ein, wer da war. Am 1. jedes Monats bekommt der Vorstand automatisch einen Bericht per Mail.

**App:** https://chev-diekirch.github.io/chev-praesenz/

## Funktionen
- **Anmeldung** nur für freigeschaltete Trainer, mit 6-stelligem Code per Mail (kein Passwort)
- **Anwesenheit eintragen** pro Mannschaft, Datum und Art (Training oder Spiel)
- **Drei Status:** Anwesend · Abwesend · FLH (Nationaltraining, zählt nicht in die Quote)
- **Bestätigung per Mail** mit Excel-Liste an alle Trainer der Mannschaft
- **Ändern** bis zum Monatsende, danach ist der Monat abgeschlossen
- **Spieler hinzufügen und entfernen** durch die Trainer, die Statistik bleibt erhalten
- **Monatsbericht** am 1. des Monats an den Vorstand: ein Blatt pro Mannschaft, als Excel und PDF

## Aufbau
Dieses Repository enthält nur die **Startseite**. Sie zeigt die eigentliche App bildschirmfüllend an und bewahrt die Anmeldung auf, damit sich die Trainer nicht jedes Mal neu anmelden müssen.

Die App selbst läuft als **Google Apps Script** und speichert alle Daten in einer Google-Tabelle des Vereins. Hier liegen keine Namen und keine Anwesenheiten.

| Datei | Inhalt |
| --- | --- |
| `index.html` | Startseite, bettet die App ein |
| `icon.png` | CHEV-Logo als Symbol für den Startbildschirm |

## Tipp für Trainer
Die App am Handy **auf den Startbildschirm** legen (iPhone: Teilen → Zum Home-Bildschirm, Android: ⋮ → Zum Startbildschirm hinzufügen). Dann öffnet sie sich wie eine normale App, und die Anmeldung bleibt erhalten.
