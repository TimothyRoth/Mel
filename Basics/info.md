### Was ist ein HTML Dokument?

Ein HTML-Dokument ist eine Textdatei, die mit der Auszeichnungssprache HTML (HyperText Markup Language) geschrieben ist. Es beschreibt den Aufbau und Inhalt einer Webseite.

Browser wie Chrome, Firefox oder Safari lesen HTML-Dokumente und zeigen sie als Webseiten an.

#### Erklärung der Bestandteile:

| Bereich           | Bedeutung                                             |
| ----------------- | ----------------------------------------------------- |
| `<!DOCTYPE html>` | Gibt an, dass es sich um ein HTML5-Dokument handelt   |
| `<html>`          | Wurzel-Element – umschließt den gesamten HTML-Code    |
| `<head>`          | Unsichtbare Infos wie Titel, Metadaten, CSS, JS       |
| `<title>`         | Titel der Seite – erscheint im Browser-Tab            |
| `<body>`          | Sichtbarer Teil der Seite (Texte, Bilder, Links usw.) |

#### Merkmale:

- Textbasiert, kann mit jedem Texteditor erstellt werden (z. B. Notepad, VS Code)
- Dateiendung ist meistens .html oder .htm
- Wird im Webbrowser angezeigt
- Kann CSS (Design) und JavaScript (Funktionalität) enthalten oder einbinden

### Was ist der HTML `<head>`-Bereich?

Der `<head>` ist ein unsichtbarer Teil einer HTML-Seite, der Meta-Informationen enthält – also Daten über die Seite selbst, nicht den sichtbaren Inhalt.

Er steht am Anfang des HTML-Dokuments und befindet sich oberhalb des `<body>`-Teils, der den sichtbaren Inhalt enthält.

#### Inhalt des `<head>`

| Tag        | Bedeutung                                               |
| ---------- | ------------------------------------------------------- |
| `<title>`  | Titel der Seite (erscheint im Browser-Tab)              |
| `<meta>`   | Metadaten wie Zeichensatz, Beschreibung, Autor          |
| `<link>`   | Einbindung externer Dateien, z. B. CSS                  |
| `<style>`  | Direkt eingebettetes CSS                                |
| `<script>` | JavaScript, das vor dem Laden der Seite ausgeführt wird |


### Was sind META-Daten?

META-Daten (auch Metadaten) sind „Daten über Daten“. Sie beschreiben Informationen über eine Datei, ein Dokument, ein Bild, eine Webseite oder ein anderes Datenobjekt, ohne selbst der eigentliche Inhalt zu sein.

| Art      | Beispiel                            |
| -------- | ----------------------------------- |
| Datei    | Erstellungsdatum, Dateigröße, Autor |
| Bild     | Auflösung, Kamera-Modell, Ort       |
| Webseite | Titel, Beschreibung, Keywords       |
| Buch     | Titel, Autor, ISBN, Verlag          |
| Musik    | Titel, Künstler, Album, Genre       |

### Wie ist ein HTML Tag aufgebaut?

<tagname>Inhalt</tagname>

- `<tagname>` → Start-Tag
- Inhalt → Der sichtbare Inhalt auf der Webseite
- `</tagname>` → End-Tag

#### Beispiel Tags und ihre Bedeutung

| Tag             | Bedeutung                    | Beispiel                                      |
| --------------- | ---------------------------- | --------------------------------------------- |
| `<h1>`          | Überschrift 1. Ordnung       | `<h1>Willkommen</h1>`                         |
| `<p>`           | Absatz (Paragraph)           | `<p>Dies ist ein Textabsatz.</p>`             |
| `<a>`           | Link (Anker)                 | `<a href="https://example.com">Zur Seite</a>` |
| `<img>`         | Bild (kein End-Tag nötig)    | `<img src="bild.jpg" alt="Bild">`             |
| `<ul>` / `<li>` | Liste / Listeneintrag        | `<ul><li>Eintrag</li></ul>`                   |
| `<div>`         | Container/Abschnitt          | `<div>Inhalt</div>`                           |
| `<br>`          | Zeilenumbruch (kein End-Tag) | `Text<br>nächste Zeile`                       |
