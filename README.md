folder2go
===========

Embed a directory into a go package

Usage:
---
```
go get dev.hexasoftware.com/stdio/folder2go

folder2go /path generated
```

Using
```go
import (
	"mypkg/generated"
	"fmt"
)

func main() {
	fmt.Printf("%s",string(generated.Data["file.txt"]	))
}

```
