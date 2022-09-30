## Day-10 Output format,Comments & User Input in Go

Yesterday, we worked with variables and constants and got an overview of them. Today we will move one step further and see how to format your output with **printf**. I will also check how to take user input with **pointers**.

## Output format with printf 🖨️
We used ``fmt.println()`` to show output to the user in our **Hello-World** code, but did you know that you can also use ``fmt.printf()`` to print output in Go? Most will say no.

Let me show you how it is done. But first, remember that both functions are not the same; their use cases are different.

### fmt.printf() ♨️
 It will formats according to format specifier and writes to standard output. What is format specifier? In Day-9 blog I mentioned about available data-types. So for different data-types we have different format specifiers which specifies type of the value.

Like,
%v - stands for default value type
%t - stands for word true or false
%b - stands for integer base 2

Checkout more from [here](https://pkg.go.dev/fmt)

```
package main

import "fmt"

func main() {
	var challenge = "#90DaysOfDevOps"

	fmt.Printf("Welcome to %v", challenge)

}
```

![Screenshot from 2022-09-30 19-58-01.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1664548092781/7lzFhoWNb.png align="left")
And in the output you can see that no new line is there after "Welcome to #90DaysOfDevOps". If you want to give a new line you have to put ``\n`` after ``%v``.

## Comments 💥
Comments are normally a syntax in code that a user creates for their own use or for their understanding. Assume you want to share your code with a friend, so you add comments to help him understand which code does which work. 
```
package main

import "fmt"

func main() {
	var challenge = "#90DaysOfDevOps"

// It will print "Welcome to #90DaysOfDevOps"
	fmt.Printf("Welcome to %v", challenge)

}
```

Comments are ignored by compilers and interpreters, so it won't generate any output. It makes the program easier to read for us.

## User input 👨‍💻
Okay, so now if a user wants to put his own value in that ``challenge variable, how would he do that? Simple, by taking input from the user using ``fmt.Scan()`` function.

```
package main

import "fmt"

func main() {
	var challenge string
    fmt.Println("Enter the challenge name: ")

// Taking user input.
    fmt.Scan(&challenge)

// It will print "Welcome to #90DaysOfDevOps".
	fmt.Println("Welcome to" , challenge)

}
```

![Screenshot from 2022-09-30 20-51-36.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1664551305379/4Njjqyywa.png align="left")

Remember that **&** is used to point the variable to where the user wants the value to be stored. It is pointing to the address of that variable. That's why it is known as **pointer**.

## Ending notes 👋
That concludes our lesson for today. See you tomorrow.




