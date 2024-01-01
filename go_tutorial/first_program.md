# Writing Your First Program

Now that we have our environment set up, we will start by writing our first Go program. Start by creating a directory named `Go` in your home directory. We will put all of our Go source code files in this directory.
```bash
sudo mkdir Go
```
`cd` into the `Go` directory.
```bash
cd GO
```

Now create a file called `hello.go` with your favorite text editor or IDE.

The `.go` format extension is very important. This allows the Go compiler to "process" your code and turn it into a program. Every program you want to write in Go must have the `.go` extension.

The first program any beginner should write is "hello, world". Don't worry, this entire program will be explained in detail.

In your text editor or IDE, write the following:

```go
package main
import ("fmt")

func main() {
    fmt.Println("Hello, World!")
}
```
Now, let's run our code. In your terminal, type:
```bash
go run hello.go
```
You may need to use `sudo` privledges. You sould see this output:
```bash
Hello, World!
```
The `go run` command tells the Go compiler to run your program.

If you want to create an executable file out of your `hello.go` file, type:
```bash
go build hello hello.go
```
The `go build` command tells the Go compiler to make an executable file, also called a binary. Then you specify the name of the file you want to make. You can name files whatever you want. Here we chose to name the file `hello`. The `hello.go` file is your `.go` file that the Go compiler turns into an executable program. This is the source code file.

After you have created your executable program, type `ls` in your terminal to list all the files in your current directory. You should see this output:
```bash
hello hello.go
```
There are two files. One is the executable program you created with the `go build` command named `hello` and the other is the original source code file named `hello.go`. To run your executable, type:
```bash
./hello
```
Note: To run any executable file in Linux, simply type the name of the executable prepended by `./`. This works only if you are in the same directory as the executable. For example, if we have an executable named `myfile`, you would type `./myfile`. This `./` tells the bash shell, or whichever shell you are using, that you want to execute the command from the current directory.

Alternatively, you could type the abosolute path to run your executable/binary.
```bash
/home/user_name/Go/hello
```
or
```
~./Go/hello
```
In both of these two cases, it doesn't matter what directory we are currently in.

In UNIX-like operating systems, the tilde symbol `~` stands for your `/user` directory.

Please note that if you decide to make an executable out of your `.go` file, you will need to recompile it every time you make a change to the source-code file.

## Understanding Our Program
Let's break this program down.

### Package Declaration

```go
package main
```
This is a **package declaration**. Every program in Go is part of a package. When you declare the package to be `main`, you are telling Go that this is your main program. You can think of **packages** in this manner, simply as programs. That is essentially all they are.n program".

In order for your code to run, it has to be part of the `main` package.

### The `import()` Function

```go
import ("fmt")
```
This is the `import()` function. Here we are telling Go that we want to import another package from the Go standard library called `fmt`, which stands for "format". This package provides the `Println()` function that allows us to print text to the screen.

We can import many pre-written functions from the Go stanard library to aid us. For now we will be focusing on the `fmt` package.

### The `main()` Function

```go
func main () {

}
```
This is the `main()` function of our code and is the main part of our program. Every program in Go must have a `main()` function. All of the other code we want to execute will be placed within this function inside of the curley brackets `{}`. There are exceptions, but we will deal with those later. For now, focus on placing all of your code within the curley brackets `{}` inside of the `main()` function.

### The `Println()` Function

```go
    fmt.Println("Hello, World!")
```
This is the `Println` function that we imported from the `fmt` package. It prints anything within the parentheses `()` to the screen. It is short for "print line". Notice that it is inside of the curley brackets `{}` within the `main` function. In order for the `Println` function to print text to the screen, the text has to be surrounded by quotation marks `" "`. However, the quotation marks are not part of the output you see printed to the screen.

In order to use functions from other packages, in this case the `fmt` package, we have to import them into our main package.

## Further Practice

Now let's write a few more programs with the `Println()` function.

Create a file named `great.go`.

First comes the package declaration that tells the Go compiler this is our main program. Then we import the `fmt` package to use the `Println()` function, followed by our main function. Inside of our `main()` function, place the `Println()` function. Then inside the parentheses, place a string of text surrounded by quotation marks.

```go
package main
import ("fmt")

func main () {
    fmt.Println("What a great day to learn Go!")
}
```
Now let's run our program:
```bash
go run great.go
```
The output you should see is:
```bash
What a great day to learn Go!
```
Great job! Look at you Go!

Now create a file named `green_eggs.go` and type in the following code:
```go
package main
import ("fmt")

func main () {
    fmt.Println("Do you like green eggs and ham?")
}
```
Now let's run our program:
```bash
go run green_eggs.go
```
This is the output you should see:
```bash
Do you like green eggs and ham?
```

Later we will learn how to pass input to our programs to answer this question!

Congratulations! You are well on your way to learning how to program!


Continue to next lesson
