[![GoDoc](https://godoc.org/github.com/Galaco/source-tools-common?status.svg)](https://godoc.org/github.com/Galaco/source-tools-common)
[![Go report card](https://goreportcard.com/badge/github.com/galaco/source-tools-common)](https://goreportcard.com/badge/github.com/galaco/source-tools-common)
[![Build Status](https://travis-ci.com/Galaco/source-tools-common.svg?branch=master)](https://travis-ci.com/Galaco/source-tools-common)

# Checksum
> Source engine CRC32 Signing

### Usage
```go

package main

import (
    "github.com/golang-source-engine/checksum"
    "log"
)

func main() {
    data := "foobar"

    crc := checksum.CRC32([]byte(data))
    log.Println(crc)
}
```