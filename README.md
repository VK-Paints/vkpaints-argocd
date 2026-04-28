# VK-Paints ArgoCD Configuration

## Description
GitOps repository defining the application state for development and production clusters.

## Structure
- apps/dev/: Manifests for the development environment.
- apps/prod/: Manifests for the production environment.

## Workflow
Changes pushed to the main branch of this repo are automatically reconciled by ArgoCD.
