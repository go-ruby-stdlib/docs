# go-ruby-stdlib docs

The documentation site for the [go-ruby-stdlib](https://github.com/go-ruby-stdlib)
ecosystem — one pure-Go, CGO-free import for the whole MRI-compatible Ruby
standard library. Served at <https://go-ruby-stdlib.github.io/docs/> and built
with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/), versioned
with [mike](https://github.com/jimporter/mike).

The [Modules](https://go-ruby-stdlib.github.io/docs/modules/) page indexes every
module in the ecosystem, each linking to its repo, landing page, and docs.

`.github/workflows/docs.yml` publishes the versioned docs to the `gh-pages`
branch on every push to `main`; GitHub Pages serves that branch at
`/docs/`.

## Local preview

```bash
pip install -r requirements.txt
mkdocs serve      # http://127.0.0.1:8000
```
