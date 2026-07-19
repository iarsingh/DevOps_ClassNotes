# DaemonSets

Notes and a manifest demonstrating Kubernetes DaemonSets, which ensure a copy of a Pod runs on
every (or every matching) Node in the cluster, including automatically on new nodes as they join.

## Contents

- `demonSet` — Explanation of what a DaemonSet is and why/when to use one.
- `DaemonSetDemo.yml` — Example DaemonSet manifest deploying an nginx-based pod (`type: webserver`)
  to every node via a label selector.
