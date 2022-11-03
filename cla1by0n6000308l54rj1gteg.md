# Day-31 Azure Networking Services

We have reviewed **Azure Compute Services**, now it's time to look at **Azure Networking Services**.

### Azure Networking Services
Like compute, **Azure** also provides networking services for its resources. With these networking services, resource groups can communicate with each other and share resources. You can create separate network groups with the required network configurations and the required range of IPs. These services are basically used to connect cloud and on-premises resources.

#### Azure Virtual Network
A virtual network is basically a representation of the physical network infrastructure of different **Azure resources**. It allows users to create, manage, monitor, and secure connectivity between Azure resources. 

![Untitled-2022-10-28-1555.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1667487592965/AZUOT1Ccg.png align="left")

If there is higher web traffic, then you can create multiple VMs and put them on separate **subnets** using virtual network. It helps to divide web traffic among different VMs at the same time.


![Untitled-2022-10-28-1555.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1667489588615/gAPnGFIlq.png align="left")

#### Azure Load Balancer
Azure load balancer distributes web traffic to multiple resources. Suppose you have two VMs and you are facing high web traffic, then the load balancer divides that traffic equally among both VMs. This will result in better scalability and higher availability of the resources.


![Untitled-2022-10-28-1555.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1667494427174/l2LlYp8d7.png align="left")

### Azure VPN Gateway
Now suppose you are running on a **hybrid** cloud model, and you want to integrate your public cloud resources with your on-premises servers. How can you do that? using the Azure VPN Gateway.

It helps your cloud resources talk to your on-premises infrastructure by creating an **encrypted network gateway**. It can also make cross-regional communications through Azure virtual networks.

#### Content Delivery Network
 Azure CDN (Content Delivery Network) allows users to deliver their web content to the closest Azure datacenters. 

This method reduces latency and provides higher availability for your web app with less load time.

### Resources
-[Azure Networking Models](https://youtu.be/5NMcM4zJPM4)
-[ Azure Fundamentals](https://youtu.be/NKEFWyqJ5XA)

So that was all about Azure Networking Services. If you like these articles and resources throughout this #90DaysOfDevOps journey, then do share them in your network and in your dev community. See you in the next blog.






