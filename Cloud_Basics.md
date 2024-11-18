Cloud computing is a fundamental concept in modern technology. Here's an overview of the basics to get you started:

## 1. What is Cloud Computing?
Cloud computing delivers computing services (e.g., servers, storage, databases, networking, software) over the internet, commonly known as "the cloud."
It enables on-demand access to resources without direct management of hardware.
Cloud services also expand the traditional IT offerings to include things like Internet of Things (IoT), machine learning (ML), and artificial intelligence (AI).
If you need to increase your IT infrastructure rapidly, you don’t have to wait to build a new datacenter—you can use the cloud to rapidly expand your IT footprint.
- Computing power: GB of RAM, Processor
- Storage: Volume of data to be stored (hard drives)
## 2. Key Characteristics
* On-demand self-service: Users can provision resources as needed without human interaction.
* Broad network access: Services are accessible from anywhere via the internet.
* Resource pooling: Multiple users share resources, which are dynamically allocated.
* Scalability: Resources can scale up or down based on demand.
* Measured service: Pay-as-you-go pricing based on usage.
## 3. Types of Cloud Deployment Models
* Public Cloud: Resources are owned and operated by third-party providers and shared among multiple users (e.g., AWS, Azure, Google Cloud). With a public cloud, anyone that wants to purchase cloud services can access and use resources. The general public availability is a key difference between public and private clouds.
  Public Cloud Use Cases:
  - Hosting web applications.
  - Development and testing environments.
  - Big Data analytics.
  - Startups needing rapid scalability.
* Private Cloud: Dedicated resources for a single organization, either on-premises or hosted. Private cloud provides much greater control for the company and its IT department. However, it also comes with greater cost and fewer of the benefits of a public cloud deployment.
  Private Cloud Use Cases:
  - Regulatory compliance requirements (e.g., healthcare, banking).
  - Handling sensitive workloads.
  - Organizations with predictable workloads.
* Hybrid Cloud: Combines public and private clouds for flexibility and optimized workloads. Hybrid cloud can be used to provide an extra layer of security. For example, users can flexibly choose which services to keep in public cloud and which to deploy to their private cloud infrastructure.
  Hybrid Cloud Use Cases:
  - Disaster recovery and business continuity.
  - Workload balancing between on-prem and cloud.
  - Temporary capacity increases.
* Multi-cloud
A fourth, and increasingly likely scenario is a multi-cloud scenario. In a multi-cloud scenario, you use multiple public cloud providers. Maybe you use different features from different cloud providers. Or maybe you started your cloud journey with one provider and are in the process of migrating to a different provider. Regardless, in a multi-cloud environment you deal with two (or more) public cloud providers and manage resources and security in both environments.
## 4. Cloud Service Models
* Infrastructure as a Service (IaaS):
  Provides virtualized computing resources like servers and storage.
  Example: Amazon EC2, Google Compute Engine.
* Platform as a Service (PaaS):
  Provides a platform for developers to build applications without worrying about infrastructure.
  Example: Google App Engine, Azure App Services.
* Software as a Service (SaaS):
  Delivers software applications over the internet.
  Example: Gmail, Salesforce, Microsoft Office 365.
## 5. Benefits
* Cost savings (no upfront hardware investment).
* Increased efficiency and productivity.
* Flexibility and scalability.
* Enhanced collaboration through remote accessibility.
## 6. Challenges
* Security and data privacy concerns.
* Downtime and internet dependency.
* Potential vendor lock-in.
## 7. Popular Cloud Providers
* Amazon Web Services (AWS): Leading provider with a vast range of services.
* Microsoft Azure: Strong integration with Microsoft products.
* Google Cloud Platform (GCP): Focused on data and machine learning solutions.
## Shared responsibility model
Start with a traditional corporate datacenter. The company is responsible for maintaining the physical space, ensuring security, and maintaining or replacing the servers if anything happens. The IT department is responsible for maintaining all the infrastructure and software needed to keep the datacenter up and running. They’re also likely to be responsible for keeping all systems patched and on the correct version.

With the shared responsibility model, these responsibilities get shared between the cloud provider and the consumer. Physical security, power, cooling, and network connectivity are the responsibility of the cloud provider. The consumer isn’t collocated with the datacenter, so it wouldn’t make sense for the consumer to have any of those responsibilities.

At the same time, the consumer is responsible for the data and information stored in the cloud. (You wouldn’t want the cloud provider to be able to read your information.) The consumer is also responsible for access security, meaning you only give access to those who need it.

Then, for some things, the responsibility depends on the situation. If you’re using a cloud SQL database, the cloud provider would be responsible for maintaining the actual database. However, you’re still responsible for the data that gets ingested into the database. If you deployed a virtual machine and installed an SQL database on it, you’d be responsible for database patches and updates, as well as maintaining the data and information stored in the database.

With an on-premises datacenter, you’re responsible for everything. With cloud computing, those responsibilities shift. The shared responsibility model is heavily tied into the cloud service types (covered later in this learning path): infrastructure as a service (IaaS), platform as a service (PaaS), and software as a service (SaaS). IaaS places the most responsibility on the consumer, with the cloud provider being responsible for the basics of physical security, power, and connectivity. On the other end of the spectrum, SaaS places most of the responsibility with the cloud provider. PaaS, being a middle ground between IaaS and SaaS, rests somewhere in the middle and evenly distributes responsibility between the cloud provider and the consumer.
## Consumption-based model
When comparing IT infrastructure models, there are two types of expenses to consider. Capital expenditure (CapEx) and operational expenditure (OpEx).

CapEx is typically a one-time, up-front expenditure to purchase or secure tangible resources. A new building, repaving the parking lot, building a datacenter, or buying a company vehicle are examples of CapEx.

In contrast, OpEx is spending money on services or products over time. Renting a convention center, leasing a company vehicle, or signing up for cloud services are all examples of OpEx.

Cloud computing falls under OpEx because cloud computing operates on a consumption-based model. With cloud computing, you don’t pay for the physical infrastructure, the electricity, the security, or anything else associated with maintaining a datacenter. Instead, you pay for the IT resources you use. If you don’t use any IT resources this month, you don’t pay for any IT resources.

This consumption-based model has many benefits, including:

No upfront costs.
No need to purchase and manage costly infrastructure that users might not use to its fullest potential.
The ability to pay for more resources when they're needed.
The ability to stop paying for resources that are no longer needed.
With a traditional datacenter, you try to estimate the future resource needs. If you overestimate, you spend more on your datacenter than you need to and potentially waste money. If you underestimate, your datacenter will quickly reach capacity and your applications and services may suffer from decreased performance. Fixing an under-provisioned datacenter can take a long time. You may need to order, receive, and install more hardware. You'll also need to add power, cooling, and networking for the extra hardware.

In a cloud-based model, you don’t have to worry about getting the resource needs just right. If you find that you need more virtual machines, you add more. If the demand drops and you don’t need as many virtual machines, you remove machines as needed. Either way, you’re only paying for the virtual machines that you use, not the “extra capacity” that the cloud provider has on hand.
## SLA -Service Level Agreement
Formal agreement between a service provider and customer. Azure is a highly available cloud environment with uptime guarantees depending on the service.
- 99% Availability => Can be unavailable upto 1.68 hrs per week
- 99.99% Availability => Can be unavailable upto 10 mins per week
## Scalability
Another major benefit of cloud computing is the scalability of cloud resources. Scalability refers to the ability to adjust resources to meet demand. If you suddenly experience peak traffic and your systems are overwhelmed, the ability to scale means you can add more resources to better handle the increased demand.

The other benefit of scalability is that you aren't overpaying for services. Because the cloud is a consumption-based model, you only pay for what you use. If demand drops off, you can reduce your resources and thereby reduce your costs.

Scaling generally comes in two varieties: vertical and horizontal. Vertical scaling is focused on increasing or decreasing the capabilities of resources. Horizontal scaling is adding or subtracting the number of resources.
## Vertical scaling
With vertical scaling, if you were developing an app and you needed more processing power, you could vertically scale up to add more CPUs or RAM to the virtual machine. Conversely, if you realized you had over-specified the needs, you could vertically scale down by lowering the CPU or RAM specifications.
## Horizontal scaling
With horizontal scaling, if you suddenly experienced a steep jump in demand, your deployed resources could be scaled out (either automatically or manually). For example, you could add additional virtual machines or containers, scaling out. In the same manner, if there was a significant drop in demand, deployed resources could be scaled in (either automatically or manually), scaling in.
## Reliability
Reliability is the ability of a system to recover from failures and continue to function. It's also one of the pillars of the Microsoft Azure Well-Architected Framework.
The cloud, by virtue of its decentralized design, naturally supports a reliable and resilient infrastructure. With a decentralized design, the cloud enables you to have resources deployed in regions around the world. With this global scale, even if one region has a catastrophic event other regions are still up and running. You can design your applications to automatically take advantage of this increased reliability. In some cases, your cloud environment itself will automatically shift to a different region for you, with no action needed on your part. You’ll learn more about how Azure leverages global scale to provide reliability later in this series.
## Predictability
Predictability in the cloud lets you move forward with confidence. Predictability can be focused on performance predictability or cost predictability. Both performance and cost predictability are heavily influenced by the Microsoft Azure Well-Architected Framework. Deploy a solution built around this framework and you have a solution whose cost and performance are predictable.
## Benefits of security and governance in the cloud
On the security side, you can find a cloud solution that matches your security needs. If you want maximum control of security, infrastructure as a service provides you with physical resources but lets you manage the operating systems and installed software, including patches and maintenance. If you want patches and maintenance taken care of automatically, platform as a service or software as a service deployments may be the best cloud strategies for you.

And because the cloud is intended as an over-the-internet delivery of IT resources, cloud providers are typically well suited to handle things like distributed denial of service (DDoS) attacks, making your network more robust and secure.
## Management of the cloud
Management of the cloud speaks to managing your cloud resources. In the cloud, you can:
- Automatically scale resource deployment based on need.
- Deploy resources based on a preconfigured template, removing the need for manual configuration.
- Monitor the health of resources and automatically replace failing resources.
- Receive automatic alerts based on configured metrics, so you’re aware of performance in real time.
## Management in the cloud
Management in the cloud speaks to how you’re able to manage your cloud environment and resources. You can manage these:
- Through a web portal.
- Using a command line interface.
- Using APIs.
- Using PowerShell.
## Describe Infrastructure as a Service
Infrastructure as a service (IaaS) is the most flexible category of cloud services, as it provides you the maximum amount of control for your cloud resources. In an IaaS model, the cloud provider is responsible for maintaining the hardware, network connectivity (to the internet), and physical security. You’re responsible for everything else: operating system installation, configuration, and maintenance; network configuration; database and storage configuration; and so on. With IaaS, you’re essentially renting the hardware in a cloud datacenter, but what you do with that hardware is up to you.
## Scenarios
Some common scenarios where IaaS might make sense include:
- Lift-and-shift migration: You’re setting up cloud resources similar to your on-prem datacenter, and then simply moving the things running on-prem to running on the IaaS infrastructure.
- Testing and development: You have established configurations for development and test environments that you need to rapidly replicate. You can start up or shut down the different environments rapidly with an IaaS structure, while maintaining complete control.
## Platform as a Service
Platform as a service (PaaS) is a middle ground between renting space in a datacenter (infrastructure as a service) and paying for a complete and deployed solution (software as a service). In a PaaS environment, the cloud provider maintains the physical infrastructure, physical security, and connection to the internet. They also maintain the operating systems, middleware, development tools, and business intelligence services that make up a cloud solution. In a PaaS scenario, you don't have to worry about the licensing or patching for operating systems and databases.

PaaS is well suited to provide a complete development environment without the headache of maintaining all the development infrastructure.
## Scenarios
Some common scenarios where PaaS might make sense include:
- Development framework: PaaS provides a framework that developers can build upon to develop or customize cloud-based applications. Similar to the way you create an Excel macro, PaaS lets developers create applications using built-in software components. Cloud features such as scalability, high-availability, and multi-tenant capability are included, reducing the amount of coding that developers must do.
- Analytics or business intelligence: Tools provided as a service with PaaS allow organizations to analyze and mine their data, finding insights and patterns and predicting outcomes to improve forecasting, product design decisions, investment returns, and other business decisions.
## Software as a Service
Software as a service (SaaS) is the most complete cloud service model from a product perspective. With SaaS, you’re essentially renting or using a fully developed application. Email, financial software, messaging applications, and connectivity software are all common examples of a SaaS implementation.

While the SaaS model may be the least flexible, it’s also the easiest to get up and running. It requires the least amount of technical knowledge or expertise to fully employ.
## Scenarios
Some common scenarios for SaaS are:
- Email and messaging.
- Business productivity applications.
- Finance and expense tracking.

## Public Cloud Use Cases
1. Hosting Web Applications
Example: An e-commerce startup, ShopEase, launches its website using AWS EC2(Elastic Computing Cloud is a service provided by AWS that offers scalable and resizable virtual servers, called "instances," in the cloud. ) instances and stores customer images in AWS S3. They can quickly scale up during holiday sales by adding more EC2 instances.
2. Development and Testing Environments
Example: A software company, CodeSpark, uses Google Cloud Platform (GCP) for their development teams. Developers create isolated testing environments with Google Compute Engine to run tests without affecting production.
3. Big Data Analytics
Example: A data analytics firm, InsightIQ, uses Azure HDInsight to process large datasets for a retail chain. They analyze purchase patterns and provide customer insights for better marketing strategies.
(Azure HDInsight is a fully managed, cloud-based service from Microsoft Azure for processing large datasets using popular open-source frameworks such as Hadoop, Spark, Hive, Kafka, and HBase. It provides a scalable, cost-effective, and enterprise-ready platform for big data analytics)
4. Startups Needing Rapid Scalability
Example: A video streaming startup, Streamify, uses AWS Lambda to handle millions of users during a viral launch event. It scales automatically without upfront investment in physical servers.

## Private Cloud Use Cases
1. Regulatory Compliance Requirements (e.g., Healthcare, Banking)
Example: A healthcare organization, MediSecure, deploys patient data management on a private cloud using OpenStack. This ensures compliance with HIPAA regulations by keeping sensitive data on-premises.
2. Handling Sensitive Workloads
Example: A defense contractor, SecureTech, uses a VMware-based private cloud to store confidential government documents. The controlled environment ensures data is not exposed to public networks.
3. Organizations with Predictable Workloads
Example: A large retail chain, RetailSphere, predicts its seasonal workload and maintains an on-premise private cloud infrastructure to handle inventory and logistics management.

## Hybrid Cloud Use Cases
1. Disaster Recovery and Business Continuity
Example: A financial services firm, FinSync, uses a hybrid cloud. Their primary database is hosted on-premises, but they replicate critical data to Azure Blob Storage in the public cloud for disaster recovery.
2. Workload Balancing Between On-Prem and Cloud
Example: A manufacturing company, FactoryPlus, uses a hybrid cloud setup. Their CAD software runs on-prem for better performance, but heavy simulations are offloaded to AWS High-Performance Compute (HPC) instances during peak times.
3. Temporary Capacity Increases
Example: An event management company, EventHive, uses a hybrid cloud. During large events, they temporarily move ticketing and guest registration systems to Google Cloud to handle increased traffic.

