# Tools

## Azure App Service:

It is Azure's **PaaS** offering for hosting websites. It allows us to run web apps build on multiple frameworks and in different programming languages.

- It is HTTP based service.
- Used to host web applications, REST APIs and Mobile back ends.


## Azure SQL:

It is a managed SQL Daatabase on Azure. It is provided as a service Azure takes care of scalability, backup and high availability of the database.

![image](https://user-images.githubusercontent.com/110366380/213700110-a29c8a8f-b2b8-43b5-aa8f-5223e59c77b4.png)

## CosmosDB

It is a **NoSQL** database offered by Azure. It is similar as DynamoDB in AWS.

- It manages data at a large scales.
- It is globally distributred.
- It provides low latency.
- It is multi-model database.

It is most commonly ues for storing catalog data and for event sourcing in order processing pipelines.

## Azure Search

Now known as **Azure Cognitive Search**, it provides indexing and querying capabilities for data uploaded to Microsoft servers.

- It provides developers with infrastructure, APIs and tools for building search functions for private application.
- It provide search option for private, heterogenouse content in web, mobile and enterprise applications.


## KeyVault

It is the service for securely storing and accessing secrets. The secrets can be API keys, passwords, certificates or cryptographic keys. It can be compared to encryption ant rest scenarios where customer data is processed by PaaS.

- It provides secure key management to protect data in the cloud.

### HSM (Hard Security Module)
- It is a physical computing device that safeguards and manages secrets, mostly digital keys.

## ARM Template

Azure Resource Manager Template is a form of infrasturucter as code. We can define the infrastructure that need to deployed. It uses declarative syntax, meaning we deinfe the resource for azure to deploy without specifying how the resources are created. It's main advantages are

- Declarative Syntax
- Repeatable Results
- Orchestration

## OAuth

Open Authoriazation is a way for internet users to grant websites or application access to their information on other website without giving them access to the passwords. It makes it possible for companies such as Amazon, Google, Facebook, Microsoft, Twittter etc to allow the users to share informatin about their accounts with third-party application or websites. A Basic workflow of OAuth can be seen from the diagram.

![image](https://user-images.githubusercontent.com/110366380/213705532-aa7bf4ff-cb9f-4b53-9ed8-7fc174a3be66.png)


## SAML

SAML stands for Security Assertion Markup Language. It is an XML based open-standard for transferring identity data between two parties, for example between an identity provider(IdP) and a service provider (SP).

![image](https://user-images.githubusercontent.com/110366380/213705343-b90ed992-cd29-46ea-a45c-8833ec2ea501.png)


### Combined use of SAML and OAuth

SAML authenticates the user's identity to a service, while OAuth authorizes the user to access specific resources owned by the service provider. Both can be used for single sign-on (SSO), which permits users to access IT resources with only one set of login credentials (e.g., username and password)

## VSTS

Visual Studio Team Service (VSTS) . Its now called Azure DevOps Services. It is an extension to MS Visual Studio architecture that allows to encompass development & testing teams, with special roles and tools for software architects, developer specialties and testers.

##  Azure DevOps vs Jenkins

- Jenkins is more flexible to create and deploy complex workflows.
- Azure DevOps is faster to adapt. 
- In most cases, organizations use both the tools and in such cases, **Azure Pipelines** supports integration with Jenkins.

## Azure Pipelines

Azure Pipelines automatically builds and tests code projects. It supports all major languages and project types and combines continuous integration, continuous delivery, and continuous testing to build, test, and deliver your code to any destination.

## ELK

Also referred to as Elasticsearch, the ELK stack gives us the ability to aggregate logs from all our systems and applications, analyze these logs, and create visualizations for application and infrastructure monitoring, faster troubleshooting, security analytics, and more.

## Grafana

It is open source analytics and interactive visulization web application.

- It is a multi-platform open source analytics and interactive visualization web application. 
- It provides charts, graphs, and alerts for the web when connected to supported data sources.

## Prometheus

It is a free software application used for event monitoring and alerting. It records real-time metrics in a time series database using a HTTP pull model, with flexible queries and real-time alerting.


