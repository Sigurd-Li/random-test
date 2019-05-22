# random-test, generate a random interger number with 1 to 10.

How to build an executable file for a variety of OS

For windows:

GOOS=windows GOARCH=amd64 go build -o /path/random.exe random.go

For Linux:

GOOS=darwin GOARCH=amd64 go build -o /path/random random.go

For Linux:

GOOS=linux GOARCH=amd64 go build -o /path/random random.go
