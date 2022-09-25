## Creating Docker Image with Dockerfile

There are many way where you can create a Docker Image and make a container of it, but using ``Dockerfile`` is an easy way. Let's create an **Apache Server** Image using this method.

In this method we are going to follow below steps:
- First choose a ``__base_image__``. In our case, base image is ``Ubuntu``.
- Execute some commands while building the image. Actually it doesn't build whole new image it converts base image into **Apache server** image.

Okay, create a new folder and give whatever name you want to give it. I am giving it ``myapache`` and switching into it.

```
$ mkdir myapache
$ cd myapache
```
Create a new file named as``Dockerfile`` (not mandatory to use the same name). Add below commands into it.

```
FROM ubuntu
RUN "apt-get update"
RUN "apt-get install apache2 -y"

```
Let's breakdown these instructions step by step. First line says that we are using **Ubuntu** as ``__base_image__``. 

Second and third line says to run the given commands. ``apt-get update`` will install the latest version of packages currently installed on user's system. Next command will install **Apache server** on the ``__base_image__``.

Here ``-y`` suggests automatic yes for any prompts in between the installing process.

Now using this ``Dockerfile`` let's build a docker image.

```
$ docker image build -t myapache .

```
You don't need to remember above command it is already present, ``docker image --help `` will help you. **myapache** is the name of the image.

One thing that i want to clarify that ``. `` is for the path of ``Dockerfile``. I am currently in the same directory that's why i used put that.

So above command will build the docker image using our ``Dockerfile ``. It will run that instructions step by step.

```
$ docker image ls

```
Type above command and you will see that **myapache** image is listed there. That confirms that our image is created successfully.


 





