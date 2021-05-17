# (CC0101EN) Introduction to Cloud Computing

### After completing this course, you will be able to: 

*   Define cloud computing and explain its essential characteristics, evolution, and business case for cloud adoption.
*   Explain how some of the emerging technologies, such as the Internet of Things, Artificial Intelligence, Blockchain, and Analytics, are being supported by the cloud.
*   Define the cloud service models (IaaS, PaaS, SaaS) and deployment models (Public, Private, Hybrid).
*   Describe the concepts and components of cloud infrastructure such as virtualization, virtual machines, bare metal servers, and containers.
*   Explain different cloud storage models including Direct Attached, File, Block, Object Storage, and CDNs.
*   Explain emergent trends related to cloud computing including Hybrid Multicloud, Microservices, Serverless computing, Cloud Native, DevOps, and Application Modernization.
*   Describe the concepts in cloud security and how organizations in different industries are benefiting from cloud.
*   List the job roles and career opportunities available in cloud computing.
*   Create an account on a IBM Cloud platform and deploy a cloud service.

## Module 1 - Introduction

In this module you will learn about the definition and essential characteristics of cloud computing. You will learn about the evolution of cloud computing and the factors that organizations need to consider while creating their cloud strategy. You will become familiar with some key cloud service providers and the services they offer. At the end of the module, you will learn how to create an account on a public cloud platform.
Learning Objectives

After completing this module, you will be able to:

*    Define cloud computing
*    Describe the essential characteristics of cloud computing
*    Briefly recount the history and evolution of cloud computing
*    Describe the key considerations that organizations can use as a guide while creating their cloud strategy
*    Describe the key cloud service providers and their services
*    Create an account on a public cloud platform

Let’s start with understanding the _five_ essential characteristics of the cloud—which include:

1. _On-demand Self-service_, the 1st characteristic, means that you get access to cloud resources such as the processing power, storage, and network you need, using a  simple interface, without requiring human interaction with each service provider.
2. The 2nd characteristic, _Broad Network Access_, means that cloud computing resources can be accessed via the network through standard mechanisms and platforms such as mobile phones, tablets, laptops, and workstations.
3. The 3rd characteristic, Resource Pooling, is what gives cloud providers economies of scale, which they pass on to their customers, making cloud cost-efficient.
Using a multi-tenant model, computing resources are pooled to serve multiple consumers; cloud resources are dynamically assigned and reassigned, according to demand, without customers needing to concern themselves with the physical location of these resources.
4. Rapid Elasticity, the 4th characteristic, implies that you can access more resources when you need them, and scale back when you don’t—because resources are elastically provisioned and released.
5. And the 5th characteristic, Measured Service, means that you only pay for what you use or reserve as you go; if you’re not using resources, you’re not paying.
Resource usage is monitored, measured, and reported transparently based on utilization.


## Module 1.b: Definition & Essential Characteristics of Cloud Computing
>Cloud computing, also referred to as “the cloud,” is the delivery of on-demand computing resources—everything from applications to data centers—over the internet on a pay-for-use basis.

>To get a common understanding of cloud computing, let’s start with the US National Institute of Standards and Technology (_NIST_’s) definition of cloud computing.
_NIST_ defines cloud computing as a model for enabling convenient, on-demand network access to a shared pool of configurable computing resources that can be rapidly provisioned and released with minimal management effort or service provider interaction.
 
Examples of computing resources include networks, servers, storage, applications, and services.
This cloud model is composed of five essential characteristics, three deployment models, and three service models.

## Module 1.c: History & Evolution of Cloud Computing
>Cloud computing is an evolution of technology over time.

The concept of cloud computing dates to the 1950s when large-scale mainframes with high-volume processing power became available.

In order to make efficient use of the computing power of mainframes, the practice of time sharing, or resource pooling, evolved.

>Using dumb terminals, whose sole purpose was to facilitate access to the mainframes, multiple users were able to access the same data storage layer and CPU power from any terminal.
>In the 1970s, with the release of an operating system called Virtual Machine (VM), it became possible for mainframes to have multiple virtual systems, or virtual machines, on a single physical node.
>The virtual machine operating system evolved the 1950s application of shared access of a mainframe by allowing multiple distinct compute environments to exist on the same physical hardware.

>Each virtual machine hosted guest operating systems that behaved as though they had their own memory, CPU, and hard drives, even though these were shared resources.
>Virtualization thus became a technology driver and a huge catalyst for some of the biggest evolutions in communications and computing.
>Even 20 years ago, physical hardware was quite expensive.

>With the internet becoming more accessible, and the need to make hardware costs more viable, servers were virtualized into shared hosting environments, virtual private servers, and virtual dedicated servers, using the same types of functionality provided by the virtual machine operating system.
>So, for example, if a company needed ‘x’ number of physical systems to run their applications, they could take one physical node and split it into multiple virtual systems.
>This was enabled by hypervisors.
A hypervisor is a small software layer that enables multiple operating systems to run alongside each other, sharing the same physical computing resources.
A hypervisor also separates the Virtual Machines logically, assigning each its own slice of the underlying computing power, memory, and storage, preventing the virtual machines from interfering with each other.

>So, if, for example, one operating system suffers a crash or a security compromise, the others keep working.
As technologies and hypervisors improved and were able to share and deliver resources reliably, some companies decided to make the cloud’s benefits accessible to users who didn’t have an abundance of physical servers to create their own cloud computing infrastructure.
Since the servers were already online, the process of spinning up a new instance was instantaneous.
Users could now order cloud resources they needed from a larger pool of available resources, and they could pay for them on a per-use basis, also known as Pay-As-You-Go.
>This pay-as-you-go or utility computing model became one of the key drivers behind cloud computing taking off.
The pay-per-use model allowed companies and even individual developers to pay for the computing resources as and when they used them, just like units of electricity.
This allowed them to switch to a more cash-flow friendly OpEx model from a CapEx model.
This model appealed to all sizes of companies, those who had little or no hardware, and even those that had lots of hardware, because now, instead of making huge capital expenditures in hardware, they could pay for compute resources as and when needed.
>It also allowed them to scale their workloads during usage peaks, and scale down when usage subsided.
And this gave rise to modern-day cloud computing.
The impact of the evolution of the cloud has been immense.
In the next training, we will go over some key considerations for cloud adoption.
