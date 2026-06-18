# Vollständiges Email & Kooperations-Tracking Dashboard

**Marek Schilke** | **Exakte Analyse** | **Stand: 18.06.2026**

## Wichtiger Hinweis zu Dropdown + Farbänderung

**Reine Markdown-Tabellen (wie hier in GitHub) können keine interaktiven Dropdown-Menüs und keine automatische Zeilen-Farbänderung** darstellen.

**Beste Lösungen:**

### Option 1 (empfohlen): Excel oder Google Sheets
- Lade die Tabelle als CSV herunter
- In Excel/Google Sheets:
  - Spalte "Status" als **Dropdown** (Data Validation) anlegen
  - **Bedingte Formatierung** einrichten (Zeile wird automatisch farbig)

### Option 2: Notion
- Sehr schöne Datenbank mit Dropdown + farbigen Zeilen

### Option 3: Hier in GitHub (Workaround)
- Wir fügen eine Spalte "Status" hinzu
- Du kannst manuell Emojis oder Kürzel eintragen
- Später in Excel importieren für volle Funktionalität

## Vorgeschlagene Status-Werte (mit Farben)

| Status                | Farbe          | Bedeutung                              | Emoji     |
|-----------------------|----------------|----------------------------------------|-----------|
| Kontaktiert           | Gelb           | Erste Kontaktaufnahme erfolgt          | 🟡    |
| FollowUp              | Orange         | Nachfassen nötig                     | 🟠    |
| Absage                | Rot            | Absage erhalten                        | 🔴    |
| Zusage                | Grün          | Positives Interesse / Zusage           | 🟢    |
| Vertragsverhandlung   | Blau           | Vertrag in Verhandlung                 | 🔵    |
| Warten auf Antwort    | Grau           | Noch keine Rückmeldung               | ⬜        |
| Termin vereinbart     | Hellblau       | Termin steht                           | 🔶    |
| Hot Lead              | Dunkelgrün   | Sehr hohes Potenzial                   | 🟩    |
| Kein Interesse        | Braun          | Kein Interesse                         | 🟤    |
| Abgeschlossen         | Schwarz        | Prozess beendet                        | ⚫      |

## Empfehlung

Ich schlage vor, wir machen **beides**:
1. Hier in GitHub eine saubere "Status"-Spalte mit Emojis
2. Du importierst die Tabelle regelmäßig in Excel/Google Sheets für die interaktive Version mit Dropdown + automatischer Farbänderung

Möchtest du, dass ich jetzt die Tabelle mit einer neuen "Status"-Spalte erweitere?