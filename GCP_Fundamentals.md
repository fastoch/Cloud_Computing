Google Cloud Platform (GCP) is one of the biggest cloud providers, right behind AWS (Amazon Web Services) and Azure (Microsoft).

# What is cloud computing?

The US National Institute of Standards and Technology (**NIST**) created this term in 2011:  
https://csrc.nist.gov/pubs/sp/800/145/final  

Cloud computing is a way of using information technology (IT) that has these 5 equally important traits:
- customers get computing resources that are on-demand and self-service (storage, processing power, and network)
- customers get access to those resources over the internet, from anywhere (through a web interface)
- the provider of those resources has a large pool of them, and allocates them to users out of that pool
- the resources are elastic, which means they can increase or decrease as needed, so customers can be flexible
- customers pay only for what they use (if they stop using resources, they stop paying)

---

# Cloud vs. traditional architecture

The trend toward cloud computing started with a **first wave** known as **colocation**.  
Colocation gave users the financial efficiency of renting physical space, instead of investing in data center real estate.  

**Virtualized data centers** of today, which is the **second wave**, share similarities with the private data centers and colocation  
facilities of decades past.  

The components of virtualized data centers match the physical building blocks of **hosted computing**: servers, CPUs, disks, load  
balancers, and so on. But now they're virtual devices.  

With virtualization, enterprises still maintained the infrastructure; it's still a user-controlled and user-configured environment.  
Several years ago, Google realized that its business couldn't move fast enough within the confines of the virtualization model.  

So Google switched to a **container-based architecture**: a fully automated, elastic **third-wave** cloud that consists of a combination  
of automated services and scalable data. Services automatically provision and configure the infrastructure used to run applications.  

Today, Google Cloud makes this third-wave cloud available to Google customers.  
Google believes that, in the future, every company will differentiate itself from its competitors through technology.  
Increasingly, that technology will be in the form of software. Great software is based on high-quality data.  
This means that every company is, or will eventually become, a data company.  

The virtual world, which includes Google Cloud's network, is built on physical infrastructure, and all those racks of humming  
servers use huge amounts of energy. Together, all existing data centers use roughly 2% of the world's electricity.

---

# IaaS, PaaS, and Saas

The move to virtualized data centers introduced customers to 2 new types of offerings: 
- infrastructure as a service
- platform as a service

**IaaS** offerings provide raw compute, storage, and network capabilities, organized virtually into resources that are similar to  
physical data centers.  

**PaaS** offerings bind code to libraries that provide access to the infrastructure applications need. This allows more resources  
to be focused on application logic.  

- In the IaaS model, customers pay for the resources they allocate ahead of time.  
- In the PaaS model, customers pay for the resources they actually use.

As cloud computing has evolved, the momentum has shifted toward managed infrastructure and managed services.  
Leveraging managed resources and services allows companies to concentrate more on their business goals and spend less time and  
money on creating and maintaining their technical infrastructure.  

**Serverless** is yet another step in the evolution of cloud computing.  
Serverless computing allows developers to concentrate on their code, rather than on server configuration, by eliminating the  
need for any infrastructure management.  

Serverless technologies offered by Google include **Cloud Functions**, which manages event-driven code as a pay-as-you-go service,  
and **Cloud Run**, which allows customers to deploy their containerized microservices-based application in a fully managed environment.  

You might also have heard about **Software as a service** and wondered what it is and how it fits into the cloud ecosphere.  
**SaaS** applications are not installed on your local computer, they run in the cloud and are consumed directly over the internet by end users.  

Google's popular applications like Gmail, Docs, and Drive, collectively known as Google Worspace, are all classified as SaaS.

---

# Google Cloud architecture

**3 layers**:
- the base layer = **networking and security**, lays the foundation to support all of Google's infrastructure and applications
- the intermediate layer = **compute** & **storage**, are decoupled so they can scale independently base on need 
- the top layer = **Big Data & ML products**, enable you to perform tasks to store, process and deliver business insights,
  data pipelines, and machine learning models

Thanks to Google cloud, you can accomplish these tasks without needing to manage and scale the underlying infrastructure.  

**Google offers a range of computing services**, which includes:
- Compute Engine
- Google Kubernetes (K8s) Engine
- App Engine
- Cloud Functions
- Cloud Run

Google Cloud also offers **a variety of managed storage options**:
- Cloud storage
- Cloud SQL
- Cloud spanner
- Cloud bigtable
- Firestore

Cloud SQL and Cloud spanner are **relational databases**, while Bigtable and Firestore are **NoSQL databases**.  

And then, there's a robust big data and ML product line. This includes:
- cloud storage
- dataproc
- bigtable
- BigQuery
- dataflow
- firestore
- pub/sub
- looker
- cloudspanner
- AutoML
- Vertex AI

As previously mentioned, the Google network is part of the foundation that supports all of Google's infrastructure and applications.  
Google's network is the largest network of its kind. This network is designed to give customers the highest possible throughput and  
lowest possible latencies for their applications by leveraging more than 100 content caching nodes worldwide.  

These nodes are locations where high demand content is cached for quicker access, to respond to user requests from the location that  
will provide the quickest response time.  

Google cloud's infrastructure is based in 5 major geographic **locations**: North America, South America, Europe, Asia, and Australia.  
Each of these locations is divided into several **regions**. Regions represent independant geographic areas, and are composed of **zones**.  
For example, London, or europe-west2, is a region that currently contains 3 different zones.  
**A zone is an area where Google Cloud resources are deployed.**  

Google Cloud lets users specify the geographical locations to run services and resources.  
In many cases, you can even specify the location on a zonal, regional, or multi-regional level.  
This is useful for bringing applications closer to users around the world, and also for protection in case there are issues with  
an entire region, say, due to a natural disaster.  

Google cloud currently supports 121 zones in 40 regions, though this is increasing all the time.  
The most up to date information can be found at cloud.google.com/about/locations  

---

# Start with a solid platform (User Interface)

You can interact with Google Cloud in 4 ways:
- Google cloud console
- Cloud SDK & Cloud shell
- APIs
- Cloud Mobile App

## The Google Cloud console

- simple web-based graphical user interface
- helps you deploy, scale, and diagnose production issues 
- easily find resources, check their health, have full management control over them, and set budgets
- provides a search facility to quickly find resources and connect to instances via SSH in the browser


  




