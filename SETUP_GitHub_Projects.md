# Setup: GitHub Projects als interaktives CRM / Pipeline

**Ziel:** Interaktives Tracking mit Dropdown-Status und automatischer Farbänderung.

## Schritt 1: Neues GitHub Project erstellen

1. Gehe zu deinem Repo: https://github.com/kibuddy/email-kooperations-tracking
2. Oben im Menü auf **Projects** klicken
3. Auf **New project** klicken
4. Wähle **Table** als Start-Layout
5. Benenne das Project z. B.:
   - `Marek Schilke – Bewerbungs- & Kooperations-Pipeline 2026`

## Schritt 2: Wichtige Custom Fields anlegen

Nachdem das Project erstellt ist, lege folgende Felder an (rechts oben auf das **+** klicken):

| Feldname              | Typ            | Empfehlung / Werte                                      |
|-----------------------|----------------|---------------------------------------------------------|
| **Status**            | Single select  | Siehe Tabelle unten                                     |
| **Organisation**      | Text           | Name der Firma / Einrichtung                            |
| **Kategorie**         | Single select  | Pädagogisch / eG-Kooperation / Cyprus Business / Sonstiges |
| **Nächster Schritt** | Text        | Konkreter nächster To-Do                               |
| **Priorität**        | Single select  | Hoch / Mittel / Niedrig                                 |
| **Letztes Update**    | Date           | Datum der letzten Aktivität                            |

## Schritt 3: Status-Feld mit Farben konfigurieren

Das wichtigste Feld ist **Status**. Lege folgende Optionen an und weise Farben zu:

| Status                 | Farbe     | Emoji | Bedeutung                              |
|------------------------|-----------|-------|----------------------------------------|
| Kontaktiert            | Gelb      | 🟡 | Erste Kontaktaufnahme                  |
| FollowUp               | Orange    | 🟠 | Nachfassen nötig                     |
| Warten auf Antwort     | Grau      | ⬜    | Noch keine Rückmeldung                |
| Termin vereinbart      | Hellblau  | 🔶 | Termin steht                           |
| Vertragsverhandlung    | Blau      | 🔵 | Vertrag in Verhandlung                 |
| Zusage                 | Grün     | 🟢 | Positives Interesse / Zusage           |
| Absage                 | Rot       | 🔴 | Absage erhalten                        |
| Hot Lead               | Dunkelgrün | 🟩 | Sehr hohes Potenzial                   |
| Kein Interesse         | Braun     | 🟤 | Deutliches Desinteresse                |
| Abgeschlossen          | Schwarz   | ⚫   | Prozess beendet                        |

**So legst du Farben fest:**
1. Klicke auf das Status-Feld
2. Bei jeder Option auf das Farb-Icon klicken und die gewünschte Farbe auswählen

## Schritt 4: Items hinzufügen

Du kannst jetzt entweder:
- Manuell neue Items anlegen, oder
- Bestehende GitHub Issues in das Project ziehen

## Schritt 5: Ansichten erstellen (empfohlen)

- **Table View** (wie Excel)
- **Board View** (Kanban)
- Optional: Roadmap View

## Nächste Schritte

1. Project wie oben beschrieben anlegen
2. Status-Feld mit Farben einrichten
3. Die aktuellen Leads aus der `tracking.md` übernehmen

Falls du möchtest, erstelle ich dir alle aktuellen Leads als GitHub Issues, damit du sie einfach per Drag & Drop ins Project ziehen kannst.