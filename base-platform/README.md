# base-platform

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] base-platform`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree base-platform`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init base-platform
kpt live apply base-platform --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
