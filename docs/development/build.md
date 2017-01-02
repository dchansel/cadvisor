# Building cAdvisor

**Note**: cAdvisor only builds on Linux since it uses Linux-only APIs.

## Installing Dependencies

cAdvisor is written in the [Go](http://golang.org) programming language. If you haven't set up a Go development environment, please follow [these instructions](http://golang.org/doc/code.html) to install go tool and set up GOPATH. Note that the version of Go in package repositories of some operating systems is outdated, so please [download](https://golang.org/dl/) the latest version.

**Note**: cAdvisor requires Go 1.6 to build.

After setting up Go, you should be able to `go get` cAdvisor as expected (we use `-d` to only download):

```
$ go get -d github.com/Brain-Gamer/cadvisor
```

## Building from Source

At this point you can build cAdvisor from the source folder:

```
$GOPATH/src/github.com/Brain-Gamer/cadvisor $ make build
```
