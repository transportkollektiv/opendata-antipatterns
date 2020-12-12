### Automatisierte Browser ausschließen

#### Kurzbezeichnung
Automaten-Diskriminierung

#### Kategorie
Zugang

#### Ungute Lösung
Filtere anfragende Clients anhand dem `navigator.webdriver` Wert aus

#### Negative Konsequenzen
Bei (manuellen) Datensatz-Abrufen aus dem Browser scheint der Abruf zu funktionieren, automatisierte schlagen (z.B. indem javascript nicht lädt) fehl

#### Ursprüngliches Problem
Mutmaßlich Maßnahme zur Blockierung  von Massenanfragen naiv abfragender Clients 

#### WorkAround
Der einfachste Weg ist vor dem Aufruf der Seite den `navigator.webdriver` zu entfernen im aktiven Tab.

#### Empfohlene Lösung
z.B. Rate-limits in Abhängigkeit der IP festlegen 

#### Beispiele

#### Cartoon/Visualisierung
?

#### Weitere Informationen
