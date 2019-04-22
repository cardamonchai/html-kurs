# Lektion 2 - CSS Selektoren und semantisches HTML

## Semantisches HTML

- Headline 1 bis 6 ist möglich.
- Statt den Absätzen zu sagen (`<div>`) "Du bist nichts", sagt man mit `<p>` "Du
  bist ein Paragraph".
- Listen (Aufzählungen) gibt es in zwei Arten (geordnet `<ol>` und ungeordnet
  `<ul>`).
- Listen-Items werden mit `<li>` gekennzeichnet.
- Blockquotes (Zitate) zeichnet man mit `<blockquote>` aus.

## Editorfunktionen

Zeilen lassen sich mit Shift + Alt + Bild runter vervielfältigen.

## CSS

CSS ist die Abkürzung für "Cascading Style Sheets". Das bedeutet, dass sich
alles vom Allgemeinen zum Speziellen hin vererbt.

- Styles siehe Lektion 1
- Eine weitere Methode, um CSS zu definieren, ist das Style-Tag im Header.
- Innerhalb des Style-Tags im Header werden Selektoren erstellt. Das Format ist
  immer:
  ```
  selektor {
      attribut-name: attributwert;
  }
  ```
- Tag-Selektor: zum Beispiel `p`vererbt die Eigenschaft an alle Paragraphs.
- Klassen-Selektor: zum Beispiel `.einleitung`vererbt die Eigenschaften an alle
  Tags mit der gleichen Klasse.
- ID-Selektor: zum Beispiel `#schluss` vererbt die Eigenschaften an das Tag mit
  der ID `schluss`.
- An jedes Tag kann eine Klasse/class (CSS-Klasse) angefügt werden.

## Attribute

- Alles, was man an ein Tag anfügt, nennt man Attribut: ``style`,`class`und`id`
- Eine Sprungmarke (Deeplink) wird über `id` definiert (Beispiel: `id="schluss"`
  ) und über einen # in der URL aktiviert - URL kopieren und unter der
  gewünschten Textstelle verlinken (Beispiel:
  `https://cardamonchai.com#schluss`).
