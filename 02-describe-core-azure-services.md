# 02 – Describe Core Azure Services 🔧

## 🎯 Skills Measured

- Describe the core architectural components of Azure
- Describe core Azure compute and networking services
- Describe core Azure storage services
- Describe core Azure database services

---

## 🧱 Azure Architecture Components

### 🔹 Azure Regions
- Physical locations around the world
- Data centers grouped by geography
- Examples: West Europe, East US, North Europe

### 🔹 Availability Zones
- 1+ datacenters within a region
- Provide redundancy and fault isolation
- Used for high-availability apps

### 🔹 Resource Groups
- Logical containers for Azure resources
- Used for organizing and managing permissions, cost, and automation

### 🔹 Azure Resource Manager (ARM)
- Deployment and management service
- Uses **JSON templates** (ARM templates)

---

## 🖥️ Core Azure Compute Services

| Service | Description | Use Case |
|--------|-------------|----------|
| **Azure Virtual Machines (VMs)** | IaaS compute with full OS control | Lift-and-shift workloads |
| **App Service** | PaaS for hosting web apps and APIs | Web apps, REST APIs |
| **Azure Container Instances** | Lightweight container hosting | Quick container runs |
| **Azure Kubernetes Service (AKS)** | Orchestrated container management | Microservices architecture |
| **Azure Functions** | Serverless code that runs on-demand | Event-driven apps |

---

## 🌐 Core Azure Networking Services

| Service | Description | Use Case |
|--------|-------------|----------|
| **Virtual Network (VNet)** | Private network space in Azure | Network isolation |
| **Load Balancer** | Distributes traffic across resources | High availability |
| **VPN Gateway** | Secure connection to on-prem network | Hybrid cloud |
| **ExpressRoute** | Private connection bypassing the internet | Low-latency critical apps |
| **Azure DNS** | DNS hosting service in Azure | Domain resolution |

---

## 💾 Core Azure Storage Services

| Service | Description | Use Case |
|--------|-------------|----------|
| **Blob Storage** | Object storage for unstructured data | Images, logs, backups |
| **File Storage** | Managed file shares with SMB protocol | Lift-and-shift file shares |
| **Disk Storage** | Persistent storage for VMs | OS and data disks |
| **Archive Storage** | Long-term cold storage | Backups, compliance data |

---

## 🗄️ Core Azure Database Services

| Service | Description | Use Case |
|--------|-------------|----------|
| **Azure SQL Database** | Fully managed relational DB (PaaS) | Web apps, SaaS solutions |
| **Azure Cosmos DB** | Globally distributed NoSQL DB | IoT, personalization |
| **Azure Database for MySQL/PostgreSQL** | Managed open-source databases | OSS workloads |
| **SQL Managed Instance** | Hybrid of IaaS and PaaS SQL | Legacy migration with SQL features |

---

## 📎 Useful Links

- [Microsoft Learn – Core Azure Services](https://learn.microsoft.com/en-us/training/modules/azure-architecture-fundamentals/)
- [Azure Regions Interactive Map](https://azure.microsoft.com/en-us/explore/global-infrastructure/geographies/)
- [What is Azure?](https://azure.microsoft.com/en-us/resources/cloud-computing-dictionary/what-is-azure/)

---

## 📌 Notes to Self

- Look up VMs vs App Services comparison
- Try out Blob storage in Azure Portal
- Understand what Cosmos DB is optimized for

---

_This file is part of my AZ-900 learning repo. See the full [index here](README.md)._
