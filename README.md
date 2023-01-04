# GO PACKAGE POC

This is a proof of concept Go package. `Hello` function just returns a hello message given a name as a parameter.

## Installing

First, use `go install` to install the latest version of the library.

```
go install github.com/crazyoptimist/go_package_poc@latest
```

Next, include the package in your application:

```go
import "github.com/crazyoptimist/go_package_poc"
```

## Usage

Example application using this package:

```go
package main

import (
        "fmt"

        "github.com/crazyoptimist/go_package_poc"
)

func main() {
        message := go_package_poc.Hello("crazy")
        fmt.Println(message)
}
```
