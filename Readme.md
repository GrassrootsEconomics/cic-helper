# cic-helper
![PyPI](https://img.shields.io/pypi/v/cic-helper?color=green&style=flat-square)
![Here Be Dragons](https://img.shields.io/badge/Here%20be%20Dragons-%F0%9F%90%89-success?style=flat-square&color=white)
```
pip install cic-helper
```

```
Usage: cic-helper [OPTIONS] COMMAND [ARGS]...

Options:
  --help  Show this message and exit.

Commands:
  get-addresses
  get-balances
  run
  send
  verify-amount
```
## Development
Requires
- [poetry](https://python-poetry.org/docs/#installation)


Setup
- `poetry install`
- `poetry run cic-helper -h`

## Contributing
- Please use [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) (i.e `fix: Barking fish`)
- These will then be used to generate a changelog and release a new version when pushed to `main`
