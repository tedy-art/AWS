# AWS
# [Cloud Computing with AWS]

**What is Cloud Computing??**

The practice of using a network of remote servers hosted on the internet to store, manage, and process data, rather than a local server or a personal computer.

| sr.no | without cloud providers         | with cloud providers                                                                                 |
|-------|---------------------------------|------------------------------------------------------------------------------------------------------|
| 1     | you own the servers             | Someone else owns the servers                                                                        |
| 2     | You hire the IT people          | Someone else hires the IT people                                                                     |
| 3     | You pay or rent the real-estate | Someone else pays or rents the real-estate                                                           |
| 4     | You take all the risk           | You are responsible for your configuring cloud services and code, someone else take care of the rest |

**Evolution of cloud hosting:**
|sr.no|Types of hosting|Description|features|
|--|--|--|--|
|1|Dedicated Server|One Physical machine dedicated one single business, runs a single web-app/site|Very Expensive, High Maintenance, *High security|
|2|Virtual private server|One Physical machine dedicated one single business.The Physial machine virtualized into sub-machinse Runs multiple web-app/sites|Better Utilization and Isolation of resources|
|3|Shared Hosting|One physical machine shared by hundred of businesses, Relies on more tenants under-utilization thier resources.|Very Cheap, Limited Functionality, Poor Isoation|
|4|Cloud Hosting|Multiple physical machine act as single system. The system abstracted into multiple cloud services.|Flexible, Scalable, Secure, Cost-Effective, High-Configurability|

**What is Amazon??**

Amazon is an American multinational computer technology corporation headquartered in Seattle, Washington.

Amazon was founded in 1994 by Jeff Bezos and company stated as an online store for books and expanded to other products.

**What is AWS??**

| full | form     |
|------|----------|
| A    | Amazon   | 
| W    | Web      |
| S    | Services |

Amazon calls their cloud provider service `Amazon Web Services` commonly reffered to just `AWS`.

 * AWS was launched in *2006 is the leading cloud provider in the word.

 * Cloud Service Providers can be initialized as CSP's.


**Which and When Services Rolled Out??**
1) Simple Queue Service(SQS):
    * SQS was the first AWS service launched for public use in 2004.
<hr>

2) Simple Storage Service(S3):
    * S3 was launched in March 2006.
<hr>

3) Elastic Compute Service(EC2):
    * EC2 was launched in August of 2006.
<hr>

| In November 2010, it was reported that all of Amazon.com's retail sites had migrated to AWS |
|---------------------------------------------------------------------------------------------|

| To support Indesrty-wide taining and skills standardzation, AWS began offering a certification program for computer engineers, on April, 2013 |
|-----------------------------------------------------------------------------------------------------------------------------------------------|

**What is a Cloud Service Provider??**

| Full | Form     |
|------|----------|
| C    | Cloud    |
| S    | Service  |
| P    | Provider |

A `Cloud Service Provider`(CSP) is a company which:
|sr.no| CSP's do |
|-|-|
|1| provides multiple cloud services e.g.tens of hundreds services.|
|2| those cloud services can be chained together to create cloud architecture.|
|3| those cloud services are accessible via single unified API e.g. AWS API.|
|4| those cloud services utilized metered billing based on usages e.g. per second, per hour.|
|5|those cloud services have rich monitering built in e.g. cloudTrail|
|6|those cloud services have an `Infrastrucute as a Service`(IaaS) offering.|
|7| those cloud services offers automation via `Infrastructue as Code`(IoC)|

 <img src="/Images/CSP.png" alt="Nw"> 

Note:
If a company offer multiple cloud services under single UI but do not meet most of or all of those requirements, it would be reffered to as a `Cloud Platform` e.g. Twilio, HashiCorp, Databricks.

**Landscape of CSPs??**

Landscape of CSP's are divided into 3 types:

**Tier-1**(Top Tier):

* Early Market, wide offering, strong synergies between services, well recognized in the industry.

Products:
    1) AWS = Amazon Web Services
    2) Azure
    3) GCP = Google Cloud Platform
    4) Alibaba Cloud

**Tier-2**(Mid Tier):

* Backed by well-known tech companies, show to innovate and turned to specialization.

Products:
    1) IBM Cloud
    2) Oracle Cloud
    3) Rackspace(OpenStack)

**Tier-3**(Light Tier):

* Virtual Private Servers(VPS) turned to offer core IaaS offering. Simple, cost-effective

Products:
    1) Vultr
    2) Digital Ocean
    3) Linode

**What is Cloud Computing?**

Cloud computing is a computing service made available over the internet.

Cloud computing is a pay-as-you-go model for delivering IT resources.

You pay only for what you use.

**Common Cloud services:**

A Cloud server provider can have hundreds of services that are grouped into various types of services.

The four most common type of cloud services(the 4 core) for Infrastructure as a Service(IaaS) would be:

*Compute :* Imagine having virtual computer that can run application, program and code.

*Networking :* Imagine having virtual network defining internet connection or network isolation between service or outbond to the internet.

*Storage :* Imagine having virtual hard drive that can store files.

*Databse :* Imagine a virtual database for storing and reporting data ot a database for general purpose web-application.

**Cloud Service providers(CSp's) that are Infrastructure as a Service(IaaS) will always have 4 cloud services offerings :**

|sr.no | Type   | Cloud Service            |
|------|--------|--------------------------|
|1     |Compute | EC2 Virtual Machine      |
|2     |Storage | EBS Virtual Hard drives  |
|3     |Database| RDS SQL database         |
|4     |Networke| VPC Private Cloud Network|

Other Service Cloud Provide:
|sr.no |         Cloud Service            |sr.no |         Cloud Service            |
|------|----------------------------------|------|----------------------------------|
|1     | Analytics                        |8     | Developer Tools                  |
|2     | Application Integration          |9     | End user computer                |
|3     | AR & VR                          |10    | Game Tech                        |
|4     | AWS cost management              |11    | Internet of Things               |
|5     | block Chain                      |12    | Machine Learing                  |
|6     | Bussiness application            |13    | Management and governance        |
|7     | Containers                       |14    | Media Services                   |
|8     | Customer Engagement              |15    | and so on                        |


**Types of Cloud Computing :**

1) SaaS : Software as a Service<br>
   1) A product that run and managed by the service provider.<br>
   2) *Don't worry about how the service is maintained.*<br>
   3) *It just works and remains available.*<br>
   4) Products : Saleforce, gmail, Office 365<br>
   5) SaaS is generally designed for Customers.

2) PaaS : Platform as a Service
   1) Focun on the deployment and management of your apps.
   2) *Don't worry about provisioning, configuring, or understanding the hardware or O.S.*
   3) Products : Elastic Beanstalk, heroku, google app engin
   4) it's use for developer.

3) IaaS : Infrastructure as a Service
   1) The basic building blocks for cloud IT.
   2) Provides access to networking feature, computers, and data storage space.
   3) *Don't worry about IT staff, data center and hardware.*
   4) Products : Microsoft Azure, AWS, Oracle Cloud.
   5) IaaS directly used from Adminstrator.

