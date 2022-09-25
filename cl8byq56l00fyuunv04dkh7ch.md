## Day-2 DevOps Lifecycle

On day-2 I went through multiple phases of a DevOps lifecycle. But before moving to that I need to know what were the flaws  in the previous SDLCs(Software Development Life Cycles).

## Why need DevOps? 🤷‍♂️
Before DevOps, we had waterfall and agile model. Waterfall model moves in linear and sequential manner like a flow of water. But in waterfall you couldn't jump to next phase without completing the previous one. Thus, it became time-consuming.

The same goes for the agile method. There was a lack of collaboration between the development team and operations teams, which resulted in slowing down the development and release process.

# Phases of DevOps life cycle 💡
There are mainly 5 phases of devops life cycle.
- Continuous Development
- Continuous Testing 
- Continuous Integration
- Continuous Deployment
- Continuous Monitoring 

## Continuous Development 👨‍💻
It is the phase where all the planning begins. As a developer, you will create a list of requirements needed for the application. No tools are required during this phase, but for better team collaboration and a well-maintained application, we will need a version control system such as **Git**, **Jira**, **BitBucket**.

## Continuous Testing ⌛
At this stage, the developed app will be continuously tested using tools like **Selenium**, **JUnit**, etc. By automating this entire phase with **Jenkins** your QA team can now focus on other things. You can create a CI/CD pipeline where you can apply testing rules like **run automated test cases** and "merge them to the main branch**.

## Continuous Integration 🧩
It is the most crucial and important phase of the entire DevOps life cycle. Whenever any developer from your team pushes changes to the main repo, they will be checked and tested. Your code will be tested through automated tests, and then it will be pushed to the main repository. 

We use tools such as **Jenkins**, **Github actions**, **Circle CI**, and others to build an automated CI/CD pipeline.

## Continuous Deployment ⚙️

After merging your changes to the main branch, now comes the deployment and configuration management part. What is configuration management? Any ideas? No!

Suppose your application is ready to be deployed on production servers, but how would those servers know how to run that application or what to install to run that application? What are the configurations needed to run that application on a production server? By the way, you have to specify these things.

And that is what is called configuration management, in simple words. Configuration scripts must be written in YAML files and placed in tools such as **Ansible**, **Chef**, and **Puppet**.They will handle the rest, like managing the updates and maintaining the state of the application.

OK, the configuration part is over. Now what? How would you deploy your app? Now containerization comes into the picture. You will convert your app into containers using tools like **Docker**, **Vagrant**. Containers will be deployed and managed by other tools like **Kubernetes**. It will also do additional things like load balancing, container orchestration, cloud migration, and lots more. 

## Continuous Monitoring 📈
So your app is deployed, huh? What's next? Netflix and chill? Who will monitor your app's performance ? If suddenly something happens to your app, who will notify you of that ?

In this phase, we have to maintain the security and availability of our app services with the help of tools like **Splunk**, **ELK Stack**, **Grafana**, etc. These tools will help you fix problems automatically as soon as they are detected.

## Resources 📚
Here are some of the resources to learn more about the DevOps life cycle and its phases. 
- [DevOps life cycle](https://www.edureka.co/blog/devops-lifecycle/) 
- [Continuous Development](https://www.youtube.com/watch?v=UnjwVYAN7Ns)
- [Continuous Testing](https://www.youtube.com/watch?v=RYQbmjLgubM)
- [Continuous Integration](https://www.youtube.com/watch?v=1er2cjUq1UI)

## End Credits 🥲
So day-2 learning summary ends here, stay tuned for Day-3 👋











