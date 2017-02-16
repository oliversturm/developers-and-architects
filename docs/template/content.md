## Developers and Architects

Strategies 2017


> Oliver Sturm &bull; @olivers &bull; oliver@oliversturm.com

<img src="devexpress.png" class="plain" style="background:transparent;opacity:0.7;" alt="DevExpress">&nbsp;&nbsp;<img src="mvp.png" class="plain" style="background:transparent;opacity:0.4;" alt="MVP">

---

## Oliver Sturm

* Training Director at DevExpress
* Consultant, trainer, author, software architect and developer for over 25 years
* Microsoft C# MVP

* Contact: oliver@oliversturm.com

---

## Agenda

Idea: Talk about technology

* Application building blocks
* Services
* Microservices
* Data persistence
* User Interfaces
* Mobile
* Cloud
* Open Source

---

## Application Building Blocks

* What is an "application" made of?
* Terminology check: 
  * Client application
  * Server application
  * Web application
  * Application system
  * Enterprise application

^

## Building Blocks

^

## Terminology: Client Application

^

## Terminology: Server Application

^

## Terminonoly: Web Application

^

## Terminology: Application System

^

## Terminology: Enterprise Application

---

## Services

* Part of most architectural concepts
* SOA?
* Web Services
* "Real-time web?" SignalR? socket.io?

^

## SOA

Remember the four tenets Don Box got excited about?

* Boundaries are explicit 
* Services are autonomous 
* Services share schema and contract, not class
* Service compatibility is determined based on policy 

SOA *resulted* in a very formal understanding of service architecture, which is fortunately not shared by too many architects today.

^

## Web Services

* ASMX -- WSE -- WCF -- WSDL -- SOAP -- Microsoft's world of enormous complexity intended to solve a very simple problem
* RESTful services: the most complicated part is the name
  * URLs and HTTP methods
  * JSON, XML and possibly other data formats, using content negotiation

^

## Real-time Web

* WebSockets and their various ancestors
* Bi-directional communication

---

## Microservices

* How big is a microservice? It depends.
  * Do one "thing" well. What's a "thing"? It depends.
  * Two-pizza team
  * Throwawayable
  * Focus on boundaries and business context, not on lines of code
  

---

## Sources

* This presentation: 
  * https://oliversturm.github.io/developers-and-architects/template

---

## Thank You

Please feel free to contact me about the content anytime.

oliver@oliversturm.com
