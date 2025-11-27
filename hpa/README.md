# hpa

## Description
扩缩容

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] hpa`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree hpa`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init hpa
kpt live apply hpa --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
