# Farbschema

Die vier interessantesten Farbschemata sind:

1. Stichworte (endliche Anzahl) bspl. `black`, `white`
2. Hexwerte mit bspl. `#ffffff`
   - Sechs Zeichen (0-9, a-f) von 0-15 (9=9, a=10, f=15) Die ersten zwei Zeichen
     von den sechs hinter dem # repräsentieren das rote Spektrum, die zweite
     zwei das grüne, die dritten zwei das blaue. So ist `#ff0000` knallrot.
   - Wenn beide Buchstaben für ein Farbspektrum (grün, rot oder blau) jeweils
     gleich sind, kann man abkürzen und statt 6 nur 3 Zeichen hinter das #
     setzen. `#f00`ist rot.
   - Mit zwei weiteren Zeichen hinter den sechs bzw. drei hinter dem # kann man
     Transparenz hinzufügen. Hier gilt: 0 ist vollständig transparent, f ist
     vollständig opak `#f008` wäre rot mit 50 % Transparenz.
3. RGB 256 (wird nie erreicht, weil die 0 mitgezählt wird)ist das Maximum, 0 ist
   das Minimum`rgb(255,0,0)` ist rot. [Vorne ist rot, Mitte ist grün, hinten ist
   blau (RGB)]
