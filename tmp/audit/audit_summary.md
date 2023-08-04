# Audit summary

Summary for [Jenkins instance](http://65.0.27.151:8080/)

- GitHub Actions Importer version: **1.3.20468 (1f080780089ca3762c0a903b2e1f3d74f455d0fe)**
- Performed at: **8/4/23 at 10:48**

## Pipelines

Total: **1**

- Successful: **0 (0%)**
- Partially successful: **1 (100%)**
- Unsupported: **0 (0%)**
- Failed: **0 (0%)**

### Job types

Supported: **1 (100%)**

- project: **1**

### Build steps

Total: **4**

Known: **4 (100%)**

- hudson.tasks.Maven: **2**
- hudson.plugins.sonar.SonarRunnerBuilder: **1**
- hudson.tasks.Shell: **1**

Actions: **6**

- run: **3**
- sonarsource/sonarcloud-github-action@v1.9: **1**
- actions/checkout@v3.5.0: **1**
- actions/setup-java@v3.12.0: **1**

### Triggers

Total: **0**

Actions: **1**

- workflow_dispatch: **1**

### Environment

Total: **3**

Known: **1 (33%)**

- hudson.plugins.ws__cleanup.PreBuildCleanup: **1**

Unknown: **1 (33%)**

- hudson.plugins.sonar.SonarBuildWrapper: **1**

Unsupported: **1 (33%)**

- hudson.plugins.timestamper.TimestamperBuildWrapper: **1**

### Other

Total: **0**

### Manual tasks

Total: **3**

Secrets: **2**

- `${{ secrets.SONAR_TOKEN }}`: **1**
- `${{ secrets.SONAR_URL }}`: **1**

Self hosted runners: **1**

- `slave`: **1**

### Partially successful

#### freestyle-job

- [freestyle-job/.github/workflows/freestyle-job.yml](freestyle-job/.github/workflows/freestyle-job.yml)
- [freestyle-job/config.json](freestyle-job/config.json)
