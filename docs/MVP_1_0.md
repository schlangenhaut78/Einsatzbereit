# Einsatzbereit – MVP 1.0 (Stufe 1, Android)

Stand: 2026-11-02 · Status: **freigegeben**
Ziel: Der Entwickler nutzt die App selbst täglich und prüft das Konzept, bevor weitere Funktionen kommen.
Testgerät: Samsung Galaxy A17.

## Schritt 0 – Technischer Vorabtest
Mini-Test-App: Liefert Health Connect auf dem A17 Ruhepuls, Schlaf, Schritte (ggf. HRV)? → danach Tracker-Kauf (Empfehlung Galaxy Fit3).

## Umfang
| Bereich | Inhalt |
|---|---|
| Start | Kurzer Datenschutzhinweis · Gesundheitscheck (ca. 7 Ja/Nein-Fragen) |
| Ziele (4 Vorlagen) | 1. Treppen steigen · 2. Getränkekisten tragen · 3. **THW: Mehrstunden-Einsatz** · 4. **Feuerwehr: Belastungsübung FwDV 7** |
| Freitext-Ziele | lokal gespeichert (Übermittlung per Mail später) |
| Leittests (5) | Treppentest · Tragetest · 30-s-Sit-to-Stand · 6-Minuten-Gehtest · Einbeinstand |
| Coach | Etappen · EIN nächster Schritt (Prognose klein) · Feedback (Borg + Beschwerden) · Symptom-Ampel · Eskalation E1–E4 · Wiederaufnahme nach E4 |
| Daten | Health Connect: Ruhepuls, Schlaf, Schritte |
| Screens | Heute · Entwicklung (einfache Kurven) · Ziele · Mehr |
| Arzt-PDF | gemäß Fachkonzept |
| Sicherung | manuelle, verschlüsselte Sicherungsdatei in Ordner nach Wahl (z. B. Google Drive) |

## Vorlage „THW: Mehrstunden-Einsatz“ (MVP-Fassung)
Grundlage: `BOS_Profile.md` Abschnitt 0 und 3.
| Etappe | Inhalt (Richtwerte, anpassbar) |
|---|---|
| 1 | 30 min aktive Belastung (Gehen + Tragen), Borg ≤ 5 |
| 2 | 60 min, darin Lastenserie (z. B. 20 × Kiste heben + 10 m tragen) |
| 3 | 2 h Block mit kurzen Pausen, Lastenserien + Treppe mit Last |
| 4 | 4 h Block (Rhythmus Arbeit/Pause) |
| Ziel | 2 Tage hintereinander 4-h-Block, Ruhepuls am Folgemorgen nahe Normalwert, Borg ≤ 6, keine Beschwerden |

Relevante Leittests: 6-Minuten-Gehtest (Langzeitausdauer), Tragetest (Funktionskraft), Sit-to-Stand (Kraftausdauer), Einbeinstand (Gleichgewicht, rutschiger Untergrund).

## Versionen ↔ Stufen
| Version | Inhalt |
|---|---|
| 1.0 | dieser MVP |
| 1.1 | Ernährung · G26-Readiness · weitere Vorlagen (u. a. Enkelkinder/Boden) · Erhalt-Modus + Folgeziele · Leittest Aufstehen vom Boden |
| 1.2 | DLRG-Profil · Nebenziele · Fragen-Assistent |
| 2.0 | iOS (Stufe 2) |
| 2.x | Schuh-Logbuch |
| 3.0 | Desktop + Sync (Stufe 3) |
| später | Tablets, Uhr-App (Stufe 4) · Gruppen-Challenges (Stufe 5) |
