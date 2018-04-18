---
layout:     post
title:      Cloud Computing Brief Introduction
date:       2016-09-13 15:31:19
summary:    Cloud Categories and Layers
categories: Techniques
---

## According to the research paper from “Cloud computing and grid computing 360-degree compared”, the Cloud architecture has four layers:

* Fabric layer: contains hardware level resource.
* Unified resource layer: contains resources that have been abstracted/encapsulated.
* Platform layer: provide platform environments and specific tools for developers.
* Application layer: contains the application that runs on clouds.

In addition, the three level services could run on one or multiple layers. I would like to introduce them one by one:

a. Infrastructure as a Service (IaaS): Mostly runs on the layer of Unified Resource Layer, sometimes could be run on the part of Fabric Layer. Normally provide the service of software environment and hardware based on the users need, such as storage and networking. Can be scaled up and down. Examples are Amazon Web Service, Cisco Metapod, and Microsoft Azure.

b. Platform as a Service (PaaS): Provide a completely environment allow developers test and deployment application. The service runs on the platform layer. Example is Apprenda.

c. Software as a Service (SaaS): Provide specific purpose software which remotely accessible consumers. Most SaaS applications can directly on the web browser without any software. The service provides on the layer of application. The examples are Google Apps, salesforces, and Cisco WebEx.

## A totally new business model just service for cloud users and providers, cloud broker.

Cloud broker is an intermediary between the user of the Cloud Computing and the provider of the service. The broker can save consumers’ time and give them the advices of the choice of the cloud vendors. The broker also can analyze the consumers’ business model to give them a good advice of which vendor is the best choice for the specific needs. Even some time, the brokers are able to distribute service across multiple vendors. In addition, the broker may recommend addition service to the consumer. The relationship between Cloud broker, consumer and Cloud Computing provider is non-dispensable. Consumers need professional advices; Brokers need customers, and Cloud computing providers need a platform to make users know more about their services.

## CloudFlare

Many banks such as JP Morgan Chase and Goldman Sachs got attacks for major financial institutions, and they asked for help from CloudFlare. The way they solved the problem was broke the "three handshakes" and built a virtual private network connection, so the client, CloudFlare service, and backend server all have the same session key. At the end of the paper, Prince mentioned many of small business trust CloudFlare more than themselves. And there are 28 of 32 building matter as central exchange point of the internet and there will be more.

Also some article suggested store data in the cloud-based peer-to-peer system rather than store all of them together in a centralized system. By following the rule of peer-to-peer storage method, it can increase the difficulties for the hack. But P2P storage might not good for big companies since they might need to control huge amount data and more parts mains more responsibilities for each of them. Oppositely, it could good enough for small business.

### reference:

* K. W. (2016, February 9). Cloud Computing Trends: 2016 State of the Cloud Survey. Retrieved September 12, 2016, from http://www.rightscale.com/blog/cloud-industry-insights/cloud-computing-trends-2016-state-cloud-survey
 
* Foster, I., Zhao, Y., Raicu, I., & Lu, S. (2008, November). Cloud computing and grid computing 360-degree compared. In2008 Grid Computing Environments Workshop (pp. 1-10). Ieee.
 
* Margaret, R. (2013, September). Cloud broker. Retrieved August 08, 2016, from http://searchcloudprovider.techtarget.com/definition/cloud-broker
 
* IaaS, PaaS, SaaS (Explained and Compared) - Apprenda. (n.d.). Retrieved August 08, 2016, from https://apprenda.com/library/paas/iaas-paas-saas-explained-compared/
 
* Cloud Services Brokerage Company List and FAQ. (2013, March 15). Retrieved August 08, 2016, from http://talkincloud.com/cloud-services-broker/cloud-services-brokerage-company-list-and-faq
