# Excel

Kleinkram, der mir geholfen hat, etwas weniger Schmerzen mit großen Tabellen zu haben.



## Zeilen abwechselnd färben ohne Formatierung als Tabelle 

Zwar färbt Excel Zeilen abwechselnd, wenn man den Bereich als Tabelle formatiert, in manchen Fällen ist das aber nicht gewünscht. Geht auch ohne:

1. Bereich markieren
2. Bedingte Formatierung &#8594; Neue Regel &#8594; Formel zur Ermittlung der zu formatierenden Zellen verwenden
3. Formel eingeben: ``=REST(ZEILE();2)=0``
4. Formatierung auswählen, Bestätigen



