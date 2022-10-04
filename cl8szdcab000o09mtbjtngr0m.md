## Day-13 Basic Linux Commands for DevOps part 2

Today we are going to see more basic Linux commands that are useful in a DevOps engineer's day-to-day life.

## Linux Commands part-2 👨‍💻

- **file `File_name`** : It will show what kind of material( type of content like ASCII, JSON data) a particular file has.
```
file package-lock.json
>> package-lock.json: JSON data
```
- **cp `Fiile_name` `path`** : It will copy a specific file to the specific path. I copied ``P2.txt`` from my home directory to the Desktop.
```
cp p2.txt ./Desktop/
```

![Screenshot from 2022-10-03 08-27-14.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1664765879393/Bd_Ptjlgo.png align="left")

- **whatis `command_name`** : It will show the results of a particular command.
```
whatis ls
>> ls (1)               - list directory contents
```
- **find `path` -name `File_name`** : It will locate a certain file at the specified path.
```
find . -name P2.txt
```

- ** head `Option` `File_name` ** : If the given file is containing hundreds of lines but you just want to see it's few lines than you can use this command. Without any option it will only print first 10 lines from the file content.

```
head -n 5 p2.txt
>> 
This just a file containing randome txt.
1232
zx
qwqa
qqwas

```
- ** tail  `Option` `File_name` ** : Similar to the `head`, but it prints from the last. 

```
tail -n 5 p2.txt
>>
12wq
adscc
asc23sa
2wawds
23das

```
- ** grep ``pattern`` ``File_name`` ** : It is used to find a specific pattern in a text file.
```
grep qwas p2.txt
>>
qqwas
qwas
```
- ** sudo ``command`` ** : It is more like Windows's ``run as administrator`` feature. Whatever command you run with `sudo` will be granted **root** privileges.


![Screenshot from 2022-10-03 21-28-08.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1664812711929/PrJiv8d6O.png align="left")

- ** history ** : It will show history of all the commands that you run till now in terminal.

```
history
>>
 1 tail -n 5 p2.txt
 2 grep 12wq p2.txt
 3 clear
 4 grep aaws p2.txt
 5 clear
 6 ls
 7 cat p2.txt
 8 grep qwas p2.txt
 9 sudo su
 10 history
```
## Resources 📚
- [Linux Cheat Sheet](https://developers.redhat.com/cheat-sheets/linux-commands-cheat-sheet-old)
- [Linux Masterclass ](https://youtu.be/nRpmRDm-QrQ)
- [Linux Crash Course](https://www.youtube.com/watch?v=ROjZy1WbCIA)

## Ending Notes 👋
That was all there was to learning some fundamental Linux commands that are helpful in DevOps. I'll see you shortly the next day.



