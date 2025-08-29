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
### Microsoft enntra id is an identity and access management service. authentication is the microsoft entra id provide for us. Single sign on feature simplifies the user experience by allowing access to multiple applications just one set of credentials. Multifactor enhances the security by requiring multiple methods of verification before granting access. Conditional accesses which customizes access policies based on the user, their location, and the device ththey are using. B2B collaboration ensures secure management of guest and partner access to resources. Application Management feature allows for easy intergration and management of application. Device management is all about controlling and 
### Microsoft entra domain service lists computers, users, and resources on a network and their respective details. Domain join allows Windows servers and computers to join secure domain without the need for a traditional domain controller. With group policies we can mange network users and computers efficiently. LDAP and Kerberos authentications are critical for supporting legacy protocols that are necessary for wide range of applications and services to functions securely and realiably. microsoft entra id use modern authentications(OpenID, OAuth, SAML)
### Tags in Azure are used to logically organize resources into a taxonomy. Each tag consists of a name and a value pair, which can help manage and account for billing by grouping resources that share characteristics.
### When planning to migrate a public website to Azure, you must plan to pay monthly usage costs. This is because Azure uses the pay-as-you-go model.
### We can use Conditional Access to validate each sign-in and apply necessary actions as required. In this case, we will set the condition as unidentified IPs and action to enforce password reset.
### Azure Container Instances offers the simplest and easiest way to deploy containers in Azure. Other container solutions are considered if you need orchestration capabilities.
### Azure Application Insights is a feature of Azure Monitor, offering analytics and performance monitoring of live applications, helping developers to diagnose issues and understand usage patterns.
### High-availability features are designed to ensure that a system achieves a certain level of operational performance for a higher than normal period. These features primarily help minimize downtime and maintain business continuity.
### Azure Virtual Machine Scale Sets let you create and manage a group of load balanced VMs. The number of VM instances can automatically increase or decrease in response to demand or a defined schedule, improving the scalability of the applications.
### With the public cloud, you get pay-as-you-go pricing – this means you pay only for what you use; there are no CapEx costs.
### With the public cloud, you have self-service management. You are responsible for the deployment and configuration of the cloud resources such as virtual machines or websites. The underlying hardware that hosts the cloud resources is managed by the cloud provider.
### Point-to-Site VPN connections can be used to establish connectivity from remote workstations or clients to Azure virtual network.
### GRS allows you to replicate data to a secondary region. In the primary region, the data will be stored in three different nodes.
### Azure Active Directory (Azure AD) is a cloud-based identity and access management service, which helps your employees sign in and access resources.
### The Azure Total Cost of Ownership (TCO) Calculator helps customers estimate the cost savings that can be realized by migrating their workloads to Azure.
### A Site-to-Site VPN gateway connection is used to connect your on-premises network to an Azure virtual network over an IPsec/IKE (IKEv1 or IKEv2) VPN tunnel. This type of connection requires a VPN device located on-premises that has an externally facing public IP address assigned to it.
### Azure Key Vault is a secure store for storing various types of sensitive information including passwords and certificates. Azure Key Vault can be used to Securely store and tightly control access to tokens, passwords, certificates, API keys, and other secrets.
### Networks in Azure are known as virtual networks. A virtual network can have multiple IP address spaces and multiple subnets. Azure automatically routes traffic between different subnets within a virtual network.
### The just-in-time (JIT) access feature in Microsoft Defender for Cloud allows you to lock down inbound traffic to your Azure Virtual Machines. This reduces exposure to attacks while providing easy access when you need to connect to a VM.
### A subscription is an agreement with Microsoft to use one or more Microsoft cloud platforms or services, for which charges accrue based on either a per-user license fee or on cloud-based resource consumption.
### Application Insights can fulfill the requirement as it’s an application performance monitoring solution.
### One of the major changes that you will face when you move from on-premises cloud to the public cloud is the switch from capital expenditure (buying hardware) to operating expenditure (paying for service as you use it). This switch also requires more careful management of your costs. The benefit of the cloud is that you can fundamentally and positively affect the cost of a service you use by merely shutting down or resizing it when it's not needed.
### We can configure alerts based on the Activity Log. Service Health Alerts cannot notify any user-initiated events.
### Azure virtual machines run on Hyper-V physical servers. The physical servers are owned and managed by Microsoft. As an Azure customer, you have no access to the physical servers. Microsoft manages the replacement of failed server hardware and the security of the physical servers, so you don’t need to do that.
### When you create a resource group, you specify which location to create the resource group in. However, when you create a virtual machine and place it in the resource group, the virtual machine can still be in a different location (different data center). Therefore, creating multiple resource groups, even if they are in separate data centers, does not ensure that the services running on the virtual machines are available if a single data center fails. To overcome data center failures, you need to place the virtual machines across availability zones.
