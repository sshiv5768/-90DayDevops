## Day-9 Variables and Constants in Go

Yesterday we learned about packages and compilation of Go code in depth. Today we are going to learn about variables and constants in Go.

## Variables & Constants 📥
Variables are used to store various types of values. Assume it is like a box containing something that is only opened when something is needed from that box. Once the variable is created, you can reference that variable name everywhere in the app.

But you can't easily create variables like ``x = 29`` like you do in **Python**. There is slight change in Golang. In Go, there are keywords defined to do specific jobs, like if you have noticed in the Hello World program, we used ``func`` before to create a function. ``func`` is a keyword defined to create a function in Go.

So, keywords are specially defined words to do certain things. You can't use those keywords as your function name or variable name.

For creating a variable, we have a keyword ``var`` here. Let's create a variable:

```
package main

import "fmt"

func main() {
    var challenge = "#90DaysOfDevOps"
    var currentDay = "9th day"
    fmt.Println("Welcome to", challenge, "")
    fmt.Println("We are at", currentDay, "in", challenge)

}
```


![Screenshot from 2022-09-29 08-04-13.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1664418869731/F9D89V37y.png align="left")

As I said in the starting variables contains various types of values and those types are known as **data types**.

Go mainly has three basic data-types: 
- bool: for boolean values: true or false 
- Numeric: represents integers, floats, and other complex values 
- String: for string value: character, sentence.

But in the above programme we haven't mentioned any of them. Why? Because Go is smart enough to get the data type passed in the variables by its own. Same like Python.

### Constants ⛎
In variables, we can change the value of that variable after it is declared and defined. If you need a variable whose value should be fixed and can't change, then you can use **constants**.
Like variables, you can define constants using ``const`` keyword.

```
package main

import "fmt"

func main() {
    var challenge = "#90DaysOfDevOps"
    var currentDay = "9th day"
    const totalDays = 90
    fmt.Println("Welcome to", challenge, "")
    fmt.Println("We are at", currentDay, "in", challenge)
    fmt.Println("Total days are", totalDays)

}

```

![Screenshot from 2022-09-29 08-12-47.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1664419380399/rKWsD_rFr.png align="left")

If you try to change the value of a constant, then it will show you this kind of error:
![Screenshot from 2022-09-29 08-16-19.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1664419586716/77_OTj5tB.png align="left")

## Ending Note 👋
So that was all for today, see you on next Day.






