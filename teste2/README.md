# teste2

## Description
teste2desc

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] teste2`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree teste2`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init teste2
kpt live apply teste2 --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
