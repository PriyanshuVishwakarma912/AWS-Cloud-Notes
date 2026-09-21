# Introduction and Basics of Cloud and Important terms and terminologies
---
### Why Cloud Computing exists?
- Before cloud computing, whenever any company wanted to deploy its application on a server, it needed to buy those servers; basically, it needed to create its own data centre. But creating your own data centre creates two major problems: one, the maintenance is very high and the second was the resouces get wasted in a large amount. Let's say a server contains 100 GB of storage, and we only use 10 GB of resources of that server, and the rest of the 90 GB of resources get wasted.
---
### What is Cloud Computing?
- Cloud computing is the on-demand delivery of computing services, including servers, storage, databases, networking, and software over the internet. Instead of managing physical hardware locally, users rent these resources from a cloud provider and typically pay only for what they use.
### Types of Cloud.
- ### Public Cloud:
    -  Public Cloud is fully owned, operated, and maintained by a third-party provider. These resources are delivered over the public internet and shared among multiple organizations. Public clouds are AWS, Microsoft Azure, and GCP.
- ### Private Cloud:
    -  Private cloud infrastructures are dedicated to a single organization and can be hosted on-premises or by a service provider. Private cloud uses those applications that have very sensitive data.
- ### Hybrid Cloud:
    -  A hybrid cloud is the combination of public and private clouds that allows data and applications to move between them.
---
### Data Centres
- Data centres are the backbone of the cloud. A data centre is a centralized facility equipped with computing resources such as servers, storage systems, networking equipment, and cooling infrastructure that is used for the delivery of cloud services over the internet.
### Region
- A region is a large geographical area where a cloud provider has multiple data centers.
- A region is located in a country or area & each region contains miltiple availability zones(AZ).
### Availability Zones(AZ)
- An availability zone(AZ) is one or more data center inside a region that works independently.
- Each availability zone(AZ) has it's own power, cooling and network.
- Availability zones(AZ) are connected with high speed private links.
- If one availability zone(AZ) fails others keep running.
### Local Zones
- A local zone is a small extension of a region that placed very close to end users in the city.
- Used for ultra low latency.
- Connected to a parent region.

- Overall:
    - Region: Where your cloud lives
    - Availability Zone: How safely it runs
    - Local Zone: How fast users can access it
--- 
### Cloud works on " PAY AS YOU GO MODEL " or "ON DEMAND SERVICE" that means you can only pay for the resources that service to use for that particular amount of time.
Note: AWS is the biggest cloud provider and it has the largest market share.
---
### Concept Of Virtualization:
- Virtualization allows you to split one physical computer into multiple virtual computer
### Hypervisor:
- The Hypervisor is a smart software that divides the physical computer resources and runs the virtual computers.
### Capital Expenditure(capex) and Operational Expenditure(opex):
- Capex: It is a big and one time investment to buy or own something.
    - Ex: Buying physical servers, network devices etc.
- Opex: Small and repetitive expenses to use something where we can use and pay for that.
    - Ex: Electricity bills, Internet charges, monthly cloud services rent, maintenance charges etc.  
