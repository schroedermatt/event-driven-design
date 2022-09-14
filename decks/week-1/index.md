
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

![venn](images/w1_convergence_venn.svg)

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

<img src="images/w1_service_graph.svg"  height="600">

Note:
- Making this graph operate requires an in depth look at the nodes and the relationships

---

## Domain Driven Design

===

