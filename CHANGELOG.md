# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Changed

- Update the app to 0.2.5
- Change team annotation in `Chart.yaml` to OpenContainers format (`io.giantswarm.application.team`).

## [0.2.0] - 2025-10-27

### Added

- Add missing Service Monitor.

## [0.1.4] - 2025-10-27

### Fixed

- Fix missing CNP to communicate with CoreDNS

## [0.1.3] - 2025-10-21

### Changed

- Update the app to 0.2.4 which removes some Gin framework warnings

## [0.1.2] - 2025-10-10

### Fixed

- Fix circle ci config to be able to create a chart on tags.

## [0.1.1] - 2025-10-09

### Changed

- Push the app to the giantswarm catalog instead of the control-plane.

## [0.1.0] - 2025-09-09

### Changed

- `app.giantswarm.io` label group was changed to `application.giantswarm.io`

### Added
 
- Pushed the app into the app collections

[Unreleased]: https://github.com/giantswarm/alertmanager-to-github-app/compare/v0.2.0...HEAD
[0.2.0]: https://github.com/giantswarm/alertmanager-to-github-app/compare/v0.1.4...v0.2.0
[0.1.4]: https://github.com/giantswarm/alertmanager-to-github-app/compare/v0.1.3...v0.1.4
[0.1.3]: https://github.com/giantswarm/alertmanager-to-github-app/compare/v0.1.2...v0.1.3
[0.1.2]: https://github.com/giantswarm/alertmanager-to-github-app/compare/v0.1.1...v0.1.2
[0.1.1]: https://github.com/giantswarm/alertmanager-to-github-app/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/giantswarm/alertmanager-to-github-app/releases/tag/v0.1.0
