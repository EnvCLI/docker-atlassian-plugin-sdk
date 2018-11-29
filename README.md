# Docker Container - Atlassian Plugin SDK

The atlassian plugin sdk is used to create extensions/plugins for atlassian products.

## Docker

```bash
docker run -it --rm envcli/atlassian-plugin-sdk:6.3.12 atlas-version
```

## EnvCLI

Define the following images in your `.envcli.yml` configuration:

```yaml
- name: atlassian-plugin-sdk
  description: Required to write plugins for atlassian products.
  provides:
  - atlas-clean
  - atlas-cli
  - atlas-clover
  - atlas-compile
  - atlas-debug
  - atlas-help
  - atlas-install-plugin
  - atlas-integration-test
  - atlas-mvn
  - atlas-package
  - atlas-release
  - atlas-release-rollback
  - atlas-remote-test
  - atlas-ruin
  - atlas-run
  - atlas-run-standalone
  - atlas-unit-test
  - atlas-update
  - atlas-version
  - atlas-create-plugin
  - atlas-create-refapp-plugin
  - atlas-create-refapp-plugin-module
  - atlas-create-stash-plugin
  - atlas-create-stash-plugin-module
  - atlas-create-bamboo-plugin
  - atlas-create-bamboo-plugin-module
  - atlas-create-bitbucket-plugin
  - atlas-create-bitbucket-plugin-module
  - atlas-create-confluence-plugin
  - atlas-create-confluence-plugin-module
  - atlas-create-crowd-plugin
  - atlas-create-crowd-plugin-module
  - atlas-create-fecru-plugin
  - atlas-create-fecru-plugin-module
  - atlas-create-home-zip
  - atlas-create-jira-plugin
  - atlas-create-jira-plugin-module
  - atlas-create-jira4-plugin
  - atlas-create-jira5-plugin
  image: envcli/atlassian-plugin-sdk:6.3.12
  shell: sh
```
