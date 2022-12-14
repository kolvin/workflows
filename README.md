<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Contents

- [Workflows](#workflows)
- [Workflows](#workflows-1)
- [Todo](#todo)
- [Contributing](#contributing)
- [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Workflows

[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-%23FE5196?logo=conventionalcommits&logoColor=white)](https://conventionalcommits.org) 
[![Terraform](https://img.shields.io/static/v1?label=&message=Terraform&color=%237B42BC&logo=terraform)](https://www.terraform.io/use-cases/infrastructure-as-code)
[![Terragrunt](https://avatars.githubusercontent.com/u/17118990?s=20)](https://github.com/gruntwork-io/terragrunt) [![Semantic Release - angular](https://img.shields.io/static/v1?label=Semantic+Release&message=angular&color=e10079&logo=semantic-release)](https://github.com/semantic-release/semantic-release) [![terraform-docs](https://img.shields.io/static/v1?label=&message=terraform-docs&color=e10079&logo=Docs.rs)](https://github.com/terraform-docs/terraform-docs) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


A collection of reusable github CI/CD workflows. Used personally across my own repositories, DRY as fuck

# Workflows
- [terragrunt](./.github/workflows/terragrunt.yaml) workflow providing [lint](https://www.terraform.io/cli/commands/lint), [plan](https://www.terraform.io/cli/commands/plan), [apply](https://www.terraform.io/cli/commands/apply) via OIDC AWS Auth with PR comments on terragrunt validate + plan outputs
- [terraform module](./.github/workflows/terraform-module-lint.yaml) workflow providing [fmt](https://www.terraform.io/cli/commands/fmt)+[validate](https://www.terraform.io/cli/commands/validate)
- [terraform module documentation](./.github/workflows/terraform-docs.yaml) workflow
  - Requires GPG secret key + Passphrase as secrets 
- [Automated releases](./.github/workflows/automated-semver.yaml) via [semantic-release](https://github.com/semantic-release/semantic-release)
  - Requires GPG secret key + Passphrase as secrets 

---

# Todo
- [x] README.md
- [x] reusable terragrunt install
- [x] reusable terragrunt lint
- [x] reusable terragrunt plan
- [x] reusable terragrunt apply
- [x] reusable terraform module lint
- [x] automate terraform module docs
- [x] automate release management

---

# Contributing

Open a PR/Issue

---
# License

The MIT License (MIT) 2017 - [Calvin Taylor](https://github.com/kolvin). Please have a look at the [LICENSE.md](LICENSE.md) for more details.
