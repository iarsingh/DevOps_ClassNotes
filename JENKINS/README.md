# Jenkins

Jenkins CI/CD notes: pipeline authoring, parameters, agents/slaves, shared libraries, and
integration with build tools and other DevOps systems.

## Contents

- `inclassCommands` — Captured terminal history from setting up Java/Maven and configuring
  Jenkins during class.
- `MVNJENKINS_NOTES.txt`, `MSBuildJenkins.docx` — Integrating Maven and MSBuild builds with Jenkins.
- `Integrating Django with Jenkins` — Building/deploying a Django app through a Jenkins pipeline.
- `ParametersPipeline`, `PARAMETERS_PIPELINE`, `parameters2`, `ENV_varablesPipeline` — Parameterized
  pipeline examples and using environment variables in pipelines.
- `Pipelinecode_SLAVES`, `LINUXSLAVE` — Configuring Linux build slaves/agents for Jenkins.
- `Sharedlibrary_jenkins.txt` — Writing and using Jenkins shared libraries.
- `Triggers_PIPELINE` — Configuring pipeline triggers (e.g. SCM polling, webhooks).
- `SKIPStagePipeline`, `StageFailure`, `JobApprovalScript.txt` — Handling stage skipping, stage
  failure, and manual approval gates in a pipeline.
- `QA&PRODSERVERpipeline`, `ECOMMDeploy.txt` — Example deployment pipelines targeting QA/Prod
  and an e-commerce app deployment.
- `Profile` — Jenkins-related shell/environment profile notes.
- `index.html` — Sample app artifact used in a deployment pipeline demo.
