# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [Released]

## [1.3.9] - 2020-04-15
### Fixed
- a typo in CAS_Client::hasSessionValue()

### Changed
- session->flush() to session->forget('phpCAS') to leave the main session intact

