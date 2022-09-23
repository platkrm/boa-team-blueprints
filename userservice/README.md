# userservice

## Description
UserService microservice configuration package.

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] userservice`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree userservice`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init userservice
kpt live apply userservice --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
