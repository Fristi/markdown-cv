---
layout: cv
title: Mark de Jong
---
# Mark de Jong
My name is Mark de Jong and I am a freelance full stack developer. Specialised in
web applications and high performance back end systems. Most notable the past
few years is my Scala experience (4 years professionally), Haskell experience,
contributions to open source (see projects), knowledge about domain driven design
and functional programming.

In my professional career I have worked at various companies doing diverse projects. Ranging from
from scratch CMS implementations, community sites, improving performance of existing software,
designing high performance game backends, financial systems to single page web apps and mobile
apps.

## Currently

### Freelance Scala Software Developer @ DHL (The Netherlands)



## Previous

### Software Developer at Lunatech
`Dec 2016 - June 2018`

Fulfilments:
- Scala Developer at several projects (see below)
- Helping recruitment with introduction and technical interviews

**Project: Veon** - One of the lead developers at the DFS (digital financial services) team at Veon. The
team is responsible to make mobile payments possible. Veon is the 6th largest telecom provider of the
world. Mostly active in Russia, Georgia, Italy, etc.

I wrote a Avro mapping library which allowed you to use a EDSL to map case classes to Avro
encoders/decoder/schema generator. The library also supports primitive data types in Scala and allows you to imap or pmap them. Once you’ve defined a Avro[A] for a type, you can reuse these
definitions to build up bigger types. The combinators imap and pmap makes it easy to introduce
support for new data types, while this is verbose in Avro4s. Also the DSL provides a way of describing a
schema in type-safe and terse fashion instead of typing JSON files. Also Avro4s derives schema’s,
encoders and decoders “magically”. While this is nice, it can become unwieldy when you have a
nested type graph. I believe it’s better to explicitly map your data types, so the cognitive process of
defining a schema is part of your job instead of a magic macro. This will become important when you
want to enforce full compatibility of your schema’s

My responsibility was also to get requirements, translate specs to code, refine stories, helping to
recruit new developers, organize workshops, architect/design new microservices and spread work
amongst the team.

Stack: Scala, Scalaz, PlayFramework, Akka, SBT, Postgres, Kafka, Avro, Slick.

**Project: ING** - Lead developer for a new Approval Workflow API. The user could make a Approval,
which needed to be approved by multiple users. There were multiple workflows possible, like
two-eyes, layered, etc. We wrote the microservice in a tagless final manner.
Also I wrote a Cassandra client library on top of the existing Supernova library (which uses the datastax
driver with some custom code). It allowed you to map case classes to Cassandra encoders/decoders.
We used plain CQL queries with a string interpolator, by doing that we could cache the queries as
prepared statements, boosting the performance. The design was inspired by Doobie.
Also my responsibility as lead developer was to come to consensus regarding requirements with the
business and architects, translate specs to code, refine stories, helping to recruit new developers and
spread work amongst the team in collaboration with the product owner.
Stack: Scala, Cats, Finch, SBT, Cassandra, Kafka.

### Software Developer at ZorgDomein Nederland B.V.
`November 2015 - April 2016 (6 months)`

Fulfilments: Extension of existing software

Stack: Scala/Spray/Akka/Oracle/Angular/SBT


### Software Developer at Q42
`March 2014 - November 2015 (1 year 9 months)`
Fulfillments: Development of software/websites, performance analysis/improvement and code
reviews
**Project: Malmberg BAPS** - Developing a CMS for Malmberg (a dutch educational publisher). Malmberg
uses this CMS to construct digital school boards, interactive practice sessions, games, etc. Stack: Scala,
Mongo, PlayFramework, SBT and Akka

### Software Engineer at Mirabeau
`May 2012 - February 2014 (1 year 10 months)`
Fulfillments: Development of software/websites, release software/websites, gave a workshop about
unit testing, organized a casus event sourcing/DDD and arranged continuous integration: Bamboo and
TeamCity
**Project: Theodoor Gilissen** - A personalized environment where customers could look up their invoices
and purses. Stack: C#, WCF, StructureMap, ASP.NET Webforms

***Project: SkillsKompas** - A rich web-application which models the 'competence domain' at companies.
You can define functions, task, competences, educations, etc. These aggregates of competences are
related to each other. With this data we can give the user advice what the next step should be in their
career (function, education, etc). Stack: Java, Spring, GWT and Hibernate.

### Software Developer at Ambrero Software B.V.
`March 2011 - April 2012 (1 year 2 months)`
Fullfillments: development of complex software/websites and documentation of the software in UML
via Confluence

**Project: Gatso Xilium** - A web application which allows you to process traffic violations. Stack:
Java,Hibernate, JBoss Seam, MySQL and ActiveMQ.

**Project: Gatso Alesi** - A web application which allows you to process traffic violations. Stack: PHP,
SOAP, BackboneJs, jQuery and MySQL.


## Education

`1654-1660`
__The King's School, Grantham.__

`June 1661 - now`
__Trinity College, Cambridge__

- Sizar

`1667 - death`
__Trinity College, Cambridge__

- Fellow



## Awards

`2012`
President, *Royal Society*, London, UK

Associate, *French Academy of Science*, Paris, France



## Publications

<!-- A list is also available [online](http://scholar.google.co.uk/citations?user=LTOTl0YAAAAJ) -->

### Journals

`1669`
Newton Sir I, De analysi per æquationes numero terminorum infinitas. 

`1669`
Lectiones opticæ.

etc. etc. etc.

### Patents

`2012`
Infinitesimal calculus for solutions to physics problems, [SMBC](http://www.techdirt.com/articles/20121011/09312820678/if-patents-had-been-around-time-newton.shtml) patent 001


## Occupation

`1600`
__Royal Mint__, London

- Warden
- Minted coins

`1600`
__Lucasian professor of Mathematics__, Cambridge University



<!-- ### Footer

Last updated: May 2013 -->


