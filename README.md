<!-- README.md -->
# **Go Language Programming**

[Link Go Lang Official  doc.](https://golang.org/doc/)

The Go programming language is an open source project to make programmers more productive.

Go is a statically typed, compiled programming language designed at Google by Robert Griesemer, Rob Pike, and Ken Thompson.

Go is syntactically similar to C, but with memory safety, garbage collection, structural typing and CSP-style concurrency.

The language is often referred to as Golang because of its domain name, golang.org, but the proper name is Go.

<br/>
<br/>

## Environment Configuration, Download Go
Download Go from official doc for Linux, Mac or Windows: https://golang.org/doc/install
<br/>
<br/>

## Go IDE
You can use ***Visual Studio Code*** installing the https://marketplace.visualstudio.com/items?itemName=golang.go extension developed by the Go Google team.
Then I suggest to download the Delve debugger (https://github.com/go-delve ) for Linux and Mac.


Even if in Mac OSX 10.13.6 (High Sierra), I was not able make Delve working, even if I followed the offical Delve docs for Mac (https://github.com/go-delve/delve/blob/master/Documentation/installation/README.md):


$ git clone https://github.com/go-delve/delve
$ cd delve
$ go install github.com/go-delve/delve/cmd/dlv

<br/>

I thought i installed ***Delve*** on my mac but i was wrong, you can test it running the following command in the Go project folder via terminal:

$ dlv debug
<br/>

For Windows 10 I found the following error when tried to install it:

- _found packages native (proc.go) and your_operating_system_and_architecture_combination_is_not_supported_by_delve (support_sentinel.go) in /home/pi/go/src/github.com/go-delve/delve/pkg/proc/native_

<br/>
<br/>

### GoLand - JetBrains
For me this is the best Go IDE on the market, tried the free-trial version on Windows 10 and it's amazing with a powerful debugger.
https://www.jetbrains.com/go/

<br/>
<br/>


## Packages

Every **Go** program is made up of _packages_.

Programs start running in package main.

This program is using the packages with import paths *"fmt"* and *"math/rand"*.

By convention, the package name is the same as the last element of the import path. For instance, the "math/rand" package comprises files that begin with the statement package rand.

Try the [Packages](https://tour.golang.org/basics/1) exercise on the _"A Tour of Go"_ official tutorial.
