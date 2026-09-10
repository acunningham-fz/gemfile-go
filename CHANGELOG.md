# Changelog

## Unreleased

### Features


## [0.15.0](https://github.com/acunningham-fz/gemfile-go/compare/v0.15.0...v0.15.0) (2026-09-10)


### Features

* ✨ support `eval_gemfile` macro for modular Gemfiles ([a489eb9](https://github.com/acunningham-fz/gemfile-go/commit/a489eb9e1f0376d0348a4fc7bde0173a25169e7d))
* ✨ support hash 🚀 syntax in gemfiles and gemspecs ([a120bcc](https://github.com/acunningham-fz/gemfile-go/commit/a120bcc01003c8e087c053dca2a5dfd50888f262))
* ✨ support hash 🚀 syntax in gemfiles and gemspecs ([d8f48ee](https://github.com/acunningham-fz/gemfile-go/commit/d8f48eef4ae5bfd3da4113346856133b61a0f1e9))
* ✨ support single group and platform values ([89c9ea4](https://github.com/acunningham-fz/gemfile-go/commit/89c9ea44c90cf7bf5cbeedb3969e5647fcf2c598))
* ✨ support single group and platform values ([c4ab169](https://github.com/acunningham-fz/gemfile-go/commit/c4ab1694953ad0e24b2affe21557993bf13a8c59))
* add Gemfile.lock writer implementation ([#5](https://github.com/acunningham-fz/gemfile-go/issues/5)) ([c5c31e2](https://github.com/acunningham-fz/gemfile-go/commit/c5c31e21918d10a79e392adca8f773fbdc59858f))
* add gemspec directive support ([#5](https://github.com/acunningham-fz/gemfile-go/issues/5)) ([#6](https://github.com/acunningham-fz/gemfile-go/issues/6)) ([ecfd4bf](https://github.com/acunningham-fz/gemfile-go/commit/ecfd4bf082ecd054b096fcd4f978290c832bbf9d))
* add platform support to Gemfile parser ([98a7f01](https://github.com/acunningham-fz/gemfile-go/commit/98a7f012c2e8119fc05f0cd27ae5741932f31d01))
* add PostInstallMessage field to GemspecFile ([a62fb45](https://github.com/acunningham-fz/gemfile-go/commit/a62fb458360b5854bcef167eaec1abf2c5391a84))
* add real-world benchmark with actual Gemfile ([a01f795](https://github.com/acunningham-fz/gemfile-go/commit/a01f7950b92faf4696799f19e99d64c836340a2d))
* add variable assignment support and fix lint issues ([1450caf](https://github.com/acunningham-fz/gemfile-go/commit/1450caff9f909305e1512f1e4313d8cb23f9029d))
* Enhance Ruby logic support in Gemfiles ([1808d5e](https://github.com/acunningham-fz/gemfile-go/commit/1808d5e7689fc6eb340d74538151bd3444a7c481))
* improve if/unless detection to avoid false positives from comments/strings ([415474f](https://github.com/acunningham-fz/gemfile-go/commit/415474f59ebbf74238e5dc5a3f0c523fd3521662))
* make filePath parameter optional for backwards compatibility ([fd0fd76](https://github.com/acunningham-fz/gemfile-go/commit/fd0fd76bfd0efc3bea657a4e1995a84c8ac78cbd))
* normalize Bundler output with bundler 4 ([#9](https://github.com/acunningham-fz/gemfile-go/issues/9)) ([965b818](https://github.com/acunningham-fz/gemfile-go/commit/965b81879414ddacd7063189ef57d9149ef7db06))
* normalize relative path sources in tree-sitter parser ([aa71e54](https://github.com/acunningham-fz/gemfile-go/commit/aa71e5474363e05aa9983ff10685445a36b4c777))
* raise error on RUBY_VERSION/RUBY_ENGINE conditions instead of logging ([8961a14](https://github.com/acunningham-fz/gemfile-go/commit/8961a14ddb9e35b9140317a212ad917ccbd71cc6))
* refactor Gemfile parser with tree-sitter AST parsing ([d1e45bf](https://github.com/acunningham-fz/gemfile-go/commit/d1e45bf66ac998834df1bf470447f70d7e9d7361))
* support Appraisal flows ([#16](https://github.com/acunningham-fz/gemfile-go/issues/16)) ([25eb8c3](https://github.com/acunningham-fz/gemfile-go/commit/25eb8c31a58863a5211973acd0f46c726354e143))
* support new gemlock stucture ([#8](https://github.com/acunningham-fz/gemfile-go/issues/8)) ([e81c160](https://github.com/acunningham-fz/gemfile-go/commit/e81c160d2b70d6ebcfdb669bb794b96aae35b9e1))


### Bug Fixes

* ✨ Add back Gemfile parsing, retaining new features of v0.14.0 ([4b9b9de](https://github.com/acunningham-fz/gemfile-go/commit/4b9b9ded8e67e84e8bdc4a6c5669612e2b74f1e0))
* 🐛 release workflow: Use proper `/v2/` in path to `golangci-lint` in `magefile.go` ([daa2e69](https://github.com/acunningham-fz/gemfile-go/commit/daa2e6961e2c2d3272218f47449c58b2e275c81d))
* 🐛 release workflow: Use proper `/v2/` in path to `golangci-lint`… ([e85f354](https://github.com/acunningham-fz/gemfile-go/commit/e85f3549e3d2f625c9060e666a37dab377fceaba))
* Add back Gemfile parsing ([8db0815](https://github.com/acunningham-fz/gemfile-go/commit/8db08155578b90025987ef3478299b24337da948))
* add testdata for examples and tests ([1fa99b4](https://github.com/acunningham-fz/gemfile-go/commit/1fa99b404f701b0c8d622aa62f343949d5995866))
* correct indentation in test function ([14a4030](https://github.com/acunningham-fz/gemfile-go/commit/14a403071a763580a3545f97a6991b063b4cbc60))
* correct test paths and add missing fixtures ([0ffa08b](https://github.com/acunningham-fz/gemfile-go/commit/0ffa08b19d7f9681206e302eb38e0d051e7499ef))
* dedup should not remove ruby ([e087caa](https://github.com/acunningham-fz/gemfile-go/commit/e087caa5ff21d1b967be5928f76168fa37c52198))
* handle Env with the parser ([d9c30aa](https://github.com/acunningham-fz/gemfile-go/commit/d9c30aa7c279b3ffb55c266b934891c1953a0c91))
* normalize gnu/musl ([b7d138c](https://github.com/acunningham-fz/gemfile-go/commit/b7d138c8d577eefb161f94e24f8153a3f3ce4a3d))
* relative path resolution in eval_gemfile to match Bundler behavior ([4b3be71](https://github.com/acunningham-fz/gemfile-go/commit/4b3be71cf7038ddfbf3730affdaf850e45108a10))
* remove debug logging from parser ([34a3307](https://github.com/acunningham-fz/gemfile-go/commit/34a3307e2641f88a53d58e06025e420fe7649483))
* Remove ENV value logging to prevent secret leakage in CI logs ([ea3e573](https://github.com/acunningham-fz/gemfile-go/commit/ea3e57340535b874504240fbca2b823f488b44f2))
* remove matrix from CI workflow ([0541f15](https://github.com/acunningham-fz/gemfile-go/commit/0541f15d994b48475fd6b17292e6f087d12b3f0f))
* resolve all golangci-lint issues ([#2](https://github.com/acunningham-fz/gemfile-go/issues/2)) ([9d654b1](https://github.com/acunningham-fz/gemfile-go/commit/9d654b183aa4a51ed6e7d214f13de875d7e2e7a2))
* update CI to use golangci-lint v2 ([#3](https://github.com/acunningham-fz/gemfile-go/issues/3)) ([a946468](https://github.com/acunningham-fz/gemfile-go/commit/a9464686ed7d1a02a73b3606c02a347cb767a657))
* update go version to 1.25 and use go-version-file in CI ([e4271dc](https://github.com/acunningham-fz/gemfile-go/commit/e4271dca8c8b6c00d5dcb5af668f5068a079e86b))
* update golangci-lint to v2 ([#14](https://github.com/acunningham-fz/gemfile-go/issues/14)) ([2db2e36](https://github.com/acunningham-fz/gemfile-go/commit/2db2e3665f88feeba88b8f7c9b46097b7de3bcdb))
* update golangci-lint to v2 in pre-commit config ([6298a7d](https://github.com/acunningham-fz/gemfile-go/commit/6298a7d53e3662a0d28973429a6743318a81e09f))
* update tests with real-world data ([ea9aa41](https://github.com/acunningham-fz/gemfile-go/commit/ea9aa419d0b2e996630ea6d713678f21cf0b9882))


### Miscellaneous Chores

* release 0.15.0 ([8db0815](https://github.com/acunningham-fz/gemfile-go/commit/8db08155578b90025987ef3478299b24337da948))

## [0.15.0](https://github.com/contriboss/gemfile-go/compare/v0.12.0...v0.15.0) (2026-02-16)


### Bug Fixes

* ✨ Add back Gemfile parsing, retaining new features of v0.14.0 ([4b9b9de](https://github.com/contriboss/gemfile-go/commit/4b9b9ded8e67e84e8bdc4a6c5669612e2b74f1e0))
* Add back Gemfile parsing ([8db0815](https://github.com/contriboss/gemfile-go/commit/8db08155578b90025987ef3478299b24337da948))


### Miscellaneous Chores

* release 0.15.0 ([8db0815](https://github.com/contriboss/gemfile-go/commit/8db08155578b90025987ef3478299b24337da948))

## [0.14.0](https://github.com/contriboss/gemfile-go/compare/v0.13.0...v0.14.0) (2026-02-15)


### Features

* ✨ Soft & Hard APIs ([16a8c56](https://github.com/contriboss/gemfile-go/commit/16a8c56cf414837a0d352ce29191c8082ebbb84b))

### Bug Fixes

* Raise errors when lockfiles are missing or invalid instead of invoking bundler
* Never install gems - remain read-only

## [0.13.0](https://github.com/contriboss/gemfile-go/compare/v0.12.0...v0.13.0) (2026-02-15)


### Features

* Fallback to bundle install when lockfile is missing ([0232609](https://github.com/contriboss/gemfile-go/commit/023260960b8958ec083b505ae0d4b5b99671f348))


### Miscellaneous Chores

* release 0.13.0 ([0232609](https://github.com/contriboss/gemfile-go/commit/023260960b8958ec083b505ae0d4b5b99671f348))

## [0.12.0](https://github.com/contriboss/gemfile-go/compare/v0.11.0...v0.12.0) (2026-02-14)


### Features

* Enhance Ruby logic support in Gemfiles ([1808d5e](https://github.com/contriboss/gemfile-go/commit/1808d5e7689fc6eb340d74538151bd3444a7c481))
* improve if/unless detection to avoid false positives from comments/strings ([415474f](https://github.com/contriboss/gemfile-go/commit/415474f59ebbf74238e5dc5a3f0c523fd3521662))
* make filePath parameter optional for backwards compatibility ([fd0fd76](https://github.com/contriboss/gemfile-go/commit/fd0fd76bfd0efc3bea657a4e1995a84c8ac78cbd))
* normalize relative path sources in tree-sitter parser ([aa71e54](https://github.com/contriboss/gemfile-go/commit/aa71e5474363e05aa9983ff10685445a36b4c777))
* raise error on RUBY_VERSION/RUBY_ENGINE conditions instead of logging ([8961a14](https://github.com/contriboss/gemfile-go/commit/8961a14ddb9e35b9140317a212ad917ccbd71cc6))


### Bug Fixes

* correct indentation in test function ([14a4030](https://github.com/contriboss/gemfile-go/commit/14a403071a763580a3545f97a6991b063b4cbc60))
* relative path resolution in eval_gemfile to match Bundler behavior ([4b3be71](https://github.com/contriboss/gemfile-go/commit/4b3be71cf7038ddfbf3730affdaf850e45108a10))
* ensure `gemspec` and `path:` sources are resolved relative to the Gemfile they are defined in
* Remove ENV value logging to prevent secret leakage in CI logs ([ea3e573](https://github.com/contriboss/gemfile-go/commit/ea3e57340535b874504240fbca2b823f488b44f2))

## [0.11.0](https://github.com/contriboss/gemfile-go/compare/v0.10.0...v0.11.0) (2026-02-11)

### Features

* ✨ support `eval_gemfile` macro for modular Gemfiles ([a489eb9](https://github.com/contriboss/gemfile-go/commit/a489eb9e1f0376d0348a4fc7bde0173a25169e7d))

## [0.10.0](https://github.com/contriboss/gemfile-go/compare/v0.9.0...v0.10.0) (2026-02-08)

### Features

* support single group and platform values (e.g., `group: :test` or `platform: :mri`) ([c4ab169](https://github.com/contriboss/gemfile-go/commit/c4ab1694953ad0e24b2affe21557993bf13a8c59))

### Bug Fixes

* `release` workflow: Use proper `/v2/` in path to `golangci-lint` in `magefile.go`

## [0.9.0](https://github.com/contriboss/gemfile-go/compare/v0.8.0...v0.9.0) (2026-02-08)


### Features

* ✨ support hash 🚀 syntax in gemfiles and gemspecs ([d8f48ee](https://github.com/contriboss/gemfile-go/commit/d8f48eef4ae5bfd3da4113346856133b61a0f1e9))

### Bug Fixes

* support hash rocket syntax for gem and gemspec options
* improve group parsing to handle comments and trailing tokens correctly
* improve version constraint extraction to correctly handle hash rocket and symbolized hash options

## [0.8.0](https://github.com/contriboss/gemfile-go/compare/v0.7.3...v0.8.0) (2026-01-22)


### Features

* support Appraisal flows ([#16](https://github.com/contriboss/gemfile-go/issues/16)) ([25eb8c3](https://github.com/contriboss/gemfile-go/commit/25eb8c31a58863a5211973acd0f46c726354e143))


### Bug Fixes

* update golangci-lint to v2 ([#14](https://github.com/contriboss/gemfile-go/issues/14)) ([2db2e36](https://github.com/contriboss/gemfile-go/commit/2db2e3665f88feeba88b8f7c9b46097b7de3bcdb))

## [0.7.3](https://github.com/contriboss/gemfile-go/compare/v0.7.2...v0.7.3) (2026-01-19)


### Bug Fixes

* handle Env with the parser ([d9c30aa](https://github.com/contriboss/gemfile-go/commit/d9c30aa7c279b3ffb55c266b934891c1953a0c91))

## [0.7.2](https://github.com/contriboss/gemfile-go/compare/v0.7.1...v0.7.2) (2026-01-13)


### Bug Fixes

* dedup should not remove ruby ([e087caa](https://github.com/contriboss/gemfile-go/commit/e087caa5ff21d1b967be5928f76168fa37c52198))

## [0.7.1](https://github.com/contriboss/gemfile-go/compare/v0.7.0...v0.7.1) (2026-01-13)


### Bug Fixes

* normalize gnu/musl ([b7d138c](https://github.com/contriboss/gemfile-go/commit/b7d138c8d577eefb161f94e24f8153a3f3ce4a3d))

## [0.7.0](https://github.com/contriboss/gemfile-go/compare/v0.6.0...v0.7.0) (2026-01-13)


### Features

* normalize Bundler output with bundler 4 ([#9](https://github.com/contriboss/gemfile-go/issues/9)) ([965b818](https://github.com/contriboss/gemfile-go/commit/965b81879414ddacd7063189ef57d9149ef7db06))

## [0.6.0](https://github.com/contriboss/gemfile-go/compare/v0.5.1...v0.6.0) (2026-01-04)


### Features

* support new gemlock stucture ([#8](https://github.com/contriboss/gemfile-go/issues/8)) ([e81c160](https://github.com/contriboss/gemfile-go/commit/e81c160d2b70d6ebcfdb669bb794b96aae35b9e1))
