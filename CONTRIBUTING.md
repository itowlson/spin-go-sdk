## Generating the WIT bindings

Whenever WIT files are changed, added to, or removed from the `wit` directory, the bindings  in `internal` should be regenerated.

### Prerequisites

- BASH or compatible shell
- `componentize-go` from https://github.com/bytecodealliance/componentize-go

### Run
```sh
bash regenerate-bindings.sh
```

## Running `go mod tidy` on all modules

This will run `go mod tidy` on the root module and all the examples and tests:

```sh
bash tidy.sh
```
