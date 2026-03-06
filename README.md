# metaflow-k8s-ci-poc
Proof of concept: GitHub Actions CI for  Metaflow Kubernetes + Argo integration testing (GSoC 2026)
# Metaflow K8s CI — Proof of Concept
### GSoC 2026 | Abhiram | github.com/abhiram123467

Proof of concept for the GSoC 2026 project:
**"GitHub Actions CI Workflow for Kubernetes + Argo Testing"**

## What This Does
Provisions a complete Metaflow-compatible Kubernetes 
stack on GitHub Actions:
- ✅ Kind cluster (Kubernetes IN Docker)
- ✅ Argo Workflows deployed
- ✅ MinIO S3-compatible datastore
- ✅ Metaflow smoke test passing
- ✅ Matrix builds: Python 3.9 / 3.10 / 3.11

## Status
![CI](../../actions/workflows/k8s-integration.yml/badge.svg)

## Part of GSoC 2026 Proposal
Full proposal submitted to help@metaflow.org
```

---

## Step 4 — Post in Metaflow #gsoc Slack

The moment the repo is created, post this:
```
Progress update 🚀

I've started building a proof-of-concept for 
the Kubernetes + Argo CI project:

github.com/abhiram123467/metaflow-k8s-ci-poc

It provisions Kind + Argo + MinIO on GitHub 
Actions with matrix builds across Python 
3.9/3.10/3.11.

Would love mentor feedback on the approach —
specifically: Kind vs k3d for the cluster setup?

GitHub: github.com/abhiram123467
