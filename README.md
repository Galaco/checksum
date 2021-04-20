[![GoDoc](https://godoc.org/github.com/Galaco/checksum?status.svg)](https://godoc.org/github.com/Galaco/checksum)
[![Go report card](https://goreportcard.com/badge/github.com/galaco/checksum)](https://goreportcard.com/badge/github.com/galaco/checksum)
[![Build Status](https://travis-ci.com/Galaco/checksum.svg?branch=master)](https://travis-ci.com/Galaco/checksum)

# Checksum
> Source engine CRC32 Signing

### Usage
```go

package main

import (
    "github.com/galaco/checksum"
    "log"
)

func main() {
    data := "foobar"

    crc := checksum.CRC32([]byte(data))
    log.Println(crc)
}
```
