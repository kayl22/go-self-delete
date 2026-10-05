# go-self-delete
Go implementation of the self-deletion of an running executable from disk.

> **DISCLAIMER.** All information contained in this repository is provided for educational and research purposes only. The owner is not responsible for any illegal use of included code snippets.

## Usage

```go
package main

import "github.com/kayl22/go-self-delete"

func main() {
	// some code ...

	if err := selfdelete.SelfDeleteExe(); err != nil{
		<ERR-HANDLING>
	}

	// some code ...
}

```

## IMPORTANT!!

If you decide to use this fork on your project, please pull `github.com/kayl22/go-self-delete@main` (specifying the main branch), or else, the go toolchain will return an error. Ex:

```bash
# From project's root dir
go get github.com/kayl22/go-self-delete@main
```

## References

- **(ORIGINAL REPO)** https://github.com/secur30nly/go-self-delete
- https://github.com/LloydLabs/delete-self-poc
- https://twitter.com/jonasLyk/status/1350401461985955840
