# CI/CD Pipeline

An end-to-end CI/CD lab that ties together Jenkins, Ansible, Docker, and Kubernetes into a
single deployment pipeline.

## Contents

- `stepbystep process.txt` — Step-by-step walkthrough: configuring Jenkins' "Publish over SSH"
  plugin to connect Jenkins to an Ansible control node.
- `jenkinsfile`, `CICD.groovy` — Pipeline-as-code definitions driving the CI/CD flow.
- `AnsibleHosts.txt`, `NewHostsfile` — Ansible inventory files used by the pipeline.
- `DockerImageParameterPlaybook`, `dockerplaybook.yml`, `dockerfile.txt` — Ansible playbooks and
  a Dockerfile for building/deploying Docker images as part of the pipeline.
- `QAServerSWARM`, `QASWARMPARAMETERIZED` — Deploying to a QA Docker Swarm cluster, including a
  parameterized variant.
- `kubeplaybook.yml`, `kubedeployment.yml` — Ansible playbook and Kubernetes manifest for
  deploying the app to Kubernetes.
- `CICDpipeline_END.png` — Diagram of the final end-to-end pipeline.
