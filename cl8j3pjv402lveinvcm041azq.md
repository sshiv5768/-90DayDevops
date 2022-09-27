## Day-7 Let's "Go"

We are going to start our programming journey with **Go** from today. But first, let me clarify something: I will not describe the entire installation process of **Go**.Because it will make this blog very lengthy and, second, I am using Linux and there might be Windows and MacOs users reading this blog, so if I describe the Linux one, I also have to mention other OS processes and it will make this blog longer and boring to read.

But don't be sad, I will share a few resource videos of the installation process on different OSs. You will also require a code editor or IDE. I'll use Visual Studio Code ([Click here to Install](https://code.visualstudio.com/)). I chose VSCode because I've been using it for a long time, so that's the first advantage. The second advantage is that it supports a variety of plugins and tools for **Go lang**. If you don't want to install VScode on your computer, you can use its [web version](https://vscode.dev/) also.


## Installation ℹ️
- [Go installation for Windows](https://youtu.be/xYpqI7GRrvE)
- [Go installation for Linux](https://youtu.be/LLqUFxAPsvs)
- [Go installation for MacOs](https://youtu.be/MbS1wn0B-fk)

## Create your first Go program 🏗️
OK, you are ready with your tools. Let's create our first Go program. I created a new folder on my desktop named it ** Go practice ** and opened it in my VSCode. Also, I created a ``main.go`` file(Go files use ``.go`` extension like Python uses ``.py`` extension). In Vscode, as soon as you create a ``main.go`` it will ask you to install the necessary **go ** extensions. Click "yes" and it will install all the supported **Go** extensions.

![Screenshot from 2022-09-27 00-00-00.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1664217012202/XjX61pIAl.png align="left")

Now copy paste the below code into ``main.go`` file.
```
package main
import "fmt"

func main() {
    fmt.Println(" #90DaysOfDevOps just started!")
}
```
It is our hello world program in Go lang.

## Code breakdown 👨‍💻
Fist line will add package to our main program. Packages are useful way to organise and reuse your code. In Go every program must start with package declaration.Second line is using import keyword to import the ``fmt`` package, which is used for printing a string here.


1.  **func**- used to create a main function.
2. **main()**- It doesn't have any attributes and It doesn't return anything. It is the starting point of the program.
3. **Println**- for printing value in the console.

## Resources 📑
- [Hello World in Go](https://www.geeksforgeeks.org/hello-world-in-golang/)
- [Tech with Nana full Go tutorial](https://www.youtube.com/watch?v=yyUHQIec83I)
- [ Learn Go in 12 min](https://youtu.be/C8LgvuEBraI) (Maggi thodi he jo 2 minitues me ban jayegi) 
- [ Why choose Go for DevOps](https://www.youtube.com/watch?v=7pLqIIAqZD4&t=9s)

## End Credits 👋

So that's all for now. We will move to the next topic tomorrow.




 
