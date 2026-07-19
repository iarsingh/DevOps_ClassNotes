# Kubernetes Troubleshooting

`kubectl`-based troubleshooting notes for diagnosing cluster, control-plane, node, and
networking issues.

## Contents

- `cluster-info.md` — Checking overall cluster health (`get componentstatus`, `cluster-info`)
  and dumping full cluster state for debugging (`cluster-info dump`).
- `control-plane-issues.md` — Diagnosing problems with the API server, scheduler, controller
  manager, and etcd.
- `node-issue.md` — Diagnosing node-level problems (NotReady nodes, kubelet issues, resource
  pressure).
- `networking-issue.md` — Diagnosing pod/service networking and connectivity issues.
