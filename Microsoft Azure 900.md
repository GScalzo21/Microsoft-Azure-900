### **Describe cloud concepts (25–30%)**

**Define cloud computing**

- *Cloud computing is the delivery of computing services over the internet*. Computing services include common IT infrastructure such as virtual machines, storage, databases, and networking. Cloud services also expand the traditional IT offerings to include things like Internet of Things (IoT), machine learning (ML), and artificial intelligence (AI).

**Describe the shared responsibility model**

- The **Shared Responsibility Model** is a **cloud security framework** that defines which responsibilities are handled by the **cloud provider** and which are handled by the **customer**.

**🔥 Cloud Provider Responsibilities**

* **Physical security** (datacenter, power, cooling).  
* **Physical network** (cables, routers, connectivity).  
* **Physical hosts** (servers and storage).

🔒 Customer Responsibilities

* **Data security** (protecting your data in the cloud).  
* **Access control** (who can access your cloud resources).  
* **Devices** (computers, phones connecting to the cloud).  
* **Accounts & identities** (managing users and permissions).✅ **Key Rule:** The more cloud-managed the service, the **less you are responsible for**

![][image1]

**Define cloud models, including public, private, and hybrid**

| Public cloud | Private cloud | Hybrid cloud |
| :---- | :---- | :---- |
| No capital expenditures to scale up | Organizations have complete control over resources and security | Provides the most flexibility |
| Applications can be quickly provisioned and deprovisioned | Data is not collocated with other organizations’ data | Organizations determine where to run their applications |
| Organizations pay only for what they use | Hardware must be purchased for startup and maintenance | Organizations control security, compliance, or legal requirements |
| Organizations don’t have complete control over resources and security | Organizations are responsible for hardware maintenance and updates |  |

Multi-Cloud \= Utilizing multiple public cloud providers 

Azure ARC

- Set of technologies that help manage your cloud environment   
  - Help manage cloud environment whether (public, private, hybrid, multi-cloud)

**Describe the consumption-based model** 

CapEx is typically a one-time, up-front expenditure to purchase or secure tangible resources. A new building, repaving the parking lot, building a datacenter, or buying a company vehicle are examples of CapEx. **(On Premise)**

OpEx is spending money on services or products over time. Renting a convention center, leasing a company vehicle, or signing up for cloud services are all examples of OpEx. (**Cloud)**

Cloud computing falls under **OpEx** because cloud computing operates on a consumption-based model. With cloud computing, you don’t pay for the physical infrastructure, the electricity, the security, or anything else associated with maintaining a datacenter. Instead, you pay for the IT resources you use. If you don’t use any IT resources this month, you don’t pay for any IT resources.

This consumption-based model has many benefits, including:

* No upfront costs.  
* No need to purchase and manage costly infrastructure that users might not use to its fullest potential.  
* The ability to pay for more resources when they're needed.  
* The ability to stop paying for resources that are no longer needed.

**Compare cloud pricing models**

Cloud computing is the delivery of computing services over the internet by using a pay-as-you-go pricing model. You typically pay only for the cloud services you use, which helps you:

* Plan and manage your operating costs.  
* Run your infrastructure more efficiently.  
* Scale as your business needs change.

To put it another way, cloud computing is a way to rent compute power and storage from someone else’s datacenter.

**Describe serverless \-** Cloud computing model that allows developers to build applications without managing infrastructure.

**Describe the benefits of high availability and scalability in the cloud**

- High availability focuses on ensuring maximum availability, regardless of disruptions  
- Scalability is the ability to adjust to resources to meet demand and to add more resources to better handle increased demand  
  - Vertical scaling is focused on increasing or decreasing the capabilities of resources  
    - *Example*: Scale up or down to add or lower CPU or RAM   
  - Horizontal scaling is adding or subtracting the number of resources  
    - *Example:* Add more additional VMS or containers, or subtract.

**Describe the benefits of reliability and predictability in the cloud**

Reliability is the ability of a system to recover from failures and continue to function. It's also one of the pillars of the Microsoft Azure Well-Architected Framework.

\-With a decentralized design, the cloud enables you to have resources deployed in regions around the world. With this global scale, even if one region has a catastrophic event other regions are still up and running

Predictability can be focused on performance predictability or cost predictability

- Performance predictability focuses on predicting the resources needed to deliver a positive experience for your customers. Autoscaling, load balancing, and high availability are just some of the cloud concepts that support performance predictability  
- Cost predictability is focused on predicting or forecasting the cost of the cloud spend.  
  - By operating in the cloud and using cloud analytics and information, you can predict future costs and adjust your resources as needed. You can even use tools like the Total Cost of Ownership (TCO) or Pricing Calculator to get an estimate of potential cloud spend.

**Describe the benefits of security and governance in the cloud**

Governance and Compliance Support

* **Predefined Templates:** Cloud services often come with set templates that help ensure deployed resources meet **corporate standards** and **government regulatory requirements**. This makes it easier to maintain compliance across the organization.

* **Automatic Updates:** As standards change, cloud platforms allow for the **automatic update** of deployed resources to meet the latest compliance standards, ensuring your infrastructure stays aligned with evolving regulations.

* **Cloud-based Auditing:** Continuous monitoring tools flag any **out-of-compliance resources**, and provide **mitigation strategies** to quickly address any issues.

  2\. Security Flexibility  
* **Customizable Security Levels:** Whether using **IaaS**, **PaaS**, or **SaaS**, you can choose a cloud solution that fits your security needs.

  * **IaaS (Infrastructure as a Service)**: Gives you **full control** over security, allowing you to manage **operating systems** and **installed software**, including patches and updates. Ideal for those who want maximum control over security.

  * **PaaS and SaaS**: Offer **automatic patches** and maintenance, reducing your security workload while still ensuring updates are applied without manual intervention.

  3\. Enhanced Network Security

* **DDoS Protection:** Cloud providers are typically equipped to handle **distributed denial of service (DDoS)** attacks. This provides an added layer of protection to your network, making it more **robust** and **secure** against malicious disruptions.


**Describe the benefits of manageability in the cloud**

Management of the Cloud \- Managing cloud resources

- Automatically scale resource deployment based on need.  
- Deploy resources based on a preconfigured template, removing the need for manual configuration.  
- Monitor the health of resources and automatically replace failing resources.  
- Receive automatic alerts based on configured metrics, so you’re aware of performance in real time.

Management in the cloud \- how you’re able to **manage** your cloud environment and resources. 

- Through a web portal.  
- Using a command line interface.   
- Using APIs  
- Using PowerShell.

**Describe cloud service types**

✅ Infrastructure as a Service (IaaS) 

**What is IaaS?**  
 IaaS is the most **flexible** cloud service model, giving you the **most control** over your resources. It’s like renting hardware from a cloud provider and managing everything else.

* **Provider Responsibilities:**  
   The cloud provider handles:

  * **Hardware maintenance** (servers, storage, etc.)

  * **Network connectivity** (to the internet)

  * **Physical security** (datacenter safety)

* **Your Responsibilities:**  
   You are in charge of:

  * **Installing and maintaining the operating system**

  * **Configuring networks**

  * **Setting up databases and storage**

  * **Managing other software configuration**

✅ Platform as a Service (PaaS) 

* **What is PaaS?**  
   PaaS is the **middle ground** between **IaaS** (renting hardware) and **SaaS** (a fully managed solution). It provides a **ready-to-use** environment for building and deploying applications without managing the underlying infrastructure.

* **Provider Responsibilities:**  
   The cloud provider handles:

  * **Physical infrastructure & security**

  * **Network connectivity**

  * **Operating systems & middleware**

  * **Development tools & databases**

  * **Licensing & patching**

* **Your Responsibilities:**  
   You focus on:

  * **Developing and managing applications**

  * **Configuring settings for your needs**

**Key Idea:** PaaS gives you a **fully managed development environment**, so you can build applications without worrying about infrastructure maintenance.

- Development framework: PaaS provides a framework that developers can build upon to develop or customize cloud-based applications. Similar to the way you create an Excel macro, PaaS lets developers create applications using built-in software components. Cloud features such as scalability, high-availability, and multi-tenant capability are included, reducing the amount of coding that developers must do.


✅Software as a Service (SaaS) 

* **What is SaaS?**  
   SaaS is the **most complete** cloud service model. It has **fully developed applications** you rent or use directly, like email, financial software, messaging apps, connectivity tools.  
* **Provider Responsibilities:**  
   The cloud provider handles **everything**:

  * **Application management**

  * **Maintenance**

  * **Updates**

  * **Security**

* **Your Responsibilities:**  
   You simply use the application, with **no infrastructure management** required.

**Key Idea:** SaaS is the **easiest** model to implement since everything is already built and managed for you, requiring little to no technical expertise.

### 

### 

### 

### 

### 

### 

### 

### **Describe Azure management and governance (30–35%)**

**Describe factors that can affect costs in Azure**

OpEx cost can be impacted by many factors. Some of the impacting factors are:

* **Resource Type** – Every Azure resource is **metered**, tracking usage to calculate billing.

* **Consumption** – Pay for what you use, allowing **cost savings for consistent workloads** and flexibility to scale when needed.

* **Maintenance** – Regularly review resources to **eliminate unnecessary costs** from unused resources.

* **Geography** – Costs vary by region due to differences in **power, labor, taxes, and fees**.

* **Subscription Type** – Different Azure subscriptions offer **usage allowances** that impact pricing.  
* **Azure Marketplace** – When buying solutions from third-party vendors, costs may include both **Azure services and vendor fees**.

**Compare the pricing calculator and the Total Cost of Ownership (TCO) Calculator**

**Pricing Calculator** helps estimate the cost of provisioning Azure resources.

* Used to calculate expenses for **compute, storage, networking**, and more.

* Allows customization for **storage type, access tier, and redundancy**.

* Ideal for planning **Azure spending** before deployment.

**TCO (Total Cost of Ownership) Calculator**

* Helps compare **on-premises vs. Azure Cloud** costs.

* Requires input on **servers, databases, storage, and network traffic** from your current setup.

* Factors in **power, IT labor, and maintenance costs**.

* Provides an estimate of **cost savings** when moving to Azure.

* Useful for businesses considering **cloud migration** and long-term cost efficiency.

**Describe cost management capabilities in Azure**

### **Cost Management in Azure**

* **Monitors and controls Azure resource costs.**

* **Creates alerts** based on spending limits.

* **Allows budgeting** to automate resource management.

#### **Cost Analysis (a subset/dropdown of Cost Management):**

* Provides **visual insights** into Azure costs.

* Filters costs by **billing cycle, region, and resource**.

* Helps **track spending trends** over time.

* Useful for **forecasting monthly, quarterly, and yearly costs**.

### **Cost Alerts in Azure**

Cost alerts help monitor **spending and budgets** in Azure. There are three types:

1️⃣ **Budget Alerts** – Notify when spending **reaches or exceeds** a set budget based on usage or cost.

2️⃣ **Credit Alerts** – Trigger when **Azure credit (for Enterprise Agreements)** is 90% or 100% consumed.

3️⃣ **Department Spending Quota Alerts** – Warn when a **department reaches a preset spending limit**.

**Describe the purpose of tags**

* Tags help **organize, manage, and optimize** cloud resources by adding metadata. They provide valuable insights and improve **cost tracking, security, and compliance**.  
* **Resource Management** – Easily locate and manage resources by workload, environment, or owner.  
* **Cost Management** – Group resources for **cost reporting, budget tracking, and forecasting**  
*  **Operations Management** – Classify resources by **business-critical importance** to define SLAs  
*  **Security** – Label resources based on **sensitivity levels** (e.g., Public, Confidential).  
* **Governance & Compliance** – Identify resources aligned with **regulatory requirements** (e.g., ISO 27001).  
* **Automation & Optimization** – Tag resources for **efficient workload management and automation**.

💡 Tags enhance visibility, streamline management, and improve cloud governance\! 🚀

**How to manage resource Tags**

You can add, modify, or delete resource tags through Windows PowerShell, the Azure CLI, Azure Resource Manager templates, the REST API, or the Azure portal.

You can use Azure Policy to enforce tagging rules and conventions

#### **Describe features and tools in Azure for governance and compliance**

**Describe the purpose of Microsoft Purview in Azure**

### **Microsoft Purview: Data Governance & Compliance**

**Microsoft Purview** is a comprehensive solution for **data governance, risk management, and compliance**. It provides a **unified view** of data across **on-premises, multicloud, and SaaS environments**, ensuring security and compliance.

### **Risk & Compliance Solutions**

Microsoft Purview integrates with **Microsoft 365 services** like **Teams, OneDrive, and Exchange** to:

* **Protect sensitive data** across clouds, apps, and devices.

* **Identify risks** and manage **regulatory compliance** needs.

* **Simplify compliance** with built-in regulatory tools.

### **Unified Data Governance**

Microsoft Purview enables seamless **data management and security** across **Azure, SQL, Hive, Amazon S3, and on-premises** environments. It helps:

* **Map your entire data estate** with classification and lineage tracking.

* **Identify sensitive data** across your organization.

* **Provide secure data access** while ensuring compliance.

* **Generate insights** on data storage and usage patterns.

* **Manage access at scale** to enhance security.

**Describe the purpose of Azure Policy**

**Azure Policy** is a service that helps you define and manage rules (policies) to control and monitor your resources in Azure. It ensures that your resources comply with specific standards and requirements.

### **Key Functions of Azure Policy:**

* **Create and Assign Policies**: You can define individual policies (e.g., ensuring only certain VM sizes are used) or group them into **initiatives** (sets of related policies).

* **Compliance Monitoring**: Azure Policy evaluates your resources to check if they meet the defined policies. If a resource is non-compliant, Azure Policy will highlight it and can even prevent non-compliant resources from being created.

* **Scope**: Policies can be applied at different levels such as resource groups, subscriptions, or individual resources. These policies are inherited, meaning policies set at a higher level (like a subscription) apply to all resources under it (like resources in a resource group).

* **Built-In Policies**: Azure comes with built-in policies for common areas like storage, networking, compute, security, and monitoring.

* **Automatic Remediation**: In some cases, Azure Policy can automatically fix non-compliant resources. For instance, if resources are missing a required tag, the policy can automatically apply it.

* **Exceptions**: If you don’t want a policy to automatically fix a particular resource, you can flag it as an exception.

* **Integration with Azure DevOps**: Azure Policy can also be integrated with Azure DevOps to ensure policies are applied during the pre- and post-deployment phases.

### **Azure Policy Initiatives:**

An **initiative** is a collection of related policies grouped together. Initiatives allow you to manage policies at a larger scale. For example, the **"Enable Monitoring in Azure Security Center"** initiative groups policies that ensure all resources are properly monitored for security issues.

Initiatives contain multiple policy definitions, such as:

* **Monitor unencrypted SQL databases**.

* **Monitor for OS vulnerabilities**.

* **Monitor for missing endpoint protection**.

Initiatives help track compliance for a broader goal and ensure consistent security and monitoring across all resources in your Azure environment.

**Describe the purpose of resource locks**

**Resource Locks** in Azure are designed to prevent critical resources from being accidentally deleted or modified, even if users have the appropriate permissions through Azure role-based access control (RBAC). By using resource locks, you can ensure that important resources are protected from accidental or unauthorized changes.

### **Purpose of Resource Locks:**

* **Protection from accidental changes:** Resource locks help safeguard your resources from being deleted or updated, reducing the risk of accidental or unauthorized modifications.

* **Applied at multiple levels:** Resource locks can be applied to individual resources, resource groups, or entire subscriptions. If you apply a lock to a resource group, all resources within that group will inherit the lock.

### **Types of Resource Locks:**

1. **Delete Lock:**

   * Prevents users from deleting the resource but still allows them to read or modify it.

   * Useful when you want to avoid accidental deletion of a resource but still need flexibility for modification.

2. **ReadOnly Lock:**

   * Prevents users from modifying or deleting the resource but allows them to read the resource.

   * Similar to restricting users to only have permissions granted by the "Reader" role.

### **Managing Resource Locks:**

* **Managing Locks:**

  * Resource locks can be managed via the Azure portal, PowerShell, Azure CLI, or Azure Resource Manager templates.

  * To manage locks in the Azure portal, navigate to the Settings section of the resource's settings pane.

* **Modifying or Deleting a Locked Resource:**

  * If you need to make changes to a locked resource, you must first remove the lock.

  * After removing the lock, you can perform the action, provided you have the required permissions.

  * Resource locks override RBAC permissions, meaning even if you're an owner of a resource, you need to remove the lock before making changes.

By using resource locks, you can ensure critical resources are protected, reducing the risk of errors in managing cloud infrastructure.

**The Microsoft Service Trust Portal** is a portal that provides access to various content, tools, and other resources about Microsoft security, privacy, and compliance practices.

#### **Describe features and tools for managing and deploying Azure resources**

**Describe the Azure portal**

The **Azure portal** is a **web-based, unified console** that provides a **graphical interface** for managing your **Azure subscription** and resources. It offers an alternative to command-line tools, making it easier to manage cloud services without requiring scripting or coding.

* **Manage and Monitor**: Enables you to build, configure, and monitor anything from simple applications to large-scale cloud deployments.

* **Custom Dashboards**: Allows you to create personalized views of your resources for easier management.

* **Accessibility Options**: Includes settings to optimize the user experience based on individual needs.

**Describe Azure Cloud Shell, including Azure Command-Line Interface (CLI) and Azure PowerShell**

**Azure Cloud Shell** is a browser-based command-line tool that allows you to manage Azure resources using either **Azure PowerShell** or the **Azure Command-Line Interface (CLI)**.

* **No installation required**: Access it directly from the Azure portal.

* **Supports Azure PowerShell & Azure CLI**: Choose between PowerShell (cmdlets) or CLI (Bash-based commands).

* **Authenticated session**: Automatically connects with your Azure credentials when logged in.

**Azure PowerShell** is a command-line tool designed for developers, IT professionals, and DevOps engineers to automate Azure tasks using **PowerShell cmdlets**.

#### **Key Features of Azure PowerShell:**

* Uses **cmdlets** that interact with the **Azure REST API** to perform tasks.

* Can be used for **one-off resource management** or **complex orchestration** (e.g., deploying multiple resources).

* Supports scripting for **repeatable automation**.

* Available on **Windows, Linux, and macOS**.

**Azure CLI** (Command-Line Interface) is an alternative to Azure PowerShell, using **Bash commands** instead of PowerShell cmdlets.

* Functionally similar to Azure PowerShell but uses **Bash syntax**.

* Used for both **individual commands** and **complex automation**.

* Available on **Windows, Linux, and macOS**, and can be accessed via **Azure Cloud Shell**.

**Describe the purpose of Azure Arc**

**Azure Arc** is a service that extends **Azure’s compliance, governance, and monitoring** to **hybrid** and **multi-cloud** environments. It enables organizations to **manage non-Azure resources** using **Azure Resource Manager (ARM)**, offering a **unified, centralized** approach to managing IT infrastructure across **on-premises, multiple clouds, and edge locations**.

1. **Unified Management** – Manage on-premises and multi-cloud resources as if they were in Azure.

2. **Consistent Governance** – Apply **Azure Policy**, **RBAC (Role-Based Access Control)**, and **security compliance** across all environments.

3. **Hybrid Cloud Flexibility** – Run **Azure services** anywhere, even outside of Azure.

4. **DevOps & Automation** – Support both **traditional IT operations (ITOps)** and **DevOps practices**  
5. **Custom Locations** – Manage **Kubernetes clusters** and **extensions** in non-Azure environments.

### **What Can Azure Arc Manage Outside of Azure?**

Azure Arc currently supports managing the following resources hosted **outside of Azure**:

* **Servers** (physical and virtual)

* **Kubernetes clusters**

* **Azure Data Services**

* **SQL Server**

* **Virtual Machines** (Preview)

**Describe infrastructure as code (IaC)**

Infrastructure as Code (IaC) means managing your IT setup using code instead of manual processes.

* **Basic Level**: Use tools like Azure Cloud Shell, PowerShell, or the Azure CLI to configure resources.

* **Advanced Level**: Automate entire deployments with templates that ensure consistency and repeatability.

* **Examples in Azure**: ARM Templates (JSON-based) and Bicep (simpler code) help manage infrastructure efficiently.

IaC makes setting up and maintaining cloud resources faster, more reliable, and easier to scale.

**Describe Azure Resource Manager (ARM) and ARM templates**

#### **Azure Resource Manager (ARM)**

Azure Resource Manager (ARM) is the **centralized management layer** for Azure. It **deploys, manages, and organizes** all Azure resources. Anytime you interact with Azure—whether through the portal, CLI, PowerShell, or APIs—ARM handles the request.

#### **Key Benefits of ARM:**

* **Consistent Management:** All Azure tools interact with resources via ARM, ensuring uniform behavior.

* **Group Resource Management:** Resources can be managed as a single unit, making deployment easier.

* **Role-Based Access Control (RBAC):** Security and access are built-in, so permissions can be assigned to users or groups.

* **Cost & Organization Tools:** Tags and resource groups help categorize resources for better billing and tracking.

#### **ARM Templates**

ARM templates are **JSON-based declarative files** that define Azure infrastructure. They describe **what** resources should be deployed without requiring step-by-step commands.

##### **Benefits of ARM Templates:**

* **Simple Syntax** – Define the desired state; Azure does the rest.  
* **Repeatability** – Deploy identical environments consistently.  
  **Orchestration** – Handles dependencies automatically, deploying resources in the correct order.  
* **Modular & Extensible** – Use linked templates, nested templates, and even integrate PowerShell or Bash scripts.

#### **Bicep: The Easier Alternative to ARM Templates**

Bicep is a **simpler, more readable** language than JSON-based ARM templates. It still uses ARM for deployments but makes writing and managing templates easier.

🔹 **ARM Template:** Written in **JSON**  
 🔹 **Bicep:** Uses a **simplified syntax**, making it easier to write and read.

In short, **ARM manages resources, ARM templates automate deployments, and Bicep simplifies the process further.** 🚀

#### **Describe monitoring tools in Azure**

**Describe the purpose of Azure Advisor**

Azure Advisor is a personalized cloud consultant that evaluates your Azure resources and provides recommendations to enhance reliability, security, performance, operational efficiency, and cost savings.

* Automated Recommendations: Scans your resources and suggests improvements.

* Personalized Insights: Tailors recommendations based on your subscriptions and usage.

* Actionable Guidance: Provides step-by-step instructions to implement improvements.

* Filtering Options: Allows you to focus on specific subscriptions, resource groups, or services.

### **Five Categories of Azure Advisor Recommendations:**

1. Reliability (High Availability): Ensures continuity of critical applications.

2. Security: Detects threats and vulnerabilities to prevent security breaches.

3. Performance: Enhances the speed and responsiveness of applications.

4. Operational Excellence: Improves workflow efficiency and best practices.

5. Cost Optimization: Identifies ways to reduce spending and improve efficiency.

By following Azure Advisor’s recommendations, you can optimize your cloud environment, improve security, and reduce costs.

**Describe Azure Service Health**

### **Azure Service Health: Monitoring Your Cloud Environment**

Microsoft Azure provides a global cloud solution to help manage infrastructure, engage customers, and adapt quickly. Monitoring the status of Azure services and your deployed resources is essential. Azure Service Health helps by offering insights into both the global Azure infrastructure and your specific resources through three key components:

#### **1\. Azure Status**

* Provides a global overview of Azure service health.

* Displays outages and service disruptions across all Azure regions.

* Accessible via the Azure Status page for real-time updates on widespread incidents.

#### **2\. Service Health**

* Focuses on the Azure services and regions relevant to your deployment.

* Informs about outages, planned maintenance, and health advisories.

* Allows you to set up alerts for service issues affecting your resources.

#### **3\. Resource Health**

* Offers a tailored view of your specific Azure resources, such as virtual machines.

* Helps identify availability issues with individual cloud services.

* Works alongside Azure Monitor to provide alerts on resource health changes.

**Describe Azure Monitor, including Log Analytics, Azure Monitor alerts, and Application Insights**

### **Azure Monitor: Comprehensive Cloud Monitoring**

Azure Monitor is a powerful platform for collecting, analyzing, visualizing, and acting on data from Azure, on-premises, and multi-cloud environments. It helps ensure the performance, availability, and security of your resources through several key components.

#### **1\. Azure Log Analytics**

* A tool in the Azure portal for writing and running log queries on data collected by Azure Monitor.

* Supports both simple queries (sorting, filtering, and analyzing records) and advanced statistical analysis.

* Provides visualization options such as charts to identify trends.

* Integrates with other Azure Monitor features, such as log query alerts and workbooks.

#### **2\. Azure Monitor Alerts**

* Automated notifications triggered when a defined threshold is crossed.

* Can monitor logs for specific events or metrics (e.g., alerting when CPU usage exceeds 80%).

* Offers real-time metric-based alerts and complex log-based alerting.

* Uses **action groups** to determine who to notify and what actions to take.

* Integrated with **Azure Monitor, Service Health, and Azure Advisor** for unified alerting.

#### **3\. Application Insights**

* A feature of Azure Monitor for monitoring web applications across Azure, on-premises, or other cloud environments.

* Can be configured via an SDK or **Application Insights agent** (supports C\#.NET, VB.NET, Java, JavaScript, Node.js, and Python).

* Monitors:

  * **Request rates, response times, and failure rates**

  * **External dependencies and their impact on performance**

  * **User behavior, page views, and load times**

  * **AJAX calls, performance counters, and network usage**

  * **Synthetic transactions** to simulate user requests during low-traffic periods

### 

### **Describe Azure architecture and services (35–40%)**

### **1\. Azure Datacenters**

Azure’s **datacenters** are physical buildings that contain thousands of servers and other hardware to provide cloud computing services

* **Dedicated power, cooling, and networking** for optimal performance.

* **Security measures** to protect physical and digital assets.

* **High-speed fiber-optic connections** for fast, low-latency communication.

Datacenters are not directly accessible; instead, they are grouped into **Regions** and **Availability Zones** to enhance resiliency.

### **2\. Azure Regions**

A **Set of datacenters** deployed within a latency-defined perimeter and connected through a dedicated regional low-latency network. 

* Azure **balances and assigns resources** within each region.

* Regions are **spread across the globe** to provide redundancy and compliance with data residency laws.

### **3\. Azure Availability Zones**

Availability Zones are **physically separate datacenters** within an Azure region. They ensure fault tolerance by providing:

* **Independent power, cooling, and networking** to prevent a single point of failure.

* **High-speed private fiber-optic connections** between zones for fast data transfer.

* **Compromised of one or more datacenters**  
* **At least three separate zones** in every availability zone-enabled region.

### **4\. Azure Region Pairs (300+ miles, chosen by Microsoft) \*\***

Relationship between 2 Azure Regions within the same geographic region for disaster recovery purposes.

**Examples of Azure Region Pairs:**

* **West US ↔ East US**

* **Southeast Asia ↔ East Asia**

Some **one-directional region pairs** exist, where one region backs up another but not vice versa (e.g., Brazil South is backed up by South Central US but does not back it up in return).

### **5\. Sovereign Regions**

Sovereign regions are **isolated from the global Azure infrastructure** for compliance and or legal purposes.  **Operated by special “Trustees”** 

* **US Government Regions** (US DoD Central, US Gov Virginia, US Gov Iowa):

  * Designed for **U.S. government agencies** with strict security requirements.

* **China Regions** (China East, China North):

  * Operated through **a unique partnership with 21Vianet** instead of Microsoft directly.

**Core Architecture Components**

#### **1\. Azure Management Groups** provide a hierarchical structure to manage **access, policies, and compliance** across subscriptions. Each directory is given a single top-level management group called “**Root”**

- Can be used to aggregate policy and initiative assignments Via Azure Policy  
- Can contain **multiple subscriptions**  
- All new subscriptions will be placed under a root management group by default.

- #### **Role-Based Access Control (RBAC)** at the **management group level**, which automatically applies to all nested subscriptions, resource groups, and resources.

### **Important Facts about Management Groups:**

* #### **10,000 management groups** can be supported within a single Azure directory. 

* #### A **management group tree** can have up to **six levels** of depth. 

* #### **Each management group and subscription** can only have **one parent**.

**2\. Azure Subscriptions**

#### An **Azure subscription** is a **unit of management, billing, and scale** that links to an Azure **account**. 

- #### Serves as a management boundary for assigning Azure policies, governance, and isolation

**Types of Azure Subscription Boundaries:**

* #### **Billing Boundary:**    Determines how Azure services are billed. Each subscription generates its own **separate billing report and invoice**. Multiple subscriptions can be used for different billing needs. 

* #### **Access Control Boundary:**    Azure applies **access-management policies** at the subscription level, meaning you can configure permissions and manage access for users in specific departments or teams within the organization.

**3\. Resource Groups**  
A container that holds related resources for an Azure solution with a common lifecycle

- Used to group resources that share the a common resource lifecycle (VM, network adapter)

**4\. Resources (contained in 1 resource group)**  
An entity managed by Azure, like a VM, virtual network, or storage account

#### Azure's hierarchy consists of **management groups** → **subscriptions** → **resource groups** → **resources**.

**Compare compute types, including containers, virtual machines, and functions**

### **1\. Azure Virtual Machines**  

- Server virtualization (compute) on-demand without need for hardware purchase

Virtual machine scale sets \- Allow you to create and manage a groups of identical, load balanced VMS. Number of VM instances can **automatically** increase or decrease in response to demand or based on a schedule.

- Focus \= Scale (Scalability, capacity) 

Virtual Machine availability sets \- Help build a more resilient, highly available environment by ensuring varied power and network connectivity.

- Focus \= resiliency (availability  
  - **Update Domains** \- allows you to apply updates while knowing that only one update domain grouping will be offline at a time  
  - **Fault Domains \-** groups your vms by common power source and network switch  
    - By default, an availability set will split your VM’s across up to three fault domains

### **2\. Containers – Lightweight, Faster Deployment**

A **container** is like a **mini VM**, but without a full OS. Instead, it runs just the app and the necessary dependencies, making it much **faster** and **more efficient** than a VM.

- Containers are a lightweight way to run apps without needing to manage an entire operating system.

### **3\. Serverless Functions – Fully Managed, Only Pay for What You Use**

A **function** is a small piece of code that runs **only when needed**—no need to manage servers at all\! Azure **automatically scales** and runs your function **only when triggered**.

**4\. Azure Functions** – Run code based on events (HTTP requests, timers, messages).

**Stateful vs. Stateless Functions:**

- **Stateless:** Runs as if it’s a fresh instance every time.  
- **Stateful (Durable Functions):** Tracks history and maintains state.

###  **Azure Virtual Desktop (AVD) \-**  is a **cloud-based Windows desktop experience** that allows users to securely access their apps and files **from anywhere**.

- Desktop and app virtualization service that runs in Microsoft Azure  
- Provides a **fully managed virtual desktop infrastructure (VDI)**.  
- Supports **multi-session Windows 11/10** (many users on a single VM)  
- 

#### **Azure Container Instances (ACI) \-** Runs Docker containers on-demand in a managed, serverless Azure environment 

- A solution for any scenario that can operatie in isolated containers, without orchestration   
- 

#### **Azure Kubernetes Service (AKS) \-** A hosted Kubernetes service, where Azure handles critical tasks like health monitoring and maintenance for you.

- You pay only for agent nodes within your clusters, not for the masters (free tier)  
- For a financially backed SLA, you pay a few cents per hour for cluster management

#### **Core Services In Azure** 

#### **Azure Virtual Networks (VNet) \-** A **Logical representation** of your network in Azure 

- Contains one or more SUBNETS  
- VNETS provide **logical isolation** in Azure dedicated to your subscription 

  - #### Create a dedicated private **cloud-only network**

  - Security extend your data center (Site-to-Site VPN)  
  - Enable hybrid cloud scenarios   
    - \*\* VMs in different VNETS **cannot** communicate by default\!\! 

#### **2\. Azure Virtual Subnets \-** Segment a VNet into smaller networks to organize and manage resources.

- #### Allows Azure resource deployment into a specific subnet

- #### Can affect outbound access and routing traffic between resources

  - #### VMs in different subnets within a VNET **can** communicate by default\! 

#### **3\. Virtual Network Peering \-** Enables seamless connections of two or more virtual networks in Azure

- The two networks function as one in terms of connectivity  
- REMEMBER \- resources different VNETS cannot communicate by default

#### **4\. Azure DNS \-** Cloud hosting service for DNS domains that provides name resolution by using Microsoft Azure infrastructure. (Uses Azure’s global infrastructure) 

- Can provide internal and external DNS \*\* exam question

### **Important Consideration:**

* **Domain Registration**: Azure DNS does not offer domain name registration. To register a domain, you can use Azure App Service Domains or a third-party registrar. Once registered, you can manage the domain’s DNS records within Azure DNS.

#### **5\. Azure VPN Gateway** \-  is a virtual network gateway that sends encrypted traffic between an Azure VNET and an on premises location over the internet

- Core component of a hybrid cloud  
- site \-to-site VPN traffic traverses the internet 

#### **6\. Azure ExpressRoute \-** Extends your on-premises networks into Azure over a private connection with the help of a connectivity provider (**Traffic does NOT traverse the internet)** 

**Service Endpoint \-** Provides a way to lock down access to **all instances** of a PaaS service to a Vnet. 

- Accessible from public internet

**Private Endpoint** \- grants access to a specific instance (resource) of a PaaS service in your VNET on a private IP address

- Enables access from on-premise without a public endpoint.

**Azure Firewall**  \- A managed, Cloud-based network security service that protects your Azure Virtual Network Resources

- Its a fully stateful firewall as a service with built-in high **availability** and unrestricted cloud **scalability**

**Azure DDoS \-** Standard tier provides enhanced DDoS mitigation features to defend against DDoS attacks

- Includes logging, alerting, and telemetry not included in the free basic tier present by default 

#### **Describe Azure storage services**

**Compare Azure Storage services**

**Azure Storage Account** is a cloud-based resource that provides a unique namespace for your storage data, accessible globally over HTTP or HTTPS. The storage within this account is secure, highly available, durable, and scalable.

#### **Storage Account Endpoints**

* Every **Azure Storage Account** has a unique namespace that ensures your data is accessible over the internet.

* **Endpoint Composition**: The **storage account name** combined with the **Azure Storage service endpoint** creates the full endpoint for your storage account.

#### **Naming Your Storage Account**

When creating a storage account, you need to adhere to these **naming rules**:

* **Length**: Storage account names must be between **3 and 24 characters** long.

* **Characters Allowed**: Only **lowercase letters** and **numbers** are allowed. No uppercase letters or special characters.

* **Uniqueness**: The storage account name must be **unique** within Azure, as no two storage accounts can have the same name. This ensures a distinct, globally accessible namespace.  
* Describe storage tiers

**Describe redundancy options**

Azure Storage ensures your data is protected through redundancy by replicating it across multiple locations. This ensures durability and high availability, even during unexpected or planned events such as hardware failures, power outages, or natural disasters. The choice of redundancy impacts both **cost** and **availability**, depending on how your data is replicated and your application's needs.

### **Redundancy in the Primary Region**

Azure provides different replication options within the **primary region** for ensuring data durability and availability:

#### **1\. Locally Redundant Storage (LRS)** \- Copies your data synchronously 3x within a single physical location in the primary region

#### **2\. Zone-Redundant Storage (ZRS) \-**  Copies your data synchronously across 3x Azure availability zones in the primary region. 

#### **Redundancy in the Secondary Region**

####  (GRZ / GZRS \- Redundancy extended to secondary region)

#### **1\. Geo-Redundant Storage (GRS) \-**  Copies your data synchronously 3x within a single physical location in the primary region using LRS

- It then copies it asynchronously to a single physical location in the secondary region. (3 copies using LRS)

#### **2\. Geo-Zone-Redundant Storage (GZRS)**\- Copies your data synchronously 3x within the primary region using ZRS.

- It then copies it asynchronously to a single physical location in the secondary region  
- 

#### **Read Access to Data in the Secondary Region**

* **Read-Access Geo-Redundant Storage (RA-GRS)** or **Read-Access Geo-Zone-Redundant Storage (RA-GZRS)** allows for read access to the data in the secondary region, even if the primary region is functioning.

* **Caution**: The data in the secondary region may be slightly out-of-date due to the **RPO** (Recovery Point Objective).


### **Choosing the Right Redundancy Option**

When selecting the appropriate redundancy option, consider:

1. **Cost vs. Availability**: Higher redundancy often means higher cost, but it provides better availability and durability.

2. **Replication Needs**: Whether you need replication only within the primary region (LRS, ZRS) or across regions (GRS, GZRS).

3. **Disaster Recovery Requirements**: How important is it to have immediate read access to data in a secondary region in case of primary region failure?

### **Important Considerations**

* **RPO** (Recovery Point Objective) determines how much data might be lost during a failover, so if your application requires near-zero data loss, you should choose higher redundancy options like **RA-GZRS**.

* Data in the secondary region is only accessible for read operations unless failover is manually triggered or **RA-GRS**/**RA-GZRS** is enabled.

### **1\. Azure Blob Storage \-** Storage optimized for storing massive amounts of **unstructured data**

- **Unstructured**: Data Cannot be contained in a row-column database (no associated data model)   
  - Images, video files, social media posts  
- **Structured**: Data contained in rows and columns   
  - Excel, MSSQL, MySQL

### **2\. Azure File Storage \-**  Fully managed file shares in Azure accessible via SMB or NFS (linux)

### **3\. Azure Queues** A service for storing large numbers of messages, accessible from anywhere via authenticated HTTP or HTTPs calls 

### **4\. Azure Disk Storage** \- Azure managed disks are block-level storage volumes that are managed by Azure and **used with Azure VMs**

### **5\. Azure Table Storage \-** A service that stores structured NoSQL data in Azure, including schemaless key/attribute store

### **Storage Tiers \-**  Azure storage hot, cool, cold and archive access tiers to store blob object data in a cost effective manner.  Use lifecycle management policies to automate tiers 

- Archive is an offline tier optimized for storing data that is rarely accessed (lowest storage cost but high access costs (Stored for minimum 180 days)   
- Cold is an online tier optimized for storing data that is rarely accessed or modified (lower storage costs and higher access costs compared to cool)  (minimum of 90 days)  
- Cool is infrequently accessed or modified (lower storage costs and higher access costs) (stored minimum of 30 days)  
- Hot is optimized for storing data that is accessed or modified frequently (highest storage costs, lowest access costs)

.

### **Azure Migrate \-** A Service that provides a simplified migration modernization and optimization for azure

- Includes all pre-migration steps such as discovery, assessments, and right sizing 

### **Integrated Migration Tools**

Azure Migrate offers several key tools to help with migration:

* **Azure Migrate: Discovery and Assessment**: Helps discover and assess on-premises servers for migration, including VMware, Hyper-V, and physical servers.

* **Azure Migrate: Server Migration**: Assists in migrating VMware and Hyper-V VMs, physical servers, and other virtualized environments to Azure.

* **Data Migration Assistant**: A standalone tool to assess SQL Servers for migration, identifying potential issues and suggesting improvements.

* **Azure Database Migration Service**: Assists in migrating on-premises databases (SQL Server, Azure SQL Database, or SQL Managed Instances) to Azure.

* **Azure App Service Migration Assistant**: A tool for assessing and migrating on-premises .NET and PHP web apps to Azure App Service.

* **Azure Data Box**: A physical device used for securely transferring large amounts of data to Azure when network bandwidth is limited.

### **Azure Data Box**

Azure Data Box is a physical data migration service, providing a fast, secure, and cost-effective method to transfer large volumes of data. You receive a Data Box device with up to 80 TB of storage, which is then shipped to your data center for data upload or export.

* **Use Cases**:

  * **One-time Migration**: Moving a large volume of data to Azure (e.g., media libraries or historical data for analysis).

  * **Initial Bulk Transfer**: Initial large-scale data transfer with subsequent incremental updates via network.

  * **Periodic Uploads**: Transferring regularly generated data to Azure.

* **Export Use Cases**:

  * **Disaster Recovery**: Restoring a copy of data from Azure to on-premises infrastructure.

  * **Security Requirements**: Exporting data from Azure due to government or compliance mandates.

  * **Migration to Another Cloud**: Moving data from Azure to another cloud or on-premises.

### **Azure File Movement Options**

Several tools help transfer individual files or small groups of files to Azure:

1. **AzCopy**: A **command-line tool** that you can use **copy blobs or files** to or from your storage account   
2. **Azure Storage Explorer**: A standalone app that provides a **graphical interface GUI** to manage files and blobs in your Azure Storage account  
   1. Supports file and blob upload, download, or move between accounts  
3. **Azure File Sync**: A tool that lets you centralize your files shares in Azure Files and keep the flexibility, performance, and compatibility of a windows file server.   
   1. Once installed on a local windows servers, it will **automatically stay bi-directionally synced** with your files in Azure

### **Azure Directory Services**

**Microsoft Entra ID** is Azure's identity and access management service, which provides cloud-based authentication for both Microsoft applications and custom applications. It integrates with on-premises Active Directory, offering a scalable, secure, and globally available identity platform.

#### **Key Features of Microsoft Entra ID:**

* **Authentication**: Ensures secure sign-ins and allows functionalities like self-service password reset, multi-factor authentication (MFA), and smart lockout services.

* **Single Sign-On (SSO)**: Users can access multiple applications using one identity, simplifying user management and improving security.

* **Application Management**: Provides tools for managing cloud and on-premises applications, such as Application Proxy and SaaS apps, improving the user experience.

* **Device Management**: Supports device registration, allowing conditional access policies that only allow access from known, trusted devices.

#### **Microsoft Entra ID Use Cases:**

* **IT Administrators**: Control access based on business needs.

* **App Developers**: Leverage Entra ID for adding authentication features (e.g., SSO) to custom apps.

* **End Users**: Manage their identities and actions like password resets.

* **Service Subscribers**: Organizations using services like Microsoft 365 or Azure use Microsoft Entra ID to authenticate users.

#### **Integration with On-Premises Active Directory:**

* You can integrate **Microsoft Entra ID** with an on-premises **Active Directory** using **Microsoft Entra Connect**. This allows synchronization of user identities, enabling consistent access management across cloud and on-premises environments.

**Microsoft Entra Domain Services** offers managed domain services like domain joining, group policies, LDAP, and Kerberos/NTLM authentication, allowing you to run legacy applications in the cloud that need traditional directory services without managing domain controllers.

#### **Key Features of Microsoft Entra Domain Services:**

* **Managed Domain Services**: Includes domain join, group policies, and traditional authentication protocols (Kerberos/NTLM).

* **Simplified Lift-and-Shift**: Migrate legacy applications from on-premises environments to the cloud without requiring changes to how the application accesses domain services.

* **No Domain Controller Management**: Microsoft Entra Domain Services manages the domain controllers in Azure, including handling backups, updates, and encryption at rest.

#### **Synchronization with Entra ID:**

* **One-way Synchronization**: User and group data is synchronized from **Microsoft Entra ID** to **Microsoft Entra Domain Services**, but changes made in the managed domain are not synced back to Entra ID.

* **Hybrid Environments**: With **Microsoft Entra Connect**, identity information from on-premises Active Directory is synchronized to Entra ID, and then Entra ID syncs it to Microsoft Entra Domain Services.

**Diagram: Microsoft Entra Connect Sync Process**

1. **On-premises AD** to **Microsoft Entra ID** via **Microsoft Entra Connect** (synchronization).

2. **Microsoft Entra ID** to **Microsoft Entra Domain Services** (one-way synchronization).

3. Applications/services in Azure can now use **domain services** like **domain join**, **LDAP**, and **Kerberos**.

### **1\. Single Sign-On (SSO)**

Single Sign-On (SSO) allows users to authenticate once and access multiple applications without needing to log in again. This simplifies the authentication process by reducing the number of credentials users must manage, which also enhances security by minimizing password fatigue. However, SSO relies on the initial authentication method being secure, as subsequent access is granted based on that first successful login.

### **2\. Multi Factor Authentication (MFA)**

Multi Factor Authentication adds an additional layer of security by requiring more than just a password to verify the user's identity. MFA combines different factors:

* **Something you know** (e.g., a password or PIN)

* **Something you have** (e.g., a phone or security token)

* **Something you are** (e.g., a fingerprint or facial recognition)

### **3\. Passwordless Authentication**

Azure also supports passwordless authentication, where passwords are replaced with more secure methods. This improves both security and user convenience. There are three main passwordless options:

* **Windows Hello for Business**: Allows users to authentication with Microsoft account, AD account, Entra ID account, Identity provider services, or FIDO v2.  
  * REPLACES PASSWORDS\! \-  \-  \- PASSWORDLESS  
* **Microsoft Authenticator App**: Users can use the Microsoft Authenticator app on their mobile devices for passwordless sign-in. The app sends a notification to the user’s phone, which they confirm using their biometrics (e.g., face or fingerprint) or PIN. This method works across platforms and browsers.

* **FIDO2 Security Keys** \-  Uses public-key (asymmetric) cryptography for user authentication  
* \- user has a physical device (USB or NFC)

### **Integration with Microsoft Entra ID**

These authentication methods integrate seamlessly with Microsoft Entra ID, Azure’s identity 

**1\. Business-to-Business (B2B) Collaboration \-**  Enable external users to use their preferred identity to sign into your Microsoft or other enterprise applications (SaaS apps, customer apps) 

- Supports Enra ID and social identities

### **2\. B2B Direct Connect \-**  Establish a **mutual, two way trust with another Entra organization** for seamless collaboration

- Useful for heavy, daily collaboration with close business partners

### **3\. Azure Active Directory Business-to-Customer (B2C)**  \- Publish modern SaaS apps or custom-developed apps to **consumers and customers** while using Entra ID B2C for identity and access management

- Supports Entra & Social Identities 

**4\. Entra ID multi-tenant organization \-**  collaborates with multiple tenants in a single Entra ID organization via cross-tenant synchronization

- Good for conglomerates, mergers, multi-cloud dept/test/staging tenants

**Conditional Access \-** Used by Entra ID to bring **signals** together, to make decisions, and enforce organizational policies

**Azure RBAC \-**  Provides fine-grained accesses management of Azure resources  
One element of “least privilege”

- Who has access to Azure Resources,  
- What they can do with those resources  
- Which resources/area they have access to.

The **Zero Trust** security model assumes that breaches are inevitable and continuously verifies every request, regardless of where it originates. It is built to address the modern complexities of cloud computing, remote workforces, and distributed resources.

1. **Verify Explicitly**: Always authenticate and authorize based on comprehensive data points (user identity, device, location, etc.).

2. **Use Least Privilege Access**: Grant users the minimum permissions necessary to complete tasks, utilizing Just-In-Time (JIT) and Just-Enough-Access (JEA) policies.

3. **Assume Breach**: Segment access to minimize blast radius 

**Defense-in-Depth** is a layered security strategy that aims to protect data and prevent unauthorized access. By using multiple layers of security, it reduces the risk of a breach and slows down any attack, allowing time for response.

### **Layers of Defense-in-Depth:**

1. **Physical Security**: Protects hardware and facilities, preventing unauthorized access to physical resources.

2. **Identity and Access**: Controls access to infrastructure, ensuring only authorized users can make changes or access resources, often using tools like multifactor authentication (MFA) and single sign-on (SSO).

3. **Perimeter Security**: Uses measures like DDoS protection and firewalls to defend against external network-based attacks.

4. **Network Security**: Limits communication between resources to reduce attack spread. It includes segmentation, access controls, and secure connectivity.

5. **Compute Security**: Ensures the security of virtual machines and endpoints by using malware protection, proper system patching, and access controls.

6. **Application Security**: Focuses on ensuring that applications are free from vulnerabilities and that sensitive information is securely stored.

7. **Data Security**: Protects the confidentiality, integrity, and availability of business and customer data, often driven by regulatory compliance.

**Network Security Group (NSG) \-** Contains security rules that allow or deny inbound network traffic to, or outbound network traffic from, several types of Azure resources.

- For each rule, you can specify source and destination port and protocol.   
- Can be applied to a subnet or network adapter

**Microsoft Defender for Cloud** \-  A unified infrastructure security management system that strengthens the **security postur**e of your cloud and on-premises data centers

- Provides security guidance for compute, data, network, storage, app and other services  
- Includes support for both Azure and on-premise workloads as well as other public clouds (AWS, GCP) 

[image1]: <data:image/png;base64,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>