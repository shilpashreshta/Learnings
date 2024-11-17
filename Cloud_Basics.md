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
* Private Cloud: Dedicated resources for a single organization, either on-premises or hosted. Private cloud provides much greater control for the company and its IT department. However, it also comes with greater cost and fewer of the benefits of a public cloud deployment.
* Hybrid Cloud: Combines public and private clouds for flexibility and optimized workloads. Hybrid cloud can be used to provide an extra layer of security. For example, users can flexibly choose which services to keep in public cloud and which to deploy to their private cloud infrastructure.
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
