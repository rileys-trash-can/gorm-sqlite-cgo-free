# GORM CGO-Free Sqlite Driver

Fork of [github.com/genc-murat/gorm-sqlite-cgo-free][//github.com/genc-murat/gorm-sqlite-cgo-free]

## USAGE

```go
import (
  sqlite "github.com/genc-murat/gorm-sqlite-cgo-free"
  "gorm.io/gorm"
   _ "modernc.org/sqlite"
)

// "modernc.org/sqlite"
db, err := gorm.Open(sqlite.Open("gorm.db"), &gorm.Config{})
```

Checkout [https://gorm.io](https://gorm.io) for details.
