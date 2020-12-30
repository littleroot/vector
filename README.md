# vector

Generic vector implementation in Go.

## Docs

https://pkg.go.dev/github.com/littleroot/vector

## Usage

Generics aren't currently supported in any released Go version. You will need
to use the `go2go` translation tool available in the `dev.go2go` branch in the
go repository.

https://go.googlesource.com/go/+/refs/heads/dev.go2go/README.go2go.md

With the `go2go` tool, you can build and test this package:

```
go tool go2go build
go tool go2go test
```
