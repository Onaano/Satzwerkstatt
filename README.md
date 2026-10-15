# 🏠 Satzwerkstatt — Sätze bauen, verstehen & richtig schreiben

Interaktives Deutsch-Lernspiel für **Klasse 1–3 (Förderunterricht, Sprachförderung, DaZ)**.
Die Kinder arbeiten in einer freundlichen Werkstatt und bauen aus fertigen Sätzen ein **Vogelhaus**. Sie lernen dabei, Wörter zu Sätzen zu ordnen, fehlende Wörter und Satzanfänge zu finden, das passende Satzzeichen zu wählen und richtige von falschen Sätzen zu unterscheiden.

## 🗂️ Die sechs Stationen
1. **Die Baustelle** (Werkbank) – „Baue den Satz!“ Wörter in die richtige Reihenfolge bringen (Antippen, Ziehen **oder** Tastatur). **Alle grammatisch richtigen Wortfolgen werden akzeptiert** („Heute fahren wir mit dem Bus.“ / „Wir fahren heute mit dem Bus.“ …).
2. **Das Ersatzteillager** – „Welches Wort fehlt?“ (genau eine passende Lösung)
3. **Der Bauplan** – „Finde den richtigen Satzanfang!“
4. **Die Zeichenstation** – „Welches Satzzeichen passt?“ (Punkt, Fragezeichen, Ausrufezeichen)
5. **Die Qualitätskontrolle** – „Welcher Satz stimmt?“ (Großschreibung, Reihenfolge, fehlende/doppelte Wörter, Satzzeichen)
6. **Die große Satzwerkstatt** – alle fünf Stationen im Wechsel, nie dieselbe Art zweimal hintereinander

Ablauf: Station wählen → Stufe (leicht / mittel / schwer) → spielen.
**Leicht**: 3–5 Wörter · **Mittel**: 5–8 Wörter · **Schwer**: 7–11 Wörter, weniger Hilfen.

## 🧩 Fortschritt: Das Vogelhaus
Eine Runde endet nach **8 richtig gelösten Aufgaben**. Jede richtige Lösung baut ein Teil des Vogelhauses (Bodenbrett, Wände, Vorderbrett, Dachhälften, Einflugloch, Wimpel). Am Ende: **„Werkstück fertig!“** mit „Noch eine Runde“ und „Zurück zur Auswahl“.
Kein Zeitlimit, keine Punkte, keine Leben, kein Game Over, kein Highscore. Falsche Antworten bekommen einen freundlichen, konkreten Hinweis, **verraten die Lösung nicht** und bringen keinen Fortschritt.

## 🔤 Material
- **135 Grundsätze** (Aussagen, W-Fragen, Ja/Nein-Fragen, Aufforderungen, Ausrufe), daraus **128 Bausätze**, **105 Lückensätze**, **124 Satzanfänge**, **135 Satzzeichen-** und **128 Kontroll-Aufgaben** (über alle Stufen).
- Sprachlich geprüft: jede Aufgabe hat genau eine richtige Lösung; beim Satzbau sind alle weiteren grammatisch richtigen Wortfolgen hinterlegt und die falschen Varianten der Qualitätskontrolle werden gegen diese Menge geprüft.
- Rundenplan: keine Satzwiederholung, kein Wortschatz-Klumpen, wechselnde Themen, richtige Antwort nie zweimal an derselben Stelle hintereinander, ausgewogene Satzzeichen-Verteilung.

## 🔊 Sprachausgabe
Browser-Sprachausgabe (de-DE) nur als Unterstützung. Sie verrät **keine Satzzeichen und keine Großschreibung**. Ohne Sprachausgabe im Browser werden die Lautsprecher-Knöpfe ausgeblendet; das Spiel bleibt vollständig spielbar.

## 📱 Geräte & Bedienung
Smartboard, PC, Laptop, Tablet, Smartphone; Maus, Touch, Tastatur; Hoch- und Querformat. Aufgaben passen **ohne Scrollen** (geprüft von 360×640 bis 2560×1440 und Laptop ab 600 px Höhe; bei Smartphones im Querformat kann sehr lange Qualitätskontrolle am Rand scrollen – Hochformat empfohlen). Touch-Ziele ≥ 44 px, sichtbare Fokusrahmen, Kontraste nach WCAG AA, `prefers-reduced-motion`, Information nie nur durch Farbe.

## 🛠️ Technik
Eine einzige `index.html` (HTML, CSS, Vanilla JavaScript). Keine Frameworks, keine externen Bilder/Schriften/APIs, keine Cookies, kein Tracking, keine Datenspeicherung. Alle Illustrationen sind eigene SVGs.
Netlify: Ordner per Drag & Drop (Build command leer, Publish directory `.`). GitHub: `index.html`, `README.md`, `.gitignore` (+ optional `arbeitsblaetter/`, `pruefung/`).

## 🖨️ Arbeitsmaterialien (`arbeitsblaetter/`, HTML + PDF)
- `teilnehmeruebersicht` – A4 quer, 30 Kinder × 10 Runden
- `arbeitsblatt-saetze-bauen` – Sätze bauen (eindeutig und mit mehreren Lösungen), Wort einsetzen, Satzanfang
- `arbeitsblatt-saetze-pruefen` – Richtigen Satz finden, richtig/falsch, Sätze verbessern, Satzzeichen setzen
- jeweils zusätzlich `-loesung` (für Lehrkräfte)

## ✅ Prüfmaterial (`pruefung/`)
`materialuebersicht.html`, `.pdf`, `.csv` – alle Aufgaben mit ID, Satz, Stufe, Satzart, Lösung, Ablenkern/falschen Varianten und allen akzeptierten Wortfolgen.

## 🧪 Qualitätssicherung
Daten- und Grammatik-Audit (0 Fehler) · Simulation von zehntausenden Runden (Rundenplan, Verteilung, Wiederholungen, Stufen) · alle 6 Stationen × 3 Stufen als volle Runden über die Oberfläche (inkl. falscher Antworten und Hinweise) · Maus-Ziehen, Touch-Ziehen, Tippen, Tastatur · Betrieb mit und ohne Sprachausgabe · Reduced Motion · 15 Bildschirmgrößen · Konsole ohne Fehler.
