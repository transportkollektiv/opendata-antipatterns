### User-Agents ausschließen
**Kurzbezeichnung:** Agenten-Diskriminierung
**Kategorie:** Zugang
**Ungute Lösung:** Filtere anfragende Clients anhand ihres User-Agents (bei Anfragen oft implizit mitgesendete Selbstauskunft des Client-Programms, z.B. curl) aus
Negative Konsequenzen: Bei (manuellen) Datensatz-Abrufen aus dem Browser scheint der Abruf zu funktionieren, automatisierte schlagen (z.B. mit Error Code 403) fehl
**Ursprüngliches Problem:** Mutmaßlich Maßnahme zur Blockierung  von Massenanfragen naiv abfragender Clients 
**WorkAround:** Den Agent explizit bei Anfragen überschreiben, z.B. bei curl: `curl -A "cu rl" url`
**Empfohlene Lösung:** z.B. Rate-limits in Abhängigkeit der IP festlegen 
**Beispiele:**
**Cartoon/Visualisierung:** ?
**Weitere Informationen:**