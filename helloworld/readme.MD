# HelloWorld Program Using Go

> To Build `go build [filename|path]` and hit enter

> To Run type the `filename` and hit enter

**OR**

> `go run [filename|path]`

----------
</br>

*NOTE:*</br>
- `go build [filename]` this command is used to compile the file, this command will generate one executable file
</br></br>
- `go run [filename]` this command is used to compile the code and invoke the compiled code. this command will not create any executable file
</br></br>

- `go fmt` Formats all the code in each file in the current directory
<br><br>

- `go install` Compiles and installs a package
<br><br>

- `go get` 
<br><br>
- `go test` 
----------


# Package
1. executable package:  `package main`
2. reusable package:  `package blabla` used to create libs, dependency or helpers functions

*note:&nbsp;*
**executable package, must have a main func**


# Import Statement
`import "fmt"` this statement imports the standard fmt | format package and expose all the function of fmt package.
