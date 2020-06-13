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