# go-ruby-stdlib documentation

**One pure-Go, CGO-free import for the whole MRI-compatible Ruby standard library.**

`go-ruby-stdlib` is the umbrella for a family of pure-Go (zero cgo)
reimplementations of the Ruby **standard library**. Each module is faithful to
reference Ruby (MRI) — validated by a **differential oracle** against the
`ruby` binary — and lives in its own org following one uniform convention.

Import the aggregate module
[`github.com/go-ruby-stdlib/stdlib`](https://github.com/go-ruby-stdlib/stdlib)
to pull the whole tower with a single import, or depend on any individual
module directly. The dependency runs the other way from the interpreter: these
libraries have **no dependency on the Ruby runtime** — each is the backend
bound by `rbgo` into
[go-embedded-ruby](https://github.com/go-embedded-ruby/ruby).

!!! success "Status: 43 modules, MRI byte-exact"
    Every module is a faithful pure-Go port, `CGO_ENABLED=0`, validated
    byte-for-byte against the system `ruby`, at 100% coverage, `gofmt` + `go vet`
    clean, CI green across the six 64-bit Go targets and three OSes.

## Install the whole standard library

```go
import _ "github.com/go-ruby-stdlib/stdlib"
```

Or pull a single module, e.g. `Set`:

```go
import "github.com/go-ruby-set/set"
```

## The ecosystem at a glance

- **[Modules](modules.md)** — every module in the ecosystem, grouped by wave,
  each with its Ruby module, one-line description, and links to its repo,
  landing page, and docs.
- **[Why pure Go](why.md)** — why this slice of Ruby lives as standalone,
  interpreter-independent Go libraries.
- **[Contributing](contributing.md)** — conventions shared across the family.

## Uniform link convention

Every module in the family resolves to three URLs derived from its `<name>`:

| Kind | URL |
| --- | --- |
| repo | `https://github.com/go-ruby-<name>/<name>` |
| landing | `https://go-ruby-<name>.github.io/` |
| docs | `https://go-ruby-<name>.github.io/docs/` |

## Principles

- **Pure Go, `CGO_ENABLED=0`** — trivial cross-compilation, a single static
  binary, no C toolchain.
- **MRI byte-exact.** Output matches reference Ruby exactly, not approximately,
  validated by a differential oracle against the `ruby` binary.
- **Standalone & reusable.** Each module is extracted from rbgo's internals; no
  dependency on the Ruby runtime — the dependency runs the other way.
- **100% test coverage** is the target, enforced as a CI gate, across 6 arches
  and 3 OSes.

The portal landing page lives at
[go-ruby-stdlib.github.io](https://go-ruby-stdlib.github.io); source at
[github.com/go-ruby-stdlib](https://github.com/go-ruby-stdlib).
