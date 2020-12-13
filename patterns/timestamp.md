### Download erzwingen bevor erkennbar ist, ob sich überhaupt etwas geändert hat

#### Kurzbezeichnung
Daten-im-Sack

#### Kategorie
Zugang

#### Ungute Lösung
Verhindere, das abrufende Clients vor dem vollständigen Download erfahren, ob sich der Datensatz seit dem letzten Download geändert hat. Sorge z.B. dafür dass

* der Server den Last-modified Antwort-Header nicht setzt, an dem Clients erkennen könnten, wann der Datensatz auf Server-Seite zuletzt aktualisiert wurde (wie z.B. curl bei Verwendung des -z Arguments)
* die HEAD-Anfrage-Methode durch den Server nicht unterstützt wird, bei der der Server statt des komplpetten Dokuments nur die Antwort-Header senden würde
* der Server kein [ETag-Attribut](https://de.wikipedia.org/wiki/HTTP_ETag) setzt, anhand dessen Clients oder Proxy-Server erkennen könnten, dass sich ein Datensatz seit dem letzten Abruf nicht geändert hat
* auch keine weitere Möglichkeit zur Feststellung einer Änderung, wie z.B. eine aus dem Dateiinhalt generierte, zusäzlich abrufbare MD5-Prüfsumme, existiert

#### Negative Konsequenzen
Auf Seite des Server-Betreibers führt dies zu unnötigem Datenverkehr und gegebenenfalls Serverlast, da unnötig viele Daten übertragen werden müssen. Aus Unkenntnis geeigneter Abilfemaßnahmen werden gegebenenfalls andere Anti-Patterns angewendet, um die Serverlast zu reduzieren.
Auf Seite der Daten-Nutzenden führt dies zu ebenfalls zu unnötigem Datenverkehr, potentiell unnötigerwese ablaufenden Weiterverarbeitungsprozesse oder alternativ zu Mehraufwand bei der Prüfung auf Änderungen nach dem Download (z.B. durch lokale Berechnung einer MD5-Prüfsumme). 

#### Ursprüngliches Problem
In der Regel Unkenntnis sinnvoller Server-Konfiguration.

#### WorkAround
Einrichtung bzw. Nutzung eines Alternativ-Portals, das seinerseits die Daten herunterlädt und nur bei Änderungen erneut publiziert.

#### Empfohlene Lösung
Korrekte Server-Konfiguration.

#### Beispiele
Negativbeispiel: Datensätze des Hamburger Transparenzportals werden ohne o.g. Antwort-Header ausgeliefert, z.B. die [GTFS-Daten des HVV](http://daten.transparenz.hamburg.de/Dataport.HmbTG.ZS.Webservice.GetRessource100/GetRessource100.svc/747d0530-b330-4b22-afed-e0a82f94dda6/Upload__HVV_Rohdaten_GTFS_Fpl_20200908.zip).

#### Cartoon/Visualisierung
?

#### Weitere Informationen