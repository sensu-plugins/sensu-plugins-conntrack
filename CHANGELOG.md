# Change Log
This project adheres to [Semantic Versioning](http://semver.org/).

This CHANGELOG follows the format listed at [Keep A Changelog](http://keepachangelog.com/)

## [Unreleased]
### Security
- updated `rubocop` dependency to `~> 0.51.0` per: https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-8418. (@jaredledvina)

### Breaking Changes
- in order to bring in new rubocop dependency we need to drop ruby 2.0 support as it is EOL and aligns with out support policy. (@jaredledvina)

### Removed
- Ruby 1.9.3 from deploy-time testing (@eheydrick)

### Added
- Ruby 2.4.1 testing

## [1.0.0] - 2016-09-27
### Removed
- Ruby 1.9.3 support

### Added
- Ruby 2.3.0 support

### Changed
- Update to rubocop 0.40 and cleanup

### Fixed
- Fix typo

## [0.0.3] - 2015-07-14
### Changed
- updated sensu-plugin gem to 1.2.0

## [0.0.2] - 2015-06-02
### Fixed
- added binstubs

### Changed
- removed cruft from /lib

## 0.0.1 - 2015-05-04
### Added
- initial release

[Unreleased]: https://github.com/sensu-plugins/sensu-plugins-conntrack/compare/1.0.0...HEAD
[1.0.0]: https://github.com/sensu-plugins/sensu-plugins-conntrack/compare/0.0.3...1.0.0
[0.0.3]: https://github.com/sensu-plugins/sensu-plugins-conntrack/compare/0.0.2...0.0.3
[0.0.2]: https://github.com/sensu-plugins/sensu-plugins-conntrack/compare/0.0.1...0.0.2
