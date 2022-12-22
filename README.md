# workflows
Reusable workflows

## Lighthouse
### Usage
  
  ```yaml
name: Lighthouse

on:
  push:
    branches:
      - master

  pull_request:
    branches:
      - master

jobs:
  ci:
    uses: tortitast/workflows/.github/workflows/lighthouse.yml@master
  ```