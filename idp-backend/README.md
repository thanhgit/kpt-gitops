# idp-backend

## Description
Backend for IDP

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] idp-backend`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree idp-backend`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init idp-backend
kpt live apply idp-backend --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
