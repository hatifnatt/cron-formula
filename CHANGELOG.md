# Changelog

# [0.4.0](https://github.com/saltstack-formulas/cron-formula/compare/v0.3.2...v0.4.0) (2022-01-14)


### Continuous Integration

* **3003.1:** update inc. AlmaLinux, Rocky & `rst-lint` [skip ci] ([d52490b](https://github.com/saltstack-formulas/cron-formula/commit/d52490b1d34690f156e2fb161f8f90fd969f5752))
* **gemfile+lock:** use `ssf` customised `inspec` repo [skip ci] ([c20c85d](https://github.com/saltstack-formulas/cron-formula/commit/c20c85d48a3a1c82b7731ce62abb13d0fa23cfe0))
* **gemfile+lock:** use `ssf` customised `kitchen-docker` repo [skip ci] ([9dd756d](https://github.com/saltstack-formulas/cron-formula/commit/9dd756d7cdf68078771ae5e77962380e2cae9ab7))
* **kitchen:** move `provisioner` block & update `run_command` [skip ci] ([53b7f38](https://github.com/saltstack-formulas/cron-formula/commit/53b7f380c2222839084c773d5c5dda43a6dafe6d))
* **kitchen+ci:** update with `3004` pre-salted images/boxes [skip ci] ([0142c55](https://github.com/saltstack-formulas/cron-formula/commit/0142c55ba5224376bd6871556d5ee6021ae805a1))
* **kitchen+ci:** update with latest `3003.2` pre-salted images [skip ci] ([dfb1c33](https://github.com/saltstack-formulas/cron-formula/commit/dfb1c33dbf0772d7853e279f4c61ed86893b9555))
* **kitchen+ci:** update with latest CVE pre-salted images [skip ci] ([2971748](https://github.com/saltstack-formulas/cron-formula/commit/29717486b9fbbd450a44d156aa4d0b0e0c40ab01))
* add `arch-master` to matrix and update `.travis.yml` [skip ci] ([8a264b7](https://github.com/saltstack-formulas/cron-formula/commit/8a264b759d8ded9e161366a7ec9249bab6d7f436))
* add Debian 11 Bullseye & update `yamllint` configuration [skip ci] ([452afbe](https://github.com/saltstack-formulas/cron-formula/commit/452afbe6ec675d60ba8896b071627752e7ab6f82))
* **commitlint:** ensure `upstream/master` uses main repo URL [skip ci] ([c9e1a2b](https://github.com/saltstack-formulas/cron-formula/commit/c9e1a2b6a3909e69786220887a61ccc6f1f8de06))
* **gitlab-ci:** add `rubocop` linter (with `allow_failure`) [skip ci] ([76ee797](https://github.com/saltstack-formulas/cron-formula/commit/76ee797cb59eabda5257d30e0acc62abda1e8b2a))
* **gitlab-ci:** use GitLab CI as Travis CI replacement ([920c438](https://github.com/saltstack-formulas/cron-formula/commit/920c4388e9bd9f25b4db4503f5a39fb42c3ab7ca))
* **kitchen+ci:** use latest pre-salted images (after CVE) [skip ci] ([64260e8](https://github.com/saltstack-formulas/cron-formula/commit/64260e85b05683b2ef61d1bad58556ba411233b0))
* **kitchen+gitlab:** adjust matrix to add `3003` [skip ci] ([9072f83](https://github.com/saltstack-formulas/cron-formula/commit/9072f83d8fef25aaa249732e6115d3cc2b0bc25b))
* **kitchen+gitlab:** remove Ubuntu 16.04 & Fedora 32 (EOL) [skip ci] ([e588573](https://github.com/saltstack-formulas/cron-formula/commit/e58857389200e73ec1e67fe611ad68cb1e1df46c))
* **kitchen+gitlab-ci:** use latest pre-salted images [skip ci] ([750e242](https://github.com/saltstack-formulas/cron-formula/commit/750e242b39b1846267f627c44fd99875c0ee4ae5))
* **pre-commit:** add to formula [skip ci] ([b36d0ec](https://github.com/saltstack-formulas/cron-formula/commit/b36d0ecd6e77722aca6fb3900f04e7fa39840e03))
* **pre-commit:** enable/disable `rstcheck` as relevant [skip ci] ([8856f60](https://github.com/saltstack-formulas/cron-formula/commit/8856f60dd22457463465a5c305235fe10d687b1f))
* **pre-commit:** finalise `rstcheck` configuration [skip ci] ([a3fa371](https://github.com/saltstack-formulas/cron-formula/commit/a3fa3710f5747ceed18ce5834a7bb41ab14bfcb9))
* **pre-commit:** update hook for `rubocop` [skip ci] ([8317265](https://github.com/saltstack-formulas/cron-formula/commit/8317265a7d7816ef8ea446058ab70abd6bafd3d1))


### Features

* **osfamilymap:** add Gentoo support ([547ae1b](https://github.com/saltstack-formulas/cron-formula/commit/547ae1b5931c6cb1e12bc32b61d6f614ab1bbfe8))


### Tests

* standardise use of `share` suite & `_mapdata` state [skip ci] ([73b9643](https://github.com/saltstack-formulas/cron-formula/commit/73b96437a1fcd4e72d9219f162b53e3c19d64ed0))

## [0.3.2](https://github.com/saltstack-formulas/cron-formula/compare/v0.3.1...v0.3.2) (2020-09-10)


### Continuous Integration

* **gemfile:** restrict `train` gem version until upstream fix [skip ci] ([ce61077](https://github.com/saltstack-formulas/cron-formula/commit/ce610777803fa67ce4e8aa4e01823741ec5844af))
* **gemfile.lock:** add to repo with updated `Gemfile` [skip ci] ([269b49f](https://github.com/saltstack-formulas/cron-formula/commit/269b49f38a304cf7ca63ae889f178a939353accd))
* **kitchen:** avoid using bootstrap for `master` instances [skip ci] ([0afa1b1](https://github.com/saltstack-formulas/cron-formula/commit/0afa1b10d2a4325880cfeda7f716d2eaf82edb4b))
* **kitchen:** use `saltimages` Docker Hub where available [skip ci] ([74999aa](https://github.com/saltstack-formulas/cron-formula/commit/74999aa17df28a7128058697f6b5f4a59ab468c6))
* **kitchen+travis:** remove `master-py2-arch-base-latest` [skip ci] ([54b5a1a](https://github.com/saltstack-formulas/cron-formula/commit/54b5a1abaad6b8a650ad48d1cee807c486e53c0b))
* **travis:** add notifications => zulip [skip ci] ([fb46b07](https://github.com/saltstack-formulas/cron-formula/commit/fb46b0799e4084a8b22f77d0c5c6b2179e20be01))
* **travis:** apply changes from build config validation [skip ci] ([730df10](https://github.com/saltstack-formulas/cron-formula/commit/730df1087fe44b7bc40bd9e2530188cb9c6ffcca))
* **travis:** opt-in to `dpl v2` to complete build config validation [skip ci] ([4fc3960](https://github.com/saltstack-formulas/cron-formula/commit/4fc3960112929de84d546e3547ce81f9685c5687))
* **travis:** quote pathspecs used with `git ls-files` [skip ci] ([0fef6f1](https://github.com/saltstack-formulas/cron-formula/commit/0fef6f12230e018b8c0402c80a2f2c98a1280ef9))
* **travis:** run `shellcheck` during lint job [skip ci] ([1b2eb28](https://github.com/saltstack-formulas/cron-formula/commit/1b2eb285a5bb62c86d6e7e64ddd76ce85a709d2b))
* **travis:** use `major.minor` for `semantic-release` version [skip ci] ([d4a6100](https://github.com/saltstack-formulas/cron-formula/commit/d4a610094969d583621cdec3195652508fe0aace))
* **travis:** use build config validation (beta) [skip ci] ([db46bd9](https://github.com/saltstack-formulas/cron-formula/commit/db46bd9c9008fddc3681602cf559513df3ee1976))
* **workflows/commitlint:** add to repo [skip ci] ([449c919](https://github.com/saltstack-formulas/cron-formula/commit/449c919f14dc295883de17db7b5b42dea1c56a2b))


### Reverts

* **codeowners:** update specific directories section [skip ci] ([2ac7785](https://github.com/saltstack-formulas/cron-formula/commit/2ac7785f6446abf26d8e9897e7a5898f5bb42d1b))


### Styles

* **state:** avoid complicated comparison ([496f09b](https://github.com/saltstack-formulas/cron-formula/commit/496f09b2e1c2ba88d8df95ec0c0011fce0d4a7a7))

## [0.3.1](https://github.com/saltstack-formulas/cron-formula/compare/v0.3.0...v0.3.1) (2019-11-04)


### Tests

* **saltcheck:** add test for cron envs (`absent` & `present`) ([82cd0a7](https://github.com/saltstack-formulas/cron-formula/commit/82cd0a7f3a2f5d61397b6cfc9a45470477dc51cf))

# [0.3.0](https://github.com/saltstack-formulas/cron-formula/compare/v0.2.4...v0.3.0) (2019-11-03)


### Bug Fixes

* **release.config.js:** use full commit hash in commit link [skip ci] ([c5eb3b7](https://github.com/saltstack-formulas/cron-formula/commit/c5eb3b78bcfa635ca7a2df01c03e5b60b4ed2758))


### Continuous Integration

* **kitchen:** use `debian-10-master-py3` instead of `develop` [skip ci] ([aca0d9e](https://github.com/saltstack-formulas/cron-formula/commit/aca0d9e437c951f798fe097415746218d84dea58))
* **kitchen:** use `develop` image until `master` is ready (`amazonlinux`) [skip ci] ([f9c61a9](https://github.com/saltstack-formulas/cron-formula/commit/f9c61a98593a90d5d4f5b0119a2f486fe70ea133))
* **kitchen+travis:** upgrade matrix after `2019.2.2` release [skip ci] ([2062f10](https://github.com/saltstack-formulas/cron-formula/commit/2062f10f947155b051ce93e7636cbd9bdb604a6c))


### Features

* **cron.env:** add env option in cron-formula ([12cee12](https://github.com/saltstack-formulas/cron-formula/commit/12cee122279fc0abe113d35d59b626e2f94913ae))


### Performance Improvements

* **travis:** improve `salt-lint` invocation [skip ci] ([624b05a](https://github.com/saltstack-formulas/cron-formula/commit/624b05a180a0013c0973e271e382cc46cf12b9c5))

## [0.2.4](https://github.com/saltstack-formulas/cron-formula/compare/v0.2.3...v0.2.4) (2019-10-23)


### Bug Fixes

* **saltcheck:** fix broken import and standardise across test files ([](https://github.com/saltstack-formulas/cron-formula/commit/7911b71))
* **saltcheck:** fix invalid `service` test ([](https://github.com/saltstack-formulas/cron-formula/commit/677c956))
* **saltcheck:** remove trailing spaces ([](https://github.com/saltstack-formulas/cron-formula/commit/aada0ae))
* **saltcheck:** replace `map.jinja` references with InSpec conditionals ([](https://github.com/saltstack-formulas/cron-formula/commit/7e9e619))
* **saltcheck:** update for `cron` instead of `cron_settings` ([](https://github.com/saltstack-formulas/cron-formula/commit/26cfa4f))


### Code Refactoring

* **config:** minimise and standardise between `.sls` & `.tst` ([](https://github.com/saltstack-formulas/cron-formula/commit/18585bd))
* **config:** remove duplication in using a loop ([](https://github.com/saltstack-formulas/cron-formula/commit/652ebff))
* **jinja:** used shortened form of `|default` filter ([](https://github.com/saltstack-formulas/cron-formula/commit/a0f891e))
* **saltcheck:** relocate `.tst` files according to 1:1 `.sls` files ([](https://github.com/saltstack-formulas/cron-formula/commit/ee65236)), closes [/github.com/saltstack-formulas/cron-formula/pull/4#issuecomment-544140377](https://github.com//github.com/saltstack-formulas/cron-formula/pull/4/issues/issuecomment-544140377)
* **saltcheck:** use `package.tst` instead of `install.tst` ([](https://github.com/saltstack-formulas/cron-formula/commit/d2c9544))
* **saltcheck:** use root-level `saltcheck-tests` directory ([](https://github.com/saltstack-formulas/cron-formula/commit/6e54c3f))


### Continuous Integration

* **travis:** obtain `saltcheck.py` and run the tests (only on `develop`) ([](https://github.com/saltstack-formulas/cron-formula/commit/8ae46e5))
* **travis:** run `salt-lint` for `.tst` files as well ([](https://github.com/saltstack-formulas/cron-formula/commit/baab964))
* **travis:** standardise `saltcheck` comments ([](https://github.com/saltstack-formulas/cron-formula/commit/e23276b))
* **travis:** update `salt-lint` config for `v0.0.10` [skip ci] ([](https://github.com/saltstack-formulas/cron-formula/commit/b701d79))


### Styles

* **config.tst:** rearrange Jinja statements for clarity ([](https://github.com/saltstack-formulas/cron-formula/commit/8abec54))
* **saltcheck:** merge `absent` & `present` into one `if` block ([](https://github.com/saltstack-formulas/cron-formula/commit/33f344c))
* **saltcheck:** use consistent order of assertions ([](https://github.com/saltstack-formulas/cron-formula/commit/88229f0))


### Tests

* **pillar:** add test for `commented` and clarify each test ([](https://github.com/saltstack-formulas/cron-formula/commit/3d0dcb2))
* **pillar:** ensure `special` is being tested as well ([](https://github.com/saltstack-formulas/cron-formula/commit/951a959))
* **saltcheck:** add first tests ([](https://github.com/saltstack-formulas/cron-formula/commit/9847aff))
* **saltcheck:** add support for `random` values ([](https://github.com/saltstack-formulas/cron-formula/commit/007970f))
* **saltcheck:** add test for `service.available` ([](https://github.com/saltstack-formulas/cron-formula/commit/226eb88))
* **saltcheck:** add test for `service.running` ([](https://github.com/saltstack-formulas/cron-formula/commit/5cdc50f))
* **saltcheck:** avoid `map.jinja`, use the test pillar instead ([](https://github.com/saltstack-formulas/cron-formula/commit/cce5e67))
* **saltcheck:** fix `config` tests ([](https://github.com/saltstack-formulas/cron-formula/commit/9225b18))
* **saltcheck:** remove duplication in `config.tst` using a loop ([](https://github.com/saltstack-formulas/cron-formula/commit/72281c7))
* **saltcheck:** test for `commented` and not `commented` ([](https://github.com/saltstack-formulas/cron-formula/commit/5070611))
* **saltcheck:** test for `special` in `config.tst` as well ([](https://github.com/saltstack-formulas/cron-formula/commit/6f2b323))
* **saltcheck:** use local `map.jinja` to workaround missing `tpldata` ([](https://github.com/saltstack-formulas/cron-formula/commit/8845b3c))

## [0.2.3](https://github.com/saltstack-formulas/cron-formula/compare/v0.2.2...v0.2.3) (2019-10-15)


### Bug Fixes

* **platform:** add support for `Arch` ([](https://github.com/saltstack-formulas/cron-formula/commit/a9968e3))


### Continuous Integration

* **platform:** enable `arch-base-latest` ([](https://github.com/saltstack-formulas/cron-formula/commit/525ecee))


### Documentation

* **contributing:** remove to use org-level file instead [skip ci] ([](https://github.com/saltstack-formulas/cron-formula/commit/c12034a))
* **readme:** update link to `CONTRIBUTING` [skip ci] ([](https://github.com/saltstack-formulas/cron-formula/commit/eccccb6))


### Tests

* **pillar:** extract test pillar from `pillar.example` ([](https://github.com/saltstack-formulas/cron-formula/commit/482e2d1))

## [0.2.2](https://github.com/saltstack-formulas/cron-formula/compare/v0.2.1...v0.2.2) (2019-10-12)


### Bug Fixes

* **rubocop:** add fixes using `rubocop --safe-auto-correct` ([](https://github.com/saltstack-formulas/cron-formula/commit/23fa917))


### Continuous Integration

* **kitchen:** change `log_level` to `debug` instead of `info` ([](https://github.com/saltstack-formulas/cron-formula/commit/dfa8565))
* **kitchen:** install required packages to bootstrapped `opensuse` [skip ci] ([](https://github.com/saltstack-formulas/cron-formula/commit/daf41cb))
* **kitchen:** use bootstrapped `opensuse` images until `2019.2.2` [skip ci] ([](https://github.com/saltstack-formulas/cron-formula/commit/91a050e))
* **platform:** add `arch-base-latest` (commented out for now) [skip ci] ([](https://github.com/saltstack-formulas/cron-formula/commit/dbeafde))
* merge travis matrix, add `salt-lint` & `rubocop` to `lint` job ([](https://github.com/saltstack-formulas/cron-formula/commit/fe3b733))
* merge travis matrix, add `salt-lint` & `rubocop` to `lint` job ([](https://github.com/saltstack-formulas/cron-formula/commit/ef8ac40))
* use `dist: bionic` & apply `opensuse-leap-15` SCP error workaround ([](https://github.com/saltstack-formulas/cron-formula/commit/e1d7d1b))
* **travis:** merge `rubocop` linter into main `lint` job ([](https://github.com/saltstack-formulas/cron-formula/commit/67c704c))
* **yamllint:** add rule `empty-values` & use new `yaml-files` setting ([](https://github.com/saltstack-formulas/cron-formula/commit/67475b0))

## [0.2.1](https://github.com/saltstack-formulas/cron-formula/compare/v0.2.0...v0.2.1) (2019-09-01)


### Code Refactoring

* **pillar:** sync map.jinja with template-formula ([e00c316](https://github.com/saltstack-formulas/cron-formula/commit/e00c316))

# [0.2.0](https://github.com/saltstack-formulas/cron-formula/compare/v0.1.0...v0.2.0) (2019-08-28)


### Continuous Integration

* **kitchen:** add Kitchen tests ([963b5eb](https://github.com/saltstack-formulas/cron-formula/commit/963b5eb))


### Features

* **semantic-release:** add semantic-release ([6002c8f](https://github.com/saltstack-formulas/cron-formula/commit/6002c8f))
