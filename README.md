# go-wol-lib

```bash
$ go get -u github.com/johnnylin-a/go-wol-lib
```

```go
package main

import "github.com/johnnylin-a/go-wol-lib/pkg/wol"

func main() {
    err := wol.Wake("YOUR_MAC_ADDR", "192.168.1.255")
    if err != nil {
        panic(err)
    }
}
```