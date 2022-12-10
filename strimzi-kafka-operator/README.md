# strimzi-kafka-operator

## Description
ONAP-based SMO strimzi-kafka-operator

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] strimzi-kafka-operator`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree strimzi-kafka-operator`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init strimzi-kafka-operator
kpt live apply strimzi-kafka-operator --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
