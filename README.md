# Pipeline Lab Course

This repository contains a simple GitHub Actions pipeline used for learning and experimentation.

## Workflow

The workflow is defined in `.github/workflows/pipeline.yml` and currently runs:

- On pushes to `main`
- On pull requests targeting `main`
- Manually via `workflow_dispatch`

It prints environment information and basic runner details.
