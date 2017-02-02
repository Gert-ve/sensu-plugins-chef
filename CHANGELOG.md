#Change Log
This project adheres to [Semantic Versioning](http://semver.org/).

This CHANGELOG follows the format listed at [Keep A Changelog](http://keepachangelog.com/)

## [Unreleased]
- in `check-chef-nodes.rb` made client name required
- in `check-chef-nodes.rb` made a sane default for client name
- fix travis builds for ruby versions that have older bundler installed

## [2.0.0] - 2016-07-25
### Changed
- bumped Chef gem to the latest available

## [1.0.0] - 2016-06-14
### Added
- check-chef-nodes.rb: add an option to "check-chef-nodes" to exclude nodes from check

### Changed
- check-chef-server.rb: loosen regex used to match chef-server-ctl status output
- Rubocop updated to ~> 0.40; automated cleanup applied.

### Removed
- Remove Ruby 1.9.3 support; add Ruby 2.3.0 support

## [0.0.6] - 2015-12-03
### Changed
- changed default time before a check is deemed critical to 38 minutes to match the chef-client cookbook (30 min + 5 in splay + 3 for converge)

## [0.0.5] - 2015-11-24
### Added
- add a check if a node exists

### Changed
- pin to varia_model 0.4.1 for Ruby 1.9.3 compatability

## [0.0.4] - 2015-09-03
### Changed
- bumped chef gem to version chef-11.18.12

## [0.0.3] - 2015-07-14
### Changed
- updated sensu-plugin gem to 1.2.0

## 0.0.2 - 2015-06-02
### Fixed
- added binstubs

### Changed
- removed cruft from /lib

## 0.0.1 - 2015-05-04

### Added
- initial release

[Unreleased]: https://github.com/sensu-plugins/sensu-plugins-chef/compare/2.0.0...HEAD
[2.0.0]: https://github.com/sensu-plugins/sensu-plugins-chef/compare/1.0.0...2.0.0
[1.0.0]: https://github.com/sensu-plugins/sensu-plugins-chef/compare/0.0.6...1.0.0
[0.0.6]: https://github.com/sensu-plugins/sensu-plugins-chef/compare/0.0.5...0.0.6
[0.0.5]: https://github.com/sensu-plugins/sensu-plugins-chef/compare/0.0.4...0.0.5
[0.0.4]: https://github.com/sensu-plugins/sensu-plugins-chef/compare/0.0.3...0.0.4
[0.0.3]: https://github.com/sensu-plugins/sensu-plugins-chef/compare/0.0.2...0.0.3
[0.0.2]: https://github.com/sensu-plugins/sensu-plugins-chef/compare/0.0.1...0.0.2
