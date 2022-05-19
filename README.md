# Workflows
This repository hosts reusable workflows intended to be consumed by other Charmed Kubernetes Github workflows. 

## Example of using a reusable workflow
```yaml
name: Example
on:
  - push

jobs:
    lint:
        uses: charmed-kubernetes/workflows/.github/workflows/lint-unit.yaml@main
```
