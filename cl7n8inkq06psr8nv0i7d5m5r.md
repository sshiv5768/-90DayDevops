## Scalability and its types in Cloud☁️☁️

## 🎯 What is Scalability?
Let's make it simple for you. Suppose you're running your own e-commerce web app like Amazon or Flipkart. For handling customer data you use rented servers or your own purchased servers. You observed high sales growth and new customers during festival season.

Now, what you would do to handle new customers ? 

Either you will increase the server capacity or you will add more servers to your list.
This ability of your infrastructure to increase or decrease IT resources as per usage and need is called Scalability.

## 💥 Types of Scaling
There are two basic types of scaling: Vertical scaling and Horizontal scaling. Let's take a look of each one by one.

### Vertical Scaling
Let's say you have a resource it can be anything a database, a VM or a container. How would you scale it?
You can scale it by increase it's size, wait what do you mean by size? Here size refers it's core features like CPU, memory and storage.

![Untitled-2022-09-04-1502.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1662284869644/f9T-n-Aa7.png align="left")
 
This method of scaling where increasing or decreasing the size of the resources happens is known as Vertical Scaling. Increasing the size is called scaling up and decreasing the size is called scaling down. 

It is easy to scale vertically but sometimes you have to face major downtime which will affect your system performance 🥵

### Horizontal Scaling
In this method we increase or decrease the amount of resources in our system to spread the workload equally. Which will result us better performance and higher availability.

![horizontal.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1662287773246/3FY5o300N.png align="left")

The risk of downtime with horizontal scaling is lower than vertically scaling. So that most of people suggest to use this type of scaling.

## 👋End credits
Now, most of the cloud service providers have a feature of Auto-scaling, which allows you to automatically scale up or scale down your cloud services like EC2, AWS S3, etc. Check-out [this](https://avinetworks.com/glossary/auto-scaling/) for more about Auto-scaling.

So that's all about scaling and its types. I will be back again with new topic in cloud and DevOps. Do subscribe my blog 🤠

