# Lektion 1 - HTML Basics und erstes CSS

## Einführung

In den ersten Lektionen wird es nur um HTML und CSS gehen -> Immer parallel
erklärt. JS kommt dann später dazu.

Prettier Plugin installiert -> Ermöglicht es, Dateien automatisch zu formatieren
(Matze erklärt das noch mal genau)

### Markdown

- 3 Backticks (`): hier kann Code eingefügt werden
- 1 Backtick: wird in GitHub Inline (innerhalb eines Satzes) als
  Monospace/Courier dargestellt

### HTML

- HTML ist ein Format von Computern und Menschen schreibbar und lesbar ist
- Browser sind dazu da, HTML-Dateien formatiert anzuzeigen (zeigt es so an, wie
  wir es anzeigt haben wollen, nicht wie wir es aufgeschrieben haben > nennt man
  "interpretieren")
- HTML hat nicht immer etwas mit dem Internet zu tun, es kann auch lokal
  erstellt werden
- Verschiedene Browser können HTLM unterschiedlich interpretieren, mann kann
  sich nicht darauf verlassen, dass alle Browser alles gleich machen - Vorsicht
  vor alten Versionen - unterschiedliche Standards
- Wenn Text nicht gestylt ist (kein CSS hat), wird er von Browsern in der
  Standardschrift angezeigt (meistens TimesNewRoman)

  Um zu sehen, was auf einer Seite passiert, während man sie bearbeitet, öffnet
  man die Developer Tools. In Windows ist das FN+F12, bei Mac OS CMD + Option +
  i. Das ist bei allen Browsern gleich.

#### Zeichen, die keine Bedeutung haben:

- div: Absatz
- span: Zeichenformat (Inlinetag) kennzeichnet etwas

Vor den Body kommt `head`(Metadatenbereich). In den Body kommt der Inhalt der
Seite.

Nachfolgend die Struktur einer HTML-Seite

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Titel der Seite (Meta Description)</title>
  </head>
  <body>
    ...
  </body>
</html>
```

## CSS

CSS kann man auf drei verschiedene Arten an Elemente anbauen

- Inline Style
- Im Head-Tag stylen
- über eine Extra-Datei

CSS besteht immer aus zwei Teilen: Property (Name der Eigenschaft) und Value
(Wert der Eigenschaft)

### Inline Style
