# Lernziele für das iSAQB Modul API (Application Programming Interfaces)

## [Thilo Frotscher](https://frotscher.com/) und [Erik Wilde](https://www.linkedin.com/in/erikwilde/) (v3, November 2024)

### Was vermittelt das Modul API?

Application Programming Interfaces, oder APIs, ermöglichen die Nutzung von digitalen Diensten über programmierbare Schnittstellen. Ihre Nutzung hat über die letzten 20 Jahre stark zugenommen. Aus Sicht der Softwarearchitektur sind APIs sowohl aus Produzenten- als auch aus Konsumentensicht relevant: Softwarekomponenten sollten idealerweise als wiederverwendbare Produkte verstanden werden; APIs helfen, eine Softwarekomponente einfach wiederverwendbar zu machen. Heute stehen mehr und mehr Dienste über APIs zur Verfügung; als Konsument dieser Dienste kann man sich besser auf Kernaufgaben konzentrieren und andere Aufgaben auslagern an externe Komponenten.

Das Modul betrachtet die verschiedenen Arten, wie APIs Wert erzeugen: Als technische Schnittstellen die es verschiedenen Komponenten ermöglichen miteinander zu kommunizieren; als organisatorische Schnittstellen die es verschiedenen Teams ermöglicht mit weniger gegenseitigen Abhängigkeiten ihre jeweiligen Komponenten zu entwickeln; und als geschäftsorientierte Bausteine die es der Organisation erlauben, neue Dienste schneller und effektiver zu entwickeln. 

Im Rahmen dieses Moduls sprechen wir bei APIs immer von Netzwerk-basierten Schnittstellen, also nicht von lokalen Programmierschnittstellen.


### Zielgruppe

Primäres Publikum sind Software Architekten, Entwickler und andere technisch orientierte Personen, die sich einen umfassenden Überblick über das Thema APIs verschaffen möchten.

Neben dem Schwerpunkt auf technischem Themen werden auch strategische Aspekte behandelt wie die Wertschöpfung und die Verwendungen von APIs als Team-Kollaboration im Unternehmen. Damit eignet sich das Modul gut, um sich dem Thema APIs mit einer weiteren Perspektive als dem rein technischen Blick zu nähern.


### Gliederung des Lehrplans und zeitliche Aufteilung

*Inhalt* | *Vortrag (empfohlene Dauer)* | *Übungen (empfohlene Dauer)*
:-- | :--: | :--:
[Übersicht und Einführung](#overview) | 90min | keine
[Wertschöpfung von APIs](#value) | 60min | 30min
[API Stile und Technologien](#styles) | 60min | 30min
[Beschreibung von APIs am Beispiel OpenAPI](#openapi) | 90min | 30min
[API Design](#design) | 90min | 30min
[API Lifecycle und API Tooling](#lifecycle) | 90min | 60min
[API Security](#security) | 60min | 30min
[APIs at Scale: Platforms und Governance](#governance) | 60min | 30min
*Summe: 14h* | 10h | 4h


### Lernziele

#### <a id="overview"></a> 1. Übersicht und Einführung 

- **LZ 1-1: Herkuft des API Begriffs kennen und einordnen**

  Teilnehmer:innen können APIs einordnen in die Geschichte der Programmierung, Computernetzwerke, verteilten Systeme, und Softwarearchitektur. Sie verstehen die Herkunft aus den ersten Modellen der Trennung verschiedener Softwarekomponenten und die weitere Evolution des Begriffs.

- **LZ 1-2**: Die Entwicklung von lokalen APIs zu Netzwerk-basierten APIs und die aktuelle API Landschaft werden in ihrem Gesamtkontext verstanden.

- **LZ 1-3**: Vergleich unterschiedlicher Integrationsstile und -konzepte  (synchron/asynchron, ...)

- **LZ 1-4**: Der Begriff der "API Economy" wird in seiner gesamten Breite verstanden und Teilnehmer können beurteilen, wie ihre Produkte und Aktivitäten dort eingeordnet werden können.


#### <a id="value"></a> 2. Wertschöpfung von APIs 

- **LZ 2-1**: Verständnis grundlegender Arten wie API Produkte die Wertschöpfung ermöglichen (intern, Partner-orientiert, öffentliche Produkte), und welche Auswirkungen das auf Design und Management hat

- **LZ 2-2**: Verständnis der möglichen Geschäftsmodelle von APIs und einiger ausgewählter Beispiele

- **LZ 2-3**: Die Verwendung von APIs als eine Grundlage digitaler Transformation und essentielle Eigenschaften der APIs


#### <a id="styles"></a> 3. API Stile und Technologien 

- **LZ 3-1**: Kenntnis verschiedener grundlegender API Stile (RPC, Resource, Hypermedia, Query, Events) und ihrer Stärken und Schwächen im Vergleich

- **LZ 3-2**: Übersicht über populäre API Technologien und deren Einteilung gemäss der verschiedenen API Stile

- **LZ 3-3**: Verständnis der Kriterien wann welche Stile/Technologien mehr oder weniger gut passen und der Konsequenzen der Auswahl


#### <a id="openapi"></a> 4. Beschreibung von APIs am Beispiel OpenAPI 

- **LZ 4-1**: Verstehen warum API-Beschreibungen Nutzen erzeugen und von wem sie wofür benutzt werden können

- **LZ 4-2**: Übersicht von OpenAPI als einer konkreten Beschreibungssprache und deren Zielen und Design

- **LZ 4-3**: Verständnis der Hauptelemente einer OpenAPI-Beschreibung im Sinne von Resourcen, Interaktionen, und Repräsentationen

- **LZ 4-4**: Kenntnis anderer Beschreibungssprachen (AsyncAPI, GraphQL, gRPC) und ihrer Unterschiede im Vergleich zu OpenAPI
 

#### <a id="design"></a> 5. API Design 

- **LZ 5-1**: API Design als "Outside-in" Ansatz bei dem das Design auf Konsumenten fokussiert ist

- **LZ 5-2**: Offenheit und Erweiterbarkeit als wichtige Aspekte um API Produkte weiterentwickeln zu können

- **LZ 5-3**: Verständnis verschiedener Aspekte der Versionierung und wie sie innerhalb des Lebenszylus eines API Produkts verwendet wird

- **LZ 5-4**: Qualitätsanforderungen: Performance, Skalierung, Caching
 

#### <a id="lifecycle"></a> 6. API Lifecycle und API Tooling 

- **LZ 6-1**: Verschiedene Schritte des Entwicklungszyklus eines API Produkts

- **LZ 6-2**: Verschiedene Phasen des Lebenszyklus eines API Produkts

- **LZ 6-3**: Übersicht über die Unterschiede zwischen der Sichtweise von Produzenten und Konsumenten

- **LZ 6-4**: Tools zur Unterstützung von Produzenten und Konsumenten wie Linting, Testing (z.B. Consumer-driven Contract Testing), Mocking, Betrieb (API Gateways)


#### <a id="security"></a> 7. API Security 

- **LZ 7-1**: Kenntnisse der Grundlagen von Kommunikationssicherheit und der Einordnung von TCP, HTTP und TLS.

- **LZ 7-2**: Verständnis von HTTPS, HTTP Authentisierung, OAuth, und OpenID Connect

- **LZ 7-3**: API Gateways und andere Modelle um APIs abzusichern
  

#### <a id="governance"></a> 8. APIs at Scale: Platforms und Governance 

- **LZ 8-1**: Plattformen, Platform Engineering, und Platform as a Product als Verbesserung der Developer Experience und Effektivität

- **LZ 8-2**: Verwendung und Pflege von API Guidelines um APIs konsistenter zu entwickeln

- **LZ 8-3**: Beispiele von API Guidelines einiger Organisationen

- **LZ 8-4**: Team Topologies als organisationelles Modell für effektiv arbeitene Teams
