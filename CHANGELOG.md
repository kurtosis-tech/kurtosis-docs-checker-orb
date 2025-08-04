# Changelog

## [0.2.10](https://github.com/kurtosis-tech/kurtosis-docs-checker-orb/compare/0.2.9...0.2.10) (2025-08-04)


### Bug Fixes

* give pr update workflow explicit perms ([#28](https://github.com/kurtosis-tech/kurtosis-docs-checker-orb/issues/28)) ([28f2702](https://github.com/kurtosis-tech/kurtosis-docs-checker-orb/commit/28f2702932fc1383b768e57a5fa12494b99ac634))

## [0.2.9](https://github.com/kurtosis-tech/kurtosis-docs-checker-orb/compare/0.2.8...0.2.9) (2024-08-10)


### Bug Fixes

* upgrade node img ([#25](https://github.com/kurtosis-tech/kurtosis-docs-checker-orb/issues/25)) ([5e7265e](https://github.com/kurtosis-tech/kurtosis-docs-checker-orb/commit/5e7265e48357a9b8f3b06d06b1d5ecce7ba3e247))

## [0.2.8](https://github.com/kurtosis-tech/kurtosis-docs-checker-orb/compare/0.2.7...0.2.8) (2024-08-10)


### Bug Fixes

* clean cache before installing ([#23](https://github.com/kurtosis-tech/kurtosis-docs-checker-orb/issues/23)) ([f8ef471](https://github.com/kurtosis-tech/kurtosis-docs-checker-orb/commit/f8ef4714627fbb10088398b9308ff1775ddc396d))

## [0.2.7](https://github.com/kurtosis-tech/kurtosis-docs-checker-orb/compare/0.2.6...0.2.7) (2024-03-11)


### Bug Fixes

* use 3.11.2 as latest is broken ([#21](https://github.com/kurtosis-tech/kurtosis-docs-checker-orb/issues/21)) ([f994acb](https://github.com/kurtosis-tech/kurtosis-docs-checker-orb/commit/f994acb5f1eea92a10909f00d23bcddeb1f6bfbb))

## [0.2.6](https://github.com/kurtosis-tech/kurtosis-docs-checker-orb/compare/0.2.5...0.2.6) (2023-12-07)


### Features

* Allow regex to exclude multiple paths ([#19](https://github.com/kurtosis-tech/kurtosis-docs-checker-orb/issues/19)) ([51e1ad7](https://github.com/kurtosis-tech/kurtosis-docs-checker-orb/commit/51e1ad7574b1d4c09d251441d4e9f2e86ccb66a7))

## [0.2.5](https://github.com/kurtosis-tech/kurtosis-docs-checker-orb/compare/0.2.4...0.2.5) (2023-04-03)


### Bug Fixes

* allow for the docs checker parameter to be empty ([#17](https://github.com/kurtosis-tech/kurtosis-docs-checker-orb/issues/17)) ([8f87ed9](https://github.com/kurtosis-tech/kurtosis-docs-checker-orb/commit/8f87ed935c2434246742361201f50516783d3c0e))

## [0.2.4](https://github.com/kurtosis-tech/kurtosis-docs-checker-orb/compare/0.2.3...0.2.4) (2023-03-10)


### Features

* add ability to exclude dirs ([#14](https://github.com/kurtosis-tech/kurtosis-docs-checker-orb/issues/14)) ([a6964b5](https://github.com/kurtosis-tech/kurtosis-docs-checker-orb/commit/a6964b5f494c37c7169bb5410b15dffec883d89d))

## 0.2.3

### Fixes
- Fixed a bug that made the orb.yml invalid

## 0.2.2

###
- The `docs-checker` can be toggled off, in order to support a repo with conventional commits & its related checker

## 0.2.1

### Changes
* Migrate repo to use new release workflow
* Merge `develop` into `master`

## 0.2.0
### Breaking Changes
* Rename `markdown_link_check_config_json` parameter to `check-docs` job to `markdown-link-check-config-json`
    * Users should update their job parameter appropriately

## 0.1.13
### Fixes
* Only check docs on PRs

## 0.1.12
### Features
* Have this orb validate its own docs

## 0.1.11
### Removals
* Remove debugging steps now that we figured out why publishing wasn't working

## 0.1.10
### Fixes
* Get rid of ridiculous .gitignore that was ignoring `orb.yml`!

## 0.1.9
* Add missing `cli` orb needed for debugging job

## 0.1.8
* Fix forgotten executor in debugging job

## 0.1.7
* Add debugging to CircleCI to figure out why publishing still is failing

## 0.1.6
* Trying again to get publishing to work

## 0.1.5
### Fixes
* Correct for inconsistent docs in CircleCI orb-tools publishing

## 0.1.4
### Fixes
* Yet another bugfix in CircleCI publishing

## 0.1.3
### Fixes
* Another bugfix in CircleCI publishing

## 0.1.2
### Fixes
* Trying again to fix the CircleCI publishing

## 0.1.1
### Fixes
* Fixed CircleCI config.yml errors

## 0.1.0
* Initial commit
