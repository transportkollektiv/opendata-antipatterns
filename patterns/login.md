## Erfordere eine Login zum Abruf der ‚offenen Daten‘

#### Kurzbezeichnung
Nur-Selbstabholung

#### Kategorie
Zugang

#### Ungute Lösung
Erfordere vor dem Abruf der Daten ein explizites Login über Login-Maske.

#### Negative Konsequenzen
Automatisierte Abrufe, wie sie zur zeitnahen Weiterverarbeitung von Daten-Updates erforderlich sind, werden hierdurch erschwert. Entweder Nutzende führen einen manuellen Login unud Download durch, oder sie implementieren durch Skript 

#### Ursprüngliches Problem
Mutmaßlich ähnliche Beweggründe wie beim Muster "[Türsteher](registrierung.md)", darüberhinaus mutmaßlich fehlendes Verständnis für die Bedeutung automatisierbarer Downloads.

#### WorkAround
Implementieren einer Skript-Lösung, die durch Browser-Automatisierung o.ä. die erforderliche Anmeldesequenz durchläuft und die Daten abruft. Im zweiten Schritt "barrierefreie" Bereitstellung der heruntergeladenen Daten.

#### Empfohlene Lösung
Verzicht auf Login-Erfordernis. Sollte, aus welchen Gründen auch immer, eine Authentifizierung/Identifizierung erforderlich sein, so sind Access-Tokens eine Alternative. Die Verwendung von Zertifikaten im Kontext von OpenData erhöht die technische Komplexität unnötig und wird nicht empfohlen.

#### Cartoon/Visualisierung

#### Beispiel

#### Weitere Informationen

