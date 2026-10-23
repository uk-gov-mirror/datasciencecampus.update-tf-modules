# Changelog

## [0.5.0](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/compare/v0.4.1...v0.5.0) (2026-10-23)


### Features

* add security analysis workflow and configuration files ([c05ffd6](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/c05ffd699bbf70a6bbf1cf8b45994f697b150bb6))
* **logging:** add ModuleOutcome dataclass and run summary ([9864042](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/986404235003d7de4fb4f94437506c69bcee84d3))
* **logging:** add per-module progress and outcome messages ([3948693](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/39486936b29ebbb10e76bd039a521eacc9dc5458))
* **logging:** add structured lifecycle output ([00aabce](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/00aabce0fbfdb187a6317b079f89acb721477116))
* **logging:** add structured progress output and stdlib logging ([dcb72e5](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/dcb72e5b76ac4c6c97a6afa59d8bf47c7a4d0e98))
* **logging:** add zero-replacement cause hints for unchanged modules ([b421f6b](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/b421f6b9d15ce4f471c0e6ea627492651701bcec))
* resolve updater_ref to commit SHA for reproducibility ([cadf084](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/cadf08432f63ba3127535adcfbfba8d49ac730d4))


### Bug Fixes

* **ci:** default updater_ref to v0, preflight-validate ref, and align docs ([0228310](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/0228310094da6382adf8f5f22de2a66cbec75773))
* **ci:** incorporate moving major tag as a step in release pipeline ([30d45f6](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/30d45f6e4a58d39613fd63bdc8253a8d6f3ead5c))
* **ci:** skip major-tag push when already up to date ([8cadcc9](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/8cadcc9150069c8596f268b96d2798f0947513ca))
* clarify permissions comment in reusable workflow contract ([9c4c84d](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/9c4c84de0097b9cdb7eb8b27798f8edfaee7acee))
* correct permissions structure in move-major-tag workflow ([20b4791](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/20b4791e9195a0537042ada408a874841b14b6f5))
* ensure major release tags (vX) are reliably moved on publish ([eee0bd5](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/eee0bd597db0f7cec1e1795f485e4b30c6296366))
* remove redundant error table for permissions in troubleshooting guide ([4669c60](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/4669c60097e056f9fc47f87d09c65c78d82d4f56))
* tighten controls around who can access the GITHUB_TOKEN ([fc9348c](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/fc9348ccd1f93d10b470d2745ffe30417b78e7d6))
* **updaters:** count only actual module source changes ([e3ff9f5](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/e3ff9f5abfcd04132f75e9090d6fb13636cdf7fd))
* **workflow:** default updater_ref to v0 and validate ref before checkout ([48d5306](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/48d530674048806f4e824ce3b6229318e5d3e069))


### Documentation

* add major-tag verification guidance ([9da2d33](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/9da2d33c68c42064dbf0875c4174ebc815c7e00e))
* adding permissions troubleshooting guide for PR creation failures. ([a28804d](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/a28804d71c289c5c0275d1106b995a6b701f3282))
* clarify release tag semantics and mutability policy ([35e3e2a](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/35e3e2a082c30168e941fd00d78952493bbf7b90))
* fixing typos ([dd7369d](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/dd7369dcc1e94a658f8f58d1b7408ced79674802))
* move maintainer TODO notes into README comments ([24bc397](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/24bc39757b5b70f37f541f4b767d5585bb0ae471))
* overhaul documentation and add first-run tutorial ([513d422](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/513d422a03265711d0511b8d74967e40147736db))
* updated filenames and locations to align more closely with Diataxis framework ([f20bbbc](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/f20bbbcfa54e7e40d6f900e7e76a9b08624b0aec))


### Refactoring

* **ci:** use release-please outputs for major-tag update ([66e548a](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/66e548a5d5751c39f89e0330337b7a2e4732ce75))
* enhance workflow_dispatch inputs for move-major-tag and update-tf-modules workflows ([537e05f](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/537e05fc8dddae83eba069722728a242fbcef0e3))
* **logging:** migrate log.py to stdlib logging, update tests to caplog ([9124e60](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/9124e607bffcb12214f15214a780472f670b0276))
* **logging:** replace package print statements with module-level loggers ([6fccf7d](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/6fccf7db3117fbd94bf83ffe23fcba900967e639))
* **logging:** replace package print statements with module-level… ([f552bb7](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/f552bb78ae1e509d53a7a82b95d7d8f82522972a))
* **logging:** use standard module loggers and remove wrapper ([1d8a2cd](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/1d8a2cd95dec380a2c62fc164d7aa1901c00dde4))
* remove redundant error block ([7bb9369](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/7bb9369bebfc7af3d903fd522bece59052be4619))
* simplify workflow_dispatch inputs and use environment variables ([9e32e9e](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/9e32e9e0826f46f6e3bbb2c612bdb875fd15aa94))
* simplify workflow_dispatch inputs for move-major-tag workflow ([cd5e895](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/cd5e8951758c05d8340e19bca68d2ee007856c54))
* simplifying validation and updating types ([dc80d32](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/dc80d3265a2691caa8eb967a7fc17e0d0e1b6f45))
* splitting module updater into package structure ([8d8d2ad](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/8d8d2ad1d11ff283d3419b08a0782bd93412666a))
* update permissions structure across workflows for clarity and security ([01ee76e](https://github.com/uk-gov-mirror/datasciencecampus.update-tf-modules/commit/01ee76e8ee58794a8bb841af96734be45c90070e))

## [0.4.1](https://github.com/datasciencecampus/update-tf-modules/compare/v0.4.0...v0.4.1) (2026-10-13)


### Bug Fixes

* clarify permissions comment in reusable workflow contract ([9c4c84d](https://github.com/datasciencecampus/update-tf-modules/commit/9c4c84de0097b9cdb7eb8b27798f8edfaee7acee))
* remove redundant error table for permissions in troubleshooting guide ([4669c60](https://github.com/datasciencecampus/update-tf-modules/commit/4669c60097e056f9fc47f87d09c65c78d82d4f56))
* tighten controls around who can access the GITHUB_TOKEN ([fc9348c](https://github.com/datasciencecampus/update-tf-modules/commit/fc9348ccd1f93d10b470d2745ffe30417b78e7d6))

## [0.4.0](https://github.com/datasciencecampus/update-tf-modules/compare/v0.3.0...v0.4.0) (2026-09-24)


### Features

* add security analysis workflow and configuration files ([c05ffd6](https://github.com/datasciencecampus/update-tf-modules/commit/c05ffd699bbf70a6bbf1cf8b45994f697b150bb6))


### Bug Fixes

* correct permissions structure in move-major-tag workflow ([20b4791](https://github.com/datasciencecampus/update-tf-modules/commit/20b4791e9195a0537042ada408a874841b14b6f5))


### Refactoring

* enhance workflow_dispatch inputs for move-major-tag and update-tf-modules workflows ([537e05f](https://github.com/datasciencecampus/update-tf-modules/commit/537e05fc8dddae83eba069722728a242fbcef0e3))
* simplify workflow_dispatch inputs and use environment variables ([9e32e9e](https://github.com/datasciencecampus/update-tf-modules/commit/9e32e9e0826f46f6e3bbb2c612bdb875fd15aa94))
* simplify workflow_dispatch inputs for move-major-tag workflow ([cd5e895](https://github.com/datasciencecampus/update-tf-modules/commit/cd5e8951758c05d8340e19bca68d2ee007856c54))
* update permissions structure across workflows for clarity and security ([01ee76e](https://github.com/datasciencecampus/update-tf-modules/commit/01ee76e8ee58794a8bb841af96734be45c90070e))

## [0.3.0](https://github.com/datasciencecampus/update-tf-modules/compare/v0.2.1...v0.3.0) (2026-09-08)


### Features

* resolve updater_ref to commit SHA for reproducibility ([cadf084](https://github.com/datasciencecampus/update-tf-modules/commit/cadf08432f63ba3127535adcfbfba8d49ac730d4))


### Bug Fixes

* **ci:** incorporate moving major tag as a step in release pipeline ([30d45f6](https://github.com/datasciencecampus/update-tf-modules/commit/30d45f6e4a58d39613fd63bdc8253a8d6f3ead5c))
* **ci:** skip major-tag push when already up to date ([8cadcc9](https://github.com/datasciencecampus/update-tf-modules/commit/8cadcc9150069c8596f268b96d2798f0947513ca))
* ensure major release tags (vX) are reliably moved on publish ([eee0bd5](https://github.com/datasciencecampus/update-tf-modules/commit/eee0bd597db0f7cec1e1795f485e4b30c6296366))


### Documentation

* add major-tag verification guidance ([9da2d33](https://github.com/datasciencecampus/update-tf-modules/commit/9da2d33c68c42064dbf0875c4174ebc815c7e00e))


### Refactoring

* **ci:** use release-please outputs for major-tag update ([66e548a](https://github.com/datasciencecampus/update-tf-modules/commit/66e548a5d5751c39f89e0330337b7a2e4732ce75))

## [0.2.1](https://github.com/datasciencecampus/update-tf-modules/compare/v0.2.0...v0.2.1) (2026-09-03)


### Refactoring

* **logging:** replace package print statements with module-level… ([f552bb7](https://github.com/datasciencecampus/update-tf-modules/commit/f552bb78ae1e509d53a7a82b95d7d8f82522972a))

## [0.2.0](https://github.com/datasciencecampus/update-tf-modules/compare/v0.1.1...v0.2.0) (2026-08-26)


### Features

* **logging:** add ModuleOutcome dataclass and run summary ([9864042](https://github.com/datasciencecampus/update-tf-modules/commit/986404235003d7de4fb4f94437506c69bcee84d3))
* **logging:** add per-module progress and outcome messages ([3948693](https://github.com/datasciencecampus/update-tf-modules/commit/39486936b29ebbb10e76bd039a521eacc9dc5458))
* **logging:** add structured lifecycle output ([00aabce](https://github.com/datasciencecampus/update-tf-modules/commit/00aabce0fbfdb187a6317b079f89acb721477116))
* **logging:** add structured progress output and stdlib logging ([dcb72e5](https://github.com/datasciencecampus/update-tf-modules/commit/dcb72e5b76ac4c6c97a6afa59d8bf47c7a4d0e98))
* **logging:** add zero-replacement cause hints for unchanged modules ([b421f6b](https://github.com/datasciencecampus/update-tf-modules/commit/b421f6b9d15ce4f471c0e6ea627492651701bcec))


### Bug Fixes

* **ci:** default updater_ref to v0, preflight-validate ref, and align docs ([0228310](https://github.com/datasciencecampus/update-tf-modules/commit/0228310094da6382adf8f5f22de2a66cbec75773))
* **updaters:** count only actual module source changes ([e3ff9f5](https://github.com/datasciencecampus/update-tf-modules/commit/e3ff9f5abfcd04132f75e9090d6fb13636cdf7fd))
* **workflow:** default updater_ref to v0 and validate ref before checkout ([48d5306](https://github.com/datasciencecampus/update-tf-modules/commit/48d530674048806f4e824ce3b6229318e5d3e069))


### Refactoring

* **logging:** migrate log.py to stdlib logging, update tests to caplog ([9124e60](https://github.com/datasciencecampus/update-tf-modules/commit/9124e607bffcb12214f15214a780472f670b0276))
* **logging:** use standard module loggers and remove wrapper ([1d8a2cd](https://github.com/datasciencecampus/update-tf-modules/commit/1d8a2cd95dec380a2c62fc164d7aa1901c00dde4))

## [0.1.1](https://github.com/datasciencecampus/update-tf-modules/compare/v0.1.0...v0.1.1) (2026-06-17)


### Documentation

* clarify release tag semantics and mutability policy ([35e3e2a](https://github.com/datasciencecampus/update-tf-modules/commit/35e3e2a082c30168e941fd00d78952493bbf7b90))
