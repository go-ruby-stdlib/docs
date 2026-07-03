# Why pure Go

The go-ruby-stdlib family reimplements the Ruby standard library in **pure Go,
with cgo disabled**. The slice of Ruby each module covers is **deterministic and
interpreter-independent**: given its inputs, the result is a pure function of
those inputs — no live binding, no evaluation of arbitrary Ruby. That is exactly
the part that can — and should — live as a standalone Go library, separate from
the interpreter.

## Extracted from rbgo, reusable by anyone

These libraries began life inside
[go-embedded-ruby](https://github.com/go-embedded-ruby/ruby)'s `rbgo` — in the
prelude/internals that back the Ruby surface. They have been **extracted into
reusable standalone libraries** so that:

- any Go program can import a module directly (e.g.
  `github.com/go-ruby-set/set`), with no Ruby runtime;
- the dependency runs the *other* way — `rbgo` binds each module as a native
  module, rather than the module depending on the interpreter;
- behaviour is pinned by a **differential oracle** against the system `ruby`,
  independent of any one consumer.

## Why pure Go matters here

Because every module is CGO-free, it:

- cross-compiles to every Go target with no C toolchain, and links into a single
  static binary;
- has **no dependency on the Ruby runtime** — the dependency runs the other way;
- can be differentially tested against the `ruby` binary wherever one is on
  `PATH`, while the cross-arch lanes (where `ruby` is absent) still validate the
  library itself.

See [Modules](modules.md) for the full ecosystem index.
