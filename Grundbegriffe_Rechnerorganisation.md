# Grundbegriffe der Rechnerorganisation

## Datentechnik

Datentechnik beschäftigt sich mit vielen Themen, unteranderem mit Daten und Informationen, Analogen und Digitalen Signalen und auch mit Datencodierung und Konvertierung. Aber natürlich auch mit Computernetzwerken und Netzwerkarchitekturen. Zusammenfassend kannn man sagen das Datentechnik die Arbeit mit Netzwerken, Servern und Datencodierung beschreibt. Andere Themen wären auch die beschreibung wie man in einem Netzwek indentifiziert werden kann, dies geschieht nämlich durch die MAC (Media Access Control) Adresse und durch die IP (Internetprotokoll) Adresse geregelt. Die MAC Adresse ist eine einzigartige Nummer die jede Netzwerktüchtige Hardware besitzt. Genau so ist es mit der IP nur das diese sich immer ändert, außer sie ist statisch, dann bleibt sie gleich.

## Binärsystem

Das binärsystem ist das System mit dem heutige Computer rechnen. Es setzt sich zusammen aus den beiden Ziffern 0 und 1. Mit dem Binärsystem kann man ganz eifach wie Rechnen. Die Stellen der einzelnen Bits (Zahlenstellen) werden einfach immer verdoppelt pro stelle. Es fängt z.B bei 1 an, dann 2, dann 4, dann 8 und immer so weiter, man muss nur darauf achten dass man die Zahlen immer verdoppelt. Das Binärsystem ist unteranderem auch die einfacher und kompaktere Version des Hexadezimalsystem, dieses besteht aus 16 Stellen, das Binäre nur aus 2.

## Hexadezimal

Das Hexadezimalsystem ist eine Erweiterung des normalen Dezimalsystems, dieses beinhaltet nämlich nicht nur 10 Stellen sondern 16. Es ist wie bei dem Dezimmalsystem, es beinhaltet die Zahlen 0-9 aber hier kommen dann Buchstaben ins Spiel. Von A-F kommen sie zum Einsatz. A=10 B=11 C=12 D=13 E=14 und F=15. Die ganzen Buchstaben kann man natürlich in Dezimal und Binär konvertieren wenn man das braucht.Um die Buchstaben umzurechnen braucht man dann 4 Bits, z.B A=10 und 10 wäre 1010. Das wären 4 Bits also 4 Stellen, so kann man alles umrechnen, das höchste also F, wäre 15 und 15 wäre 1111.

### UTF-8 Umrechnen

UTF-8 ist ein Konvertierungsstandard der heutzutage unteranderem mit UTF-16 angewendet wird. Computer arbeiten nur mit dem Binärsystem also mit 0 und 1, diese kann man in alles Konvertieren, egal ob Zahlen, Buchstaben oder Sonderzeichen, dank des UTFs werden diese umgewandelt und übersetzt. Der Unterschied zwischen UTF-8 und 16 liegt darin das UTF-8 nur einen Byte verabeitet, während UTF-16 immer zwei Byte verwendet. UTF-8 verwendet 1 Byte für ASCII-Zeichen, 2 Bytes für Zeichen aus einigen anderen Bereichen und 3 Bytes für den Rest der BMP. Ergänzende Zeichen benötigen 4 Bytes. UTF-16 verwendet 2 Bytes für alle Zeichen der BMP und 4 Bytes für ergänzende Zeichen.

## Dezimalsystem

Dezimalsystem ist das häufigste verwendete Zahlensystem, es beinhaltet die Zahlen 0-9. Mit dem Dezimalsystem werden tägliche Rechnungen ganz normal erfüllt. Es ist das am einfachsten zu verstehende Zahlensystem, man lernt es schon von klein auf. Man kann alle Zahlen wie auch schon beim Hexadezimal System mit 4 Bit ins binäre oder Hexadezimal umrechnen bzw. Konvertieren. Dafür muss man die Dezimal Zahl immer durch zwei dividieren um eine Binär Zahl zu erhalten. Um sie ins Hexadezimal umrechnen zu können kann man einfachsten dann einfach die Binärzahl nehmen und sich dann immer die 4 Bit Blöcke nehmen und umrechnen.

## Operatoren
 Operatoren sind Symbole oder Wörter, die in verschiedenen Kontexten verwendet werden, um Operationen durchzuführen oder Beziehungen zwischen Elementen auszudrücken. In der Mathematik werden Operatoren wie Addition (+), Subtraktion (-), Multiplikation (×), und Division (÷) verwendet, um arithmetische Operationen durchzuführen. In der Informatik spielen logische Operatoren wie AND, OR und NOT eine wichtige Rolle bei der Auswertung von Bedingungen und bei der Steuerung von Programmflüssen. In der Linguistik dienen Operatoren wie "und", "oder" und "nicht" dazu, logische Beziehungen zwischen Wörtern oder Sätzen auszudrücken. Operatoren sind daher grundlegend für die Durchführung von Berechnungen, die Steuerung von Programmen und die Analyse von Sprache.

## Operatortypen

Es gibt sechs verschiedene Typen von Operatoren: Arithmetisch, Logisch, Relationar, binäre, unäre und ternäre. Arithmethische Operatoren sind z.B +,-, * und /, das sind die ersten Operatoren die man so im Leben lernt. Logische Operatoren wären AND, OR und NOT, diese werden beispielsweise bei der Booleschen Algebra angewendet. Relationäre wären z.B <,>, ==, != usw. diese werden benutzt um Dinge zu vergleichen. Bei binären Operatoren handelt es sich um Operatoren die sich auf 2 Zahlen beziehen, bspw. 1+1. Unäre beziehen sich auf eine bspw. -4. Und ternäre auf 3 also, 7?5:6.

## Operatorenpräzedenz

Die Operatorpräzedenz bezieht sich auf die Rangfolge der einzelnen Operatoren, das heißt sie beschreibt und gibt vor welcher Operator mehr oder weniger Wert ist als der andere. Ein Beispiel wäre dass bspw. eine Multiplikation also dieser Operator * hier mehr Wert hätte als eine Addition also das +. Beim Rechnen würde das ganze so aussehen: 1+2*6. Wenn man die Präzedenz nicht beachtet kommt hier ein völlig anderes Ergebnis raus. Ohne die Präzedenz wäre es 18, man denkt nämlich das man von links nach rechts alles zusammenrechnet beachtet man allerdings die Reihenfolge würde 13 Rauskommen. Es wird nämlich zuerst die Multiplikation gerechnet in diesem Fall also 2*6, dann kann man die 1 dazu addieren.