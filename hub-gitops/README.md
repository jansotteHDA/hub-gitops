# Hub GitOps Repository

This repository contains the GitOps configuration for the Hub platform.

Structure:
- clusters/: cluster-specific bootstrap configuration
- apps/: application definitions managed by ArgoCD

Local development is deployed on k3s via ArgoCD.
