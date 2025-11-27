# hpa-1

## Description
扩缩容

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] hpa-1`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree hpa-1`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init hpa-1
kpt live apply hpa-1 --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
