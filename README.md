# M291-2025/2026

# Richtlinien für die Ordnerstruktur und Code-Konventionen

## Ordnerstruktur

- **HTML-Dateien** im Hauptverzeichnis.
- **CSS-Dateien** im Ordner `css`.
- **JS-Dateien** im Ordner `js`.
- **Bilder** im Ordner `images`.

**Dateinamen für HTML, CSS und JS Dateien**:

- Der Dateiname entspricht immer dem Namen der Web Page, zu der die Datei gehört. Beispiel: `promotion.html` für die Promotion Page.
- Dateien, die auf mehreren Web Pages eingebunden werden, müssen mit "common" angeschrieben werden. Beispiel: `common.css` enthält das Page Layout, das für alle Webpages gleich ist.

## Code-Praktiken

- **Kein Inline CSS oder Inline JS**: Keep HTML, CSS, JS separated!
  JavaScript Code muss in `.js` Dateien, CSS-Code muss in `.css`-Dateien stehen. JS oder CSS Code in HTML Dateien ist nicht erlaubt.
- **Kein überflüssiger oder duplizierter Code**: Keep your codebase clean!
  Code, der keinen Effekt hat, oder nicht verwendet wird, muss gelöscht werden.

## Verwendung externer Quellen

- Die Verwendung externer Quellen ist erlaubt. Trennen Sie eigenen Code und kopierten Code in separaten Dateien. Dokumentieren Sie externe Quellen in der Projektdokumentation entsprechend den Vorgaben.
