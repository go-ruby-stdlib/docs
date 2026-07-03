# Modules

Every module in the pure-Go Ruby standard library, grouped by delivery wave.
Each links to its **repo**, **landing** page, and **docs** — the three uniform
URLs derived from the module `name`.

### Waves 1–2 — core

| Module | Ruby | Description | Links |
| --- | --- | --- | --- |
| **`regexp`** | `Regexp` | Onigmo-compatible regular-expression engine | [repo](https://github.com/go-ruby-regexp/regexp) · [landing](https://go-ruby-regexp.github.io/) · [docs](https://go-ruby-regexp.github.io/docs/) |
| **`erb`** | `ERB` | ERB embedded-Ruby templating | [repo](https://github.com/go-ruby-erb/erb) · [landing](https://go-ruby-erb.github.io/) · [docs](https://go-ruby-erb.github.io/docs/) |
| **`yaml`** | `YAML/Psych` | YAML emitter and loader (Psych) | [repo](https://github.com/go-ruby-yaml/yaml) · [landing](https://go-ruby-yaml.github.io/) · [docs](https://go-ruby-yaml.github.io/docs/) |
| **`format`** | `format/sprintf` | sprintf / format / String#% formatting | [repo](https://github.com/go-ruby-format/format) · [landing](https://go-ruby-format.github.io/) · [docs](https://go-ruby-format.github.io/docs/) |
| **`strscan`** | `StringScanner` | StringScanner lexical scanning | [repo](https://github.com/go-ruby-strscan/strscan) · [landing](https://go-ruby-strscan.github.io/) · [docs](https://go-ruby-strscan.github.io/docs/) |
| **`optparse`** | `OptionParser` | OptionParser command-line option parsing | [repo](https://github.com/go-ruby-optparse/optparse) · [landing](https://go-ruby-optparse.github.io/) · [docs](https://go-ruby-optparse.github.io/docs/) |
| **`json`** | `JSON` | JSON generation and parsing | [repo](https://github.com/go-ruby-json/json) · [landing](https://go-ruby-json.github.io/) · [docs](https://go-ruby-json.github.io/docs/) |
| **`bigdecimal`** | `BigDecimal` | arbitrary-precision decimal arithmetic | [repo](https://github.com/go-ruby-bigdecimal/bigdecimal) · [landing](https://go-ruby-bigdecimal.github.io/) · [docs](https://go-ruby-bigdecimal.github.io/docs/) |
| **`date`** | `Date/DateTime` | Date and DateTime | [repo](https://github.com/go-ruby-date/date) · [landing](https://go-ruby-date.github.io/) · [docs](https://go-ruby-date.github.io/docs/) |
| **`uri`** | `URI` | URI parsing and manipulation | [repo](https://github.com/go-ruby-uri/uri) · [landing](https://go-ruby-uri.github.io/) · [docs](https://go-ruby-uri.github.io/docs/) |
| **`csv`** | `CSV` | CSV reading and writing | [repo](https://github.com/go-ruby-csv/csv) · [landing](https://go-ruby-csv.github.io/) · [docs](https://go-ruby-csv.github.io/docs/) |
| **`shellwords`** | `Shellwords` | POSIX shell-style word splitting and escaping | [repo](https://github.com/go-ruby-shellwords/shellwords) · [landing](https://go-ruby-shellwords.github.io/) · [docs](https://go-ruby-shellwords.github.io/docs/) |
| **`digest`** | `Digest` | message digests (MD5/SHA1/SHA2/…) | [repo](https://github.com/go-ruby-digest/digest) · [landing](https://go-ruby-digest.github.io/) · [docs](https://go-ruby-digest.github.io/docs/) |
| **`marshal`** | `Marshal` | Marshal binary object serialization | [repo](https://github.com/go-ruby-marshal/marshal) · [landing](https://go-ruby-marshal.github.io/) · [docs](https://go-ruby-marshal.github.io/docs/) |

### Wave 3 — collections, numerics, text & net

| Module | Ruby | Description | Links |
| --- | --- | --- | --- |
| **`set`** | `Set` | unordered unique collection with full set algebra | [repo](https://github.com/go-ruby-set/set) · [landing](https://go-ruby-set.github.io/) · [docs](https://go-ruby-set.github.io/docs/) |
| **`time`** | `Time` | Time extensions (parse/strptime/RFC formats) | [repo](https://github.com/go-ruby-time/time) · [landing](https://go-ruby-time.github.io/) · [docs](https://go-ruby-time.github.io/docs/) |
| **`getoptlong`** | `GetoptLong` | GNU-style command-line option parsing | [repo](https://github.com/go-ruby-getoptlong/getoptlong) · [landing](https://go-ruby-getoptlong.github.io/) · [docs](https://go-ruby-getoptlong.github.io/docs/) |
| **`scanf`** | `scanf` | formatted input scanning | [repo](https://github.com/go-ruby-scanf/scanf) · [landing](https://go-ruby-scanf.github.io/) · [docs](https://go-ruby-scanf.github.io/docs/) |
| **`stringio`** | `StringIO` | in-memory string-backed IO | [repo](https://github.com/go-ruby-stringio/stringio) · [landing](https://go-ruby-stringio.github.io/) · [docs](https://go-ruby-stringio.github.io/docs/) |
| **`abbrev`** | `Abbrev` | unambiguous abbreviation calculation | [repo](https://github.com/go-ruby-abbrev/abbrev) · [landing](https://go-ruby-abbrev.github.io/) · [docs](https://go-ruby-abbrev.github.io/docs/) |
| **`tsort`** | `TSort` | topological sorting | [repo](https://github.com/go-ruby-tsort/tsort) · [landing](https://go-ruby-tsort.github.io/) · [docs](https://go-ruby-tsort.github.io/docs/) |
| **`prime`** | `Prime` | prime generation and Baillie-PSW primality | [repo](https://github.com/go-ruby-prime/prime) · [landing](https://go-ruby-prime.github.io/) · [docs](https://go-ruby-prime.github.io/docs/) |
| **`cgi`** | `CGI` | CGI escaping, cookies, and helpers | [repo](https://github.com/go-ruby-cgi/cgi) · [landing](https://go-ruby-cgi.github.io/) · [docs](https://go-ruby-cgi.github.io/docs/) |
| **`zlib`** | `Zlib` | deflate/inflate/gzip plus CRC32/Adler32 | [repo](https://github.com/go-ruby-zlib/zlib) · [landing](https://go-ruby-zlib.github.io/) · [docs](https://go-ruby-zlib.github.io/docs/) |
| **`did-you-mean`** | `DidYouMean` | spelling suggestions for names | [repo](https://github.com/go-ruby-did-you-mean/did-you-mean) · [landing](https://go-ruby-did-you-mean.github.io/) · [docs](https://go-ruby-did-you-mean.github.io/docs/) |
| **`ipaddr`** | `IPAddr` | IPv4/IPv6 address manipulation | [repo](https://github.com/go-ruby-ipaddr/ipaddr) · [landing](https://go-ruby-ipaddr.github.io/) · [docs](https://go-ruby-ipaddr.github.io/docs/) |
| **`pathname`** | `Pathname` | filesystem-path objects | [repo](https://github.com/go-ruby-pathname/pathname) · [landing](https://go-ruby-pathname.github.io/) · [docs](https://go-ruby-pathname.github.io/docs/) |
| **`rational`** | `Rational` | exact rational numbers | [repo](https://github.com/go-ruby-rational/rational) · [landing](https://go-ruby-rational.github.io/) · [docs](https://go-ruby-rational.github.io/docs/) |
| **`prettyprint`** | `PrettyPrint` | Wadler pretty-printing engine | [repo](https://github.com/go-ruby-prettyprint/prettyprint) · [landing](https://go-ruby-prettyprint.github.io/) · [docs](https://go-ruby-prettyprint.github.io/docs/) |
| **`unicode-normalize`** | `unicode_normalize` | Unicode normalization (NFC/NFD/NFKC/NFKD) | [repo](https://github.com/go-ruby-unicode-normalize/unicode-normalize) · [landing](https://go-ruby-unicode-normalize.github.io/) · [docs](https://go-ruby-unicode-normalize.github.io/docs/) |
| **`cmath`** | `CMath` | complex-valued math functions | [repo](https://github.com/go-ruby-cmath/cmath) · [landing](https://go-ruby-cmath.github.io/) · [docs](https://go-ruby-cmath.github.io/docs/) |
| **`matrix`** | `Matrix` | Matrix and Vector linear algebra | [repo](https://github.com/go-ruby-matrix/matrix) · [landing](https://go-ruby-matrix.github.io/) · [docs](https://go-ruby-matrix.github.io/docs/) |
| **`complex`** | `Complex` | complex numbers | [repo](https://github.com/go-ruby-complex/complex) · [landing](https://go-ruby-complex.github.io/) · [docs](https://go-ruby-complex.github.io/docs/) |
| **`resolv`** | `Resolv` | DNS resolution primitives | [repo](https://github.com/go-ruby-resolv/resolv) · [landing](https://go-ruby-resolv.github.io/) · [docs](https://go-ruby-resolv.github.io/docs/) |
| **`rexml`** | `REXML` | XML DOM, parsing, serialization, XPath subset | [repo](https://github.com/go-ruby-rexml/rexml) · [landing](https://go-ruby-rexml.github.io/) · [docs](https://go-ruby-rexml.github.io/docs/) |

### Wave 4 — utilities

| Module | Ruby | Description | Links |
| --- | --- | --- | --- |
| **`logger`** | `Logger` | leveled logging | [repo](https://github.com/go-ruby-logger/logger) · [landing](https://go-ruby-logger.github.io/) · [docs](https://go-ruby-logger.github.io/docs/) |
| **`base64`** | `Base64` | Base64 encode/decode (SIMD-accelerated) | [repo](https://github.com/go-ruby-base64/base64) · [landing](https://go-ruby-base64.github.io/) · [docs](https://go-ruby-base64.github.io/docs/) |
| **`securerandom`** | `SecureRandom` | cryptographically-secure random values | [repo](https://github.com/go-ruby-securerandom/securerandom) · [landing](https://go-ruby-securerandom.github.io/) · [docs](https://go-ruby-securerandom.github.io/docs/) |
| **`ostruct`** | `OpenStruct` | dynamic attribute objects | [repo](https://github.com/go-ruby-ostruct/ostruct) · [landing](https://go-ruby-ostruct.github.io/) · [docs](https://go-ruby-ostruct.github.io/docs/) |
| **`benchmark`** | `Benchmark` | timing measurement | [repo](https://github.com/go-ruby-benchmark/benchmark) · [landing](https://go-ruby-benchmark.github.io/) · [docs](https://go-ruby-benchmark.github.io/docs/) |
| **`pstore`** | `PStore` | transactional file-backed object store | [repo](https://github.com/go-ruby-pstore/pstore) · [landing](https://go-ruby-pstore.github.io/) · [docs](https://go-ruby-pstore.github.io/docs/) |
| **`observer`** | `Observable` | publish/subscribe mixin | [repo](https://github.com/go-ruby-observer/observer) · [landing](https://go-ruby-observer.github.io/) · [docs](https://go-ruby-observer.github.io/docs/) |
| **`find`** | `Find` | recursive directory traversal | [repo](https://github.com/go-ruby-find/find) · [landing](https://go-ruby-find.github.io/) · [docs](https://go-ruby-find.github.io/docs/) |

