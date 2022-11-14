# Day-38 Need of Docker in DevOps

Now we are diving deep into DevOps tools. Our first tool is Docker; we'll look at what it is and why it's important in this DevOps pipeline.

## Scenario
Let's assume we have one web application and we want to simply run that application. What do we need for that? Servers ! Right, we need two types of servers. 


![Untitled-2022-11-14-2122.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668442053473/XBxVjG1iy.png align="left")

One will be a web server, which handles the front-end part of the site, and the next one will be a database server, which handles database requests and the back-end part. Both should be interconnected so that data transfer is possible. 

Now you want to deploy this project. Let's discuss all the possible ways to deploy this web application.

### Physical Servers
You can rent physical servers with the required configurations, like RAM, hard disks, network devices, etc., and deploy your application on them. But it is not the perfect way; there are few flaws in it. You will pay a higher amount as an upfront cost for renting servers. 

![Higher cost](https://media.giphy.com/media/67ThRZlYBvibtdF9JH/giphy.gif)
You always have to purchase higher servers resources( RAM, CPU, Storage) than the actual need of it. For example you application servers require 4 GB RAM but it is not enough because still your OS and other software consumes memory. so your actual need is 4 GB but you have to purchase more.

**Flaws**:
- Costly
- Under usage of server resources(you purchased 16 GB RAM but your application only needs 10 GB)

### Virtualization 
You can use something new but older to save money spent on wasting resources. I am talking about virtualization. You can set up virtual machines and run your app on them. 

![Untitled-2022-11-14-2122 (1).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668450664584/JrR6zHzSg.png align="left")

In this process, on one physical server, you can create multiple virtual machines using a **hyperviser** like VMware or software like Virtual Box, and then you can use these VM as physical servers and deploy your application.

** Advantages: ** 
- Cost effective
- More efficient use of server resources.

**Cons: **
- Still OS resources and cost are involved

However, do you believe this is the best way? No! because you are still paying for OS licensing and allocating resources to that OS. So it's like you are saving something but also losing something. 

![Cost](https://media.giphy.com/media/2wZpm9zyceDyXHPf5S/giphy.gif)

My company, as a software company, believes that we should continue to reduce our costs on OS in VMs and focus more on application performance. This thought process led to the development of a new technology known as "containerization."

### Containerisation
In this method, the OS layer on which both servers were dependent is removed. Not totally, but a small amount of OS is still present to perform certain operations.

Basically in containerisation you will have one OS( it can be on physical machine or virtual machine) and on top of that you will have container technology **Docker**(It is not necessary that it should be docker there are lot's of alternative available)
 
![Untitled-2022-11-14-2122 (2).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668453927401/-zj6uU5Iz.png align="left")

That Docker will create containers in which your web server and database server reside. That container contains a very thin layer of OS. It is designed in such a way that whenever you ask for any process, it will redirect that process request to the **Host OS**.  

It is like a virtual machine but without OS overhead.

**Advantages: **
- It reduces your OS overhead expenses.
- Containers can run on any platform, including your laptop and cloud providers (AWS, Azure, GCP, etc).

Docker is extremely useful for the concept of microservices. It aids in the rapid and secure deployment of microservices. 

## Conclusion
So what is our final conclusion? What is the purpose of Docker? to give importance to our application and not to the OS. We reduced burdens through our application throughout this scenario's journey to make it faster. And by the way, what is the main purpose of DevOps? Deploy solutions faster than others.

## Resources
- [Docker Tutorial](https://www.tutorialspoint.com/docker/index.htm)
- [Why Docker?](https://www.jobsity.com/blog/8-reasons-why-docker-matter-for-devs)
- [ Docker Tutorial for Beginners](https://youtu.be/pTFZFxd4hOI)















