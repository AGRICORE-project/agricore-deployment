# Installation

```
helm repo add superset https://apache.github.io/superset
helm upgrade --install --values values.yaml superset superset/superset --namespace agricore --create-namespace
```