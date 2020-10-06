# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
- Initial support for configuration files
- Initial override of [DoctrineMigrationsBundle](https://github.com/doctrine/DoctrineMigrationsBundle) commands
  - Ability to execute migrations commands to all entity managers, or filtered by the option `--em=default`
  - Supported command `doctrine:migrations:diff`
  - Supported command `doctrine:migrations:migrate`
  - Supported command `doctrine:migrations:version`