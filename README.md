# GORM CGO-Free Sqlite Driver

![CI](https://github.com/go-gorm/sqlite/workflows/CI/badge.svg)

## USAGE

```go
import (
  sqlite "github.com/genc-murat/gorm-sqlite-cgo-free"
  "gorm.io/gorm"
   _ "modernc.org/sqlite"
)

// github.com/mattn/go-sqlite3
db, err := gorm.Open(sqlite.Open("gorm.db"), &gorm.Config{})
```

Checkout [https://gorm.io](https://gorm.io) for details.
