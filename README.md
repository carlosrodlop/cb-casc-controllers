# cb-casc-controllers

[![gitleaks badge](https://img.shields.io/badge/protected%20by-gitleaks-blue)](https://github.com/zricethezav/gitleaks#pre-commit) [![gitsecrets](https://img.shields.io/badge/protected%20by-gitsecrets-blue)](https://github.com/awslabs/git-secrets)

Repository for [Configuration as Code (CasC) for Controllers](https://docs.cloudbees.com/docs/cloudbees-ci/latest/casc-controller/).

Plugins and plugin catalogs curated with [casc-plugin-dependency-calculation](https://github.com/kyounger/casc-plugin-dependency-calculation).

Replace `variables.yaml` with your own values and push to the repository.

Inheritance Merge strategies are explained [here](https://docs.cloudbees.com/docs/cloudbees-ci/latest/casc-controller/advanced#_configuring_bundle_inheritance_with_casc).

These bundles have been validated against `CBCI_VERSION` (`CBCI_VERSION_APP`) from CloudBees CI deployed [here](https://github.com/carlosrodlop/K8s-lib/blob/main/bash/make/cb-ci/Makefile).
