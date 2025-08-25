### The private cloud is solution for businesses with stringent sequrity requirements. Private cloud offers best security within their own data centre.
### Public cloud is a vast expanse owned and operated by a cloud service provider like microsoft. amazon, google or oracle. It's a shared space, offering its boundary of resources and services to multiple organizations simutanesouly.
### Vertical scalling or scalling up involves adding more power to the existing machines like upgrading server with a more powerful cpu. Horizontal scalling also known as scalling out, refers to adding more machines to the network.
### The horizontal scalling is the true auto-scalling. Cloud works with the consumption-based model.
### The cloud offers governance and compliance tools that help businesses define, enforce and monitor governance policies. These tools enable automated compliance checks, policy enforcement, and reporting.
### Elasticity is the ability of a system to adapt to workload changes by provisioning and deprovisioning resources in an autonomus manner.
### With Iaas companies can rent servers and storage spaces in the cloud, allowing them to avoid the expenses and complexities of buying and managing physical servers and other data center infrastructure. Iaas offers a scalable environment that can grow or shrink. eg: Azure virtual machine
### The Saas option reduces the effort in the software maintenance and infrastructure management, Everything provides by the cloud provider.
### Shared responsibility is devided; the provider secures the infrastructure, while the customer secures their data.
### In the saas model, customers have the least control over the computing environment, as the service provider manages everything from the application down to the hardware.
### Iaas focuses on providing virtualized computing resources over the internet, allowing users to run and manage applications without dealing with physical hardware directly.
### Availability zone is a collection of data centers within a single region that are isolated to prevent outages from affecting the entire region.
### Azure regions are designed to allow users to deploy cloud resources close to their physical location to reduce latency and improve service performance.
### Availability is a feature in azure that ensures your application is available during planned and unplanned maintenance events.
### Azure function is a serverless computer service.
### Virtual machines- Complex applications, full-stack control
### Azure Virtual Desktop - Remote Work, BYOD policies
### Azure App Services- Web Applications, RESTful APIs
### Containers- Microservices, rapid development/deployment
### Azure Functions- Short lived, event-triggered tasks, microservices
### VPN Gateway is a specific type of Virtual Network Gateway that is used to send encrypted traffic between azure virtual network and on-premises. Site to site is more between one site to another site. Point to site a single point, like individual device to cloud. Express route is something called connectivity provider. It uses for hybrid cloud deployments. Companies with strict data protection regulations can utilizes expressroute to ensure data does not travel through the public internet. 
### Azure virtual machines are best for traditional applications that require full control of the OS, where as azure functions are desinged for smaller, event-driven tasks.
### Purpose of the azure dns is to manage domain names and provide dns resolution.Azure Virtual Machine Scale Sets allow you to create and manage a group of identical, load-balanced VMs. The number of VM instances can automatically increase or decrease in response to demand or a defined schedule, which is ideal for supporting large-scale services such as big data, containerized workloads, microservices, and cloud services.
### Azure App Services is a platform-as-a-service (PaaS) offering of Microsoft Azure that allows developers to quickly build, deploy, and scale web applications and APIs using a fully managed platform.
### Azure storage accounts encompass a range of services including blob storage for storing images, and all those unstructured data, file storage for managing file shares, queue storage for messaging queuing, and Table Storage for NoSQL data. 
### Storage redundancy is a method of ensuring data is replicated and stored in multiple locations to prevent data loss and improve data availability.
### Locally redundant storage(LRS) - Replicates data within a single storage facility in a single region.
### Zone-redundant storage(ZRS) - Replicates data across multiple data centers in a single or multiple regions.
### Geo-redundant storage(GRS) - A single data center in the primary and secondary region.
### Geo-zone-redundant storage(GZRS) - Combines both ZRS and GRS for higher durability and availability.
### Azure storage services provide a comprehensive solution for storing, accessing, and managing data in the cloud based on the data requirements.
### Azure blob - This is for storing unstructured data like documents, images, or videos.
### Disk storage - Disk for azure virtual machines.
### Queue storage - This is designed for reliable messaging between application components.
### Azure files - Offers managed file file shares for cloud or on-premises deployments.
### Azure tables - Provides a NoSQL storage solution for rapid deployment and development. 
### The Hot tier is ideal for data that we need to access quickly and often.
### The cool tier si for short term back up where we don't access the data as often.
### The archive access tier is optimised for data that is rarely accessed and stored for at least 180 days with flexibel lattency requirements(on the order of hours)
### Azure migrating is a service that provides tools to assist organizations in migrating their existing on-premises workloads to azure.
### 32 bits os are not supported for azure.
### Azure databox is a data transfer solution provided by azure for moving large amounts of data into Azure storage and compute services. This is perfect for physical data transfer. Perfect for online data transfer. If the files are too large, we can't send them over the network, we just plug this device in the data center, copy all the files and send it to the Azure Data Center. Data Box Disk - for smaller data loads, Data Box - for large data volumes, Data Box Heavy - for very large scale data transfer needs.
### AZ Copy is a command line utility that specializes in transfering files quickly. Perfect for large scale operations like bulk data transfer, backup, and archiving directly to azure storage.
### Azure Storage Explore is perfect for ad hoc transfers and day to day management of data, offering an interactive and intuitive approach to exploring and managing files.
### Azure file sync act as a bridge, synchronizing files across azure file shares and your on-premises windows servers.
### Life cycle management policies in azure storage can be used to automate the transition of data to teh most cost-effective access tier based on how frequently the data is accessed and how long it's stored.
### Azure Storage Explorer is a standalone app that enables you to easily work with Azure Storage data on Windows, macOS, and Linux.Locally redundant storage (LRS) replicates your data three times within a single storage scale unit located in a single region. This provides high durability for your data if there is a failure within the data center.
### 
