# Kubernetes Monitoring

Manifests for deploying a Prometheus-based monitoring stack into a Kubernetes cluster.

## Contents

- `prometheus.yaml` — Creates a dedicated `monitoring` namespace and a Prometheus server
  ConfigMap/deployment for scraping cluster metrics.
- `kube_state_metrics/standard/` — Standard manifests for `kube-state-metrics`
  (`service-account.yaml`, `cluster-role.yaml`, `cluster-role-binding.yaml`, `deployment.yaml`,
  `service.yaml`), which exposes Kubernetes object state (deployments, pods, nodes, etc.) as
  Prometheus metrics.
