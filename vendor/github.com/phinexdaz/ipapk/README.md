# ipapk
ipa or apk parser written in golang, aims to extract app information

## INSTALL
	$ go get github.com/zylcold/ipapk
  
## USE
```go
package main

import (
	"fmt"
	"github.com/zylcold/ipapk"
)

func main() {
	apk, _ := ipapk.NewAppParser("test.apk")
	fmt.Println(apk)
}
```
