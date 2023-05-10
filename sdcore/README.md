# sdcore

## Description
sdcore

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] sdcore`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree sdcore`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init sdcore
kpt live apply sdcore --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
