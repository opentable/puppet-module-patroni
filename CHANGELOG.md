# Change log

All notable changes to this project will be documented in this file. The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/) and this project adheres to [Semantic Versioning](http://semver.org).

## [v2.1.0](https://github.com/tailored-automation/puppet-module-patroni/tree/v2.1.0) (2025-01-04)

[Full Changelog](https://github.com/tailored-automation/puppet-module-patroni/compare/v2.0.1...v2.1.0)

### Added

- Harden the datatypes [\#48](https://github.com/tailored-automation/puppet-module-patroni/pull/48) ([ghoneycutt](https://github.com/ghoneycutt))

## [v2.0.1](https://github.com/tailored-automation/puppet-module-patroni/tree/v2.0.1) (2025-01-04)

[Full Changelog](https://github.com/tailored-automation/puppet-module-patroni/compare/v2.0.0...v2.0.1)

### Fixed

- Fix existing issues so tests work again [\#47](https://github.com/tailored-automation/puppet-module-patroni/pull/47) ([ghoneycutt](https://github.com/ghoneycutt))

### Merged pull requests:

- Fix crash if pg password starting with bracket [\#42](https://github.com/tailored-automation/puppet-module-patroni/pull/42) ([ghoneycutt](https://github.com/ghoneycutt))
- Fix crash if pg password starting with bracket [\#39](https://github.com/tailored-automation/puppet-module-patroni/pull/39) ([mouchymouchy](https://github.com/mouchymouchy))
- adding standby cluster config [\#31](https://github.com/tailored-automation/puppet-module-patroni/pull/31) ([plmayekar](https://github.com/plmayekar))

## [v2.0.0](https://github.com/tailored-automation/puppet-module-patroni/tree/v2.0.0) (2023-11-27)

[Full Changelog](https://github.com/tailored-automation/puppet-module-patroni/compare/v1.6.0...v2.0.0)

### Changed

- Major updates, see description [\#37](https://github.com/tailored-automation/puppet-module-patroni/pull/37) ([treydock](https://github.com/treydock))

### Merged pull requests:

- PDK update [\#34](https://github.com/tailored-automation/puppet-module-patroni/pull/34) ([ghoneycutt](https://github.com/ghoneycutt))
- Fix CI [\#32](https://github.com/tailored-automation/puppet-module-patroni/pull/32) ([ghoneycutt](https://github.com/ghoneycutt))
- PDK Update [\#25](https://github.com/tailored-automation/puppet-module-patroni/pull/25) ([treydock](https://github.com/treydock))

## [v1.6.0](https://github.com/tailored-automation/puppet-module-patroni/tree/v1.6.0) (2021-11-02)

[Full Changelog](https://github.com/tailored-automation/puppet-module-patroni/compare/v1.5.0...v1.6.0)

### Added

- Add ability to configure Patroni DCS configs [\#24](https://github.com/tailored-automation/puppet-module-patroni/pull/24) ([treydock](https://github.com/treydock))

## [v1.5.0](https://github.com/tailored-automation/puppet-module-patroni/tree/v1.5.0) (2021-06-19)

[Full Changelog](https://github.com/tailored-automation/puppet-module-patroni/compare/v1.4.0...v1.5.0)

### Added

- Add Puppet 7 and use Github Actions [\#22](https://github.com/tailored-automation/puppet-module-patroni/pull/22) ([treydock](https://github.com/treydock))
- enable support for cipher flag [\#21](https://github.com/tailored-automation/puppet-module-patroni/pull/21) ([mrstrozy](https://github.com/mrstrozy))

## [v1.4.0](https://github.com/tailored-automation/puppet-module-patroni/tree/v1.4.0) (2021-04-28)

[Full Changelog](https://github.com/tailored-automation/puppet-module-patroni/compare/v1.3.0...v1.4.0)

### Added

- Add support for specifying a custom pip provider [\#19](https://github.com/tailored-automation/puppet-module-patroni/pull/19) ([ghoneycutt](https://github.com/ghoneycutt))

## [v1.3.0](https://github.com/tailored-automation/puppet-module-patroni/tree/v1.3.0) (2021-04-07)

[Full Changelog](https://github.com/tailored-automation/puppet-module-patroni/compare/v1.2.0...v1.3.0)

### Merged pull requests:

- Fix acceptance tests [\#14](https://github.com/tailored-automation/puppet-module-patroni/pull/14) ([treydock](https://github.com/treydock))
- Make managing the postgresql package repo optional [\#12](https://github.com/tailored-automation/puppet-module-patroni/pull/12) ([ghoneycutt](https://github.com/ghoneycutt))

## [v1.2.0](https://github.com/tailored-automation/puppet-module-patroni/tree/v1.2.0) (2020-10-17)

[Full Changelog](https://github.com/tailored-automation/puppet-module-patroni/compare/v1.1.0...v1.2.0)

### Added

- Add better unit tests and support getting coverage [\#10](https://github.com/tailored-automation/puppet-module-patroni/pull/10) ([treydock](https://github.com/treydock))
- Support puppet/python v5.x [\#8](https://github.com/tailored-automation/puppet-module-patroni/pull/8) ([treydock](https://github.com/treydock))

### Fixed

- Set PIP\_PREFIX for python resources [\#9](https://github.com/tailored-automation/puppet-module-patroni/pull/9) ([treydock](https://github.com/treydock))

## [v1.1.0](https://github.com/tailored-automation/puppet-module-patroni/tree/v1.1.0) (2020-10-12)

[Full Changelog](https://github.com/tailored-automation/puppet-module-patroni/compare/v1.0.1...v1.1.0)

### Fixed

- Readme updates [\#6](https://github.com/tailored-automation/puppet-module-patroni/pull/6) ([treydock](https://github.com/treydock))
- Ensure postgresql\_version is used [\#5](https://github.com/tailored-automation/puppet-module-patroni/pull/5) ([treydock](https://github.com/treydock))

## [v1.0.1](https://github.com/tailored-automation/puppet-module-patroni/tree/v1.0.1) (2020-09-28)

[Full Changelog](https://github.com/tailored-automation/puppet-module-patroni/compare/v1.0.0...v1.0.1)

### Merged pull requests:

- Fix release process [\#4](https://github.com/tailored-automation/puppet-module-patroni/pull/4) ([treydock](https://github.com/treydock))
- Fix links in metadata and documentation [\#3](https://github.com/tailored-automation/puppet-module-patroni/pull/3) ([ghoneycutt](https://github.com/ghoneycutt))

## [v1.0.0](https://github.com/tailored-automation/puppet-module-patroni/tree/v1.0.0) (2020-09-25)

[Full Changelog](https://github.com/tailored-automation/puppet-module-patroni/compare/0.1.6...v1.0.0)

### Merged pull requests:

- V1 [\#1](https://github.com/tailored-automation/puppet-module-patroni/pull/1) ([ghoneycutt](https://github.com/ghoneycutt))

## [0.1.6](https://github.com/tailored-automation/puppet-module-patroni/tree/0.1.6) (2020-08-13)

[Full Changelog](https://github.com/tailored-automation/puppet-module-patroni/compare/0.1.5...0.1.6)

## [0.1.5](https://github.com/tailored-automation/puppet-module-patroni/tree/0.1.5) (2020-04-06)

[Full Changelog](https://github.com/tailored-automation/puppet-module-patroni/compare/0.1.4...0.1.5)

## [0.1.4](https://github.com/tailored-automation/puppet-module-patroni/tree/0.1.4) (2020-01-17)

[Full Changelog](https://github.com/tailored-automation/puppet-module-patroni/compare/0.1.3...0.1.4)

## [0.1.3](https://github.com/tailored-automation/puppet-module-patroni/tree/0.1.3) (2019-12-11)

[Full Changelog](https://github.com/tailored-automation/puppet-module-patroni/compare/0.1.2...0.1.3)

## [0.1.2](https://github.com/tailored-automation/puppet-module-patroni/tree/0.1.2) (2019-11-13)

[Full Changelog](https://github.com/tailored-automation/puppet-module-patroni/compare/0.1.1...0.1.2)

## [0.1.1](https://github.com/tailored-automation/puppet-module-patroni/tree/0.1.1) (2018-07-18)

[Full Changelog](https://github.com/tailored-automation/puppet-module-patroni/compare/0.1.0...0.1.1)

## [0.1.0](https://github.com/tailored-automation/puppet-module-patroni/tree/0.1.0) (2018-07-11)

[Full Changelog](https://github.com/tailored-automation/puppet-module-patroni/compare/15ab29b2005e537b33a4fad75c22364ce436c439...0.1.0)



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
