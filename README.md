# computer
go package


# Package structure
```go
var logMessage
var Version // Public
func internalSum(4)
func Sum(4, 5)  // Public
```

# How to use

go.mod
```go
require (
  github.com/ZeroMarker/computer v0.1.0
)
```

main.go
```go
package main

import (
	"github.com/ZeroMarker/computer";
	"fmt"
)

func main() {
	fmt.Println(computer.Sum(4, 5))
}
```

Build & Run

```shell
go mod download

go build
./hello
```
