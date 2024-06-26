# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Fixed
- Helm remove remove syntax

## [0.1.25] - 2024-04-10
### Fixed
- Public helm chart workflow

## [0.1.24] - 2024-04-10
### Added
- Add public chart support

## [0.1.23] - 2024-04-10
### Fixed
- Helm install step no longer set to fail on stderr, as helm now writes there for non-errors

## [0.1.22] - 2024-04-10
### Fixed
- HelmChartVersion parameter definition for Azure DevOps pipeline

## [0.1.21] - 2024-04-10
### Fixed
- Azure DevOps Helm deploy now done inside Azure CLI context

## [0.1.20] - 2024-04-10
### Fixed
- Indentation on AzureKeyVault Azure Pipelines task

## [0.1.19] - 2024-04-10
### Fixed
- Manually specify service connections

## [0.1.18] - 2024-04-10
### Fixed
- Bad template format for part2 template

## [0.1.17] - 2024-04-10
### Fixed
- Add missing steps sequence in Azure DevOps deploy pipeline

## [0.1.16] - 2024-04-10
### Changed
- Update to split deploy template again, but better

## [0.1.15] - 2024-04-09
### Added
- Add installation of kubelogin when AKS is being used

### Changed
- Restructure Azure DevOps deployment pipeline to be single file

## [0.1.14] - 2024-04-09
### Changed
- Convert AKS auth to use format azure

## [0.1.13] - 2024-04-09
### Fixed
- Fix bad scriptType for AzureCLI task in azure-pipelines-deploy-template.yml

## [0.1.12] - 2024-04-09
### Fixed
- Bad logic around registry types

## [0.1.11] - 2024-04-09
### Fixed
- Close unclosed if in Azure DevOps deployment template

## [0.1.10] - 2024-04-09
### Added
- Support for deploying charts from OCI repositories

## [0.1.9] - 2024-04-07
### Fixed
- Removed special characters from acr_login_method question

## [0.1.8] - 2024-04-07
### Fixed
- Broken azdo pipeline slugification

## [0.1.7] - 2024-04-07
### Fixed
- Bad data for deploy pipeline

## [0.1.6] - 2024-04-07
### Fixed
- Bad variable naming for AKS clusters

## [0.1.5] - 2024-04-07
### Fixed
- Bad formatting for dict access in templates

## [0.1.4] - 2024-04-07
### Fixed
- Broken README jinja

## [0.1.3] - 2024-04-07
### Fixed
- Add slug extension to requirements.txt

## [0.1.2] - 2024-04-07
### Fixed
- Import slug extension in template/copier.yml

## [0.1.1] - 2024-04-07
## Changed
- Remove unneeded question

## [0.1.0] - 2024-04-06
### Added
- Initial release

[Unreleased]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/compare/v0.1.25..HEAD
[0.1.25]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/compare/v0.1.24..v0.1.25
[0.1.24]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/compare/v0.1.23..v0.1.24
[0.1.23]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/compare/v0.1.22..v0.1.23
[0.1.22]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/compare/v0.1.21..v0.1.22
[0.1.21]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/compare/v0.1.20..v0.1.21
[0.1.20]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/compare/v0.1.19..v0.1.20
[0.1.19]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/compare/v0.1.18..v0.1.19
[0.1.18]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/compare/v0.1.17..v0.1.18
[0.1.17]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/compare/v0.1.16..v0.1.17
[0.1.16]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/compare/v0.1.15..v0.1.16
[0.1.15]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/compare/v0.1.14..v0.1.15
[0.1.14]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/compare/v0.1.13..v0.1.14
[0.1.13]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/compare/v0.1.12..v0.1.13
[0.1.12]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/compare/v0.1.11..v0.1.12
[0.1.11]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/compare/v0.1.10..v0.1.11
[0.1.10]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/compare/v0.1.9..v0.1.10
[0.1.9]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/compare/v0.1.8..v0.1.9
[0.1.8]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/compare/v0.1.7..v0.1.8
[0.1.7]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/compare/v0.1.6..v0.1.7
[0.1.6]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/compare/v0.1.5..v0.1.6
[0.1.5]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/compare/v0.1.4..v0.1.5
[0.1.4]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/compare/v0.1.3..v0.1.4
[0.1.3]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/compare/v0.1.2..v0.1.3
[0.1.2]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/compare/v0.1.1..v0.1.2
[0.1.1]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/compare/v0.1.0..v0.1.1
[0.1.0]: https://github.com/natescherer/postmodern-helm-deploy-copiertemplate/tree/v0.1.0