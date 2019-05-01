# Lektion 3

## Inhalte: Semantischer Aufbau einer Webseite und CSS-Special

### Semantischer Aufbau einer Webseite

Bevor die CSS geschrieben wird, wird die Seite nach semantischen Gesichtspunkten
aufgebaut. Die drei wichtigsten Tags dabei sind `header`, `main` und `footer`
für oben, Hauptteil und unten. Weitere semantische Tags werden später noch
verraten.

### CSS-Special

Die dritte Methode um CSS oder Style auf die Seite zu bekommen, ist das Laden
einer CSS-Datei. Im Headbereich wird dafür folgendes eingefügt:

```
<link rel="stylesheet" href="./style.css" />
```

#### Boxmodel

Alles auf einer HTML-Seite wird in Boxen dargestellt (Jedes HTML-Element wird
von einer Box repräsentiert). Eine Box ist nichts anders als ein Rechteck um den
eigentlichen Inhalt herum. Dazu gibt es zusätzlich drei Attribute, die den
Abstand zu den anderen Elementen definieren.

- `margin` bestimmt den Abstand zu Eltern und Geschwisterelementen.
- `border` bestimmt den Rahmen.
- `padding` bestimmt den Abstand zu Kindelemente und dem Inhalt der Box.

#### Werte für Margins und Paddings

- Einfache Angaben gelten für alle Richtungen. `10px`
- Wenn man zwei Werte angibt, gilt der erste für oben und unten und der zweite
  für links und rechts. `10px 20px`
- Wenn man vier Werte angibt, gilt der Uhrzeigersinn oben beginnend.
  `10px 20px 30px 40px`

### Tagstruktur in HTML

Der Aufbau der Tagstruktur in HTML ist wie ein Baum.

- Elemente innerhalb eines anderen Elements sind **Kinder** (children).

  ´´´

  <div class='element'>
    <div class='child'></div>
  </div>
  ´´´

- Elemente neben einem anderen Element sind **Geschwister** (siblings).

  ´´´

  <div class='element'></div>
  <div class='sibling'></div>
  ´´´

- Elemente, die ein Element umschliessen heissen **Eltern** (parents).

  ´´´

  <div class='parent'>
    <div class='element'></div>
  </div>
  ´´´
