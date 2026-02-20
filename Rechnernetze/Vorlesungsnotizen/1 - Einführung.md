Einführung in Rechnernetze – Klassifikationen und Netztopologien.

[[#Überblick und Ressourcen|Zum Überblick]].

>[!example]- Inhalte
>1. [[#Rechnernetze|Definition Rechnernetze]]
>2. [[#Klassifizierung|Klassifikationen]]
>3. [[#Netztopologien|Netztopologien mit Vor- und Nachteilen]]

![[#^tldr]]

---
## Rechnernetze

Ein *Rechnernetz* ist ein System aus Datenendeinrichtungen (PC, Drucker, ...), die miteinander über Medien (Glasfaser, Funk, ...) mittels Übertragungseinrichtungen (Modems, Multiplexer, ...) und Vermittlungseinrichtungen (Router, Switches, ...) oder weitere Rechnernetze verbunden sind.

---
## Klassifizierung

Die *Klassifizierung* von Kommunikationsnetzen geschieht nach verschiedenen Kriterien. Darunter die der Zugang auf das Netz, die Rolle im Netzverbund, die Vermittlungsart sowie die Reichweite und Technologien.

### Zugang

<table>
	<tr>
		<th>Öffentlich</th>
		<td>- Dienste und Netze werden allgemein angeboten.<br>- <i>Beispiel</i>: Telekommunikationsanbieter: DSL, Glasfaser, Mobilkommunikation, WLAN-Hotspots.</td>
	</tr>
	<tr>
		<th>Privat</th>
		<td>- Dienste und Netze werden individuell einer geschlossenen Benutzergruppe oder Organisation angeboten.<br>- <i>Beispiel</i>: Intranet = privates Netz einer Organisation mit Internet.</td>
	</tr>
	<tr>
		<th>Virtuelles Privates Netz (VPN)</th>
		<td>- Logisches Netz, die wie ein privates Netz wirkt, auf öffentlicher Netzinfrastruktur.<br>- <i>Beispiel</i>: Netz von Firma in verschiedenen Städten nutzt öffentliche Infrastruktur.</td>
	</tr>
</table>

### Rolle im Netzverbund

<table>
	<tr>
		<th>Kernnetz (Core Network, Backbone Network)</th>
		<td>- Hauptverbindungsstruktur eines Netzverbundes.<br></td>
	</tr>
	<tr>
		<th>Zugangsnetz (Access Network)</th>
		<td>- Ermöglichen, das Kernnetz aus vielen Orten aus zu erreichen.<br>- Für private Endsysteme (z.B. DSL, Kabelmodems, Glasfaser).<br>- Für mobiles Endsysteme (z.B. GSM/LTE/5G, WLAN).<br>- Für institutionelle Endsysteme und Subnetze (z.B. LANs).</td>
	</tr>
</table>

### Vermittlungsart[^1]

<table>
	<tr>
		<th>Leitungsvermittlung</th>
		<td>- Feste Verbimdung zwischen Endgeräten.<br>- Reservierte Leitung, bis die Datenübertragung abgeschlossen ist.</td>
	</tr>
	<tr>
		<th>Paketvermittlung</th>
		<td>- Nachrichten werden in kleinere Pakete geteilt.<br>- Für alle Pakete einer Nachricht wird einmalig ein Weg ermittelt.</td>
	</tr>
</table>

[^1]: Externe Quelle (Beschreibungen): [Vermittlungstechniken in Informatik, Mirko Hans](https://www.mirko-hans.de/info/gk_12/dateien/netzwerke/Vermittlungstechniken.pdf)

### Reichweite und Technologien

<table>
	<tr>
		<th>Personal Area Network (PAN)</th>
		<td>Persönliches Netz für Geräte eines Benutzers.<br>- Bis zu 10m.<br>- <i>Technologie</i>: Bluetooth.</td>
	</tr>
	<tr>
		<th>Storage Area Network (SAN)</th>
		<td>Spezielle Speichernetze innerhalb von Rechenzentren, dient zur Verbindung von Server mit Speichersystem.<br>- Bis zu 100m.<br>- <i>Technologien</i>: Fibre Channel, Infiniband.</td>
	</tr>
	<tr>
		<th>Lokales Netz (Local Area Network, LAN)</th>
		<td>Netz innerhalb eines Standorts einer Organisation. Standard für lokale Festnetze ohne speziellen Anforderungen.<br>- 10m bis 10km.<br>- <i>Technologien</i>: Ethernet, WLAN, Feldbusse (Industrielle Bussysteme).</td>
	</tr>
	<tr>
		<th>Stadtnetz (Metropolitan Area Network, MAN)</th>
		<td>- 10km bis 100km<br>- <i>Technologien</i>: OTN, MPLS, Ethernet.</td>
	</tr>
	<tr>
		<th>Weitverkehrsnetz (Wide Area Network, WAN)</th>
		<td>Netz mit großer Ausdehnung, z.B. deutschlandweit.<br>- Fernbereich, mehr als 100km.<br>- <i>Technologien</i>: OTN MPLS, Ethernet.</td>
	</tr>
	<tr>
		<th>Weltweites Netz (Global Area Network, GAN)</th>
		<td>Netze mit weltweiter Ausdehnung. Der Begriff kommt in der Praxis selten vor.</td>
	</tr>
</table>

### Transparenz der Diensterbringung

Die *Transparenz* beschreibt die Fähigkeit eines Systems, bestimmte Systemeigenschaften vor Nutzern zu verbergen. Kommt es darauf an, wie etwas realisiert ist, nennt man es nichttransparent.

<table>
	<tr>
		<th>Ortstransparenz</th>
		<td>Weiß man, wo gewisse Vorgänge im Netz stattfinden?</td>
	</tr>
	<tr>
		<th>Replikationstransparenz</th>
		<td>Sind die Netzwerkverbindungen und Systeme redundant vorhanden und würden auch im Fehlerfall noch funktionieren?</td>
	</tr>
	<tr>
		<th>Leistungstransparenz</th>
		<td>In welchem Maß ist die Leistungsfähigkeit des Netzes ausgeschöpft?</td>
	</tr>
</table>

Die Transparenz ist oft das Kriterium zum Unterscheiden zwischen einem Rechnernetz und einem verteiltem System. Rechnernetze sind nichttransparent, verteilte Systeme transparent.

---
## Netztopologien

Die Verbindung von Endgeräten in einem Festnetz kann in verschiedenen Strukturen erfolgen, die als *Netztopologien* bezeichnet werden. Oftmals verwenden diese Strukturen zusätzliche Zwischensysteme oder Endgeräte als Sender und Empfänger direkt.

Die Vor- und Nachteile jeweiliger Topologien basieren auf nachfolgende Kriterien:

- *Kosten*: Relevante Kosten, Kabel, Funktionsaufwand, zusätzliche Zwischensysteme.
- *Installation und Erweiterbarkeit*: Einfache Inbetriebnahme, Erweiterbarkeit.
- *Übertragungskapazität*: Parallele Kommunikation, Wie viele Geräte gleichzeitig?
- *Ausfallsicherheit*: Auswirkung von Fehlern, fällt das gesamte Netz aus?
- *Fehlersuche*: Aufwand von Fehlersuche und Behebung.
- *Broadcast*: Wie einfach ist die Implementation eines Broadcasts?
- *Abhörsicherheit*: Wie schwer ist es, Kommunikationen zweier Endgeräten abzufangen und mitzuhören?

### Bustopologie

In einer *Bustopologie* sind alle Endgeräte an einen Bus, ein gemeinsam genutztes Kabel, angeschlossen.

![[bus_topology.png]]

| Vorteile                                                                                                                                                              | Nachteile                                                                                                          |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| *Kostengünstig*, da Kabelstrecken kurz sind und keine zusätzliche Hardware erfordert wird.                                                                            | *Begrenzte Kapazität*, da keine parallele Kommunikation möglich ist. Es käme sonst zu Kollisionen.                 |
| *Einfache Installation und Erweiterbarkeit*, da jedes Endgerät sich ohne Zusatzgeräte anschließen lässt. Lediglich die Verlängerung des Busses kann aufwändig werden. | *Schwierige Fehlersuche*, da Störungen auf den Bus nur schwer zu lokalisieren sind, insbesondere bei Störsignalen. |
| *Endgeräteausfall unproblematisch*. Sendet ein Gerät Störsignale betrifft es jedoch den gesamten Bus.                                                                 | *Busausfall führt zu Netzausfall*.                                                                                 |
| *Einfacher Broadcast*, da auf der physikalischen Ebene jede Dateneinheit ohnehin jedes Endgerät erreicht.                                                             | *Nicht abhörsicher*, da jedes Endgerät die Informationen aller anderen Endgeräte mitlesen kann.                    |

### Sterntopologie
  
In einer *Sterntopologie* sind alle Endgeräte mit eigenen Leitungen über eine zusätzliche Hardware (Sternkoppler) miteinander verbunden. Dieses dient lediglich zur Weiterleitung von Dateneinheiten und ist kein Endgerät.

![[star_topology.png]]

Es werden zwei Arten von Sternkoppler unterschieden.

- *Hub*: Leitet Signale, die es an einem Port erhält an alle anderen Ports weiter; ermöglicht nur eine Kommunikation zur Zeit.
- *Switch*: Leitet Signale gezielt weiter, basierend auf Auswertung von Adressen; gleichzeitiger Datenaustausch mehrerer Endgeräte möglich.

Da Hubs veraltet sind, beziehen sich die Vor- und Nachteile auf die Sterntopologie mit Switch.

| Vorteile                                                                                          | Nachteile                                                                                                                                                                                         |
| ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| *Hohe Kapazität*, da parallele Kommunikation möglich ist.                                         | *Single Point of Failure*. Fällt der Switch aus, fällt das gesamte Netz aus.                                                                                                                      |
| *Einfache Fehlersuche*, da jedes Endgerät sein eigenes Netz-Segment hat.                          | *Hohe Kosten*\*, da für jedes Endgerät ein eigenes Kabel benötigt wird das an dem Switch angeschlossen wird, welches selbst auch erworben werden muss.<br><br>\*heutzutage jedoch dennoch günstig |
| *Einfache Erweiterung*, da bei freien Ports ein neues Endgerät einfach angeschlossen werden muss. |                                                                                                                                                                                                   |
| *Einfacher Broadcast*, da ein Broadcast einfach an alle Ports weitergeleitet wird.                |                                                                                                                                                                                                   |
| *Abhören schwierig*, da der Switch nur an das Empfängersystem weiterleitet.                       |                                                                                                                                                                                                   |

### Baumtopologie

Wenn mehrere Sterne zu einer größeren Einheit zusammengefasst werden, indem man die Sternkoppler miteinander verbindet, entsteht die *Baumtopologie*.
Die Struktur entsteht durch hierarchische Sterne, wodurch Teilnetze über die Wurzel kommunizieren.

![[tree_topology.png]]

Die Vor- und Nachteile ergeben sich aus den Eigenschaften der Sterntopologie.
Zusätzlich führt der Ausfall eines Knotenpunktes zur Abtrennung von Teilnetzen vom Rest des Netzes. Außerdem konzentriert sich der Datenverkehr besonders in den oberen Hierarchieebenen.

### Ringtopologie

Bei der einfachen *Ringtopologie* werden die Endgeräte ringförmig verbunden. Es gibt immer einen eindeutigen Vor- und Nachgänger (vergleichbar mit einer Linked List). Daten bewegen sich in eine Richtung. Fällt ein Knoten oder eine Verbindung aus, so ist das Netzwerk nicht funktionstüchtig.

![[ring_topology.png]]

Liegt ein zweiter, entgegengesetzter Ring vor, spricht man von einem doppelten Ring. Dadurch sind Kommunikationen in beiden Richtungen möglich.


| Vorteile                                                                                                           | Nachteile                                                                                                                                  |
| ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------ |
| *Parallele Kommunikation*, mindestens auf beiden Ringen und in modernen Ringtopologien auch auf dem gleichen Ring. | *Geringe Ausfallsicherheit*, da ein defektes Endgerät für einen Totalausfall führt. Defekte Leitungen bei einfachen Ringen auch.           |
| *Einfache Erweiterbarkeit*, da weitere Endgeräte einfach reingehangen werden können.                               | *Aufwändigere Komponenten*, da die Endsysteme die Dateneinheiten aktiv weiterleiten und das Netzmanagement insgesamt auch aufwändiger ist. |
| *Einfacher Broadcast*, da dieser einfach über den Ring geleitet wird.                                              | *Keine Abhörsicherheit*, da Dateneinheiten immer den kompletten Ring durchlaufen.                                                          |
|                                                                                                                    | *Schwierige Fehlersuche*, da das defekte Endgerät bzw. die defekte Leitung erst durch Untersuchungen festgestellt werden muss.             |

### Vermaschung

Ist ein Netz mit redundanten Verbindungen zwischen den Knoten aufgebaut, spricht man von einem *vermaschten Netz*. Gibt es von einem Endgerät eine Verbindung zu jedem anderen Endgerät handelt es sich um eine Vollvermaschung. Das liegt jedoch kaum vor, da der Aufwand quadratisch steigt.

![[mesh_topology.png]]

Vermaschung findet man meist nur in wichtigen, vor Allem Weitverkehrs-, Netzen, aufgrund hohem Aufwand. Bei den Knoten handelt es sich dann eher um Netzknoten (z.B. Router), an denen lokale Netze angeschlossen sind, die mit einer anderen Topologie realisiert sein können.

| Vorteile                                                                                                                                               | Nachteile                                                                                                                                                                                   |
| ------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| *Große Ausfallsicherheit*, da durch die redundanten Verbindungen einzelne Ausfälle kompensiert werden können.                                          | *Hohe Anschaffungskosten*, da eine Vielzahl an Verbindungen implementiert werden müssen, was viele Kabel und Ports erfordert. Auch eine Wegewahl muss auf den Geräten implementiert werden. |
| *Parallele Kommunikation*, da mehrere gleichzeitige Kommunikationsmöglichkeiten gegeben sind.                                                          | *Schwierige Erweiterbarkeit*, da jeder weitere Knoten mehrere Verbindungen braucht, um redundant zu sein.                                                                                   |
| *Einfache Fehlersuche*, da bei Fehlern der Großteil des Netztes noch funktioniert. Es ergibt sich leicht, welcher Knoten bzw. Leitung die Ursache ist. | *Schwieriger Broadcast*, da ein spezieller Mechanismus erforderlich ist damit keine Duplikate eines Broadcasts entstehen.                                                                   |
|                                                                                                                                                        | *Abhören ggf. möglich*, wenn über mehrere Knoten hinweg eine Dateneinheit geschickt wird.                                                                                                   |

---
## Überblick und Ressourcen

>[!tldr] tl;dr
>- *Rechnernetze* sind Netze aus Endgeräten und anderen Netzen, die miteinander mittels Leitungen und Vermittlungseinrichtungen (Switches, Router) verbunden sind.
>- Rechnernetze werden *klassifiziert* nach Zugang (Öffentlich, Privat, VPN), Rolle im Netzverbund (Kern- / Zugangsnetz), Vermittlungsart (Leitungen, Pakete), Reichweite & Technologie (PAN, LAN, etc.), Transparenz.
>- *Netztopologien* beschreiben die Strategie des Zusammenschluss des Netzes, z.B. über einen gemeinsamen Bus, als Stern an einen Sternkoppler, mehrere Sterne als Baum, als Ring oder vermascht.
>^tldr

>[!link] Hilfreiche Links
>- [RN Grundlagen Playlist (YouTube)](https://www.youtube.com/playlist?list=PLQvKY4d5Oi9NKNfF4zV3bL5h7Fyfsf2BO)
>- [Selbsttest zur Einführung](https://lernraum.th-luebeck.de/mod/quiz/view.php?id=46947)

>[!source] Quellen
>- RN Foliensatz 1 - Einführung
>- [RN Loop - Rechnernetze Grundlagen (1)](https://lernraum.th-luebeck.de/mod/loop/link.php?loop=vfhkon1a.eduloop.de&page=Rechnernetze_Grundlagen&skin)
>^sources
