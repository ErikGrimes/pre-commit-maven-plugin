# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.0] - 2018-06-09
### Added
- New argument `hookTypes` for installing multiple different hook types
- Python output is now always written to maven output. `download-binary` is very
  verbose and is therefore written to DEBUG which requires `-X` to see.

### Changed
- Changed the `version` argument to `precommitVersion` to differentiate it from
  the plugin version

## [0.1.0] - 2018-06-06
### Added
- Initial release of the plugin

[Unreleased]: https://github.com/oslomarketsolutions/pre-commit-maven-plugin/compare/v0.2.0...HEAD
[0.2.0]: https://github.com/oslomarketsolutions/pre-commit-maven-plugin/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/oslomarketsolutions/pre-commit-maven-plugin/compare/e5dfac7097cb80b54dc3e802b453f40fd2f05fb6...v0.1.0

