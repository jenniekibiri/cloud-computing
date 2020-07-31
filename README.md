# principles of cloud computing
![cloud image](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2018/11/Cloud-Computing-Tutorial.jpg)
### what is cloud computing
* Cloud computing is renting resources, like storage space or CPU cycles, on another company's computers. 
and company offering the services are the cloud providers
* Amazon 
* Microsoft
* Google
# Goal of cloud computing
makes running a business easier and effiecient
# cloud computing services
* compute power-how much processing your computer can do
* the cloud provider can maintain your software but if you want to handle the maintenance you can create a vm-(an emulation of computer the difference being the vm is being run in the cloud so no need of buying the hardware)
with the vm you can install whatever tools you need to run the tasks in the cloud 
vm uses guest os
other computing choices include 
1. # container
containers a software that packages code and all its depencies so that the appilication runs quickly and reliable from one computing env to another
uses containers
Docker
1. # serverless
 lets you run application code without creating, configuring, or maintaining a server. application is broken into functions and run when triggered by a some action
 The serverless model differs from VMs and containers in that you only pay for the processing time used by each function as it executes.
storoge -files and databases
![Compute approaches](https://docs.microsoft.com/en-gb/learn/modules/principles-cloud-computing/media/2-vm-vs-container-vs-serverless.png)
# storage
the space to store your 
data files it supports different formats 
the advantage of using cloud based storage is the you can scale to meet your needs 
# Benefits of cloud computing
companies that already established can do gradual movement to the cloud - lift and ship while start up companies can start in the cloud

1. # cost Effective 
   * with pay-as-you-go/consumption based  
  *  no upfront charges(layman language-deposit)
  * no need to purchase infrastructure that you dont use.
  * pay for additional resources that only when needed
 *  you can stop paying for resources that you dont use any more
this allows cost prediction for each period .....history usage is provided by the cloud provider


2. # scalable
you can increase or decrease the resources and services used based on workload for a particular time
* (vertical scaling)
scaling up- adding resources to increase the power of the server eg. more cpus and memory
* (vertical scaling)
'scaling out'-adding more servers that function together as one units

3. # elastic
as workload changes to spike or drop in demand a cloud computing system can automatically add or remove resources - workload can spike due to increase in traffic

4. # current 
handles upgrades,maintenance ,s/w patches  and disk failures this ensure you're using the lastest tools

5. # reliable 
cloud computing makes data available.Offers backups disaster recovery and data reprication

6. # global
 redundant datacenters in various region all over the globe.
 this give local presence
  close to your customers to give them the best response time possible no matter where in the world they are.

 7. # secure 

 # Economies of scale
 ability to do things effieciently at a lower cost
 cloud helps users save in ways such  as acquire  h/w at a lower cost tax saving,low power price cooling and high speed network

 # Approaches to investment

 ## Capital expenditure (capEx)
spending money on physical infrastructure up front, and then deducting that expenses from your tax bill over time CapEx is an upfront cost, which has a value that reduces over time.



## Operational Expenditure (OpEx)

 spending money on services or products now and being billed for them now.There's no upfront cost. You pay for a service or product as you use it.

# CapEx computing costs 

* server costs
* storage costs 
* network costs
* backup and archive tools
* disaster recovery
# OpEx computing 

With cloud computing, many of the costs associated with an on-premises datacenter are shifted to the service provider
* Leasing software and customized features -you can actively manage subscriptions 
* scaling charges based on usage 
* Billing at the user or organization level.
# benefits of capex

you plan  your expenses at the start,the costs are fixed 
# benefits of opex

Demand and growth can be unpredictable and can outpace expectation, which is a challenge for the CapEx model as shown in the following graph.

![opex/capex-grap](https://docs.microsoft.com/en-gb/learn/modules/principles-cloud-computing/media/3c-capexvsopex.png)
if your service peaks one month, you can scale to demand and pay a larger bill for the month. If the following month the demand drops, you can reduce the used resources and be charged less. This agility lets you manage your costs dynamically, optimizing spending as requirements change.

# cloud deployment models
### public 

you have no local hardware to manage or keep up-to-date – everything runs on your cloud provider's hardware.
## Advantages of public
 * high scalability
 * pay as you go
 * you're not responsible for maintenance updates

 less technical knowledge to use and set up
 ## disadvantages
 * some security requirements cannot be met
 * some govtpolices/industry standards cannot be meet

## private  

you create a cloud environment in your own datacenter and provide self-service access to compute resources to users in your organization.you're responsible for maintenance of the hardware and software services you provide.

# hybrid 
'
A hybrid cloud combines public and private clouds, allowing you to run your applications in the most appropriate location.

 ## advantages

 You can keep any systems running and accessible that use out-of-date hardware or an out-of-date operating system
 ## disadvantages
 * hard to set up
 * its expensive 

 # Types of cloud services

## Infrastructure as a service (IaaS)

most flexible
t aims to give you the most control over the provided hardware that runs your application (IT infrastructure servers and virtual machines (VMs), storage, and operating systems). Instead of buying hardware, with IaaS, you rent it. It's an instant computing infrastructure, provisioned and managed over the internet.
* there is shared responsibility model.
- the cloud customer is responsible for ensuring the service they are using is configured correctly
- the cloud provider is responsible for ensuring the cloud infrastructure is functioning correctly;
 Iaas is mostly used for -migrating workloads
                          - test and development
                          -Storage, backup, and recover
## Platform as a service (PaaS)
PaaS provides an environment for building, testing, and deploying software applications. The goal of PaaS is to help you create an application quickly without managing the underlying infrastructure. For example, when deploying a web application using PaaS, you don't have to install an operating system, web server, or even system updates.

## Software as a service (SaaS)
SaaS is software that is centrally hosted and managed for the end customer. It is usually based on an architecture where one version of the application is used for all customers, and licensed through a monthly or annual subscription. Office 365, Skype
 
 ![clearpic](https://docs.microsoft.com/en-gb/learn/modules/principles-cloud-computing/media/5-layer-diagram.png)
 # What is an App Service?
Azure App Service is an HTTP-based service that enables you to build and host many types of web-based solutions without managing infrastructure. For 
# Creating resources in Azure
 The resource group allows us to administer all the services, disks, network interfaces, and other elements that potentially make up our solution as a unit. 
 # Choosing a location
 # azure cloud shell 
 browser based cmd for managing azure resources
 * work with the right subscription
 * az - using the cli
 * az-account -list
 by default the cmd returns json string 
 so we format the output into table
 * az-group-list ---- list the resource group
 * az webapp stop \ stops the site from running
 * syntax
 az webapp start \
    --resource-group learn-c2fa7e33-7eb2-438e-b0e7-7e865970ca34 \
    --name <web app name>
    Scale refers to adding network bandwidth, memory, storage, or compute power to achieve better performance.
    * scale up/vertical -increase the memory, storage, or compute power on an existing virtual machine.
    scale out/horizontal-add extra virtual machines to power your application

# Core Cloud Services - Azure architecture and service guarantees
## Understand Datacenters and Regions in Azure
What is a region?
A region is a geographical area on the planet containing at least one, but potentially multiple datacenters that are nearby and networked together with a low-latency network.
## Geographies in Azure
An Azure geography is a discrete market typically containing two or more regions that preserve data residency and compliance boundaries
## Availability Zone
Availability Zones are physically separate datacenters within an Azure region.

