# DevOps Class Notes

<!-- repository-summary -->
DevOps notes, interview material, scripts, and labs covering Linux, Git, Jenkins, Docker, Ansible, Kubernetes, and monitoring.
<!-- /repository-summary -->

A personal collection of class notes, cheat-sheets, playbooks, pipeline scripts, and lab
walkthroughs collected while learning core DevOps tooling: source control, CI/CD,
configuration management, containers, orchestration, and monitoring. Most content is raw
notes taken during instructor-led sessions plus hands-on files (playbooks, Jenkinsfiles,
Dockerfiles, Kubernetes manifests) produced during labs.

## Modules

| Folder | Covers |
|---|---|
| [`OverviewDevops/`](OverviewDevops) | What DevOps is and why, SDLC phases, Agile/Waterfall comparisons, and a tour of the common DevOps toolchain. |
| [`GIT/`](GIT) | Git and GitHub/BitBucket fundamentals: version control concepts, branching strategies, remote pushes, SSH auth, and real-time branching scenarios. |
| [`LinuxFundamentals/`](LinuxFundamentals) | Core Linux commands and shell basics needed before touching any DevOps tooling. |
| [`Ansible/`](Ansible) | Ansible setup, ad-hoc/playbook examples (address book app, file management, networking), Ansible Vault, and Ansible Tower notes. |
| [`Puppet/`](Puppet) | Puppet master/agent setup on AWS and configuration-management basics. |
| [`Docker/`](Docker) | Docker installation and commands, Dockerfiles, Docker Compose (incl. a WordPress stack), Docker Swarm, container networking, volume backups, and using containers as Jenkins slaves. |
| [`JENKINS/`](JENKINS) | Jenkins pipeline notes: parameterized/parallel/shared-library pipelines, Maven/MSBuild integration, Linux slave setup, approval gates, triggers, and stage-skip/failure handling. |
| [`CICD pipeline/`](CICD%20pipeline) | End-to-end CI/CD pipeline exercises tying Jenkins, Ansible, Docker, and Kubernetes together (Jenkinsfile, Ansible playbooks/hosts, Kubernetes deployment). |
| [`Kubernetese/`](Kubernetese) | Kubernetes cluster setup (kubeadm on Ubuntu/CentOS) plus deep-dive subfolders on Helm, Ingress, HPA, StatefulSets, DaemonSets, ConfigMaps, PersistentVolumes, logging (EFK), monitoring, deployment strategies (blue-green, canary), and troubleshooting. See its own [README](Kubernetese/Readme.md) and subfolder READMEs for details. |
| [`Nagios/`](Nagios) | Nagios and Nagios XI installation/monitoring notes. |
| [`CloudSetup/`](CloudSetup) | Account setup guides for AWS and GCP. |

## Other files at the repo root

Miscellaneous root-level items include interview-question docs (`DevOps-Interview-Questions.docx`,
`Docker-Interview-questions.docx`), a pre-assessment (`DevOps-Pre-Assesment-Quest.txt`), a Tomcat-on-EC2
walkthrough (`TomcatInstallation_EC2.md`), a pipeline-tools diagram (`DevOPSPipelineTools.png`), and a
few standalone lab notes (`MultipleLinuxServer`, `Simultaneous_Push`, `pomXML.txt`, `new.rtf`).

## Note on content

These are informal, in-progress class notes rather than polished documentation — expect shorthand,
copy-pasted terminal history, and lab-specific IPs/hostnames.
