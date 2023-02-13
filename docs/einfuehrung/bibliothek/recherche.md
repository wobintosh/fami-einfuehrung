# Recherche



## Bedeutung 

- Ermittlungsarbeit
  - &#8594; Übermitteln
  - &#8594; gezieltes Wiederauffinden (Information Retrieval)
- tiefere/genauere Recherche
- Recherchestrategien
- &#10132; **professionelle Suche**



## Recherche nach Büchern (Monographien, mehrbändige Werke)

- mit den Begriffen arbeiten, die zur Verfügung stehen
- Sucheingabe:
  - leichteste Suchkategorie wählen: ``ALL``
  - Verfassernachname und 1 sinntragendes Wort aus dem Titel kombinieren (``UND-Verknüpfung``)
  - Verfassernachname weglassen (am fehlerträchtigsten), weitersuchen mit 2 sinntragenden Wörtern aus dem Titel (Trunkieren)
- wenn keine Ergebnisse: 
  - Suchkategorie wechseln
  - Rechtschreibung prüfen
  - Erweiterte Suche benutzen
  - Trunkierung ändern
  - Suchgeschichte ansehen



## Recherche nach Zeitschriften oder Zeitschriftenaufsätzen 

- Aufsatz als unselbstständiges Werk ermittelbar? (Im GVK als **unselbstständige Literatur** verzeichnet)
- Reihenfolge bei der Literaturangabe beachten (i.d.R.: Zeitschriftentitel (= selbstständiges Werk) hinter "In:")
- ggf. Kombination von Angaben aus dem Aufsatz mit Angaben aus dem Zeitschriftentitel in der Kategorie ``ALL``
- wenn es keine Ergebnisse gibt, ist der Aufsatz vermutlich nicht verzeichnet, also Suche auf Zeitschriftenebene:
  - Suche nach Titel über ``ALL``, spezialisierte Suchkategorien (``SER``, ``GTI``)
  - Sucheingabe:
    - sinntragende Worte des Zeitschriftentitels
    - Zitiertitel (= Abkürzungen)
    - bei längeren Ergebnislisten werden offene Aufnahmen i.d.R. am Ende gelistet



## Operatoren 

| Suchoperatoren                      | Nachbarschaftsoperatoren[^1]              |
| ----------------------------------- | ----------------------------------------- |
| Einbindung direkt im Suchbegriff    | GVK: Vor und nach Suchbegriff Leerzeichen |
| Platzhalter für einzelne Buchstaben | Platzhalter für ganze Wörter              |



## Operatoren (GVK) 

Hier werden die Suchoperatoren des GVK behandelt, für die allgemein üblichen Booleschen Operatoren siehe [unten](#booleshe-operatoren).



### Platzhalter 

- auch: Wildcards, Joker
- Schreibweise des Suchbegriffs unbekannt, Suche nach Variationen des Suchbegriffs
- am Ende des Suchbegriffs (__Trunkierung__) oder in der Mitte eines Suchbegriffs (__Maskierung__) möglich, nicht jedoch am Anfang eines Suchbegriffs



**Übersicht über die Platzhalter**

| Zeichen | Verwendung | Ergebnis                          | Bedeutung                              |
| ------- | ---------- | --------------------------------- | -------------------------------------- |
| *       | Verwan*    | z.B. Verwandte, Verwandtschaft, … | Platzhalter für beliebig viele Zeichen |
| ?       | Verwan?    | z.B. Verwandte, Verwandtschaft, … | Platzhalter für beliebig viele Zeichen |
| #       | Schmied#   | z.B. Schmied, Schmiede            | Platzhalter für ein oder kein Zeichen  |
| !       | Schmidtsk! | z.B. Schmidtski, Schmidtsky       | Platzhalter für exakt ein Zeichen      |



### Beispiele 
#### Trunkierung 
Eingabe: ``Fähr?``

Ergebnis: ``Fähre, fährt, Fährte, Fährschifffahrt, Fährleute, Fährhafen``


#### Maskierung

Eingabe: ``fähr\*e\*``
Ergebnis: ``Fähre, Fährte, Fährleute, Fährstrecke``

Eingabe: ``fähr!e``
Ergebnis: ``Fährte, jedoch nicht Fähre, Fährschiffe, Fährleute``

Eingabe: ``fähr#e``
Ergebnis: ``Fähre oder Fährte, nicht jedoch Fährschiffe, Fährleute etc.``

**Die Platzhalter können auch kombiniert werden**:[^2]

Eingabe: ``micro!p*``

Ergebnis: ``microsperma, microsphere, microoptics, Microspectrophotometry``



## Boolesche Operatoren 

| Operator           | Verwendung                              | Ergebnis                                               |
| ------------------ | --------------------------------------- | ------------------------------------------------------ |
| UND/Leerzeichen    | ``Suchbegriff1 **UND** Suchbegriff2``   | Ergebnisse, die alle Suchbegriffe enthalten            |
|                    | ``Suchbegriff1 Suchbegriff2``           |                                                        |
| ODER/Klammern      | ``Suchbegriff1 **ODER** Suchbegriff2``  | Ergebnisse, die einen oder alle Suchbegriffe enthalten |
|                    | ``(Suchbegriff1 Suchbegriff2``          |                                                        |
| NICHT/Minuszeichen | ``Suchbegriff1 **NICHT** Suchbegriff2`` | Ergebnisse, die nur den ersten Suchbegriff enthalten   |
|                    | `Suchbegriff1 - Suchbegriff2`           |                                                        |



[^1]: Nach TU Kaiserslautern (Hg.), [Glossar zu Begriffen der Informationskompetenz, Nachbarschaftsoperator](https://glossar.ub.uni-kl.de/begriff333) (zuletzt abgerufen am 14.04.2016). [Memento](https://web.archive.org/web/20161111193654/https://glossar.ub.uni-kl.de/begriff333) auf archive.org vom 11.11.2016
[^2]: Vgl. [gbv.de, Suchoperatoren](https://www.gbv.de/benutzer/datenbanken/hilfe/suchoperatoren), zuletzt abgerufen am 14.04.2016

