# Go release infrastructure

## Release and installer tools

- golang.org/dl:
    [Google Source](https://go.googlesource.com/dl/),
    [GitHub](https://github.com/golang/dl),
    [GoDoc](https://godoc.org/golang.org/dl)
- golang.org/x/website/internal/dl:
    [GitHub](https://github.com/golang/website/tree/master/internal/dl),
    [GoDoc](https://godoc.org/golang.org/x/website/internal/dl)
- golang.org/x/tools/cmd/getgo:
    [GitHub](https://github.com/golang/tools/tree/master/cmd/getgo),
    [GoDoc](https://godoc.org/golang.org/x/tools/cmd/getgo)
- golang.org/x/build/cmd/release:
    [Google Source](https://go.googlesource.com/build/+/refs/heads/master/cmd/release/),
    [GitHub](https://github.com/golang/build/tree/master/cmd/release),
    [GoDoc](https://godoc.org/golang.org/x/build/cmd/release)
- dlgo.go by bradfitz:
    [GitHub Gist](https://gist.github.com/bradfitz/5c17a11e1f631e81073c)

## Partial build listings

- https://golang.org/dl/?mode=json&include=all
- https://storage.googleapis.com/go-builder-data/dl-index.txt
- https://storage.googleapis.com/golang/

## Changes

- Aug 2017: From go1.9rc2 forward, all tar.gz files are GPG signed with
  asc signature files (msi and pkg installers continue to be signed).
  See [issue 14739](https://github.com/golang/go/issues/14739).
- Jan 2016: Switched from SHA-1 to SHA-256 checksums.
  See [issue 12057](https://github.com/golang/go/issues/12057).
