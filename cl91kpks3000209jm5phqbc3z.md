# Day-17 File Permissions in Linux

OK, so tomorrow, we checked the Linux file system where we looked over a few directories and commands. Today we are going to check file permissions and how you can modify them using ``chmod``.

You may have noticed that sometimes you want to access one file but you can't. It throws some errors like ``Permission denied``. That is because you don't have access to that file.

## File permissions 🗄️🔐
As discussed in the previous blog, Linux is made up of a lot of configuration files. Many critical (IMP) files require administrator permissions to **r **(read), **w** (write), and **x** (execute). 


![Screenshot from 2022-10-09 19-08-47.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665322755971/8s8lz0Cmu.png align="left")

Checkout the above image. When you type `ls -l` it will give you a more detailed view of the listed files currently available in your current folder. 

Let's breakdown that output. Here I have a total of 115696, items in my home directory. Here it represents the size of the file, who is the user, when it was created, and its name.

I don't have much interest in the above details, but I want to know what those first 10 letters( `-rw-rw-r--`)? What is the use of that?

![horizontal (1).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665324072493/8PcpfmYnv.png align="left")

Actually it is divided in four parts.

1. 
`-`: It represents file type. 
  - `d` stands for directory.
  - `c` stands for character.
  - `-` stands for file.
  - `l` stands for link.

2. 
`rwx`: It shows **user** permissions. What sort of permissions does the user have for that specific file or folder?

3.
`r-x`: It stands for **group** permissions. A group can contain multiple users and can have different permissions.

4.
`r-x`: This is for other users available in the system.

## Changing File Permissions
### Chmod
So now you know about file permissions, now what? How about changing file permissions? But how? There is one command ``chmod`` you can use to change file permissions.



![Screenshot from 2022-10-09 21-48-21.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665332318920/CV-71XDJw.png align="left")

See above image. We first created a `test.txt` file and checked its permissions. For other users, it was `r--` only(reading permission only). Later, we gave `w` permission to `o`(other) using `chmod`. Here `+` used to add a new permission.

There are also numeric representation available for these permissions. Check out [this](https://www.ibm.com/docs/en/aix/7.2?topic=modes-numeric-representation-access) to know more about that.

## Resources & Ending notes 📚👋
- [Linux File Permissions](https://youtu.be/hxNFeL2qY-k)
- [Understand Linux File Permissions](https://www.linuxfoundation.org/blog/blog/classic-sysadmin-understanding-linux-file-permissions)

That was it for the topic of permissions and **chmod**. I'll be back with a new topic tomorrow.