# flink

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] flink`
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
