# Cloud Concepts (25–30%)

## Define Cloud Computing
Cloud computing is the delivery of computing services over the internet. Computing services include common IT infrastructure such as virtual machines, storage, databases, and networking. Cloud services also expand the traditional IT offerings to include things like Internet of Things (IoT), machine learning (ML), and artificial intelligence (AI).

## Describe the Shared Responsibility Model
The **Shared Responsibility Model** is a cloud security framework that defines which responsibilities are handled by the cloud provider and which are handled by the customer.

### 🔥 Cloud Provider Responsibilities
- Physical security (datacenter, power, cooling).
- Physical network (cables, routers, connectivity).
- Physical hosts (servers and storage).

### 🔒 Customer Responsibilities
- Data security (protecting your data in the cloud).
- Access control (who can access your cloud resources).
- Devices (computers, phones connecting to the cloud).
- Accounts & identities (managing users and permissions).

> **Key Rule:** The more cloud-managed the service, the less you are responsible for.

## Define Cloud Models, Including Public, Private, and Hybrid

### Public Cloud
- No capital expenditures to scale up.
- Provides the most flexibility.
- Applications can be quickly provisioned and deprovisioned.
- Organizations pay only for what they use.
- Data is not collocated with other organizations’ data.

### Private Cloud
- Organizations have complete control over resources and security.
- Hardware must be purchased for startup and maintenance.
- Organizations control security, compliance, or legal requirements.
- Organizations are responsible for hardware maintenance and updates.

### Hybrid Cloud
- Organizations determine where to run their applications.
- Organizations don’t have complete control over resources and security.
  
## Multi-Cloud
Utilizing multiple public cloud providers.

### Azure ARC
A set of technologies that help manage your cloud environment, whether **public, private, hybrid, or multi-cloud**.

## Describe the Consumption-Based Model

**CapEx (Capital Expenditure):** Typically a one-time, up-front expenditure to purchase or secure tangible resources, such as:
- A new building.
- Repaving the parking lot.
- Building a datacenter.
- Buying a company vehicle (On Premise).

**OpEx (Operational Expenditure):** Spending money on services or products over time. Examples include:
- Renting a convention center.
- Leasing a company vehicle.
- Signing up for cloud services (Cloud).

Cloud computing falls under **OpEx** because it operates on a consumption-based model. With cloud computing, you don’t pay for the physical infrastructure, the electricity, the security, or anything else associated with maintaining a datacenter. Instead, you pay for the IT resources you use. If you don’t use any IT resources this month, you don’t pay for any IT resources.

### Benefits of the Consumption-Based Model
- No upfront costs.
- No need to purchase and manage costly infrastructure that users might not use to its fullest potential.
- Ability to pay for more resources when needed.
- Ability to stop paying for resources that are no longer needed.

## Compare Cloud Pricing Models
Cloud computing is the delivery of computing services over the internet by using a **pay-as-you-go** pricing model. You typically pay only for the cloud services you use, which helps you:
- Plan and manage your operating costs.
- Run your infrastructure more efficiently.
- Scale as your business needs change.

To put it another way, cloud computing is a way to rent compute power and storage from someone else’s datacenter.

## Describe Serverless Computing
A cloud computing model that allows developers to build applications without managing infrastructure.

## Describe the Benefits of High Availability and Scalability in the Cloud

### High Availability
Focuses on ensuring maximum availability, regardless of disruptions.

### Scalability
The ability to adjust resources to meet demand and to add more resources to better handle increased demand.

- **Vertical Scaling:** Increasing or decreasing the capabilities of resources (e.g., adding or lowering CPU or RAM).
- **Horizontal Scaling:** Adding or subtracting the number of resources (e.g., adding or subtracting virtual machines or containers).

## Describe the Benefits of Reliability and Predictability in the Cloud

### Reliability
The ability of a system to recover from failures and continue to function. It's also one of the pillars of the Microsoft Azure Well-Architected Framework. With a decentralized design, the cloud enables you to have resources deployed in regions around the world. Even if one region experiences a catastrophic event, other regions remain operational.

## Describe Predictability in the Cloud

### Performance Predictability
Performance predictability focuses on predicting the resources needed to deliver a positive experience for your customers. Cloud concepts like autoscaling, load balancing, and high availability support performance predictability.

### Cost Predictability
Cost predictability focuses on forecasting cloud spend. By using cloud analytics and information, you can predict future costs and adjust resources as needed. Tools like the **Total Cost of Ownership (TCO)** or **Pricing Calculator** can help estimate potential cloud spend.

---

## Describe the Benefits of Security and Governance in the Cloud

### 1. Governance and Compliance Support
- **Predefined Templates:** Cloud services often come with set templates that help ensure deployed resources meet corporate standards and government regulatory requirements, making it easier to maintain compliance across the organization.
  
- **Automatic Updates:** Cloud platforms allow for the automatic update of deployed resources to meet the latest compliance standards, ensuring your infrastructure stays aligned with evolving regulations.
  
- **Cloud-based Auditing:** Continuous monitoring tools flag any out-of-compliance resources and provide mitigation strategies to address issues quickly.

### 2. Security Flexibility
- **Customizable Security Levels:** Whether using **IaaS**, **PaaS**, or **SaaS**, you can choose a cloud solution that fits your security needs.

  - **IaaS (Infrastructure as a Service):** Gives you full control over security, allowing you to manage operating systems and installed software, including patches and updates. Ideal for those who want maximum control over security.
  
  - **PaaS and SaaS:** Offer automatic patches and maintenance, reducing your security workload while ensuring updates are applied without manual intervention.

### 3. Enhanced Network Security
- **DDoS Protection:** Cloud providers are typically equipped to handle Distributed Denial of Service (DDoS) attacks, providing an added layer of protection to your network and making it more secure against malicious disruptions.

---

## Describe the Benefits of Manageability in the Cloud

### Management of the Cloud - Managing Cloud Resources
- Automatically scale resource deployment based on need.
- Deploy resources based on a preconfigured template, removing the need for manual configuration.
- Monitor the health of resources and automatically replace failing resources.
- Receive automatic alerts based on configured metrics to stay aware of performance in real time.

### Management in the Cloud - How You’re Able to Manage Your Cloud Environment and Resources
You can manage your resources via:
- Web portal
- Command line interface (CLI)
- APIs
- PowerShell

---

## Describe Cloud Service Types

### ✅ Infrastructure as a Service (IaaS)

**What is IaaS?**
IaaS is the most flexible cloud service model, giving you control over your resources. It’s like renting hardware from a cloud provider and managing everything else.

#### Provider Responsibilities:
- Hardware maintenance (servers, storage, etc.)
- Network connectivity (to the internet)
- Physical security (datacenter safety)

#### Your Responsibilities:
- Installing and maintaining the operating system
- Configuring networks
- Setting up databases and storage
- Managing other software configurations

---

### ✅ Platform as a Service (PaaS)

**What is PaaS?**
PaaS provides a ready-to-use environment for building and deploying applications without managing the underlying infrastructure. It’s the middle ground between IaaS (renting hardware) and SaaS (fully managed solutions).

#### Provider Responsibilities:
- Physical infrastructure & security
- Network connectivity
- Operating systems & middleware
- Development tools & databases
- Licensing & patching

#### Your Responsibilities:
- Developing and managing applications
- Configuring settings for your needs

> **Key Idea:** PaaS gives you a fully managed development environment, so you can build applications without worrying about infrastructure maintenance.

PaaS provides a development framework that allows developers to create or customize cloud-based applications using built-in software components. Cloud features like scalability, high-availability, and multi-tenant capability are included, reducing the amount of coding required.

---

### ✅ Software as a Service (SaaS)

**What is SaaS?**
SaaS is the most complete cloud service model, offering fully developed applications you rent or use directly, such as email, financial software, messaging apps, and connectivity tools.

#### Provider Responsibilities:
The cloud provider handles everything.

## Application Management

### Maintenance & Updates
In **SaaS**, maintenance and updates are entirely managed by the cloud provider. You simply use the application, with no infrastructure management required.

> **Key Idea:** SaaS is the easiest model to implement, as everything is already built and managed for you, requiring little to no technical expertise.

### Security
Security is handled by the cloud provider in SaaS. Your responsibility is limited to how you use the application and ensuring that your credentials and access control measures are securely implemented.

---

## Describe Azure Management and Governance (30–35%)

### Describe Factors That Can Affect Costs in Azure

Several factors influence operational expenses (OpEx) in Azure. These factors include:

- **Resource Type:** Every Azure resource is metered, tracking usage to calculate billing.
  
- **Consumption:** With Azure's pay-for-what-you-use model, you can save costs for consistent workloads and scale resources flexibly as needed.
  
- **Maintenance:** Regularly reviewing your resources helps eliminate unnecessary costs from unused or underused resources.
  
- **Geography:** Costs vary by region due to differences in power, labor, taxes, and fees.
  
- **Subscription Type:** Different Azure subscription models come with usage allowances that affect pricing.
  
- **Azure Marketplace:** When purchasing solutions from third-party vendors, costs may include both Azure services and vendor fees.

---

### Compare the Pricing Calculator and the Total Cost of Ownership (TCO) Calculator

#### **Pricing Calculator**
- Helps estimate the cost of provisioning Azure resources.
- Used for calculating expenses across compute, storage, networking, and more.
- Customizable for storage type, access tier, and redundancy options.
- Ideal for planning Azure spending before deployment.

#### **TCO (Total Cost of Ownership) Calculator**
- Helps compare on-premises versus Azure Cloud costs.
- Requires input on current servers, databases, storage, and network traffic.
- Factors in costs such as power, IT labor, and maintenance.
- Provides an estimate of potential cost savings when migrating to Azure.
- Useful for businesses considering long-term cloud migration and cost efficiency.

---

### Describe Cost Management Capabilities in Azure

Azure offers several tools for monitoring and controlling resource costs:

#### **Cost Management in Azure**
- Monitors and manages Azure resource costs.
- Sets up alerts based on spending limits.
- Allows budgeting for automated resource management.

#### **Cost Analysis**
- A feature within Cost Management that provides visual insights into Azure costs.
- Allows filtering of costs by billing cycle, region, and resource.
- Tracks spending trends over time and helps forecast costs for different periods (monthly, quarterly, yearly).

#### **Cost Alerts in Azure**
Azure offers three types of alerts to monitor spending:

1️⃣ **Budget Alerts:** Notifies you when spending reaches or exceeds a preset budget based on usage or cost.

2️⃣ **Credit Alerts:** Triggers when Azure credit (for Enterprise Agreements) is 90% or 100% consumed.

3️⃣ **Department Spending Quota Alerts:** Warns when a department reaches its preset spending limit.

---

### Describe the Purpose of Tags

Tags help organize, manage, and optimize cloud resources by adding metadata. They provide valuable insights and improve cost tracking, security, and compliance.

- **Resource Management:** Easily locate and manage resources by workload, environment, or owner.
  
- **Cost Management:** Group resources for cost reporting, budget tracking, and forecasting.

- **Operations Management:** Classify resources based on business-critical importance to define SLAs.

- **Security:** Label resources based on sensitivity levels (e.g., Public, Confidential).

## Governance & Compliance

### Identify Resources Aligned with Regulatory Requirements
Regulatory compliance is essential for cloud resources, particularly when dealing with sensitive data. Examples include aligning with ISO 27001, GDPR, or other industry standards. Tags can help organize resources based on these requirements.

---

### Automation & Optimization
By tagging resources, you can efficiently manage workloads, automate processes, and improve resource allocation for optimization.

💡 **Tags enhance visibility, streamline management, and improve cloud governance!** 🚀

### How to Manage Resource Tags
You can add, modify, or delete resource tags through various methods:
- **Windows PowerShell**
- **Azure CLI**
- **Azure Resource Manager templates**
- **REST API**
- **Azure Portal**

To ensure compliance with tagging rules, you can also use **Azure Policy** to enforce specific conventions and standards for your resources.

---

## Describe Features and Tools in Azure for Governance and Compliance

### Describe the Purpose of Microsoft Purview in Azure

#### **Microsoft Purview: Data Governance & Compliance**
Microsoft Purview is a comprehensive solution for data governance, risk management, and compliance. It provides a unified view of data across on-premises, multicloud, and SaaS environments, ensuring security and compliance.

#### **Risk & Compliance Solutions**
Microsoft Purview integrates with Microsoft 365 services like Teams, OneDrive, and Exchange to:
- Protect sensitive data across clouds, apps, and devices.
- Identify risks and manage regulatory compliance needs.
- Simplify compliance with built-in regulatory tools.

#### **Unified Data Governance**
Purview enables seamless data management and security across Azure, SQL, Hive, Amazon S3, and on-premises environments, helping to:
- Map your entire data estate with classification and lineage tracking.
- Identify sensitive data across your organization.
- Provide secure data access while ensuring compliance.
- Generate insights on data storage and usage patterns.
- Manage access at scale to enhance security.

---

### Describe the Purpose of Azure Policy

#### **Azure Policy Overview**
Azure Policy is a service that helps define and manage rules (policies) to control and monitor your resources in Azure, ensuring that your resources comply with specific standards and requirements.

#### **Key Functions of Azure Policy:**
- **Create and Assign Policies:** You can define individual policies or group them into initiatives (sets of related policies).
- **Compliance Monitoring:** Azure Policy evaluates resources to check compliance. Non-compliant resources are flagged, and the creation of non-compliant resources can be prevented.
- **Scope:** Policies can be applied at different levels, such as resource groups, subscriptions, or individual resources, with inherited policies from higher levels.
- **Built-In Policies:** Azure provides built-in policies for common areas like storage, networking, compute, security, and monitoring.
- **Automatic Remediation:** Some policies can automatically fix non-compliant resources (e.g., adding missing tags).
- **Exceptions:** Policies can be exempted from automatic remediation for specific resources.
- **Integration with Azure DevOps:** Policies can be enforced during pre- and post-deployment phases in Azure DevOps.

#### **Azure Policy Initiatives:**
An initiative is a collection of related policies grouped together. Initiatives help manage policies at a larger scale to ensure consistent security and monitoring. Examples include:
- Monitoring unencrypted SQL databases
- Monitoring OS vulnerabilities
- Monitoring missing endpoint protection

---

### Describe the Purpose of Resource Locks

Resource Locks in Azure prevent critical resources from being accidentally deleted or modified, even when users have appropriate permissions through Azure role-based access control (RBAC). Resource locks help protect against accidental or unauthorized changes.

#### **Purpose of Resource Locks:**
- **Protection from Accidental Changes:** Locks safeguard resources from being deleted or updated, reducing the risk of accidental or unauthorized modifications.
- **Applied at Multiple Levels:** Locks can be applied to individual resources, resource groups, or entire subscriptions. If applied to a resource group, all resources within that group inherit the lock.

#### **Types of Resource Locks:**
1. **Delete Lock:** Prevents the deletion of a resource but still allows for reading and modifying it. This lock is useful for avoiding accidental deletion while maintaining flexibility for modifications.
   
2. **ReadOnly Lock:** Prevents modification or deletion of a resource but allows it to be read. This is similar to the "Reader" role permissions, where users can only view the resource without making changes.

## Managing Resource Locks

### Managing Locks:
Resource locks can be managed via various tools:
- **Azure Portal**
- **PowerShell**
- **Azure CLI**
- **Azure Resource Manager templates**

To manage locks in the Azure portal, navigate to the **Settings** section of the resource's settings pane.

### Modifying or Deleting a Locked Resource:
To make changes to a locked resource, you need to remove the lock first. Once the lock is removed, you can perform the action as long as you have the necessary permissions.

**Note:** Resource locks override RBAC permissions. Even if you're an owner of a resource, you must remove the lock before making changes.

By using resource locks, you ensure that critical resources are protected, reducing the risk of errors in managing cloud infrastructure.

---

### Microsoft Service Trust Portal
The Microsoft Service Trust Portal provides access to various content, tools, and resources related to Microsoft’s security, privacy, and compliance practices.

---

## Features and Tools for Managing and Deploying Azure Resources

### Azure Portal
The Azure portal is a web-based, unified console that provides a graphical interface for managing your Azure subscription and resources. It offers an alternative to command-line tools, making it easier to manage cloud services without needing scripting or coding expertise.

#### **Key Features:**
- **Manage and Monitor:** Allows you to build, configure, and monitor everything from simple applications to large-scale cloud deployments.
- **Custom Dashboards:** Enables you to create personalized views of your resources for easier management.
- **Accessibility Options:** Provides settings to optimize the user experience for individuals with specific needs.

### Azure Cloud Shell
Azure Cloud Shell is a browser-based command-line tool that allows you to manage Azure resources using either **Azure PowerShell** or the **Azure Command-Line Interface (CLI)**. 

#### **Key Features:**
- **No Installation Required:** Access directly from the Azure portal.
- **Supports Both Azure PowerShell & Azure CLI:** Choose between PowerShell cmdlets or Bash commands.
- **Authenticated Session:** Automatically connects with your Azure credentials when logged in.

#### **Azure PowerShell:**
Azure PowerShell is a command-line tool for developers, IT professionals, and DevOps engineers to automate Azure tasks using PowerShell cmdlets.

- **Key Features:**
  - Uses cmdlets to interact with the Azure REST API to perform tasks.
  - Supports scripting for repeatable automation.
  - Available on Windows, Linux, and macOS.

#### **Azure CLI:**
Azure CLI is an alternative to Azure PowerShell, using Bash commands instead of PowerShell cmdlets. It is functionally similar to Azure PowerShell but uses Bash syntax.

- **Key Features:**
  - Used for both individual commands and complex automation.
  - Available on Windows, Linux, and macOS.
  - Can be accessed via Azure Cloud Shell.

---

### Azure Arc
Azure Arc extends Azure's compliance, governance, and monitoring to hybrid and multi-cloud environments. It allows you to manage non-Azure resources using Azure Resource Manager (ARM), offering a unified approach to managing IT infrastructure across on-premises, multi-cloud, and edge locations.

#### **Key Features of Azure Arc:**
- **Unified Management:** Manage on-premises and multi-cloud resources as if they were in Azure.
- **Consistent Governance:** Apply Azure Policy, RBAC, and security compliance across all environments.
- **Hybrid Cloud Flexibility:** Run Azure services anywhere, even outside of Azure.
- **DevOps & Automation:** Supports both traditional IT operations and DevOps practices.
- **Custom Locations:** Manage Kubernetes clusters and extensions in non-Azure environments.

#### **What Can Azure Arc Manage Outside of Azure?**
Azure Arc supports managing the following resources hosted outside of Azure:
- **Servers (physical and virtual)**
- **Kubernetes clusters**
- **Azure Data Services**
- **SQL Server**
- **Virtual Machines (Preview)**

---

## Infrastructure as Code (IaC)

Infrastructure as Code (IaC) refers to managing your IT infrastructure using code instead of manual processes.

#### **Basic Level:**
- Use tools like **Azure Cloud Shell**, **PowerShell**, or **Azure CLI** to configure resources manually.

#### **Advanced Level:**
- Automate entire deployments with templates that ensure consistency and repeatability.

#### **Examples in Azure:**
- **ARM Templates** (JSON-based) 
- **Bicep** (simpler code)

IaC enables faster, more reliable, and scalable setup and maintenance of cloud resources.

---

## Azure Resource Manager (ARM) and ARM Templates

**Azure Resource Manager (ARM)** is the deployment and management service for Azure. ARM allows you to manage your Azure resources (such as VMs, storage accounts, and networking) through a consistent interface, providing features like resource grouping, role-based access control (RBAC), and policy enforcement.

#### **ARM Templates:**
- ARM templates are **JSON-based files** that define the infrastructure and configuration of Azure resources.
- They help automate the deployment and configuration of resources in a consistent, repeatable way.
- You can use ARM templates to deploy a wide variety of resources in Azure, ensuring that your infrastructure is version-controlled and reusable.
  
**Bicep** is a simpler, more readable language for defining Azure resources, providing a more user-friendly alternative to JSON-based ARM templates.

## Azure Resource Manager (ARM)

Azure Resource Manager (ARM) is the centralized management layer for Azure. It is responsible for deploying, managing, and organizing all Azure resources. Anytime you interact with Azure—whether through the portal, CLI, PowerShell, or APIs—ARM handles the request.

### Key Benefits of ARM:
- **Consistent Management:** All Azure tools interact with resources via ARM, ensuring uniform behavior.
- **Group Resource Management:** Resources can be managed as a single unit, simplifying deployment.
- **Role-Based Access Control (RBAC):** Security and access are built-in, allowing permissions to be assigned to users or groups.
- **Cost & Organization Tools:** Tags and resource groups help categorize resources for better billing and tracking.

---

## ARM Templates

ARM templates are **JSON-based declarative files** that define Azure infrastructure. They describe what resources should be deployed without requiring step-by-step commands.

### Benefits of ARM Templates:
- **Simple Syntax:** Define the desired state, and Azure does the rest.
- **Repeatability:** Deploy identical environments consistently.
- **Orchestration:** Handles dependencies automatically, deploying resources in the correct order.
- **Modular & Extensible:** Use linked templates, nested templates, and even integrate PowerShell or Bash scripts.

---

## Bicep: The Easier Alternative to ARM Templates

Bicep is a simpler, more readable language than JSON-based ARM templates. It still uses ARM for deployments but makes writing and managing templates easier.

- **ARM Template:** Written in JSON
- **Bicep:** Uses a simplified syntax, making it easier to write and read.

In short, ARM manages resources, ARM templates automate deployments, and Bicep simplifies the process further. 🚀

---

## Monitoring Tools in Azure

### Azure Advisor

Azure Advisor is a personalized cloud consultant that evaluates your Azure resources and provides recommendations to improve reliability, security, performance, operational efficiency, and cost savings.

- **Automated Recommendations:** Scans your resources and suggests improvements.
- **Personalized Insights:** Tailors recommendations based on your subscriptions and usage.
- **Actionable Guidance:** Provides step-by-step instructions for implementing improvements.
- **Filtering Options:** Allows you to focus on specific subscriptions, resource groups, or services.

### Five Categories of Azure Advisor Recommendations:
- **Reliability (High Availability):** Ensures continuity of critical applications.
- **Security:** Detects threats and vulnerabilities to prevent security breaches.
- **Performance:** Enhances the speed and responsiveness of applications.
- **Operational Excellence:** Improves workflow efficiency and best practices.
- **Cost Optimization:** Identifies ways to reduce spending and improve efficiency.

By following Azure Advisor’s recommendations, you can optimize your cloud environment, improve security, and reduce costs.

---

### Azure Service Health

Azure Service Health helps monitor your cloud environment by providing insights into both the global Azure infrastructure and your specific resources through three key components:

1. **Azure Status:**  
   - Provides a global overview of Azure service health.
   - Displays outages and service disruptions across all Azure regions.
   - Accessible via the **Azure Status** page for real-time updates on widespread incidents.

2. **Service Health:**  
   - Focuses on the Azure services and regions relevant to your deployment.
   - Informs you about outages, planned maintenance, and health advisories.
   - Allows you to set up alerts for service issues affecting your resources.

3. **Resource Health:**  
   - Offers a tailored view of your specific Azure resources (e.g., virtual machines).
   - Helps identify availability issues with individual cloud services.
   - Works alongside **Azure Monitor** to provide alerts on resource health changes.

---

### Azure Monitor: Comprehensive Cloud Monitoring

Azure Monitor is a powerful platform for collecting, analyzing, visualizing, and acting on data from Azure, on-premises, and multi-cloud environments. It helps ensure the performance, availability, and security of your resources through several key components.

1. **Azure Log Analytics:**
   - A tool in the Azure portal for writing and running log queries on data collected by Azure Monitor.
   - Supports both simple queries (sorting, filtering, and analyzing records) and advanced statistical analysis.
   - Provides visualization options, such as charts, to identify trends.
   - Integrates with other Azure Monitor features, such as log query alerts and workbooks.

## 2. Azure Monitor Alerts

Azure Monitor Alerts provide automated notifications triggered when a defined threshold is crossed.

- **Event/Metric Monitoring:** Can monitor logs for specific events or metrics (e.g., alerting when CPU usage exceeds 80%).
- **Real-Time Alerts:** Offers real-time metric-based alerts and complex log-based alerting.
- **Action Groups:** Uses action groups to determine who to notify and what actions to take.
- **Unified Alerting:** Integrated with Azure Monitor, Service Health, and Azure Advisor for unified alerting.

---

## 3. Application Insights

**Application Insights** is a feature of Azure Monitor for monitoring web applications across Azure, on-premises, or other cloud environments.

- **Configuration:** Can be configured via an SDK or Application Insights agent (supports C#.NET, VB.NET, Java, JavaScript, Node.js, and Python).
- **Monitors:**
  - **Request Rates, Response Times, and Failure Rates**
  - **External Dependencies and Their Impact on Performance**
  - **User Behavior, Page Views, and Load Times**
  - **AJAX Calls, Performance Counters, and Network Usage**
  - **Synthetic Transactions:** Simulates user requests during low-traffic periods.

---

## Azure Architecture and Services (35–40%)

### 1. Azure Datacenters

Azure’s datacenters are physical buildings that contain thousands of servers and other hardware to provide cloud computing services.

- **Key Features:**
  - Dedicated power, cooling, and networking for optimal performance.
  - Security measures to protect physical and digital assets.
  - High-speed fiber-optic connections for fast, low-latency communication.
- **Geographic Distribution:** Datacenters are grouped into **Regions** and **Availability Zones** to enhance resiliency.

---

### 2. Azure Regions

Azure Regions are a set of datacenters deployed within a latency-defined perimeter and connected through a dedicated regional low-latency network.

- **Key Features:**
  - Azure balances and assigns resources within each region.
  - Regions are spread globally to ensure redundancy and compliance with data residency laws.

---

### 3. Azure Availability Zones

Availability Zones are physically separate datacenters within an Azure region. They ensure fault tolerance by providing:

- **Key Features:**
  - Independent power, cooling, and networking to prevent a single point of failure.
  - High-speed private fiber-optic connections between zones for fast data transfer.
  - Comprised of one or more datacenters.
  - At least three separate zones in every availability zone-enabled region.

---

### 4. Azure Region Pairs (300+ miles, chosen by Microsoft)

A relationship between two Azure Regions within the same geographic region for disaster recovery purposes.

- **Examples of Azure Region Pairs:**
  - West US ↔ East US
  - Southeast Asia ↔ East Asia
  - Some one-directional region pairs exist, where one region backs up another but not vice versa (e.g., Brazil South is backed up by South Central US but does not back it up in return).

---

### 5. Sovereign Regions

Sovereign regions are isolated from the global Azure infrastructure for compliance and legal purposes. They are operated by special “Trustees.”

- **Examples:**
  - **US Government Regions:** Designed for U.S. government agencies with strict security requirements (e.g., US DoD Central, US Gov Virginia, US Gov Iowa).
  - **China Regions:** Operated through a unique partnership with 21Vianet instead of Microsoft directly (e.g., China East, China North).

---

## Core Architecture Components

### 1. Azure Management Groups

Azure Management Groups provide a hierarchical structure to manage access, policies, and compliance across subscriptions. Each directory has a single top-level management group called **Root**.

- **Key Features:**
  - Can be used to aggregate policy and initiative assignments via **Azure Policy**.
  - Can contain multiple subscriptions.
  - All new subscriptions are placed under a root management group by default.
  - **Role-Based Access Control (RBAC):** Applied at the management group level, which automatically applies to all nested subscriptions, resource groups, and resources.

- **Important Facts about Management Groups:**
  - Up to **10,000 management groups** can be supported within a single Azure directory.
  - A management group tree can have up to **six levels** of depth.
  - Each management group and subscription can only have one parent.

## 2. Azure Subscriptions

An **Azure subscription** is a unit of management, billing, and scale that links to an Azure account. It serves as a management boundary for assigning Azure policies, governance, and isolation.

### Types of Azure Subscription Boundaries:
- **Billing Boundary:** Determines how Azure services are billed. Each subscription generates its own separate billing report and invoice. Multiple subscriptions can be used for different billing needs.
- **Access Control Boundary:** Azure applies access-management policies at the subscription level, meaning you can configure permissions and manage access for users in specific departments or teams within the organization.

---

## 3. Resource Groups

A **Resource Group** is a container that holds related resources for an Azure solution with a common lifecycle. It is used to group resources that share a common resource lifecycle (e.g., VM, network adapter).

---

## 4. Resources (Contained in 1 Resource Group)

A **Resource** is an entity managed by Azure, like a Virtual Machine (VM), virtual network, or storage account. Azure's hierarchy consists of:

- **Management Groups** → **Subscriptions** → **Resource Groups** → **Resources**

---

## Compare Compute Types: Containers, Virtual Machines, and Functions

### 1. Azure Virtual Machines

Azure Virtual Machines provide server virtualization (compute) on-demand without the need for hardware purchase.

- **Virtual Machine Scale Sets:** Allow you to create and manage a group of identical, load-balanced VMs. The number of VM instances can automatically increase or decrease in response to demand or based on a schedule.
  - **Focus:** Scalability, capacity.
- **Virtual Machine Availability Sets:** Help build a more resilient, highly available environment by ensuring varied power and network connectivity.
  - **Focus:** Resiliency (availability).
  - **Update Domains:** Allows you to apply updates while knowing that only one update domain grouping will be offline at a time.
  - **Fault Domains:** Groups your VMs by common power source and network switch. By default, an availability set will split your VMs across up to three fault domains.

---

### 2. Containers – Lightweight, Faster Deployment

A **Container** is like a mini VM, but without a full OS. Instead, it runs just the app and the necessary dependencies, making it much faster and more efficient than a VM.

- Containers are a lightweight way to run apps without needing to manage an entire operating system.

---

### 3. Serverless Functions – Fully Managed, Only Pay for What You Use

A **Function** is a small piece of code that runs only when needed—no need to manage servers at all! Azure automatically scales and runs your function only when triggered.

- **Stateful vs Stateless Functions:**
  - **Stateless:** Runs as if it’s a fresh instance every time.
  - **Stateful (Durable Functions):** Tracks history and maintains state.

---

### Azure Virtual Desktop (AVD)

Azure Virtual Desktop (AVD) is a cloud-based Windows desktop experience that allows users to securely access their apps and files from anywhere.

- Provides a fully managed virtual desktop infrastructure (VDI).
- Supports multi-session Windows 11/10 (many users on a single VM).

---

### Azure Container Instances (ACI)

Azure Container Instances (ACI) runs Docker containers on-demand in a managed, serverless Azure environment. It is a solution for any scenario that operates in isolated containers, without orchestration.

---

### Azure Kubernetes Service (AKS)

Azure Kubernetes Service (AKS) is a hosted Kubernetes service, where Azure handles critical tasks like health monitoring and maintenance for you.

- You pay only for agent nodes within your clusters, not for the masters (free tier).
- For a financially backed SLA, you pay a small fee per hour for cluster management.

---

## Core Services in Azure

### 1. Azure Virtual Networks (VNet)

An **Azure Virtual Network (VNet)** is a logical representation of your network in Azure. It contains one or more **subnets**.

- **Key Features:**
  - VNets provide logical isolation in Azure dedicated to your subscription.
  - Create a dedicated private cloud-only network.
  - Extend your data center with **Site-to-Site VPN**.
  - Enable hybrid cloud scenarios.
  - **Important:** VMs in different VNets cannot communicate by default.

---

### 2. Azure Virtual Subnets

**Azure Virtual Subnets** segment a VNet into smaller networks to organize and manage resources.

- **Key Features:**
  - Allows Azure resource deployment into a specific subnet.
  - Can affect outbound access and routing traffic between resources.
  - **Important:** VMs in different subnets within a VNet can communicate by default.

---

### 3. Virtual Network Peering

**Virtual Network Peering** enables seamless connections between two or more virtual networks in Azure. The two networks function as one in terms of connectivity.

- **Important Reminder:** Resources in different VNets cannot communicate by default.

---

### 4. Azure DNS

**Azure DNS** is a cloud hosting service for DNS domains that provides name resolution using Microsoft Azure infrastructure.

- **Key Features:**
  - Can provide both internal and external DNS.
  - **Important Consideration:** Azure DNS does not offer domain name registration. To register a domain, you can use **Azure App Service Domains** or a third-party registrar. Once registered, you can manage the domain’s DNS records within Azure DNS.

---

### 5. Azure VPN Gateway

An **Azure VPN Gateway** is a virtual network gateway that sends encrypted traffic between an Azure VNet and an on-premises location over the internet.

- **Key Role:** Core component of a hybrid cloud.
- **Site-to-Site VPN:** Traffic traverses the internet.

---

### 6. Azure ExpressRoute

**Azure ExpressRoute** extends your on-premises networks into Azure over a private connection with the help of a connectivity provider. Traffic does **NOT** traverse the internet.

---

### Service Endpoint

**Service Endpoint** provides a way to lock down access to all instances of a PaaS service to a VNet. It is accessible from the public internet.

# Azure Network and Storage Services Overview

## Private Endpoint
- Grants access to a specific instance (resource) of a PaaS service in your VNET on a private IP address.
- Enables access from on-premise without a public endpoint.

## Azure Firewall
- A managed, cloud-based network security service that protects your Azure Virtual Network Resources.
- It is a fully stateful firewall as a service with built-in high availability and unrestricted cloud scalability.

## Azure DDoS
- **Standard Tier**: Provides enhanced DDoS mitigation features to defend against DDoS attacks.
- Includes logging, alerting, and telemetry not included in the free basic tier present by default.

---

# Azure Storage Services

## Azure Storage Account
- A cloud-based resource that provides a unique namespace for your storage data, accessible globally over HTTP or HTTPS.
- The storage within this account is secure, highly available, durable, and scalable.

### Storage Account Endpoints
Every Azure Storage Account has a unique namespace that ensures your data is accessible over the internet.

#### Endpoint Composition:
The storage account name combined with the Azure Storage service endpoint creates the full endpoint for your storage account.

---

## Naming Your Storage Account
When creating a storage account, adhere to these naming rules:
- **Length**: Storage account names must be between 3 and 24 characters long.
- **Characters Allowed**: Only lowercase letters and numbers are allowed. No uppercase letters or special characters.
- **Uniqueness**: The storage account name must be unique within Azure, ensuring a distinct, globally accessible namespace.

---

# Azure Storage Tiers
- **Hot**: Optimized for frequently accessed data.
- **Cool**: Optimized for infrequently accessed data.
- **Cold**: Optimized for rarely accessed or modified data (requires a minimum of 90 days for storage).
- **Archive**: Offline storage for data rarely accessed (requires a minimum of 180 days for storage). This tier has the lowest storage cost but high access costs.

---

# Redundancy Options in Azure Storage

Azure Storage ensures your data is protected through redundancy by replicating it across multiple locations. This guarantees durability and high availability, even during unexpected events such as hardware failures, power outages, or natural disasters. Redundancy choice impacts both cost and availability.

## Redundancy in the Primary Region:
1. **Locally Redundant Storage (LRS)**: Copies your data synchronously 3x within a single physical location in the primary region.
2. **Zone-Redundant Storage (ZRS)**: Copies your data synchronously across 3 Azure availability zones in the primary region.

## Redundancy in the Secondary Region:
1. **Geo-Redundant Storage (GRS)**: Copies your data synchronously 3x within a single physical location in the primary region using LRS, then asynchronously to a secondary region (3 copies).
2. **Geo-Zone-Redundant Storage (GZRS)**: Copies your data synchronously 3x within the primary region using ZRS, then asynchronously to a secondary region.

## Read Access to Data in the Secondary Region
- **RA-GRS (Read-Access Geo-Redundant Storage)**: Allows read access to data in the secondary region, even if the primary region is functioning.
- **RA-GZRS (Read-Access Geo-Zone-Redundant Storage)**: Allows read access to data in the secondary region using ZRS replication.

**Caution**: Data in the secondary region may be slightly out-of-date due to the Recovery Point Objective (RPO).

---

## Choosing the Right Redundancy Option

When selecting the appropriate redundancy option, consider:
- **Cost vs. Availability**: Higher redundancy options often incur higher costs but provide better availability and durability.
- **Replication Needs**: Decide if you need replication only within the primary region (LRS, ZRS) or across regions (GRS, GZRS).
- **Disaster Recovery Requirements**: Consider the importance of immediate read access to data in the secondary region in case of primary region failure.

---

# Important Considerations
- **RPO (Recovery Point Objective)**: Determines how much data might be lost during a failover. If near-zero data loss is required, choose higher redundancy options like RA-GZRS.
- **Data Accessibility**: Data in the secondary region is only accessible for read operations unless failover is manually triggered or RA-GRS/RA-GZRS is enabled.

---

# Azure Storage Services

1. **Azure Blob Storage**: Optimized for storing massive amounts of unstructured data like images, video files, and social media posts.
   - **Unstructured Data**: Data that cannot be contained in a row-column database (e.g., images, videos).
   - **Structured Data**: Data in rows and columns (e.g., Excel, MSSQL, MySQL).

2. **Azure File Storage**: Fully managed file shares in Azure accessible via SMB or NFS (Linux systems).

3. **Azure Queues**: A service for storing large numbers of messages, accessible via authenticated HTTP or HTTPS calls.

4. **Azure Disk Storage**: Azure-managed disks are block-level storage volumes used with Azure Virtual Machines.

5. **Azure Table Storage**: A service for storing structured NoSQL data in Azure, including a schemaless key/attribute store.

---

# Storage Tiers

- **Hot**: For frequently accessed data.
- **Cool**: For infrequently accessed data.
- **Cold**: For rarely accessed or modified data (minimum storage of 90 days).
- **Archive**: Offline tier for rarely accessed data (minimum storage of 180 days).

Use **lifecycle management policies** to automate tier management based on the data access patterns.

---

# Azure Services Documentation

## Private Endpoint
- Grants access to a specific instance (resource) of a PaaS service in your VNET on a private IP address.
- Enables access from on-premises without a public endpoint.

## Azure Firewall
- A managed, cloud-based network security service that protects your Azure Virtual Network Resources.
- Fully stateful firewall as a service with built-in high availability and unrestricted cloud scalability.

## Azure DDoS Protection
- **Standard tier** provides enhanced DDoS mitigation features to defend against DDoS attacks.
- Includes logging, alerting, and telemetry not included in the free basic tier.

---

## Azure Storage Services Overview
- Azure Storage Account is a cloud-based resource that provides a unique namespace for your storage data, accessible globally over HTTP or HTTPS. 
- The storage is secure, highly available, durable, and scalable.

### Storage Account Endpoints
- Every Azure Storage Account has a unique namespace ensuring data is accessible over the internet.

### Endpoint Composition
- The storage account name combined with the Azure Storage service endpoint creates the full endpoint for your storage account.

### Naming Your Storage Account
- **Length**: Storage account names must be between 3 and 24 characters long.
- **Characters Allowed**: Only lowercase letters and numbers are allowed (no uppercase letters or special characters).
- **Uniqueness**: The storage account name must be unique within Azure.

---

## Storage Tiers and Redundancy Options
Azure Storage ensures data protection through redundancy, replicating it across multiple locations for durability and high availability.

### Redundancy in the Primary Region
- **Locally Redundant Storage (LRS)**: Copies data synchronously 3 times within a single physical location.
- **Zone-Redundant Storage (ZRS)**: Copies data synchronously across 3 Azure availability zones within the primary region.

### Redundancy in the Secondary Region
- **Geo-Redundant Storage (GRS)**: Copies data synchronously 3 times within the primary region using LRS and asynchronously to a secondary region.
- **Geo-Zone-Redundant Storage (GZRS)**: Copies data synchronously 3 times within the primary region using ZRS, then asynchronously to a secondary region.

### Read Access to Data in the Secondary Region
- **RA-GRS/RA-GZRS**: Allows read access to data in the secondary region, even if the primary region is functioning.

### Choosing the Right Redundancy Option
- **Cost vs. Availability**: Higher redundancy often means higher cost but better availability.
- **Replication Needs**: Whether you need replication within the primary region (LRS, ZRS) or across regions (GRS, GZRS).
- **Disaster Recovery Requirements**: Consider if read access to data in a secondary region is necessary.

---

## Azure Storage Types
1. **Azure Blob Storage**: Optimized for storing unstructured data like images, videos, and social media posts.
2. **Azure File Storage**: Fully managed file shares accessible via SMB or NFS (Linux).
3. **Azure Queues**: A service for storing large numbers of messages accessible via authenticated HTTP/HTTPS calls.
4. **Azure Disk Storage**: Managed disks used with Azure Virtual Machines (VMs).
5. **Azure Table Storage**: A service for structured NoSQL data, including a key/attribute store.

---

## Storage Tiers
- **Archive**: Optimized for rarely accessed data, lowest storage cost but high access costs (stored for a minimum of 180 days).
- **Cold**: Optimized for infrequently accessed or modified data, lower storage costs, and higher access costs (stored for a minimum of 90 days).
- **Cool**: Optimized for data that is rarely accessed or modified, lower storage costs, and higher access costs (stored for a minimum of 30 days).
- **Hot**: Optimized for frequently accessed or modified data, highest storage costs, lowest access costs.

---

## Azure Migrate
- A service that provides simplified migration, modernization, and optimization for Azure.
- Includes pre-migration steps such as discovery, assessments, and right sizing.

### Key Migration Tools
1. **Azure Migrate: Discovery and Assessment**: Helps discover and assess on-premises servers for migration (e.g., VMware, Hyper-V).
2. **Azure Migrate: Server Migration**: Assists in migrating VMs, physical servers, and other virtualized environments to Azure.
3. **Data Migration Assistant**: A standalone tool to assess SQL Servers for migration, identifying issues and suggesting improvements.
4. **Azure Database Migration Service**: Assists in migrating SQL Servers, SQL Database, or Managed Instances to Azure.
5. **Azure App Service Migration Assistant**: A tool for assessing and migrating on-premises .NET and PHP apps to Azure App Service.
6. **Azure Data Box**: A physical device used for securely transferring large amounts of data to Azure when network bandwidth is limited.

### Azure Data Box Use Cases
- **One-time Migration**: Large-volume data transfer (e.g., media libraries).
- **Initial Bulk Transfer**: Initial large-scale transfer with subsequent incremental updates.
- **Periodic Uploads**: Regularly generated data transfer to Azure.

### Azure File Movement Options
1. **AzCopy**: A command-line tool for copying blobs or files to/from a storage account.
2. **Azure Storage Explorer**: A GUI tool for managing files and blobs in your Azure Storage account.
3. **Azure File Sync**: Centralizes file shares in Azure Files while retaining Windows server compatibility.

---

## Microsoft Entra ID (Azure Active Directory)
- Provides cloud-based authentication for Microsoft applications and custom applications, integrating with on-premises Active Directory.

### Key Features of Microsoft Entra ID
- **Authentication**: Secure sign-ins, self-service password reset, MFA, and smart lockout services.
- **Single Sign-On (SSO)**: One identity for accessing multiple applications.
- **Application Management**: Tools for managing cloud and on-premises applications.
- **Device Management**: Supports conditional access policies for trusted devices.

### Integration with On-Premises Active Directory
- Microsoft Entra ID integrates with on-premises AD via Microsoft Entra Connect for consistent access management across cloud and on-premises environments.

---

## Microsoft Entra Domain Services
- Managed domain services like domain joining, group policies, LDAP, and Kerberos/NTLM authentication for running legacy applications in the cloud.

### Key Features of Microsoft Entra Domain Services
- **Managed Domain Services**: Domain join, group policies, and traditional authentication protocols.
- **Simplified Lift-and-Shift**: Migrate legacy applications to the cloud without modifying domain access.
- **No Domain Controller Management**: Managed domain controllers with Azure.

---
## Hybrid Environments

With **Microsoft Entra Connect**, identity information from on-premises Active Directory is synchronized to Entra ID, and then Entra ID syncs it to Microsoft Entra Domain Services.

### Diagram: Microsoft Entra Connect Sync Process

- **On-premises AD to Microsoft Entra ID** via Microsoft Entra Connect (synchronization).
- **Microsoft Entra ID to Microsoft Entra Domain Services** (one-way synchronization).

Applications/services in Azure can now use domain services like domain join, LDAP, and Kerberos.

---

## Authentication Methods

1. **Single Sign-On (SSO)**  
   SSO allows users to authenticate once and access multiple applications without needing to log in again. This simplifies the authentication process by reducing the number of credentials users must manage, enhancing security by minimizing password fatigue. However, SSO relies on the initial authentication method being secure, as subsequent access is granted based on that first successful login.

2. **Multi-Factor Authentication (MFA)**  
   MFA adds an additional layer of security by requiring more than just a password to verify the user's identity. MFA combines different factors:
   - Something you know (e.g., a password or PIN)
   - Something you have (e.g., a phone or security token)
   - Something you are (e.g., a fingerprint or facial recognition)

3. **Passwordless Authentication**  
   Azure supports passwordless authentication, replacing passwords with more secure methods. This improves both security and user convenience. Three main passwordless options are:
   - **Windows Hello for Business**: Allows users to authenticate with Microsoft accounts, AD accounts, Entra ID accounts, or FIDO v2.  
     _**REPLACES PASSWORDS!**_
   - **Microsoft Authenticator App**: Users can use the Microsoft Authenticator app on mobile devices for passwordless sign-in. The app sends a notification, which users confirm with biometrics (e.g., face or fingerprint) or PIN.
   - **FIDO2 Security Keys**: Uses public-key (asymmetric) cryptography for user authentication. The user has a physical device (USB or NFC).

These authentication methods integrate seamlessly with **Microsoft Entra ID**.

---

## Collaboration Methods

1. **Business-to-Business (B2B) Collaboration**  
   Enables external users to use their preferred identity to sign into your Microsoft or other enterprise applications (SaaS apps, customer apps). Supports Entra ID and social identities.

2. **B2B Direct Connect**  
   Establish a mutual, two-way trust with another Entra organization for seamless collaboration. Useful for heavy, daily collaboration with close business partners.

3. **Azure Active Directory Business-to-Consumer (B2C)**  
   Publish modern SaaS apps or custom-developed apps to consumers and customers using Entra ID B2C for identity and access management. Supports Entra & Social Identities.

4. **Entra ID Multi-Tenant Organization**  
   Collaborates with multiple tenants in a single Entra ID organization via cross-tenant synchronization. Ideal for conglomerates, mergers, and multi-cloud departments or test/staging tenants.

---

## Security Practices

### Conditional Access

Entra ID uses signals to make decisions and enforce organizational policies.

### Azure RBAC

Provides fine-grained access management for Azure resources. It is an element of the "least privilege" principle:
- Who has access to Azure resources?
- What they can do with those resources.
- Which resources/areas they have access to.

### Zero Trust Security Model

- **Verify Explicitly**: Always authenticate and authorize based on comprehensive data points (user identity, device, location, etc.).
- **Use Least Privilege Access**: Grant users the minimum permissions necessary to complete tasks, utilizing Just-In-Time (JIT) and Just-Enough-Access (JEA) policies.
- **Assume Breach**: Segment access to minimize the blast radius.

### Defense-in-Depth

A layered security strategy that protects data and prevents unauthorized access, using multiple layers of security:

1. **Physical Security**: Protects hardware and facilities from unauthorized access.
2. **Identity and Access**: Controls access to infrastructure, often using MFA and SSO.
3. **Perimeter Security**: Protects against external network-based attacks (e.g., DDoS protection, firewalls).
4. **Network Security**: Limits communication between resources to reduce attack spread (e.g., segmentation, access controls).
5. **Compute Security**: Ensures the security of virtual machines and endpoints through malware protection, system patching, and access controls.
6. **Application Security**: Ensures applications are free from vulnerabilities and sensitive information is securely stored.
7. **Data Security**: Protects the confidentiality, integrity, and availability of data, often driven by regulatory compliance.

---

## Security Tools

1. **Network Security Group (NSG)**  
   NSGs define rules to allow or deny inbound or outbound network traffic for Azure resources. For each rule, you can specify source/destination ports and protocols. NSGs can be applied to a subnet or network adapter.

2. **Microsoft Defender for Cloud**  
   A unified infrastructure security management system that strengthens security across cloud and on-premises data centers. It provides security guidance for compute, data, network, storage, and app services, including support for both Azure and other public clouds (AWS, GCP).
