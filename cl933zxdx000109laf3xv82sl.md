# Day-18 Text Editors in Linux

Ok, we saw about file systems and file permissions, but now suppose you want to change or edit a file. How would you do that?
We can do that using text-editors. There are a lot of text-editors available, like Vim, Nano, Gedit, VScode, GNU emacs, etc. However, we will only look at three editors: **Vim**, **Nano**, and **Gedit**. 

## Gedit
The GNOME desktop environment comes with the Gedit editor by default. Whenever you open a file, it will open with the Gedit editor. It offers simple features similar to those of a standard text editor.

```
gedit <file_name>

```

![Screenshot from 2022-10-10 23-38-32.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665425330202/oGEZ8RgOt.png align="left")

## Vim
It is one of the most popular and effective command-line editors. The majority of Linux distributions by default support it. It is user-friendly and offers the same layout for all Linux distributions.

The vim editor, sometimes referred to as a programmer's editor, supports the majority of file types. According to our needs, we can use its plugin. It is also the most difficult one. Seriously, when I was learning it, my major issue was how to exit it 😅

### Installation
It is easy to install just type below command and you are ready to go with it.

```
sudo apt-get install vim

```

![Screenshot from 2022-10-10 23-51-38.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665426110240/7hOIcLBft.png align="left")

``` 
vim <file_name>

```


![Screenshot from 2022-10-10 23-58-24.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665426514420/5mHIC-LKc.png align="left")

When type something in **vim** window it will automatically goes into insert mode and you can edit that file. If you wish to add text, you must switch to insert mode by pressing the ``I`` key. If you have added text and want to save your changes, you must press the ``escape`` key and then``: wq``.

## Nano
The editor Nano is simple to use. It is intended for both novice and expert users. It has various options for modification.


