# Changelog

## [0.18.4](https://github.com/saltstack-formulas/bind-formula/compare/v0.18.3...v0.18.4) (2019-10-10)


### Bug Fixes

* **config.sls:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/bind-formula/commit/920615a))
* **named.conf.local.jinja:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/bind-formula/commit/67736a2))
* **named.conf.logging.jinja:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/bind-formula/commit/f220886))


### Continuous Integration

* merge travis matrix, add `salt-lint` & `rubocop` to `lint` job ([](https://github.com/saltstack-formulas/bind-formula/commit/5883c09))

## [0.18.3](https://github.com/saltstack-formulas/bind-formula/compare/v0.18.2...v0.18.3) (2019-10-07)


### Bug Fixes

* **pillar.example:** fix `yamllint` error ([eb29e00](https://github.com/saltstack-formulas/bind-formula/commit/eb29e00)), closes [/travis-ci.org/myii/bind-formula/builds/594704904#L211-L213](https://github.com//travis-ci.org/myii/bind-formula/builds/594704904/issues/L211-L213)


### Continuous Integration

* use `dist: bionic` & apply `opensuse-leap-15` SCP error workaround ([90abafa](https://github.com/saltstack-formulas/bind-formula/commit/90abafa))
* **kitchen:** change `log_level` to `debug` instead of `info` ([e0be98a](https://github.com/saltstack-formulas/bind-formula/commit/e0be98a))
* **kitchen:** install required packages to bootstrapped `opensuse` [skip ci] ([a5ad4c6](https://github.com/saltstack-formulas/bind-formula/commit/a5ad4c6))
* **kitchen:** use bootstrapped `opensuse` images until `2019.2.2` [skip ci] ([0d02016](https://github.com/saltstack-formulas/bind-formula/commit/0d02016))
* **platform:** add `arch-base-latest` (commented out for now) [skip ci] ([c091c74](https://github.com/saltstack-formulas/bind-formula/commit/c091c74))
* **yamllint:** add rule `empty-values` & use new `yaml-files` setting ([9163726](https://github.com/saltstack-formulas/bind-formula/commit/9163726))

## [0.18.2](https://github.com/saltstack-formulas/bind-formula/compare/v0.18.1...v0.18.2) (2019-09-05)


### Continuous Integration

* **kitchen+travis:** replace EOL pre-salted images ([3a4d4e8](https://github.com/saltstack-formulas/bind-formula/commit/3a4d4e8))


### Tests

* **inspec:** improve to work on `amazon` as well ([59684c6](https://github.com/saltstack-formulas/bind-formula/commit/59684c6))

## [0.18.1](https://github.com/saltstack-formulas/bind-formula/compare/v0.18.0...v0.18.1) (2019-08-18)


### Bug Fixes

* **tests:** move to controls sub-directory ([74bbc5b](https://github.com/saltstack-formulas/bind-formula/commit/74bbc5b))


### Continuous Integration

* **travis:** re-enable `fedora` ([4a6ac4e](https://github.com/saltstack-formulas/bind-formula/commit/4a6ac4e))

# [0.18.0](https://github.com/saltstack-formulas/bind-formula/compare/v0.17.0...v0.18.0) (2019-08-17)


### Continuous Integration

* **kitchen+travis:** modify matrix to include `develop` platform ([641e641](https://github.com/saltstack-formulas/bind-formula/commit/641e641)), closes [#129](https://github.com/saltstack-formulas/bind-formula/issues/129)


### Features

* **yamllint:** include for this repo and apply rules throughout ([a81c9ff](https://github.com/saltstack-formulas/bind-formula/commit/a81c9ff))

# [0.17.0](https://github.com/saltstack-formulas/bind-formula/compare/v0.16.0...v0.17.0) (2019-05-24)


### Continuous Integration

* reduce platforms tested ([374b777](https://github.com/saltstack-formulas/bind-formula/commit/374b777))


### Features

* implement an automated changelog ([61bb936](https://github.com/saltstack-formulas/bind-formula/commit/61bb936))


### Tests

* **inspec:** fix suse/opensuse tests ([64872f6](https://github.com/saltstack-formulas/bind-formula/commit/64872f6))
