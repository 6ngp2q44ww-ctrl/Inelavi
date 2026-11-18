# Termin-Abstimmung

Kleine Web-App, mit der eine WhatsApp-Gruppe über Datum und Uhrzeit einer Sitzung abstimmt.

## So funktioniert's
1. App öffnen, Sitzung benennen, mehrere Terminvorschläge (Datum + Uhrzeit) eintragen.
2. **Abstimmung erstellen** → **Per WhatsApp senden** und die Gruppe auswählen.
3. Alle öffnen den Link, geben ihren Namen ein und wählen pro Termin Ja / Vielleicht / Nein.
4. Nach dem Speichern den **neuen Link** wieder in die Gruppe schicken. Der neueste Link enthält immer alle Stimmen.
5. Unter „Für Organisator*innen“ kann der Termin festgelegt werden (inkl. Kalenderdatei .ics).
   Haben zwei Leute gleichzeitig abgestimmt, lassen sich die beiden Links dort zusammenführen.

Kein Server, keine Anmeldung: Der gesamte Stand steckt im Link.

## Online stellen (GitHub Pages)
Repository → **Settings → Pages** → Source „Deploy from a branch“ → Branch wählen, Ordner `/ (root)` → Save.
Danach ist die App unter `https://<benutzer>.github.io/<repo>/` erreichbar.
