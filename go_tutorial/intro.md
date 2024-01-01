# Intro To Programming With Go

### What is programming?

Programming is the process of "speaking to a computer" in order to get it to do a specific task or set of tasks. In order for us to speak to a computer, we have to speak to it in its language. The only language a computer understands is 0s and 1s, what's called binary or machine code. You can also think of this as false/true or off/on. Zeroes (off/false) and ones (on/true) are the only two states a computer recognizes.

However, we are not capable of actually programming in machine code. It's just far too tedious and error-prone. Therefore, we have what are called high-level programming languages that look more like the language that we can speak and understand. These high-level programming languages are then compiled or interpreted into the language the computer understands, into binary or machine code.


### What is Go?

Go is an open-source programming language developed by Ken Thompson (of C and UNIX fame), Rob Pike, and Robert Griesemer at Google. Go is easy to learn and has a great community around it. The first version was released in 2009.

OpenSUSE defines the Go programming language this way:

Go is a compiled, garbage-collected, concurrent programming language.

Go is an expressive, concurrent, garbage collected systems programming language that is type safe and memory safe. It has pointers but no pointer arithmetic. Go has fast builds, clean syntax, garbage collection, methods for any type, and run-time reflection. It feels like a dynamic language but has the speed and safety of a static language.

### Static Type vs. Dynamic Type
Programming languages are either one of two type systems, static or dynamic. This refers to how the programming language handles the data types of variables, what's called type checking. If the data types are checked at compile time, the language is of static type. If the variables data types are checked at runtime, the language is of dynamic type.

In a statically typed language, you can think of the data type as "hard coded" into the variable. Once a variable is assigned a certain data type, it cannot be changed to a different data type. Examples of data types are `int` for integer, `string` for a text string (like "Hello, World!), and `bool` for boolean.

For example:
```go
var a int = 10
```
This is a variable named `a` of data type `int` with a value of 10. This variable named `a` cannot be assigned another value with a different data type. In other words, variable `a` can only hold a value of data type `int`.

For example, you cannot do the following, change the data type of the variable `a` after you have already assigned it a value of a certain type:
```go
// You cannot do the following
var a int = 10
var a string = "Hi"
```

Here is an example of a dynamic type system, from Python:
```python
a = 10
a = "Hi"
```
The value of 10 which is data type `int` was first assigned to the variable `a` and then data type of `string` was assigned to the variable `a`.

### Compiled vs. Interpreted

Programming languages are either compiled or interpreted. Go is a compiled language. Python is an example of an interpreted language.
