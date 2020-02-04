# jenkins-docker-agent

This repository contains Java 11 based Jenkins docker agent for Openshift 3.x with [
Haskell Dockerfile Linter](https://github.com/hadolint/hadolint)

Sample check Dockerfiles in Jenkins pipelines:
```bash
sh "hadolint Dockerfile"
```
