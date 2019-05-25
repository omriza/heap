# Go part1

## Agenda
This session is intended to provide a quick taste of Go

## Who uses go
Add YouTube, Twitter, Apple

## Go Tools

### go get
Install Go packages

### go build / go install
These 2 commands compile packages and dependencies
(deep dive in a later session)
[read more](https://dev.to/plutov/go-tools-are-awesome-bom)

###  go list
Lists packages by import paths

### go env
Prints Go environment information

### gofmt
Reformat your code based on the Go standards
- ```goimports``` is based on ```go fmt```. Updates your Go import lines, adding missing ones and removing unreferenced ones.

### go vet

take example from [here](http://blog.ralch.com/tutorial/golang-tools-inspection/)

### golint
Checks for style violations and output suggestions

### go test
- ```-v``` Prints the test name, its status (failed or passed), how much it took to run the test, any logs from the test case, etc.
- ```-race``` to run Go race detector.
- ```-bench``` to run benchmarks.
- ```-cpuprofile cpu.out``` writes a CPU profile to the specified file before exiting.
- ```-memprofile mem.out``` writes a memory profile to the file after all tests have passed.
- ```-cover``` measures the percentage of lines of code that are executed while running a suite of tests.


### go generate
Powerful code generation
- Go code from templates

- Mocks
- Much much more

[read more](https://blog.gopheracademy.com/advent-2015/reducing-boilerplate-with-go-generate/)
[genny](https://github.com/cheekybits/genny) is a tool written on top of go generate that helps with generating generics-like code from your code.

### go doc
Prints out the documentation for whatever argument you pass it (can be a package, const, func, type, var, or method).

Go docs are similar to Java doc but without the strict formatting rules.

The additional binary ```godoc``` will run a webserrver on your localhost that will host all Go standard library package documentation in addition to all packages that live in your $GOPATH.

### check
https://gitlab.com/opennota/check

### So many more
[article](https://dominik.honnef.co/posts/2014/12/go-tools/#godepgraph)

## Go WTFs
[sizeof](http://golang-sizeof.tips/)

## Summary
Tell us which subjects you are most curious about

### Links

- [The Go programming language tour](http://tour.golang.org/)
- [The Go Bootcamp Book](http://www.golangbootcamp.com/book/)
- [Go by example](https://gobyexample.com/)
- [Effective Go](http://golang.org/doc/effective_go.html)
- [The Go language FAQ](http://golang.org/doc/go_faq.html)
- [The Go style guide](https://github.com/golang/go/wiki/Style)
- [Damian Gryski’s Gophervids](http://gophervids.appspot.com/) is an aggregator for recordings of Go meetups and conferences.
- [An incomplete list of Go tools](http://dominik.honnef.co/posts/2014/12/an_incomplete_list_of_go_tools/) by [Dominik Honnef](http://dominik.honnef.co/)
- [Go Koans](https://github.com/cdarwin/go-koans)
