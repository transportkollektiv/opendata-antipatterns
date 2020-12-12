### Jede neue Version unter neuer Adresse veröffentlichen

#### Kurzbezeichnung
Verkleidungskünstler (bessere Vorschläge gesucht)

#### Kategorie
Zugang

#### Ungute Lösung
Veröffentliche neue Versionen eines Datensatzes unter einer neuen URL, z.B. indem Du das Veröffentlichungsdatum in den Dateinamen aufnimmst, oder - noch besser - eine neue unratbare uuid generierst

#### Negative Konsequenzen
Automatisierte Aktualsierungen durch Nutzende der Daten werden so erschwert

#### Ursprüngliches Problem
Mutmaßlich unterstützt die verwendete OpenData-Plattform nicht oder nur mit Aufwand die Veröffentlichung unter gleichbleibender URL. Oder alte Datenbestände sollten weiterhin abrufbar bleiben.

#### WorkAround
Wenn das Datum Bestandteil des Namens ist, so können eine begrenzte Anzahl an URLs ausprobiert werden, ansonsten müssen schwerere Geschütze aufgefahren werden, wie z.B. Abruf/Parsen der vorgeschalten Seite oder im Worst Case eines Selenium Skripts... 

#### Empfohlene Lösung Software-Update? Oder
Zusätzlich zu individuellen URLs eine weitere, konstante (!) die jeweils den aktuellsten Datenstand wiedergibt, z.B. `.../current`

#### Beispiele

#### Cartoon/Visualisierung
?

#### Weitere Informationen