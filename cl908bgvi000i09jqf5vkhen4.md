# Day-16 Linux File System

We looked at Linux user administration yesterday, along with a few user management-related functions. Today, we'll take a look at the Linux file system as well as some straightforward techniques for testing Linux drives and partitions.

## Linux File System: 🧑‍💻
A file system is a manner that various files are organised. Similar to a database, it. Linux is built with configuration files which you can check using `ls /etc`.


![Screenshot from 2022-10-08 07-42-53.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665195255571/UpLES1Hsd.png align="left")

Several Linux file system commands, like "cd," "mkdir," "pwd," "cat," etc., have already been discussed in earlier blogs. So, we'll look at some other extremely useful commands and directories.

## Directories
- `/etc` : It is the directory where Linux's all configuration files live.
- `/bin` : It includes commands for Linux that a user or a system administrator can use. It essentially consists of executable and binary files that can be used to run Linux commands.

![Screenshot from 2022-10-08 08-11-25.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665196893105/vX1SUJR_k.png align="left")

- `/dev` : It consists of files that represent devices that are attached to the local system. These files are not regular files that a user can read. These files are called **Device drivers**.

![Screenshot from 2022-10-08 08-16-18.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665197187262/0xp1Mwwya.png align="left")

- `/boot`: It contains necessary booting file needed for booting the system.

![Screenshot from 2022-10-08 08-53-19.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665199408846/3kiCbQ8F5.png align="left")

- `/home `: It is a home directory for users.

![Screenshot from 2022-10-08 23-01-23.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665250895349/mUDLWpIPq.png align="left")

- `/lib `: It contains library files and kernel related files which are needed in system boot process.


![Screenshot from 2022-10-08 23-15-20.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665251130235/BLVA9b--D.png align="left")

## System Administrator Commands

Here are few Linux commands that you may daily use as system administrator.

- `df `: It will show you available free disk space in your system. You can use flags like `-k`(represent it in kilobytes), `-h`(for more human readable form).


![Screenshot from 2022-10-08 23-02-45.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665250990764/yRu1nuLZx.png align="left")

- `mount`: It will mount local and remote file system. It makes that file system accessible and attach it to the current file system. for more info checkout this official [documentation](https://man7.org/linux/man-pages/man8/mount.8.html).


![Screenshot from 2022-10-08 23-09-51.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665251005582/2zhnKfGTL.png align="left")

- `unmount`: It is quite opposite of `mount` command. It will hide that mounted file system from the normal user.

- `du `: It will generate a detailed view of `df` command. It will take all the files available in your system and prints which file is taking how much disk space. Yes, you can use flags like `-k` and `-h`.
 

![Screenshot from 2022-10-08 23-20-25.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665251435890/7gZVoU-jB.png align="left")
  
## Resources & Ending note 📚👋

- [Linux File System and Partitions](https://youtu.be/PbMT53jaUaU)
- [Linux Full tutorail](https://youtu.be/iwolPf6kN-k)  
- [Linux File System Commands](https://doc.nuxeo.com/nxdoc/filesystem-commands/)

This concludes our discussion of the Linux file system and administrator commands. Without a doubt, there is a lot more (like file permissions, chmod,  etc,) in this topic, but we will cover that in a future blogs. 






