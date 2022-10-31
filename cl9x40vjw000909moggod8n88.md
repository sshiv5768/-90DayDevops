# Day-29 Azure Fundamentals- Subscriptions, Resource Groups and Azure Account

Today we are going to explore the Azure subscription model, and in the upcoming blogs we will cover Azure services. 

### Getting started with Azure 🦸‍♂️
![How to start](https://media.giphy.com/media/ywHP9r7U2xL62bmCur/giphy.gif)

To start with Azure and to use its services, you have to create an Azure account. To create an account, move to [Azure portal](https://portal.azure.com/#home) and choose your preferred plan. 

You will have a choice of 3 plans:
- Free-trial account 
- Student account 
- Pay-As-You-Go plan

I mentioned the **Free-trial plan** earlier. If you are a student with a valid college or school **Email ID**, you can apply for a **Student Plan**, which includes **$100** in Azure credits to help you get started with its services.

After your **Free Trial** expires or you run out of your limited number of credits, you are automatically switched to **Pay-As-You-Go** mode, where you have to pay on an hourly basis.

### Subscriptions and Resource Groups
A single Azure account can contain multiple **subscriptions**. How subscription model works? Suppose you have one Azure account for your organization and there are multiple teams working on different projects and they also need to use Azure resources. 

![Screenshot (4).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1667237257720/qC-eOUHKV.png align="left")

Subscriptions allow you to set access control boundaries for multiple teams in your organization. As I said, you can have multiple subscriptions in one Azure account and, with that, you can allocate access boundaries for different resources for your team. This way, you can also reduce your costs.


![Screenshot (5) (1).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1667238147090/-sGCNdRuT.png align="left")

Here In the above screenshot, I am using Microsoft Learn's sandbox method to access Azure's virtual platform. If I click on the **Subscriptions** and see, I have **concierge subscription** with limited access to resources.

### Resource Groups🧾
Now, let's talk about **resource groups**. So, your team has various subscriptions, but all the team members want to access different resources under a separate group. And you also want to allocate specific resources to specific team members to save on your costs and improve work management.

Resource groups can help you in this matter. You can create multiple resource groups with limited access and assign roles in those groups to your team members.

#### Features:
- There is one resource manager who exists in every resource group.
- Resource groups can also access resources outside of the allocated region.
- Resource groups can communicate with each other and can also share resources with each other.

![Screenshot (7) (1).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1667239572914/GoXinQJe_.png align="left")

I only have one resource group here, which was created by **sandbox**. 

![Screenshot (8).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1667239856883/kgsW3-yp5.png align="left")

I only have access to **Azure Cloud Shell** in this resource group. You can create your own different resource group and assign resources to it.

### Resources 📚
- [ Manage Resource Groups](https://bit.ly/3FtIQ9q)
- [ Azure tutorial](https://youtu.be/FAbqJqr93v8)
- [ AZ-900 tutorial by FreeCodeCamp](https://youtu.be/NKEFWyqJ5XA)

### Ending Credits👋
So, this was all that I explored today. On the next day, I will start exploring different **Azure services** and share my learning. So, stay tuned!






