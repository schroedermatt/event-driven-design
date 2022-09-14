
# Week 1
#### Introduction to Event-Driven Design

===

### Readings

* Building Event-Driven Microservices
    - Preface (pg. xiii)
    - Chapter 1: Why Event-Driven Microservices (pg. 1-20)

--

_Total Pages: 21_

---

> The tools that we use shape and influence our inventions significantly.

Note:
Event driven architectures are made possible by a whole host of technologies that have only recently become readily available.

* Distributed, fault-tolerant, high-capacity, and high-speed event brokers underpin the architectures.

===

![venn](decks/week-1/assets/w1_convergence_venn.svg)

Note:
- This demand coincides the rise of containerization and availability of compute resources which has simplified hosting, scaling, and management of hundreds/thousands microservices

===

## Event Driven Services

* Event-based communication is not new.
* Processing demanding volumes of data at scale in near-real time is new.

Note:
* This style of design has existed for many years under different names 
* Systems produce & consume events (multiple times)
* Events are consumed and NOT destroyed

===

## Identifying Service Boundaries

- Small, purpose built (2-4 week build time)
- Fits (conceptually) in 1 engineer's head

===

<img src="decks/week-1/assets/w1_service_graph.svg"  height="600">

Note:
- Making this graph operate requires an in depth look at the nodes and the relationships

---

## Domain Driven Design

===

> There is no sense in talking about the solution before we agree on the problem, and no sense talking about the implementation steps before we agree on the solution.

_-Efrat Goldratt-Ashlag_

Note:
- Problem: what's the _business domain_? What are the _business goals_? What is the strategy to achieve them?
- _Ubiquitous language_ helps gain a deep understanding of the domain.
- Manage the complexity by breaking it apartinto _bounded contexts_. Each implements a single model the of domain, aimed at solving a specific problem.

- DDD p.267

===

### Types of Subdomains

<img src="decks/week-1/assets/w1_subdomains_table.svg">

Note:
- DDD p.267

===