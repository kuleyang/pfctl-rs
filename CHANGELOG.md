# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/).

### Categories each change fall into

* **Added**: for new features.
* **Changed**: for changes in existing functionality.
* **Deprecated**: for soon-to-be removed features.
* **Removed**: for now removed features.
* **Fixed**: for any bug fixes.
* **Security**: in case of vulnerabilities.

## [unreleased]


## [0.1.1] - 2018-01-08
### Changed
- Removed building the C bindings in build.rs. Instead commit the generated bindings directly in
  the crate. This makes it possible to build the crate on non-macOS and on macOS without Xcode
  installed.


## [0.1.0] - 2017-12-20
### Added
- Initial functionality able to control most parts of the PF firewall on macOS

