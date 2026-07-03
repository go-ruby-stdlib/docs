# Contributing

Every module in the go-ruby-stdlib family meets one uniform standard.

## Shared conventions

- **Pure Go, `CGO_ENABLED=0`.** No cgo, no vendoring — build from source.
- **MRI byte-exact.** Behaviour is pinned by a differential oracle against the
  system `ruby` binary, compared byte-for-byte (gated on a Ruby being present;
  cross-arch lanes still build and test the library).
- **100% coverage**, enforced as a CI gate, including error branches.
- **6 arches × 3 OSes.** Green across the six 64-bit Go targets (amd64, arm64,
  riscv64, loong64, ppc64le, s390x) and Linux/macOS/Windows.
- **`gofmt` + `go vet` clean**, `go.mod` floor `go 1.26.4`.
- **BSD-3-Clause**, copyright "the go-ruby-&lt;org&gt;/&lt;repo&gt; authors".
- Public GitHub content (issues, PRs, commits) in **English**.

## Repository layout per module

Each module `<name>` ships as its own org with:

| Repo | What it is |
| --- | --- |
| `github.com/go-ruby-<name>/<name>` | the library |
| `github.com/go-ruby-<name>/docs` | MkDocs Material docs (versioned with mike) |
| `github.com/go-ruby-<name>/go-ruby-<name>.github.io` | the Hugo landing page |
| `github.com/go-ruby-<name>/brand` | logo and brand assets |

The aggregate [`stdlib`](https://github.com/go-ruby-stdlib/stdlib) module
re-exports the whole tower behind one import.
