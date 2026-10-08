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
version = "^0.1"
```

Then bind the library in a source file:

```mach
use json;
```


## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for building, testing and the contribution rules.


## License

[MIT](LICENSE)
