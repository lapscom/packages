# timescaledb

## Description
A very simple timescaledb deployment.

There is a secret for the `POSTGRES_PASSWORD` environement variable: it's set to `postgres` and should be changed to something else before deployment.

## Usage

### Fetch the package
`kpt pkg https://github.com/lapscom/packages/timescaledb@v0.1`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree timescaledb`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init timescaledb
kpt live apply timescaledb --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
