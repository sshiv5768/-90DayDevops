## Day-8  Dive Deeper in Go "Hello World"

So on Day-7, we just took a little overview of the Go programming and our first Go program. Today we will have a deeper look into that.

## Compilation in Go 📝
Languages like Python, Go, and JavaScript are high-level languages, which means they are human readable. But what about the machine? We are writing programmes in our readable language (which is Go syntax), but the machine only reads 0's and 1's.


![Untitled Diagram.drawio.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1664301720351/06oxZ5nR9.png align="left")
Here the compiler arrives as a saviour. It converts our Go file into a binary executable file, which our machine can easily understand. And this process of converting human-readable to machine code is called **Compilation**. 

## More about packages 📦
The last day we saw packages, but it was just like a summary. Let's see more of it. Packages are nothing more than a bunch of Go files in the same directory. If you see complex Go programs, you will find that there are multiple folders containing multiple Go files.

How would you use a calculator or any other type of math function in your program, such as log, sin(), cos(), and so on? Will you create it from the start? No! Then how about you already have that programme available in the same directory? You just need to import them as a package.

![Screenshot from 2022-09-28 00-10-05.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1664304020745/45E6U0yUW.png align="left")
That's what a package do, we use packages so we can reuse other people's code, so we don't need to whole program from scratch. First line of every Go program ``package main `` defines that this file is part of the main package, which is the starting point of the program.

`` main `` function is also known as the execution point of any programme because the compiler knows from here it has to start the execution.

## More Resources for Go 🔖
- [FreeCodecamp Go tutorial ](https://www.youtube.com/watch?v=YS4e4q9oBaU&t=1025s)
- [Introduction to Go compiler ](https://www.pluralsight.com/blog/software-development/the-go-compiler)

## End Credits 😇
So this was all about diving deeper in Hello world program. See you on the next Day.



