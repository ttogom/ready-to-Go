## 01 hell_world.go
- `package main`: Declares this as the main package, which is required for executable programs.
- `import "fmt"`: Imports the fmt package, which provides formatting and printing functions.
- `func main()`: Defines the main function, the entry point of the program.
- `fmt.Println("Hello, World!")`: Prints the string "Hello, World!" to the console.

In-depth explanation: When you run this file, the Go runtime first looks for the main package. Within this package, it searches for the main() function, which serves as the entry point. Once found, the runtime begins executing the code inside main(). The package "fmt" stands for "format", and it's one of Go's standard library packages which provides I/O operations. "fmt" includes both high-level convenience functions (like Println) and lower-level formatting and scanning functions.

#### Executing .go file
There are two different ways to execute `.go` file.
1. Build and Execute by one command (`go run`): The `go run` command compiles and executes a Go program in one step.
    - `go run main.go`
2. Build then Execute: This method involves two steps which are building an executable and then running it.
    - `go build main.go`
    - `./main`

When executed by the either method, hello_world.go will produce "Hello, World!" on the console