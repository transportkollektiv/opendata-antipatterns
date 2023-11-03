# OpenData Anti-Patterns

## Zielsetzung
Diese Sammlung ist aus dem [XMAS Open Mobility Meetup](https://gobeta.de/veranstaltungen/xmas-open-mobility-data-community-remote-meetup-2020-xomdcrm20/) entstanden. Wir sammeln häufige dysfunktionale Muster, mit denen die Veröffentlichung von Open Data leicht zu einem Beispiel für "das Gegenteil von gut ist gut gemeint" wird. Hoffentlich können wird durch diese Infos dazu beitragen, dass mehr tatsächlich gute OpenData-Angebote entstehen.

Sobald die Daten auf einem brauchbaren Stand sind, werden wir diese Liste auch als Blog über Github pages veröffentlichen - das ist dann etwas übersichtlicher zu lesen als direkt hier.

Alles hier ist noch in Diskussion – falls ihr noch Ideen dazu habt, helft gerne mit (siehe unten).

## Liste der Anti-Patterns
* Zugang
  * [Noch ein Daten-Portal erstellen](patterns/datenportal.md)
  * [User-Agents ausschließen](patterns/useragents.md)
  * [Jede neue Version unter neuer Adresse veröffentlichen](patterns/versionierung.md)
  * [Verwende für Features keine, nur Dir bekannte, am besten ständig wechselnde IDs, die es unmöglich machen, sie mit Daten anderer Quellen zu verknüpfen](patterns/ids.md)
  * [Erfordere eine Registrierung zum Abruf der ‚offenen Daten‘](patterns/registrierung.md)
  * [Erfordere ein Login zum Abruf der ‚offenen Daten‘](patterns/login.md)
  * [Mache Deine Daten unauffindbar](patterns/hide-and-seek.md)
  * [Nutze Dienste ohne Zugriff auf Deine Daten sicherzustellen](patterns/saas.md)
  * [Verwechsle deinen Datenkatalog mit einer Nachrichtenseite oder einem Social Network](patterns/wohnzimmerdatenportal.md)

* Struktur / Format
  * [Daten mit syntaktischen Fehlern veröffentlichen](patterns/syntaxfehler.md)
  * [Datenformat unangekündigt ändern](patterns/formataenderung.md)
  * [Verwende dein selbstdefiniertes Datenformat, obwohl es Standards gibt](patterns/eigenesdatenformat.md)
  * [Fragmentiere Deine Daten so sehr, dass es Nutzenden nicht möglich ist, sie zu einem kohärenten Ganzen zusammenzufügen](patterns/fragmentierung.md)

* Inhalt
  * [Daten mit zeitlichem Verzug bereitstellen](patterns/verzug.md)
  * [Daten mit engem zeitlichem Vorausblick bereitstellen](patterns/vorausblick.md)
  * [Download erzwingen bevor erkennbar ist, ob sich überhaupt etwas geändert hat](patterns/timestamp.md)
  * [Behaupte, Du verwendest das Standardformat, obwohl du nur das technische Protokoll meinst](patterns/formatprotokoll.md)
  * [Generiere eine bunte Webseite statt der Daten](patterns/html.md)

* Lizenz
  * [Bezeichne es als OpenData, obwohl es keines ist](patterns/pseudoopen.md)

* Unkategorisiert
  * [Die eigenen ‚offenen Daten‘ nicht nutzen](patterns/ungenutzt.md)

## Mitarbeit
Wir bieten mehrere Möglichkeiten, beizutragen:
 * Erstelle ein [Issue](https://github.com/transportkollektiv/opendata-antipatterns/issues)
 * Forke das Repository und erstelle einen Pull Request
 * Frage einen Zugang als Collaborator an (sinnvoll, wenn du bereits im Umfeld des Transportkollektiv bekannt bist)

Egal, ob du in einem Fork arbeitest oder nicht: Füge neue Patterns hinzu, indem du diese [Vorlage](patterns/template.md) kopierst, ausfüllst und oben in der Liste verlinkst.

## Weiterführende Infos
### Best Practices / Empfohlene Patterns
* Das [OpenDataInstitute](https://theodi.org/) hat Policy-Design-Patterns veröffentlicht (Motivation, Struktur, Vor-/Nachteile), warum welche Daten veröffentlicht werden sollten: [Policy design patterns that help you use data to create impact ](https://theodi.org/article/policy-design-patterns-that-help-you-use-data-to-create-impact/). 
  * Insbesondere der Katalog [Strategic government interventions using data]( https://docs.google.com/document/d/1WfRZRudauA7QVXkT9DgwrWIC61e6DMf3LM_HPJiNxxQ/edit#heading=h.nbez2ng74heg)
* [Open Data - typische Argumente](https://www.linkedin.com/pulse/open-data-typische-argumente-michael-binzen/) gegen Open Data und mögliche Gegenargumente
