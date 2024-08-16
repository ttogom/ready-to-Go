# ready to Go
This project is a hands-on learning tool designed to explore and master the Go programming language and its ecosystem, particularly focusing on web development using the Gin framework. Through the process of building a RESTful API, this project aims to provide practical experience in Go, API design, and modern backend development practices.

### Key Goals
1. Implement CRUD operations for a simple resource (e.g., users, tasks, or products)
2. Utilize Gin's routing and middleware capabilities
3. Implement proper error handling and logging
4. Add basic authentication and authorization
5. Connect to a database (e.g., PostgreSQL or MongoDB)
6. Write unit tests for API endpoints
7. Document the API using Swagger or a similar tool

Let's dive into the project

## Installing and Basics
### Initializing a new Go module
If you haven't already, download Go in the following [link](https://go.dev/dl/). <br />
Now, following command will initialize a Go module. The convention is known as the module path:

> `go mod init github.com/yourusername/yourprojname`

Above command will create a `go.mod` file, which manages the dependencies of the current project.

### Little bit about dependency management
The directory containing the `go.mod` file is considered the root of your module/project. Go will use this go.mod file to manage dependencies for all Go files in this directory and its subdirectories. If there's no `go.mod` in the current directory, Go will look in the parent directory, and keep going up until it finds one or reaches the root of the file system.

### Installing Gin framework
Following command will add Gin framework as a dependency of the current project:
> `go get -u github.com/gin-gonic/gin`
- Note that the `-u` flag in the command stands for update. With `-u`, it will check for updates to all direct and indirect dependencies and download the latest compatible versions.
- After applying the command, you will see that `require ( ... )` field has been added to the `go.mod` file.

The following instructions will go straight into using Gin framework. If this is your first time programming in Go, look at `/syntax` directory of the project to learn the basic syntaxo.