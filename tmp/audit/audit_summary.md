# Audit summary

Summary for [Jenkins instance](http://65.0.27.151:8080/)

- GitHub Actions Importer version: **1.3.20468 (1f080780089ca3762c0a903b2e1f3d74f455d0fe)**
- Performed at: **8/4/23 at 13:09**

## Pipelines

Total: **2**

- Successful: **1 (50%)**
- Partially successful: **1 (50%)**
- Unsupported: **0 (0%)**
- Failed: **0 (0%)**

### Job types

Supported: **2 (100%)**

- flow-definition: **1**
- project: **1**

### Build steps

Total: **5**

Known: **5 (100%)**

- hudson.tasks.Maven: **2**
- hudson.plugins.sonar.SonarRunnerBuilder: **1**
- hudson.tasks.Shell: **1**
- echo: **1**

Actions: **8**

- run: **4**
- actions/checkout@v3.5.0: **2**
- actions/setup-java@v3.12.0: **1**
- sonarsource/sonarcloud-github-action@v1.9: **1**

### Triggers

Total: **1**

Known: **1 (100%)**

- hudson.triggers.SCMTrigger: **1**

Actions: **3**

- workflow_dispatch: **1**
- schedule: **1**
- push: **1**

### Environment

Total: **3**

Known: **1 (33%)**

- hudson.plugins.ws__cleanup.PreBuildCleanup: **1**

Unknown: **1 (33%)**

- hudson.plugins.sonar.SonarBuildWrapper: **1**

Unsupported: **1 (33%)**

- hudson.plugins.timestamper.TimestamperBuildWrapper: **1**

### Other

Total: **1**

Unsupported: **1 (100%)**

- timeout: **1**

### Manual tasks

Total: **3**

Secrets: **2**

- `${{ secrets.SONAR_TOKEN }}`: **1**
- `${{ secrets.SONAR_URL }}`: **1**

Self hosted runners: **1**

- `slave`: **1**

### Successful

#### declarative

- [declarative/.github/workflows/declarative.yml](declarative/.github/workflows/declarative.yml)
- [declarative/config.json](declarative/config.json)
- [declarative/jenkinsfile](declarative/jenkinsfile)

### Partially successful

#### freestyle-job

- [freestyle-job/.github/workflows/freestyle-job.yml](freestyle-job/.github/workflows/freestyle-job.yml)
- [freestyle-job/config.json](freestyle-job/config.json)
