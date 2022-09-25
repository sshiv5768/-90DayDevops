## Day-4 Zooming Out DevOps Life cycle

Last time we just over viewed different phases of the DevOps life-cycle, but today we are going to zoom out on each phase and look for each sub-phase. In-short, we are going to look at the DevOps life cycle at a micro level.


![devops-fig8-1024x527.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663958391120/TWeu85689.png align="left")

## Continuous Development ⏩

### Plan
As discussed further in this phase, the team starts building a road-map for the project. In this phase, product and project managers come into the picture. By collaborating with them, you can gather requirements from the stockholders or clients. Here, the devops engineer is not involved, but you, as a devops engineer, have to be in touch with the team to get a basic idea of the project. so that you don't face any understanding issues further.

![Screenshot from 2022-09-23 08-14-21.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1663901081504/Vv86_ke4M.png align="left")
Tools like **Azure Devops (Boards)** and **Jira** can be used to create a digital plan for the project. Assign tasks to each team member and set a reminder or set a different tags like  **epic**, **important**, **bug**, **feature**, etc.

### Code
All the planning sessions are over. Now what? The coding phase begins. In this phase, you, as a devops engineer, may or may not be part of the team, but you can help the team understand the infrastructure. You can suggest available tools to them so that they can design the software accordingly. The team will set up coding standards and make others follow them so that code-styling and code-readability stay consistent.

Here, tools like **git**, **github**, **bitbucket**become super useful for better team work and code management. If you are working in a team, then you can create multiple branches and assign each separately to each team member. 

## Continuous Testing 📝
### Build
Whenever a developer makes any changes to the code, he needs to push the changes to his assigned branch and then other developers review those changes. If both are happy, then go to the next step. which is making a pull request. From here, a devops engineer's work begins. He created a CI/CD pipeline to automate the build process using tools like **Jenkins**, ** Github actions ** and ** Circle Ci**. 

To build a CI/CD pipeline, you should be familiar with scripting and have a basic understanding of YAML (Yet Another Markup Language-literally, I thought the same thing). It doesn't stop here. As a devops engineer, you should be prepared for the next phase, so converting that project into a container is your next task. Create a container and make a Docker image of it.

### Testing
Now comes the real hard-work. Testing! Normally, it is not that hard if you know how to build test cases and automate them using CI/CD pipelines. Manual testing is time-consuming and needs additional manpower. But with automated testing, you not only save time but also do security scans along with automated test cases. You can create a separate test environment using IaaC(Infrastructure as a Code) tools..

## Continuous Integration 🧤
### Release
OK, your application has completed the testing phase, which means it is ready for production use. Then go ahead with the production part. If you already have a Docker image of your app, then publish it on image registries like Docker Hub. From there, production servers can easily deploy your app.

At this stage, each code has passed the automated test cases, which means your code is ready for release. You can set different release sets, like you can choose whether you want to release a new feature or a regular release.

## Continuous Deployment 🚢
### Deploy
Now in this phase, your team's efforts will meet at their destination. Your build is ready to be released on production servers. There are some tools through which you can automate this process, like **AWS Code Deploy**, **Ansible**, ** Chef **, ** Puppet ** and others.

### Operate
Your app is deployed and now you think you are the most relaxed person in the world. You are wrong. There is still lots more to do. Suppose you deployed an e-commerce app and during high times like festival season, lots of new users are signing up and purchasing from your app. Suddenly, your app crashed. Your servers failed to manage the high amount of traffic. What will you do? You will use auto-scale functionality where you can automatically scale up (by adding more servers ) and scale down according to observed traffic. 

Making your app highly available and fault-tolerant is the main goal of this phase. which you can achieve by deploying your app to cloud services like **Azure**, **AWS**, **GCP**, etc. These platforms have multiple features to increase your app's performance.

## Continuous Monitoring 💻
### Monitor
And the final phase is monitoring. Monitoring your app's availability and working. If anything happens midway, then there should be someone who should notify you. So tools like **Splunk**, PagerDuty, **Prometheus play an important role in this phase. There are various types of monitoring, like infrastructure monitoring, application monitoring, and network monitoring. And different tools are used for all these types of monitoring. Checkout resources for more.

## Resources 📚

- [Continuous Monitoring](https://www.headspin.io/blog/what-is-continuous-monitoring-in-devops)
- [ The eight phases of a DevOps Pipline ](https://medium.com/taptuit/the-eight-phases-of-a-devops-pipeline-fda53ec9bba)

# End Credits 👋
So that's all for today's blog see you on next day.


 
