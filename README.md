# ArgoCD applications

This repo contains the ArgoCD application specs using a public OCI helm chart
hosted at gcr.io/renovate-oci-demo/chart
(https://github.com/younqix/renovate-oci-demo-chart). It provides a
reproduction to add renovate support for ArgoCD OCI helm charts.

There should be two possible ways to configure the repository, the first
explicitly defining the repoURL with `oci://` prefix, the second implicitly
assuming that the repoURL points to an OCI chart.
