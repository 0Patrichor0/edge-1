# hello

## Description


## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] hello`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree hello`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init hello
kpt live apply hello --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
