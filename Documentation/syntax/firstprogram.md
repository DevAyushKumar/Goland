initialize our project or module

go mod init <mdoule path>
-> creates new module 
->Modular path can correspond to the repository you plan to publish yout mouel to (example github,etc.)

go mod init <module path>
-> initialized a go.mod file
-> Describe the module: with name/module path and go version used in the program
-> The module path is also the import path 
(ex: import "github.com/nana/booking-app)

All code must belong to a package
the first statement in the go file mus belong to a "package"

The main function is the entry point in the go program.
A program can have only 1 main function because you can only have 1 entrypoint 

"fmt" stands for formate package


Go packages:
-> Go programs are orgaized into packages
-> Go's standard library, provides different core packages for us to use
-> fmt is one of the these, which you can use by importing it
-> A package is a collection of source files

go run <file name> = compiles and runs the code
