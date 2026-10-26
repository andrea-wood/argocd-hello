# Changelog

All notable changes to this chart are documented in this file.
The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/)
and the chart adheres to [Semantic Versioning](https://semver.org/).

## [Unreleased]

## [0.2.0] - 2026-10-21

### Added
- `message` value to customize the page served by nginx.
- ConfigMap `<release>-html` mounted in `/usr/share/nginx/html`.
- `checksum/config` annotation so pods restart when the ConfigMap changes.

## [0.1.0] - 2026-10-21

### Added
- Initial chart: nginx Deployment and Service.
