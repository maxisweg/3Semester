Softwareprojekte definiert als Produkt – Output, Outcome, Impact und Produktentwicklung.

[[#Überblick und Ressourcen|Zum Überblick]]

>[!example]- Inhalte
>- Definition des Begriffs Produkt
>- Überblick über die Produktenentwicklung mit ihren Bestandteilen
>- Produktlebenszyklus

![[#^tldr]]

---
## Produkt

>[!theorem] Produkt
>>„Betriebswirtschaftlich betrachtet ist euer Produkt eine von euch erzeugte Ware oder eine Dienstleistung. In der Ware oder Dienstleistung kommt an irgendeiner Stelle Software vor.“
>>
>\- Beneken et al. 2025, S. 121

Verschiedene Arten von Software-Produkten:

- *Software als Produkt*:
	- Computerprogramme oder Apps,
	- Software as a Service.
- *Software im Produkt (Hardware)*:
	- Teil eines Hardware Produkts,
	- z.B. Smart Home, Staubsaugerroboter.
- *Software als Produkt (Dienstleistung)*:
	- Teil einer Dienstleistung,
	- z.B. Banking-Dienstleistung.

Ziele von Softwareprodukten:

- Software sollte kein Selbstzweck sein,
- Unterstützung bei der Lösung von realen Problemen bzw. Aufgaben,
- Verbesserung der User Experience / des Wohlbefindens von Menschen.

>[!info] Output
>Als *Output* bezeichnet man die Ergebnisse eines Projekts.
>
>>[!example] Beispiele
>>Programmcode, Dokumentation, Anforderungslisten, Projektpläne.

>[!info] Outcome
>Als *Outcome* bezeichnet man den Erfolg des Produkts.
>
>Löst das Produkt das Problem? Führt es zu Verhaltensänderung und Zufriedenheit?

>[!info] Impact
>Als *Impact* bezeichnet man das Nutzen des Software-Produkts.
>
>>[!example] Beispiele
>>Betriebswirtschaftliche oder gesellschaftliche Auswirkungen.

---
## Überblick über die Produktentwicklung

#todo image

>[!info]- Vision
>Eine *Vision* ist ein eher langfristig ausgelegtes, erstrebenswertes, inspirierendes, eher abstraktes Ziel.
>
>>[!example]- Beispiele
>>>„Die Informationen dieser Welt organisieren und allgemeinzugänglich und nutzbar machen.“ 
>>
>>\- Google
>>
>>>„Den Menschen die Möglichkeit zu geben, Gemeinschaften zu bilden, und die Welt näher zusammenzubringen.“
>>
>>\- Facebook
>

>[!info]- Personas
>*Personas* sind Beschreibungen einer beispielhaften, fiktiven Person einer Nutzergruppe und dient zur Charakterisierung typischer Vertreter einer Zielgruppe.
>
>>[!example]- Beispiele
>>Typische Eigenschaften:
>>- Name
>>- Bild
>>- Demographische Daten (Name, Alter, Geschlecht, ...)
>>- Ausbildung und Fähigkeiten (Bildungsabschluss, Beruf, Funktion im Unternehmen, Tätigkeiten)
>>- Ziele und Bedürfnisse, sowie Erwartungen an das Produkt
>>- Hindernisse
>>- Technologische Voraussetzungen (z.B. Nutzung bestimmter Endgeräte oder Betriebssysteme)

>[!info]- Nutzungskontext
>Als *Nutzungskontext* versteht man die Umgebung, in dem die Software durch die Benutzer eingesetzt werden soll.
>
>>[!example]- Beispiele
>>- *Ruhige Umgebung*:
>>	- Situation: Bibliothek; keine lauten Gespräche oder Geräusche sozial akzeptiert.
>>	- Folgerung: keine Sprachgesteuerten Interaktion möglich (Audio-Input und -Output).
>>- *Laute Umgebung*:
>>	- Situation: laute Umgebung, z.B. im öffentlichen Raum (Bahnhof).
>>	- Folgerung: keine Sprachausgabe oder -steuerung möglich wegen technischer Restriktionen.
>>- *Industrielle Fertigung*:
>>	- Situation: Mitarbeitende arbeiten in Industrieunternehmen in manuellen, händischen Fertigungsprozessen.
>>	- Folgerung: ggf. keine händische Bedingung von Endgeräten möglich, ggf. aber Sprachsteuerung oder Einsatz von Datenbrillen möglich.

>[!info]- Rahmenbedingungen
>*Rahmenbedingungen* sind Vorgaben, die bei der Entwicklung einer Software beachtet werden müssen. Dies können allgemeine gesetzliche als auch kundenspezifische Vorgaben sein.
>
>>[!example]- Beispiele
>>Häufige Rahmenbedingungen beziehen sich auf:
>>- Erstellungsprozess (z.B. vorgegebene Werkzeuge oder Dokumente)
>>- Rahmenarchitekturen (z.B. Einschränkungen der Technologien, Programmiersprachen oder Systeme)
>>- Styleguides (z.B. Corporate Design)
>>- Gesetze (z.B. DSGVO oder Medizinproduktegesetz)
>>- Normen

>[!info]- Ziele
>*Ziele* dienen zur Operationalisierung der Vision und sollten konkret und messbar formuliert sein.
>
>>[!example]- Beispiele
>>Häufig werden Ziele nach dem "SMART"-Schema formuliert:
>>- Spezifisch;
>>- Messbar;
>>- Akzeptiert;
>>- Realistisch;
>>- Terminiert.

>[!info]- Product Backlog
>Der *Product Backlog* beschreibt eine Liste von Anforderungen, die im Produkt implementiert werden sollen und dient als Grundlage für die Implementierung.
>
>>[!note]- Product Backlog erstellen
>>- *Relevante Merkmale*:
>>	- Identifikationsnummer (z.B. GitLab Issue Nummer);
>>	- Anforderungstitel ("sprechende Überschrift");
>>	- Schätzung (z.b: absolut in Personentagen oder relativ (hoch, mittel, gering));
>>	- Priorität (z.B. MuSCoW-Schema: Must, Should, Could, Won't);
>>	- Weitere Merkmale möglich (z.B. Quelle, Risiko, Kategorien, ...).
>>- *Erstellung*:
>>	1. Product Owner sammelt Anforderungen, Wünsche und gefundene Fehler (z.B. vom Kunden).
>>	2. Anforderungen werden eingeplant als grobe Anforderungen oder verworfen.
>>	3. Anforderungen werden nach Bedarf verfeinert und präzisiert bevor sie in die Umsetzung (z.B. in einem Sprit) gelangen.
>>- *Beispielhafte Dokumentation*:
>>	- Als Persona möchte ich Wunsch haben, um Nutzen zu erzielen.
>>- *Mögliche Verschriftlichung*:
>>	- Whiteboard
>>	- Tabellen
>>	- Tickets (z.B. in GitLab)

>[!info]- Minimum Viable Product (MVP)
>*Minimum Viable Product* beschreibt eine kleinstmögliches (Software-) Produkt, dass die essenziellen Anforderungen oder Features implementiert.
>
>---
>MVPs dienen zum Testen (z.B. UI-Experimenten) und müssen nicht (vollständig) in Software implementiert sein, sondern können etwa Mockups/Wireframes sein.

---
## Produktlebenszyklus

Der *Produktlebenszyklus* beschreibt alle relevanten Prozesse und/oder Schritte, die im Rahmen der Entwicklung und des Betriebs einer Software durchlaufen werden.

#todo image

---
## Überblick und Ressourcen

>[!tldr] tl;dr
>#todo
>^tldr

>[!link] Hilfreiche Links
>#todo

>[!source] Quellen
>SWT I Foliensatz 2 - Produkt
>^sources
