title: Entwickler und Architekten
subtitle: Strategien 2020
class: animation-fade
layout: true

<!-- This slide will serve as the base layout for all your slides -->

.bottom-bar[
{{title}}
]

---

class: impact

# {{title}}

## {{subtitle}}

.title-oli[
Oliver Sturm &bull; @olivers[@fosstodon.org] &bull; oliver@oliversturm.com
]

.title-logo[
<img src="template/devexpress.png" id="devexpress" alt="DevExpress">
]

---

## Oliver Sturm

- Training Director at DevExpress
- Consultant, trainer, author, software architect and developer for over 25 years

- Contact: oliver@oliversturm.com

---

## Agenda

Idee: Technologie diskutieren

Was sind Ihre Fragen? Diskussionspunkte?

---

class: columns-ul

## Anregungen

- COVID-19 - was ändert sich?
- Microservices, ja oder nein? Und wie?
- Cloud - muss das sein? Welche? Worauf kommt's an?
- Serverless - wird da nicht alles schwieriger?
- CQRS? Event Sourcing? Eventual Consistency? GraphQL? Moderne Datenzugriffspatterns
- Container und VMs - Docker, Kubernetes, Vagrant, Terraform...
- Blazor? Ist das die Zukunft? Server mit SignalR oder Client mit WASM?
- Wie mache ich am besten Mobile?
- gRPC - Microsoft's neuer (?) Hype
- React vs Vue vs Angular usw....
- TypeScript oder doch einfach JavaScript?
- Oliver Sturm's Best Practices Architekturmodell

---

class: columns-ul

## Fragen

- Cloud - Kostenkontrolle - wie weiss man, was die eigene Anwendung kostet?
- Hochverfuegbarkeit notwendig - kann man "hybrid" oder lokal arbeiten, wenn die Cloud unzugaenglich ist? Docker - Registry lokal?
- On Premise-System in die Cloud migrieren, moeglichst ohne Aenderungen, was sind die Stolpersteine?
- GraphQL - wo gehoert das ins Datenzugriffssystem? Im Vergleich mit OData?
- Daten transferieren zwischen lokal und Cloud im Hybridsetup? Datenbankinhalte
- Beispiel Consul - Azure-Service oder separater Container - SaaS oder separates Deployment?

---

## Vor COVID - Eingeschränkter Remotezugriff

.svg-light-width-padding[![](pre-covid-remote-access-org.png)]

---

## Vor COVID - Eingeschränkte Remote-Funktionalität

.svg-light-100[![](pre-covid-remote-access-erp-modules.png)]

---

## Fernzugriff auf eine Datenbank

.svg-light-100[![](database-remote-access-through-vpn.png)]

---

## Fernzugriff mit Remote Desktop

.svg-light-100[![](remote-desktop-access.png)]

---

## Einfache Web-Anwendung

.svg-light-100[![](simple-web-application.png)]

---

## (Micro-?) Services

.svg-light-100[![](microservices-based-application.png)]

---

## Dienststruktur - Micro oder Größer

.svg-light[![](microservices-logical.svg)]

---

## CQRS

.svg-light[![](cqrs.svg)]

---

## CQRS mit Event Sourcing

.svg-light[![](cqrs-es.svg)]

---

## GraphQL Basics

.svg-light[![](graphql-basics.svg)]

---

## GraphQL Endpoint in Readmodel

.svg-light[![](graphql-endpoint-in-read-model.svg)]

---

## GraphQL - Frontend Service

.svg-light[![](frontend-graphql-service.svg)]

---

## Hypervisors

.svg-light-width[![](hypervisors.svg)]

---

## Container und VMs

.svg-light[![](containers-and-vms.svg)]

---

## CAP Theorem

.svg-light[![](cap-theorem.svg)]

---

## JavaScript vs TypeScript

.svg-light[![](static-types.svg)]

---

## Sources

- This presentation:

  - https://oliversturm.github.io/developers-and-architects/basta-2020
  - PDF download: <br>https://oliversturm.github.io/developers-and-architects/basta-2020/slides.pdf

---

class: impact

# Thank You

Please feel free to contact me about the content anytime.

.title-oli[
Oliver Sturm &bull; @olivers[@fosstodon.org] &bull; oliver@oliversturm.com
]

.title-logo[
<img src="template/devexpress.png" id="devexpress" alt="DevExpress">
]
