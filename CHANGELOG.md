# Changelog

## [0.2.2](https://github.com/saltstack-formulas/stunnel-formula/compare/v0.2.1...v0.2.2) (2019-10-12)


### Bug Fixes

* **rubocop:** add fixes using `rubocop --safe-auto-correct` ([](https://github.com/saltstack-formulas/stunnel-formula/commit/3738a21))


### Continuous Integration

* merge travis matrix, add `salt-lint` & `rubocop` to `lint` job ([](https://github.com/saltstack-formulas/stunnel-formula/commit/687e84f))
* **travis:** merge `rubocop` linter into main `lint` job ([](https://github.com/saltstack-formulas/stunnel-formula/commit/823496b))

## [0.2.1](https://github.com/saltstack-formulas/stunnel-formula/compare/v0.2.0...v0.2.1) (2019-10-10)


### Bug Fixes

* **macro.jinja:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/stunnel-formula/commit/09646f9))
* **pillar_certs.sls:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/stunnel-formula/commit/79100c1))


### Continuous Integration

* **kitchen:** install required packages to bootstrapped `opensuse` [skip ci] ([](https://github.com/saltstack-formulas/stunnel-formula/commit/219bf04))
* **kitchen:** use bootstrapped `opensuse` images until `2019.2.2` [skip ci] ([](https://github.com/saltstack-formulas/stunnel-formula/commit/9c9a58d))
* merge travis matrix, add `salt-lint` & `rubocop` to `lint` job ([](https://github.com/saltstack-formulas/stunnel-formula/commit/94f95e2))

# [0.2.0](https://github.com/saltstack-formulas/stunnel-formula/compare/v0.1.1...v0.2.0) (2019-09-25)


### Bug Fixes

* **pillar.example:** ensure comments would pass `yamllint` as well ([e2f5a95](https://github.com/saltstack-formulas/stunnel-formula/commit/e2f5a95))


### Continuous Integration

* **kitchen:** add binstub for Kitchen command ([d373390](https://github.com/saltstack-formulas/stunnel-formula/commit/d373390))
* **kitchen:** extract test pillars in file ([924fd71](https://github.com/saltstack-formulas/stunnel-formula/commit/924fd71))
* **kitchen:** fix stunnel don't start because certs are missing ([ce6971f](https://github.com/saltstack-formulas/stunnel-formula/commit/ce6971f))
* **kitchen:** rename Kitchen config file ([e83fa64](https://github.com/saltstack-formulas/stunnel-formula/commit/e83fa64))
* **kitchen:** update gems ([1110a9d](https://github.com/saltstack-formulas/stunnel-formula/commit/1110a9d))
* **kitchen:** update platforms list ([1264438](https://github.com/saltstack-formulas/stunnel-formula/commit/1264438))
* **travis:** run tests on Debian/Ubuntu first ([403c025](https://github.com/saltstack-formulas/stunnel-formula/commit/403c025))


### Features

* **semantic-release:** add semantic-release ([261f484](https://github.com/saltstack-formulas/stunnel-formula/commit/261f484))
* **semantic-release:** implement for this formula ([9cd995a](https://github.com/saltstack-formulas/stunnel-formula/commit/9cd995a))


### Tests

* **inspec:** add Inspec tests ([5650446](https://github.com/saltstack-formulas/stunnel-formula/commit/5650446))
