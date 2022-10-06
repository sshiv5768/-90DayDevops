## Day-14 Linux Standard Streams

On the last day, we saw more basic Linux commands which are useful in DevOps. Now today we will move deeper into Linux and will learn about Standard Streams.
 
## Linux Standard Streams 👨‍💻

Standard streams are input and output (I/O) channels, or you could say a bridge between a programme and its environment, in Linux and other generic computer programming languages.

They are also known as input/output(I/O) streams. There are 3 input and output streams in Linux : **Standard Input(stdin)**, **Standard Output(stdout)** and **Standard Error(stderr)**.

Any command you perform in Linux have to deal with these streams. These stream are also classified by specific numbers called as file descriptors. 

- Standard Input(stdin) : 0
- Standard Output(stdout): 1
- Standard Error(stderr): 2

### Standard Input(stdin):

Standard input can be in any form in Linux, it can be a file, a command from the keyboard. Normally it is recognised by `<` symbol. ``cat`` is best example of **stdin**.


![Screenshot from 2022-10-06 06-22-46.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665017592241/NtLt4RLwp.png align="left")

See, It is taking**stdin** and generating **stdout**. This is how these streams work.

### Standard Output(stdout):

**Stdout** can take any form, such as a terminal window, a file, or a response to other commands using **pipe**. It is represented by ``>`` symbol.


![Screenshot from 2022-10-06 06-39-17.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665018571346/OkK1U01oH.png align="left")

In above process we get the output of `ls` command for **Desktop** folder and redirects it to the file `p3.txt`.

Check below image also where we passed output of ``ls`` to ``cat > p4.txt `` using ``|`` symbol.

![Screenshot from 2022-10-06 06-44-10.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665018955276/NrAam6rAd.png align="left")

### Standard Error(stderr):

All error messages from a process are sent to **standard error(stderr)**. This is the display screen by default, however it can be redirected just like standard out. However, using ">" to direct the error output to a certain file won't work. Want to see? Try it out.

![Screenshot from 2022-10-06 06-56-10.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665019634010/DysVqnuAO.png align="left")

For redirecting output of **stderr** we have to use its file descriptor. Now try with ``2>``. It won't be blank again. 


![Screenshot from 2022-10-06 06-56-10.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665019855389/VzUyAP-1k.png align="left")

See, I told you!

## Resources 📚
- [Linux Standard Stream and File input](https://youtu.be/xVaC_G6aeH0)
- [Linux Fundamentals ](https://www.putorius.net/linux-io-file-descriptors-and-redirection.html)

## Ending Credits 👋
Okay, so today we looked over to the Linux standard streams and their examples. See you next week with a new Linux topic.



