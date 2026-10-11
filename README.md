## Reflexion

### 1. Welches Format was am mühsamsten abzubilden - und warum?

XML war für mich am mühsamsten, weil jedes Element einen öffnenden und einen schließenden Tag benötigt.
Dadurch musste ich mehr schreiben und auf die richtige Verschachtelung achten.

### 2. Wie sind Sie in der CSV mit der verschachtelten Liste und dem verschachtelten Objekt umgegangen? Was geht dabei verloren?

Die Zutaten wurden mit dem zusätzlichen Trennzeichen `|` in einer Zelle zusammengefasst.
Das Objekt `quelle` wurde in die Spalten `quelle_name` und `quelle_url` aufgeteilt.
Die Daten sind noch vorhanden, aber die ursprüngliche Struktur geht verloren;
um die Daten wieder richtig zusammensetzen, muss man wissen, wie sie vorher aufgebaut waren.

### 3. An welcher Stelle wäre ein Schema (XSD) hilfreich, wenn zwei Firmen Ihre Daten austauschen wollten?
Ein XSD-Schema hilft, die XML-Datei vor dem Import zu überprüfen.
Es legt Pflichtfelder und Datentypen fest, zum Beispiel positive ganze Zahlen für `portionen` und `zeitangabeMinuten` sowie einen Wahreitswert für `vegetarisch`.
Außerdem kann es festlegen, dass `quelle`die Elemente `name` und `url`enthalten muss.