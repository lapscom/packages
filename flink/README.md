# flink

## Description
A very simple flink deployment.

## Usage

### Fetch the package
`kpt pkg get https://github.com/lapscom/packages/flink@v0.1`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree flink`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init flink
kpt live apply flink --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
