# 📘 ERM Mapping Guidelines for Labs

## 🎯 Purpose
This document serves as the **standard reference** for mapping:
- **Intended Audience**
- **Azure Services & Products**

for all **new lab additions** to the catalog.

All mappings **must strictly use the values defined in the ERM database**.

---

## ⚠️ Mandatory Guidelines

- ✅ Only use **predefined values** from ERM (listed below)
- ❌ Do NOT create new audience types or service names manually
- 📌 If a required value is missing:
  - Contact your **team leads**
  - Raise a request to get it added via the **Engineering team in ERM database**

---

## 👥 Intended Audience (ERM Approved List)

Use only from the below list:

| Column 1 | Column 2 | Column 3 | Column 4 |
|----------|----------|----------|----------|
| .NET Developers | AI Architects | AI Data Scientists | AI Developers |
| AI Engineers | AI Enthusiasts | Analysts | Application Developers |
| Architects | Azure Administrators | BI Developers | Business Analysts |
| Business Professionals | Call Center Managers And Supervisors | Citrix Administrators | Cloud Administrators |
| Cloud Architects | Cloud Consultant | Cloud Engineers | Cloud Solution Architects |
| Customer Support Managers | Cybersecurity Specialists | Data Analysts | Data Architects |
| Data Engineers | Data Scientists | Database Administrators | Database Admins |
| Database Developers | Developers and Programmers | DevOps/DevSecOps Practioners | Educational Institution |
| Educators and Students | Infrastructure Analysts | Infrastructure Managers | IT Administrators |
| IT Directors | IT Managers | IT Professionals | IT Security Professionals |
| Linux System Administrators | Machine Learning Enthusiasts | Managed Service Providers (MSPs) | Network Administrators |
| NLP Enthusiasts | Power Users | Product Managers | Researchers |
| Security Analysts | Security Engineers | Security Professionals | Security Solution Architect |
| Software Architects | Software Developers | Software Engineers | Solution Architects |
| SQL Developers | System Administrators | System Engineers | Tech Professional |
| Technical Enthusiasts | Web Developers | AI Developers and Engineers | Automation Engineers |
| Java Developers | Students and Researchers | Enterprise Engineers | IT Admins |
| Data Scientists and Machine Learning Engineers | Developers and DevOps Engineers | Operations Team | Students and Learners |
| Industry Solutions | Open Source Contributors | Business Analysts and IT Professionals | Data Engineers and Data Scientists |
| Enterprise Architects | SAP Customers and Partners | SAP Developers and Consultants | Customer Success Managers |
| Strategists | HR Professionals | Enterprise IT Team | Infrastructure Architects and Enterprise Customers |
| Platform Engineers | Development teams | ISVs | IT Teams |
| IT Architects | Virtualization Specialists | DevOps Professionals | Database Practitioners |
| Cloud-native Developer | Advanced Analysts | Security-focused Architects | Cloud Practitioners |
| Innovation Leaders | Sales and Customer Success Professionals | DevSecOps Teams | Decision-Makers |
| Support Analysts | Citizen Developers | Solution Designers | Machine Learning Developers |
| Power BI professionals | CISOs & Security Leaders | Cloud Security Analysts | Data Governance Leads |
| Security Operations Center (SOC) Teams | AI/ML Engineers | GitHub Administrators | API Engineers |
| Business and Technical Decision Makers and Professionals | Power Platform Developer | Engineering Managers | Pre-Sales Consultants |
| Data Security | QA/Test Engineers | Account Managers | Administrators |
| Business Administrators | Business Leaders | Business Technologists | Business Users |
| CISOs | Cloud Consultants | Cloud Professionals | Compliance Officers |
| Consultants | Customer Success Teams | Cybersecurity Managers | Cybersecurity Professionals |
| Data Professionals | Department Heads | Digital Transformation Managers | Domain Experts |
| Educators | Financial Analysts | HR Managers | Industry Professionals |
| Infrastructure Engineers | IT Consultants | IT Operations Managers | IT Operations Teams |
| Marketing Managers | Marketing Professionals | Microsoft 365 / Copilot Program Owners | Microsoft 365 Administrators |
| ML Engineers | Modern Work Leads | Modern Work Professionals | Network Architects |
| Operations Specialists | Platform Owners | Pro Developers | Programmers |
| Risk Specialists | SecOps Teams | Security Administrators | Security Architects |
| Security Consultants | Security Leaders | Security Managers | SOC Teams |
| Solution Developers | Talent Acquisition Teams | Technical Analysts | Technical Consultants |
| Technical Managers | Technical Professionals | Technologists | Technology Enthusiasts | 

---

## ☁️ Azure Services & Products (ERM Approved List)

Use only from the below list:

| Column 1 | Column 2 | Column 3 | Column 4 |
|----------|----------|----------|----------|
| ADLS Gen2 Connectivity | Anomaly Detector | Application Insights | Microsoft Entra ID |
| Azure Arc | Azure Arc-Enabled Data Services | Azure Cosmos DB | Azure Database For MySQL |
| Azure Database For Postgres SQL | Azure Database Migration Service | Azure Load Testing | Log Analytics Workspaces |
| Azure Migrate | Azure OpenAI | Azure SQL | Azure SQL Database |
| Azure SQL Managed Instance | Azure SQL Migrate | Azure SQL Server | Azure Synapse Analytics |
| Azure Virtual Desktop | Docker | GitHub | GitHub CI/CD |
| GitHub Copilot | GitOps | Microsoft Defender For Cloud | Microsoft Dev Box |
| Microsoft Fabric | Microsoft Power Platform | Microsoft Sentinel | Power Automate |
| Power BI | PowerApps | Private DNS Zone | Route Table |
| Site Recovery | Streamlit | Virtual Network Gateway | Azure PostgreSQL Databases |
| Azure Spring Apps | App Services | ARO Cluster | Microsoft Foundry |
| Azure DevOps | Key Vault | Load Balancer | SQL Server Databases |
| Microsoft 365 E5 License | Microsoft Sustainability Trial | GitHub Advanced Security (GHAS) | Container Registry |
| GitHub Actions & Workflows | Microsoft 365 Copilot | Microsoft 365 applications | Microsoft Copilot Studio |
| Semantic Kernel | Dall-E | Text Embedding | RAG |
| Azure Local | Flexible Server | Azure Red Hat | OpenShift cluster |
| Azure CosmosDB for MongoDB | Microsoft Purview | Enterprise Mobility + Security E5 | Entra P2 License |
| Custom Vision | Microsoft Priva | Azure cyclecloud for Slurm | AI Search |
| Azure Active Directory Domain Services | Azure Application Gateway | Azure Arc-enabled SQL Server | Azure Automation |
| Azure Batch | Azure Bicep | Azure Blob Storage | Azure Communication Services |
| Azure Container Apps | Azure Container Registry | Azure Content Delivery Network (CDN) | Azure Cosmos DB for MongoDB |
| Azure Data Explorer | Azure Data Migration Assistant | Azure Database for MySQL/PostgreSQL | Azure Database for PostgreSQL |
| Azure Database for PostgreSQL – Flexible Server | Azure DNS Private Resolver | Azure Event Hubs | Azure Functions |
| Azure IoT Hub | Azure Key Vault | Azure Kubernetes Service (AKS) | Azure Landing Zone (CAF) |
| Azure Log Analytics | Azure Managed Identity | Azure Policy | Azure Private DNS Zone |
| Azure Recovery Services Vault | Azure Red Hat OpenShift | Azure Route Table | Azure Site Recovery |
| Azure SQL Migration Extension | Azure Stream Analytics | Azure Virtual Machine Scale Sets | Azure Virtual Machines |
| Azure Virtual Network Gateway | Azure Virtual WAN | Azure VPN Gateway | Bing Search API |
| Content Safety | Data Migration Assistant | Dataverse | DNS Forwarding Ruleset |
| Document Intelligence | Face API | GitHub (GitOps) | GitHub Actions |
| GitHub Advanced Security | Hyper-V | Microsoft 365 Applications (Teams, Outlook, Word, Excel, PowerPoint) | Microsoft 365 E5 |
| Microsoft Copilot for Security | Microsoft Defender for Cloud - CSPM | Microsoft Defender for Endpoint | Microsoft Defender for Identity |
| Microsoft Defender for Office 365 | Microsoft Entra ID P2 | Microsoft Graph | Microsoft Intune |
| Microsoft Power Automate | Microsoft Sustainability Manager | Microsoft Teams | OneLake |
| Outlook | Power Apps | SharePoint | Translator |
| Visual Studio Code |  |  |  |  

---

## 🔄 Mapping Workflow

1. Identify lab scenario and objectives  
2. Select:
   - Relevant **Intended Audience**
   - Relevant **Azure Services & Products**
3. Validate against ERM list  
4. If missing:
   - ❗ Do NOT proceed with custom values  
   - 📩 Contact Leads → Raise ERM update request  

---

## 🚫 Common Mistakes to Avoid

- Creating new audience labels (e.g., "AI Beginners")  
- Using slightly modified names (e.g., "Azure Open AI" instead of "Azure OpenAI")  
- Not validating against ERM before publishing  

---

## 📩 Support

For additions or corrections:
- Contact your **Practice/Program Leads**
- Submit request to **Engineering Team (ERM DB updates)**
