# Day-30 Azure Services: Compute

In the previous blog, we talked about subscriptions and resource groups. There is one more thing known as **Management Groups** which I didn't mention in my previous blog.

Management groups help you manage your multiple **subscriptions** with a set of policies and conditions.
To know more about this topic checkout [this](https://learn.microsoft.com/en-us/azure/governance/management-groups/overview)

### Azure Services
![Memes](https://media.giphy.com/media/3o6MbsWjZwURvye0ko/giphy.gif)

As discussed in [Day-27](https://sshivlal.hashnode.dev/day-27-different-cloud-models) blog, the cloud has three basic models: **IAAS**, **PAAS** and **SAAS**. Azure provides more than 150 services, and these services are divided on the basis of these cloud models.

**Compute**, **networking**, **security** and **storage** are the four main uses of cloud computing, and we are going to look **Azure** services through these.

### Azure Compute Services
Azure compute services satisfy your basic computing needs like disks, processors, networking, memory, and operating systems.

Let's say you have multiple applications and want to deploy them all. You would face some issues if you deployed them all on a single physical machine. Maybe some applications need higher processing power, and some need a different OS than others, so it won't be possible with a single physical machine.

You need a better solution. Here comes the concept of **Virtualization**. You can create multiple virtual machines and deploy your apps on those VMs. VMs are basically virtual compute devices with desirable hardware and software configurations. These VMs are created by third party virtualization software, which is called as **Hyperwiser**.
 

![Untitled-2022-10-28-1555.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1667403459266/UlA8Ti9iJ.png align="left")

Virtualization provides you access of the required computer hardware with better utilization. More details can be found [here](https://www.ibm.com/cloud/learn/virtualization-a-complete-guide).

### Azure Compute Services⚙

#### Azure Virtual Machines
- Falls in **IaaS**(Infrastructure as a service) category
- Gives you pure control over OS(Windows/Ubuntu)
- You can run any web application, database, or desk application on it.
- Can scale it vertically and horizontally. (But autoscaling feature is not there)

#### Azure VM Scale Sets
- It is basically a set of identical VMs.
- It has autoscaling features, so whenever there are higher workloads or traffic, it automatically adds VMs with similar configurations to the set.
- Best suited for load balancing.

#### Azure Container Instances
#### Azure Kubernetes Services
#### Azure App Services
- Enterprise level web app **PaaS** service
- Helps you quickly build and deploy any web app or API using any programming language.

#### Azure Functions 
- Falls into **PaaS** category.
-  Serverless solution to apply your system's logic by reducing your efforts in writing code and infrastructure maintenance.  
- Designed for micro-service apps.

Azure Container Instances) and AKS (Azure Kubernetes Services) will be covered deeply when we reach the container and cluster parts of this #90DaysOfDevOps series. 

### Resources📚
- [Azure Virtual Machines](https://learn.microsoft.com/en-us/azure/virtual-machines/overview)
- [Azure Compute Services](https://youtu.be/inaXkN2UrFE)

That's all for today. Subscribe to the newsletter for such DevOps blogs and resources. See you in the next blog.














