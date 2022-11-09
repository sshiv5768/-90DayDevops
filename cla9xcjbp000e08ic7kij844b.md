# Day-35 Introduction to Git and Version Control System.

Before we move on to Git, we must first define version control system and why it is important for current SDLCs (software development lifecycles). Also, we'll look at some basics of Git.

### What exactly is a Version Control System(VCS)?🧐
![What is that](https://media.giphy.com/media/dp74BKs7XV7Ve/giphy.gif)

Ok, to understand it, let's take one example. Suppose you are working on a large project where multiple teams are involved in different aspects of the project, like the web dev team, the backend team, the QA team, the DevOps team, etc. Your product is production-ready, and you want to deploy it for your customers.

You deployed the project and marked it as version ** 0.0.1**. Now, after a few times, you add a few features to your app and redeploy it with the version name **0.0.2**.  The same thing happens whenever you add new features or make changes to its previous version, new versions are created.

But ![Spiderman](https://media.giphy.com/media/MCZ39lz83o5lC/giphy.gif)

Similarly, there are a few drawbacks to using this older versioning method.
- No proper track or record of the changes made to the source code exists.
- Less collaboration between teams.
- Previous versions cannot be restored.

👉 With a version control system:

- All changes can be tracked using **commit** messages.
- It provides better collaboration between developer teams. Whether you and your team members are in different parts of the world, you can still make changes in the source code, and all the changes will be stored as commit history. This is what you can achieve by converting your project into **repository** using VCS.
- There is one very important feature in VCS which is **branching**. You can create separate branches and assign them to different people on your team. You can also give names to those branches like "V.0.0.1", "Test", "Web team", etc.


![Untitled-2022-10-28-1555.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668012767251/mP_OIeL_m.png align="left")


If there is a need to revert changes in any branch, then you can easily switch to that branch and revert your changes. If a bug exists in a specific branch, you can investigate its commit history and resolve it.

Okay, let's talk about Git now.

### What is GIT? 🙋‍♀️

It is a tool that keeps track of changes made to the source code, or you can say that it is an **open-source distributed version control system**. 

Git is not the only version control system available.
- [Subversion (SVN) ](https://tortoisesvn.net/)
- [Helix Core](https://www.perforce.com/products/helix-core)
- [Azure DevOps Server](https://azure.microsoft.com/en-us/products/devops/server/)

You can download Git from [here](https://git-scm.com/downloads).

### Resources 📚
- [ Version Control System](https://www.youtube.com/watch?v=Yc8sCSeMhi4)
- [ Types of Version Control System](https://youtu.be/kr62e_n6QuQ)
- [ Introduction to Git](https://youtu.be/8JJ101D3knE)
- [Complete Git and Github Tutorial](https://youtu.be/apGV9Kg7ics)

So today, this was all we covered about version control systems and Git. In upcoming blogs, we will see the installation of Git and Git commands. So, stay tuned! 👋





 












