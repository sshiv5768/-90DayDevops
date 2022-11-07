# Day-34 Intro to Azure Active Directory

In a previous blog, we overviewed **Azure Database Services** and today we are going to look at a very important Azure service. If I say you are using this Azure service in your daily IT routine, you won't believe me, but when I give you examples of it, you will be shocked. Even I was also shocked😂

### Azure Active Directory🔐
Azure Active Directory is a cloud-based identity and access management service that is also a centralized security service for multiple Microsoft apps like **Skype**, **Outlook**, **Teams**, **Microsoft Office 365**, etc. If you use any of the above apps, then you are already a customer and user of Azure Active Directory.

![Untitled-2022-10-28-1555.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1667837569190/coY652Fn1.png align="left")

It is also responsible for authentication and access management for various Azure services. It allows you to use your purchased services, your subscriptions, and your resource groups.


![Untitled-2022-10-28-1555.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1667838874999/YWw4yuan7.png align="left")


#### Azure AD (active directory) as Identity Provider
Before talking about identity provider, let's talk about identity. What is identity? 
**Identity** is a thing that is exchanged with the server to get **authenticated**. It can be a username and password or a secret key.

How does Azure AD work in the identity verification process?

Normally, when a client wants to retrieve sensitive information from the server, it needs to be authenticated. For that reason, the client shares his or her identity with the server. But with Azure AD, this process becomes totally different.


![Untitled-2022-10-28-1555.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1667841145957/0cpZ-ofSX.png align="left")

First, the client sends identity information to the Azure AD, which verifies the information and assigns a **token** to the client. which is later sent to the server for further verification. The server will verify that token from AD and authenticate the client.

### Other Azure Services
So now this Azure blog series comes to an end, but I want to inform you that there are many more categories in Azure that have lots of other services.

- AI+ML Services
- Analytics Services
- Developer Tools
- DevOps
- Integration
- IOT (Internet of Things)
- Management and Governance

and many more. You can find the complete list [here](https://azure.microsoft.com/en-in/products/).

I think this one [resource](https://youtu.be/Ma7VAQE7ga4) is enough to learn about Azure AD.

So, our cloud journey ends here, and I know there is still a lot remaining in this journey. I will cover that in upcoming separate blogs. From upcoming blogs, we will cover DevOps tools like **Git**, **Docker**, **Kubernetes**, etc.





