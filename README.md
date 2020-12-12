# OpenData Anti-Patterns

## Zielsetzung
Diese Sammlung ist aus dem [XMAS Open Mobility Meetup](https://gobeta.de/veranstaltungen/xmas-open-mobility-data-community-remote-meetup-2020-xomdcrm20/) entstanden. Wir sammeln häufige dysfunktionale Muster, mit denen die Veröffentlichung von Open Data leicht zu einem Beispiel für "das Gegenteil von gut ist gut gemeint" wird. Hoffentlich können wird durch diese Infos dazu beitragen, dass mehr tatsächlich gute OpenData-Angebote entstehen.

Alles hier ist noch in Diskussion, falls ihr noch Ideen dazu habt, helft gerne mit,fügt weitere Beschreibungen als Pull Request hinzu, legt ein Issue an, oder fragt uns nach einem direkten Zugang zum mitschreiben.

### Liste der Anti-Patterns
* Zugang
  * [Noch ein Daten-Portal erstellen](patterns/datenportal.md)
  * [User-Agents ausschließen](patterns/useragents.md)
  * [Jede neue Version unter neuer Adresse veröffentlichen](patterns/versionierung.md)
  * [Verwende für Features keine, nur Dir bekannte, am besten ständig wechselnde IDs, die es unmöglich machen, sie mit Daten anderer Quellen zu verknüpfen](patterns/ids.md)
  * [Erfordere eine Registrierung zum Abruf der ‚offenen Daten‘](patterns/registrierung.md)
  * [Findbarkeit der Daten](patterns/findbarkeit.md)
* Inhalt
  * [Daten mit syntaktischen Fehlern veröffentlichen](patterns/syntaxfehler.md)
  * [Daten mit zeitlichem Verzug bereitstellen](patterns/verzug.md)
  * [Daten mit engem zeitlichem Vorausblick bereitstellen](patterns/vorausblick.md)
  * [Download erzwingen bevor erkennbar ist, ob sich überhaupt etwas geändert hat](patterns/timestamp.md)
  * [Verwende dein selbstdefiniertes Datenformat, obwohl es Standards gibt](patterns/eigenesdatenformat.md)
  * [Behaupte, Du verwendest das Standardformat, obwohl du nur das technische Protokoll meinst](patterns/formatprotokoll.md)
  * [Fragmentiere Deine Daten so sehr, dass es Nutzenden nicht möglich ist, sie zu einem kohärenten Ganzen zusammenzufügen](patterns/fragmentierung.md)
* Lizenz
  * [Bezeichne es als OpenData, obwohl es keines ist](patterns/pseudoopen.md)
* Unkategorisiert
  * [Die eigenen ‚offenen Daten‘ nicht nutzen](patterns/ungenutzt.md)

### Mitarbeit
Füge neue Patterns hinzu, indem du diese [Vorlage](patterns/template.md) kopierst, ausfüllst und oben in der Liste verlinkst.
### Best Practices / Empfohlene Patterns
* Das [OpenDataInstitute](https://theodi.org/) hat Policy-Design-Patterns veröffentlicht (Motivation, Struktur, Vor-/Nachteile), warum welche Daten veröffentlicht werden sollten: [Policy design patterns that help you use data to create impact ](https://theodi.org/article/policy-design-patterns-that-help-you-use-data-to-create-impact/). 
* Insbesondere der Katalog [Strategic government interventions using data]( https://docs.google.com/document/d/1WfRZRudauA7QVXkT9DgwrWIC61e6DMf3LM_HPJiNxxQ/edit#heading=h.nbez2ng74heg)