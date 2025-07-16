## Theorie fragen
# Frage 1: Was sind Void-Elemente? Gib zwei Beispiele.
Void-Elemente sind HTML-Elemente, die keinen schließenden Tag benötigen, weil sie keinen Inhalt haben. Sie sind selbstschließend. Zwei Beispiele sind
<img>
(für Bilder) und
<br>
(für Zeilenumbruch).

# Frage 2: Übernimmt ein Element standardmäßig die Border-Eigenschaft seines Elternteils?
Nein, standardmäßig erbt ein Element die Border-Eigenschaft nicht vom Elternteil. Border ist eine eigene Eigenschaft, die standardmäßig auf "none" gesetzt ist, es sei denn, sie wird explizit definiert.

# Frage 3: Ist #example ein gültiger CSS-Klassenselektor?
Nein,
#example
ist kein Klassenselektor, sondern ein ID-Selektor. Ein Klassenselektor würde
.example
heißen. Das
#
steht für eine ID, während
.
für eine Klasse steht.

# Frage 4: Erkläre den Unterschied zwischen Block- und Inline-Elementen.
Block-Elemente nehmen die gesamte verfügbare Breite ein und beginnen immer auf einer neuen Zeile. Inline-Elemente nehmen nur so viel Platz ein wie nötig und fließen innerhalb einer Zeile. Beispiel für Block-Elemente:
<div>
,
<p>
. Für Inline-Elemente:
<span>
,
<a>
.

# Frage 5: Was ist die Farbe Rot in Hex, RGB und HSL?

    Hex:
    #FF0000
    RGB:
    rgb(255, 0, 0)
    HSL:
    hsl(0, 100%, 50%)

# Frage 6: Erkläre das Box-Modell und seine Beziehung zum Outline.
Das Box-Modell beschreibt, wie HTML-Elemente auf der Seite aufgebaut sind: Inhalt, Padding, Border und Margin. Das Outline ist eine Linie, die um das Element herum gezeichnet wird und außerhalb des Borders liegt. Es beeinflusst nicht die Größe des Elements im Layout, sondern dient vor allem der Hervorhebung.

# Frage 7: Erkläre
border-radius: 1em 1em 3em 1em
.
Diese CSS-Anweisung setzt die Rundung der Ecken eines Elements fest. Die Werte entsprechen den vier Ecken im Uhrzeigersinn: oben links, oben rechts, unten rechts, unten links.

    oben links: 1em
    oben rechts: 1em
    unten rechts: 3em
    unten links: 1em

Das bedeutet, die unteren rechten Ecken sind stärker abgerundet als die anderen.