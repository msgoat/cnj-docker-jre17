# Changelog
All notable changes to `cnj-docker-jre17` will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
### Changed
### Fixed

## [1.0.1] - 2023-05-25
### Fixed
- explicitly added Zscaler CA to JRE truststore using keytool since update-ca-certificates does not update Java cacerts

## [1.0.0] - 2023-05-23
### Added
- first release with Zscaler CA added to the system and the JRE truststore
