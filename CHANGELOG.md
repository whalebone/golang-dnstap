# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [v0.2.0-originv0.4.0] - 2025-02-26
### Added
- The `dnstap` message is extended with `ratelimited` flag indicating whether DNS request was rate-limited. (https://whaleboneio.atlassian.net/browse/PD-5774)

## [v0.1.0-originv0.4.0] - 2024-11-21
### Added
- The `dnstap` message is extended with `tag` representing tag associate with the policy selected for given DNS request. (https://whaleboneio.atlassian.net/browse/PD-3520)