# Nodes

Notes on Kubernetes Node objects and common `kubectl` commands for inspecting/labeling them.

## Contents

- `kube-node.md` — What a Node is (a worker machine, VM or physical), how the Node object
  relates to the underlying machine, and who creates it.
- `lab.md` — Hands-on `kubectl` commands: listing nodes (`get nodes`, `-o wide`), describing a
  node, filtering worker vs. master nodes by selector, showing labels, and labeling a node.
