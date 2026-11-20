# mach-json

<p>
  <a href="https://github.com/briar-systems/mach-json/actions/workflows/ci.yml"><img src="https://github.com/briar-systems/mach-json/actions/workflows/ci.yml/badge.svg" alt="CI"></a>
  <a href="LICENSE"><img src="https://img.shields.io/github/license/briar-systems/mach-json?color=FF00FF&labelColor=000000" alt="License"></a>
</p>

**A Mach library for JSON (RFC 8259) reading and writing.**

## Usage

Add the dependency to `mach.toml`:

```toml
[dep.json]
git = "https://github.com/briar-systems/mach-json"
ref = "branch/dev"
```

Then import each module by its source path in the package:

```mach
use json.ndjson;
use json.parse;
use json.value;
use json.write;
```

`parse.parse` reads JSON text into a `value.Value` tree, released with `value.dnit`. `write.write_value` and the streaming functions such as `ndjson.object_begin` emit JSON through a `std.io.writer` Writer. The parse error is `json.error.JsonError`.


## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for building, testing and the contribution rules.


## License

[MIT](LICENSE)
