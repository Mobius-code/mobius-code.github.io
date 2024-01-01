# Keywords
Like nearly every programming language, Go has **keywords** that have special meaning and usage. Keywords are also called reserved words, which means these words are reserved for a specific purpose.

When you type a `keyword` into your program, it performs a specific action. Therefore, keywords are used in a specific context.

You can think of keywords as telling the Go compiler to take special notice.

Let's look at a few keywords you are already familiar with so that you can understand their purpose and how they are used.

## The `package` Keyword

In Go, the `package` keyword has special meaning and usage.

When we begin our program we have to declare to the Go compiler our main package, or program. We do this with the `package` keyword. Recall that it looks like this:
```go
package main
```

Here we are declaring to the Go compiler that this is our main package.

This is the only way in which the `package` keyword can be used.

## The `import` Keyword

Likewise, when we want to import packages from the Go standard library, we use the `import` function. Recall that it looks like this:
```go
import ("fmt")
```
Here we are importing the `fmt` package from the Go standard library.

This is the only way in which the `import` keyword can be used.

## The `func` Keyword

The `func` keyword is used for creating functions. We use the `func` keyword when creating our main function. Recall that it looks like this:
```go
func main() {

}
```
`func` tells the Go compiler that we want to create a function. In this example, `func` specifies the main function, but it's also used to create your own functions.

This is the only way in which the `func` keyword can be used.

---

Hopefully with these examples, you understand what keywords are and how they are used.

Here are all of the Go keywords:
```
break        default      func         interface    select
case         defer        go           map          struct
chan         else         goto         package      switch
const        fallthrough  if           range        type
continue     for          import       return       var
```
They each serve a very specific purpose when programming in Go.

It is not necessary at this point to memorize or become familiar with all of these keywords now. You will be introduced to all of them at the proper time throughout this tutorial.

It is important to note that the names that you give to arrays, functions and variables cannot be one of the Go keywords. They are reserved for performing specific actions within your program and should only be invoked when you want to perform their specific action.
