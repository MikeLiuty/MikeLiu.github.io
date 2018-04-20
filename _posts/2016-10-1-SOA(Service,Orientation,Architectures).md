---
layout:     post
title:      SOA(Service Oriented Architecture)
date:       2016-10-1 15:31:19
summary:    A introduction of SOA
categories: New Area
---
I found a blog named "How is Business Process Management related to Service Oriented Architecture?", which explained the relationship between SOA and business process management. In the article, the author described the relationship as twins, similar and different at the same time.

## Definitions.

1. Business Process Management is the organization of business capabilities (people, process, technology, and data) so that common mechanisms can be discovered, simplified, and improved.  The result: a simpler, more efficient and more rational portfolio of processes.  This reduces cost and increases business agility.
2. Service Oriented Architecture is the organization of technical capabilities (activities, events, documents, and data) so that common services can be discovered, simplified, and improved.  The result: a simpler, more efficient and more rational portfolio of services.  This reduces cost and increases business agility.

From the definitions, we can see that the difference are the mean target object, BPM is meanly for people, technologies, and discover mechanisms. Oppositely, SOA is for activities, events, and discover more services. But the main purpose is same, which are simpler the process, improve efficiency and reduce cost.

Their "parents".

They both are for data and event. The common data model is important, and it should be as slender as possible. Also, business event ontology is required for both of them since they need same starting event and same ending event. Before design BPM or SOA, we need the data and event "grow" a while until we understand them well, otherwise the design will not be integrity.

https://blogs.msdn.microsoft.com/nickmalik/2007/07/26/how-is-business-process-management-related-to-service-oriented-architecture/

## ITIL are doing three main tasks for SOA

![image](http://www.ebizq.net/blogs/bethgb/SOA%20%E2%80%93%20ITIL%20Governance%20Synergy.jpg)

* ITIL focuses on delivery IT service, which means focuses on service itself. The service includes software, infrastructure, and more. "this may be the best representation of a governance framework simply because it focuses on service delivery from a purely service-centric perspective and not a technological perspective." The service could be misunderstood or forgotten sometimes in SOA, but ITIL can perfectly fix it.
* The heart of ITIL is the concept of service strategy, which focus on value creation. "ITIL’s focus on value creation means that the first step in service delivery is starting from a strategic viewpoint with no limitations placed on the outcome by past attempts at providing this service." From a reasonable outcome can help to make a more proactive beginning.
* ITIL will design the service by using service design package which encapsulate all the requirements and metrics.

https://www.infoq.com/articles/itil-v3-soa-governance
