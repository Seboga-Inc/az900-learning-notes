# 01 – Describe Cloud Concepts 

##  Skills Measured

- Describe the benefits and considerations of using cloud services
- Describe the differences between categories of cloud services (IaaS, PaaS, SaaS)
- Describe the differences between types of cloud computing (public, private, hybrid)

---

##  Checklist

- [x] CapEx, OpEx and Consumption-based - https://youtu.be/WiwV9wb0GMo [00:07:13]
- [X] Differences Between Cloud Service Categories - https://youtu.be/IqQC1EOQqeU [00:15:16]
- [X] Identify the Right Service Type - https://youtu.be/KH8NH76h2vc [00:04:01]
- [X] Differences Between Types of Cloud Computing - https://youtu.be/7dlCrF2wmXU [00:12:41]
- [X] Benefits of High Availability and Scalability in the Cloud - https://youtu.be/JRbhGzGzoOA [00:15:24]
- Reliability and Predictability - https://youtu.be/kD2YqdDaO1w [00:07:16]

---

##  Benefits of Cloud Computing

- **High availability**: When events occur of disruption the service keep functing, the need for muliple resources across regions* 
- **Scalability**: Scale up/down based on demand: vertical (more CPU or memory) or horizontal (additional CPU or memory)
- **Agility**: Quickly deploy and experiment
- **Fault tolerance**: Automatic failover systems
- **Disaster recovery**: Backup and restore options
- **Elasticity**: Auto-scale services
- **Cost efficiency**: Pay-as-you-go model
- **Security**: Built-in security controls

## CapEx, OpEx and Consumption-based

| Type    | Description | Example |
|---------|-------------|---------|
| CapEx | Capital Expenditure | On-premises, purchage upfront | 
| OpEx  | Operateional Expenditure  | Cloud , purchace service based | 

Consumption-based: i pay for what i'm using, this moment is time 

---

## Cloud Service Categories 

The shared responsibility model:
The line of reponsibility shifts: think about the layers [top-bottom] data - application - runtime - OS - vM - compute - network - storage
On-premisese - IaaS - Paas - Saas

| Model | Description | Example Services |
|-------|-------------|------------------|
| IaaS  | Infrastructure as a Service, most flexible – provides VMs, compute networking, storage | Azure VMs, Virtual Network, Load Balancer |
| PaaS  | Platform as a Service, less reponsbility – focus on apps & data, not infra | Azure App Services, Azure SQL, AzureKubernetes (AKS) |
| SaaS  | Software as a Service – fully managed apps, delivers business value, no responsiblity | Microsoft 365, Outlook.com |

Serverless computing (PaaS): 
Event driven: pay for the work that is done (CPU service), i dont pay for it messages, schudele events
e.g. Azure Functions; LogicApps

Sevice type based on a use case:
Based on the repsoniblity of the layer

---

## Types of Cloud Computing

Cloud Computing: 
(consists of)
  - Pooling Resources: created efficiency and capacity & elasticity & agility
  - Self service: e.g. quotas, policies; on demand
  - Showback/chargeback  

| Type    | Description | Example | 
|---------|-------------|---------|
| Public  | Services available to the public over the internet | Azure, AWS | Over the internet, limitless | 
| Private | Dedicated cloud infrastructure for one org | On-premise Azure Stack | Fixed set of service | 
| Hybrid  | Combines on-prem and cloud | Management (policies) on cloud e.g. Azure Arc, Azure Stack, hybrid apps |


---


## Notes to Self

- Practice quiz: cloud models and benefits
- Watch short video on scalability vs elasticity

---

## Useful Links

- [Microsoft Learn: Cloud Concepts](https://learn.microsoft.com/en-us/training/modules/intro-to-azure-fundamentals/)
