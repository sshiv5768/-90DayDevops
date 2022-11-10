# Day-36 Installation and Basics of Git.

Okay, so we had some small talks on **Git** and **Version Control System** yesterday. Let's get started with Git and git commands.

But before we move on to the basics, we need to install it first. 

Follow the below process for the installation of Git:
- [Windows](https://youtu.be/oGAxB9r2V_g)
- [Linux](https://youtu.be/PLQQ3tJwBJg)
- [MacOS](https://youtu.be/ZM3I16Z-lxI)

### Git Basics ✨
![Basics](https://media.giphy.com/media/F1ZR9NJoNMmLWynn2M/giphy.gif)
As we discussed in a previous blog, Git is an open-source distributed version-control system that keeps track of your source-code changes. There is no central server on which Git is dependent, you can clone (make a copy of the original) the full source code with the whole commit history on your local machine. 

We are hearing that Git keeps track of changes made to source code. But how? 

### Behind the Scenes
There are a few terms in Git that you should know first.

**Repository**:  You can call it your project folder, but it is remote. It is nothing more than a collection of source code.


![Untitled-2022-10-28-1555.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668099892094/mJfwdiKmG.png align="left")

  
The entire change tracking process can be divided into three steps:
1. You modified something in your current **working directory**.
2. You use ``git add`` command to move your changes from your working directory to **staging area**.
3.  Now you commit changes using ``git commit`` where changes are stored in the **local repository** and using ``git push`` you push your changes to the **remote repo.**

Suppose someone from your team made any changes in the source code in a separate branch; now that changes have been accepted by your team lead, and you want to merge them to your main branch, then you can use ``git merge`` to merge changes to the main branch.

![Untitled-2022-10-28-1555.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668101497007/TEzyzv3E_.png align="center")

Changes are merged to the main branch, but you are working on another branch with the same file, now if you try to push changes to the main branch, there will be a **conflict**. because the same file changed a few minutes ago and the changes were not reflected on your branch.

To resolve it, you must keep your branch in sync with the main branch. To do that you need to pull the changes from main using ``git pull``.

There is one more case of **forking**. 


![Untitled-2022-10-28-1555.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668102560994/zPXdUTb8K.png align="left")
If you are working on someone else's repo and you **forked** that repo and cloned it into your local machine, then you need to use ``git fetch`` to fetch changes from the original repo to your forked repo. Then later you can use ``git pull``.

In this case, you can't just merge or push the changes to the original repo's main branch. You need to send a **pull request (PR)** to the repository's maintainer or host. If he/she reviews and accepts your changes, then your changes are merged.

### Resources📚
- [Git basics with Bitbucket by Atlassian](https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud)
- [Git basics from Freecodecamp](https://www.freecodecamp.org/news/learn-the-basics-of-git-in-under-10-minutes-da548267cc91/)
- [Git and Github Tutorial](https://youtu.be/apGV9Kg7ics)

So that was all about Git and Git basics, but we are not done yet. This was just theory; practical stuff is coming in the next blog. So, stay tuned and subscribe to the newsletter.





