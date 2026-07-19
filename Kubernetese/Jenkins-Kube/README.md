# Jenkins + Kubernetes

Notes and Ansible playbooks for standing up a Kubernetes cluster on AWS and driving
deployments to it from Jenkins.

## Contents

- `Kubernetes_setup.md` — Setting up a K8s cluster on AWS EC2: creating Ubuntu instances,
  installing the AWS CLI, and installing `kubectl`.
- `deployPlaybook.yml` — Ansible playbook that runs `kubectl apply` on a deployment manifest
  (`deploy1.yml`) against the `kube` host group.
- `ServicePlaybook.yml` — Ansible playbook that runs `kubectl apply` on a service manifest
  (`service1.yml`) against the `kube` host group.
