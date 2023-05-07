# reusable_workflow
A reusable workflow for doing x, y, and z.

## Installation
Add a new workflow under `.github/workflows/` with the following contents.
```yml
name: New Reusable Workflow
run-name: New Reusable Workflow

on:
  push:

jobs:
  reusable_workflow:
    uses: Arthri/reusable_workflow/.github/workflows/reusable_workflow.yml@v1

```

## Usage
1. Do this.
1. Do that.
1. This happens.
