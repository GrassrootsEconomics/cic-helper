# cic_helper

```
Usage: cic_helper [OPTIONS] COMMAND [ARGS]...

Options:
  --help  Show this message and exit.

Commands:
  get-addresses
  send
  verify
```

## Send

```
Usage: cic_helper send [OPTIONS] FILENAME TOKEN_ADDRESS

Options:
  -v, --verbose  Verbosity Level (-v,-vv, -vvv)
  -f, --force    Send the requrested amount even if the users balance is
                 ~=send_amount
  --help         Show this message and exit.
```

## Get Addresses

```
Usage: cic_helper get-addresses [OPTIONS] FILENAME

Options:
  -v, --verbose  Verbosity Level (-v,-vv, -vvv)
  -f, --force    Updates the users address even if it is present
  --help         Show this message and exit.
```

## Verify

```
Usage: cic_helper verify [OPTIONS] FILENAME

Options:
  -v, --verbose  Verbosity Level (-v,-vv, -vvv)
  -u, --user     Check that all users have a valid address
  -t, --token    Check that all users have a valid token address
  -b, --balance  Check that all user balances are > send_amount - 1
  -a, --all      Check All
  --help         Show this message and exit.
```
