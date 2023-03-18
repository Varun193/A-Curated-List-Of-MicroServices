# awesome-microservice
A curated list of Microservice resources

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.
## Philosophy of  Microservice

### Origin of Microservice

* [Microservices from Martin Fowler](http://martinfowler.com/articles/microservices.html)
* [Microservices from Martin Fowler In Chinese](http://blog.csdn.net/wurenhai/article/details/37659335)


### Architectural Patterns(similar to book software-architecture-patterns from O`REILLY )

#### Core patterns

* [Monolithic architecture from Chris Richardson](http://microservices.io/patterns/monolithic.html)
* [Microservices architecture from Chris Richardson](http://microservices.io/patterns/microservices.html)
* [API Gateway from Chris Richardson](http://microservices.io/patterns/apigateway.html)
* [Bounded Context from Martin Fowler](http://martinfowler.com/bliki/BoundedContext.html)
* [Circuit Breaker from Martin Fowler](http://martinfowler.com/bliki/CircuitBreaker.html)
* [Circuit Breaker ~ netflix](http://doc.akka.io/docs/akka/snapshot/common/circuitbreaker.html)
* [Circuit Breaker open/closed/half-open](https://blog.bitsrc.io/circuit-breaker-pattern-in-microservices-26bf6e5b21ff)
* [Circuit Breaker fallback implementation](https://www.credera.com/insights/circuit-breaker-pattern-in-spring-boot)
* [Hystrix Circuit Breaker — How To Set It Up Properly](https://medium.com/@darekmydlarz/hystrix-circuit-breaker-how-to-set-it-up-properly-84c75cfbe3ee#:~:text=The%20default%20value%20is%205,opened%20for%20consecutive%205%20seconds.)
* [How to Use Feign Client in Spring Boot](https://javatodev.com/how-to-use-feign-client-in-spring-boot/#comments)
* [Feign Client to Call Another Microservice](https://www.appsdeveloperblog.com/feign-client-to-call-another-microservice/)
* [Introduction to Spring Cloud Load Balancer](https://www.baeldung.com/spring-cloud-load-balancer#:~:text=Load%20balancing%20is%20the%20process,instance%20to%20send%20its%20request.)
* [API Gateway Pattern](https://medium.com/design-microservices-architecture-with-patterns/api-gateway-pattern-8ed0ddfce9df)
* [Spring Cloud Gateway offical doc](https://cloud.spring.io/spring-cloud-gateway/reference/html/)
* [Microservices Config Server — Centralized Configuration with Spring Cloud](https://medium.com/@ijayakantha/microservices-centralized-configuration-with-spring-cloud-f2a1f7b78cc2)

#### Deployment patterns

* [Multiple service instances per host](http://microservices.io/patterns/deployment/multiple-services-per-host.html)
* [Service instance per host](http://microservices.io/patterns/deployment/single-service-per-host.html)
* [Service instance per VM](http://microservices.io/patterns/deployment/service-per-vm.html)
* [Service instance per Container](http://microservices.io/patterns/deployment/service-per-container.html)

#### Service discovery


* [Client-side discovery from Chris Richardson](http://microservices.io/patterns/client-side-discovery.html)
* [Server-side discovery from Chris Richardson ](http://microservices.io/patterns/apigateway.html)
* [Service registry from Chris Richardson](http://microservices.io/patterns/apigateway.html)
* [Self registration from Chris Richardson](http://microservices.io/patterns/apigateway.html)
* [3rd party registration from Chris Richardson](http://microservices.io/patterns/apigateway.html)
* [Service discovery with consul & etcd](https://aws.amazon.com/blogs/compute/service-discovery-via-consul-with-amazon-ecs/)



### Debates between advantage and disvantage

* [ PaaS vs. IaaS for Microservices Architectures: Top 6 Differences](http://blog.altoros.com/microservices-architectures-paas-vs-iaas-top-6-differences.html)
* [Microservices Are Not a free lunch!](http://contino.co.uk/microservices-not-a-free-lunch/)
* [The Hidden Costs of Microservices by Justin Leitgeb](http://www.stackbuilders.com/news/the-hidden-costs-of-microservices)


## Books About Microservice

* [Antifragile: Things That Gain from Disorder](http://www.amazon.com/gp/product/0812979680)
* [The Black Swan](http://www.amazon.com/The-Black-Swan-Improbable-Robustness/dp/081297381X)
* [Implementing Domain-Driven Design](http://www.amazon.co.uk/Implementing-Domain-Driven-Design-Vaughn-Vernon/dp/0321834577)
* [Building Micro Services - Sam Newman](http://www.amazon.co.uk/Building-Microservices-Sam-Newman/dp/1491950358)
* [Building Micro Services - Sam Newman Downloadable preview edition](http://nginx.com/wp-content/uploads/2015/01/Building_Microservices_Nginx.pdf)
* [Antifragile Software - Russ Miles](https://leanpub.com/antifragilesoftware)
* [software-architecture-patterns from O`REILLY in English](http://www.oreilly.com/programming/free/files/software-architecture-patterns.pdf)
* [software-architecture-patterns from O`REILLY in Chinese](https://raw.githubusercontent.com/bboyfeiyu/android-tech-frontier/master/software-architecture-patterns/%E8%BD%AF%E4%BB%B6%E6%9E%B6%E6%9E%84%E6%A8%A1%E5%BC%8F.pdf)
* [Production Ready Microservices - Susan J. Fowler](http://shop.oreilly.com/product/0636920053675.do)
* [Microservices in Production - Susan J. Fowler (free ebook)](http://www.oreilly.com/programming/free/microservices-in-production.csp)
* [Microservices with Docker, Flask, and React - Michael Herman](https://testdriven.io/)

## Online Videos and Presentations

* [Microservices - Martin Fowler](https://www.youtube.com/watch?v=wgdBVIX9ifA)
* [State of the Art in Microservices - Adrian Cockcroft](https://www.youtube.com/watch?v=nMTaS07i3jk)
* [Deploying And Testing Microservices - Sam Newman](https://www.youtube.com/watch?v=FotoHYyY8Bo)
* [Microservices Anti-Patterns](https://www.youtube.com/watch?v=I56HzTKvZKc)
* [Practical Considerations For Microservice Architectures - Sam Newman](https://www.youtube.com/watch?v=5NOaUK74Jt4)
* [Migrating to Microservices - Adrian Cockcroft](http://www.infoq.com/presentations/migration-cloud-native)
* [Microservices at Netflix](https://www.youtube.com/watch?v=LEcdWVfbHvc)
* [Microservices: Adaptive Systems for Innovative Organizations](https://www.youtube.com/watch?v=GDVcUM5wbxU)
* [Pros and Cons of a MicroServices Architecture talk at AWS ReInvent](http://www.slideshare.net/stonse/pros-and-cons-of-a-microservices-architecture-talk-at-aws-reinvent)
* [Chris Richardson: Developing event-driven microservices with event sourcing and CQRS](https://www.youtube.com/watch?v=9XhBPFjD0hw)
* [Microservices  on  InfoQ website](http://www.infoq.com/cn/microservice)
*[API gateway microservices](https://www.solo.io/topics/api-gateway/api-gateway-microservices/)

## Events

## Best Practises from Industry

### Articles and Blogs

* [ service principles from Yelp-A guide to service principles at Yelp for our service oriented architecture](https://github.com/Yelp/service-principles)
* [Adopting Microservices at Netflix serial 1: It’s Time to Move to a Four-Tier Application Architecture](http://nginx.com/blog/time-to-move-to-a-four-tier-application-architecture/)
*  [Adopting Microservices at Netflix serial 2: Adopting Microservices at Netflix: Lessons for Architectural Design](http://nginx.com/blog/microservices-at-netflix-architectural-best-practices/)
* [Adopting Microservices at Netflix serial 3: Adopting Microservices at Netflix: Lessons for Team and Process Design ](http://nginx.com/blog/adopting-microservices-at-netflix-lessons-for-team-and-process-design/)
* [Microservices - A Reality Check(point)by Andrew Harmel-Law — on Development, Microservices, Java, Camel, NetflixOSS, Spring 17 Oct 2014](http://capgemini.github.io/architecture/microservices-reality-check/)
*   [Idempotency is not a Medical Condition - Pat Helland](http://queue.acm.org/detail.cfm?id=2187821)
*   [Martin Fowler - You Must Be This Tall To Use Microservices](http://martinfowler.com/bliki/MicroservicePrerequisites.html)
*   [Adrian Cockroft - Migrating to Microservices](http://qconlondon.com/dl/qcon-london-2014/slides/AdrianCockcroft_MigratingToMicroservices.pdf)
*   [Michael Nygaard - Stability Patterns, and Ant-Patterns…](http://www.slideshare.net/justindorfman/stability-patterns-presentation)
*   [Eric Evans - Domain Driven Design: Tackling Complexity in the Heart of Software](http://www.amazon.co.uk/Domain-driven-Design-Tackling-Complexity-Software/dp/0321125215)
*   [Uncle Bob - Microservices and Jars](http://blog.cleancoder.com/uncle-bob/2014/09/19/MicroServicesAndJars.html)
*   [Steve Jones - Microservices - Money for old rope or re-badging SOA for the cool kids](http://service-architecture.blogspot.co.uk/2014/03/microservices-money-for-old-rope-or-re.html)
*   [Sonu K. Meena - How to build microservice?](https://www.linkedin.com/pulse/how-build-microservice-sonu-meena)
*	[Introduction to Microservices](http://nginx.com/blog/introduction-to-microservices/)
*	[Building Microservices: Using an API Gateway ](http://nginx.com/blog/building-microservices-using-an-api-gateway/)
*   [Building Microservices: Inter-Process Communication in a Microservices Architecture](https://www.nginx.com/blog/building-microservices-inter-process-communication/)
*	[Service Discovery in a Microservices Architecture ](https://www.nginx.com/blog/service-discovery-in-a-microservices-architecture/)
*	[Event-Driven Data Management for Microservices](https://www.nginx.com/blog/event-driven-data-management-microservices/)
*	[0 to Microservice in 5 minutes with Go, go-microservice-template and Minke](http://nicholasjackson.github.io/microservices/go/building-and-testing-microservices-part1/)
*	[IS REST BEST IN A MICROSERVICES ARCHITECTURE?](http://capgemini.github.io/architecture/is-rest-best-microservices/)

### Example Projects

* [Chris Richardson has published the example code for his QCONSF talk on building event-driven microservices. The example microservices-based application is built using event sourcing and command query responsibility separation (CQRS). There are currently two versions of the application - Scala/Spring and Java/Spring - with others to follow. Take a look!](https://github.com/cer/event-sourcing-examples)
* [Building Microservices with Open Source Technologies by Suresh Balla](http://www.developer.com/open/building-microservices-with-open-source-technologies.html)
* [NetflixOSS Acme Air Sample and Benchmark](https://github.com/aspyker/acmeair-netflix/tree/astyanax)
* [ Experiments With Docker For Acme Air Dev](http://ispyker.blogspot.tw/2014/01/experiments-with-docker-for-acme-air-dev.html)
* [CRUD using Spring Data Rest and AngularJS using Spring Boot](http://www.programming-free.com/2014/07/spring-data-rest-with-angularjs-crud.html)
* [ microservice of convert html to pdf](https://github.com/shouldbee/docker-html2pdf)
* [ Microservices tests with RabbitMQ and Docker](https://github.com/codescrum/microservice-tests-01)
* [ A demonstration of a Microservices architecture using Spring Boot, Docker and Fig.](https://github.com/boonen/microservices-demo)
* [ Experiments with microservices and Docker](https://github.com/mboeh/oignon-exp)
* [ Example code for my building and deploying microservices with event sourcing, CQRS and Docker presentation](https://github.com/cer/event-sourcing-examples)
* [ Some idea of how micro-services can be handled using SkyDNS, SkyDock and Docker](https://github.com/criolit/docker-microservices)
* [ This is a presentation on Docker held at FINN Architecture Summit - Service Orientation on 2015.01.21.](https://github.com/finn-no/Docker-and-Microservices)
* [ Dummy project to try out new tools for me like Docker and RabbitMQ](https://github.com/jordi-chacon/dummy-dockerized-microservices)
* [ OAuth2 authentication server designed to work in a docker-based microservices architecture.](https://github.com/nielskrijger/auth-server)

### MicroServices interview Questions
* [50 Microservices Design and Architecture Interview Questions for Experienced Java Programmers](https://medium.com/javarevisited/50-microservices-interview-questions-for-java-programmers-70a4a68c4349)

### Library and Tools



## People

* James Lewis
* Sam Newman
* Russ Miles
* Martin Fowler
* Chris Richardson
* Daniel Woods

## Discussion Group

* [Join the microservices google group](https://groups.google.com/forum/#!forum/microservices)


Many thanks to [Owain Lewis](https://github.com/owainlewis/microservice-design)
and [Chris Richardson](http://microservices.io/index.html) [i5ting](https://github.com/i5ting)


##  Notes :



##  Domain Driven Design​​ & Microservices: An Approach to Modeling Microservices

 
​​Domain-Driven Design (DDD for short) and design patterns accompyning it has been used in the industry for over a decade to tackle complexity of enterprise software development. Domain-Driven Design concepts were introduced by Eric Evans in the seminal work in his book Domain-Driven Design: Tackling Complexity in the heart of Software​, published in 2003.​ DDD principles are particularly well suited for Microservices Architrcture style. The DDD principles provide an approach to decompose an application and identify or right size a microservice. 

DDD is an approach to software development for complex needs by connecting the implementation to an evolving model [2][5]. The premise of domain-driven design is the following:
•placing the project's primary focus on the core domain and domain logic;

•basing complex designs on a model of the domain;

•initiating a creative collaboration between technical and domain experts to iteratively refine a conceptual model that addresses particular domain problems.​


Domain-driven design is not a technology or a methodology. DDD provides a structure of practices and terminology for making design decisions that focus and accelerate software projects dealing with complicated domains [2] [5]. Let's define term domain before we look at DDD design patterns that help in building an application using Microservices Architecture.





Domain: It is a sphere of knowledge and activity around which the application logic revolves. It is what an organization does and the world it does it in. 


​​​​


DDD includes a set of design patterns that ​enable domain experts and software development teams to tackle complexity. The key patterns that apply to Microservices Architecture style are:



• Bounded Context​: ​Bounded Context is a central pattern in Domain-Driven Design. It is the focus of DDD's strategic design section which is all about dealing with large models and teams. DDD deals with large models by dividing them into different Bounded Contexts and being explicit about their interrelationships. 

• Ubiquitos Language: It is the practice of building up a common, rigorous language between developers and users, to connect all the activities of the team with the software. Every term has a precise and unambiguous definition​. This language should be based on the Domain Model used in the software. It it used consistently in speech, documentation, diagrams and code.

• ​Aggregate: It is a cluster of domain objects that can be treated as a single unit. An aggregate will have one of its component objects be the aggregate root. Any references from outside the aggregate should only go to the aggregate root. The root can thus ensure the integrity of the aggregate as a whole. Aggregates are the basic element of transfer of data storage - you request to load or save whole aggregates. Transactions should not cross aggregate boundaries.​​

•​Entitities​: are objects which have an identity which remains the same throughout the states of the software. Entities must be distinguished from other similar objects having the same attributes by unique Identity (e.g. Joe's Bank Account). Entities in DDD have behavior (think of them as Business Objects with attributes and behavior in a domain).


##  ​B​ounded Context, Aggregates and Microservices

​ 

Context: A context means a specific responsibility. 


Bounded Context: A bounded context means that responsibility is enforced with explicit boundaries.


The core idea of Bounded Context is that any given domain consists of multiple bounded contexts, and residing within each are things (doman model & business logic/capability/functionality) that do not need to be communicated outside as well as things (domain model) that are shared externally with other bounded contexts. Each bounded context has an explicit interface, where it decides what models to share with other contexts, from Sam Newman in [7]. ​



Given, a Bounded Context is “a specific responsibility enforced by explicit boundaries.”​, if you want information from a bounded context, or want to make requests of functionality within bounded context, you communicate with its explicit boundary using models. 


Bounded Context is widely considered to be a starting point and prime candidate for a microservice in microservice architecture:


•​“One micro-service should cover one bounded context”  -  Vaughn Vernon.​

•Sam Newman in [7] in chapter 3 - How to Model Services - uses a Bounded Context as the starting point for modeling a microservice


Key DDD principles of Ubiquitos Language, Aggregates, Aggregate Root and Entities - all reside and have a specific meaning within a Bounded Context.​ 

Given microservices are organized around business capability, a Bounded Context is an excellent approach to modeling a microservice. While Bounded Context decouples domain logic, microservices decouple the technical decisions, performance, scalability, availability, robustness, security and so on. Since a Bounded Context has well-defined responsibility and explicit interface, it natually leads to less coordination and synchronization between teams and increases team velocity - all benefits very well-aligned with Microservices Architecture style.


Bounded contexts contain clusters of different data entities and processes that can control a significant area of functionality such as order fulfilment or inventory in an online ecommerce store. Hence depending on the domain, they can actually be quite large. A more finely grained DDD unit is the aggregate which describes a cluster of objects and behaviours that can be treated as a single cohesive unit. An aggregate is regarded as the basic unit of data transfer – a classic example is an order that contains a bunch of line items.​​ 

Aggregates [2] [4] have following properties:

•An Aggregate is a cluster of Entities and Value objects i.e. an Object Graph. Each aggregate is treated as one single unit.

•Aggregate boundary is transactional boundary i.e. Entities in an Aggregate are updated in one transaction.

•Each Aggregate has one root entity know as the Aggregate Root.

•The root identity is global, the identities of entities inside are local.

•External objects may have references only to root entity.

•Internal objects cannot be changed outside the Aggregate.

• An Aggregate can be modified from outside only via Aggregate Root.

•In distributed environment, keep an aggregate together on one server. Allow different aggregates to be distributed among nodes.


Given that an aggregate is a cohesive unit, it can be a reasonable indicator of the smallest meaningful scope for a microservice. It will be difficult to split an aggregate across service boundaries without compromising service autonomy.  Thus Aggregates also serve as an excellent boundary for a microservice. 





Choosing Aggregate as boundary of a microservice can lead to a very granular microservice and result in following problems:


•Tends to give rise to anaemic services that do little more than expose CRUD-style methods, degenerates to grouping data entities together rather than encapsulating business capabilities
•Can lead to a very “chatty” service infrastructure where the majority of processing time is spent on remote calls between services


Aggregate as a boundary for a microservice is useful in domains where a bounded context is large or anytime you find a bounded context that is very large and there is a need to find a smaller boundary for a microservice. 







## ​​​​Best Practice​

A microservice i.e. single deployable unit or service should be no bigger than a bounded context, but no smaller than an aggregate. 
Start with relatively broad service boundaries to begin with, refactoring to smaller ones as time goes on.

