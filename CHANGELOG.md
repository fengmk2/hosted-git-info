# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="2.8.0"></a>
# [2.8.0](https://github.com/npm/hosted-git-info/compare/v2.7.1...v2.8.0) (2019-08-05)


### Bug Fixes

* Allow slashes in gitlab project section ([bbcf7b2](https://github.com/npm/hosted-git-info/commit/bbcf7b2)), closes [#46](https://github.com/npm/hosted-git-info/issues/46) [#43](https://github.com/npm/hosted-git-info/issues/43)
* **git-host:** disallow URI-encoded slash (%2F) in `path` ([3776fa5](https://github.com/npm/hosted-git-info/commit/3776fa5)), closes [#44](https://github.com/npm/hosted-git-info/issues/44)
* **gitlab:** Do not URL encode slashes in project name for GitLab https URL ([cbf04f9](https://github.com/npm/hosted-git-info/commit/cbf04f9)), closes [#47](https://github.com/npm/hosted-git-info/issues/47)
* do not allow invalid gist urls ([d5cf830](https://github.com/npm/hosted-git-info/commit/d5cf830))
* **cache:** Switch to lru-cache to save ourselves from unlimited memory consumption ([e518222](https://github.com/npm/hosted-git-info/commit/e518222)), closes [#38](https://github.com/npm/hosted-git-info/issues/38)


### Features

* give these objects a name ([60abaea](https://github.com/npm/hosted-git-info/commit/60abaea))



<a name="2.7.1"></a>
## [2.7.1](https://github.com/npm/hosted-git-info/compare/v2.7.0...v2.7.1) (2018-07-07)


### Bug Fixes

* **index:** Guard against non-string types ([5bc580d](https://github.com/npm/hosted-git-info/commit/5bc580d))
* **parse:** Crash on strings that parse to having no host ([c931482](https://github.com/npm/hosted-git-info/commit/c931482)), closes [#35](https://github.com/npm/hosted-git-info/issues/35)



<a name="2.7.0"></a>
# [2.7.0](https://github.com/npm/hosted-git-info/compare/v2.6.1...v2.7.0) (2018-07-06)


### Bug Fixes

* **github tarball:** update github tarballtemplate ([6efd582](https://github.com/npm/hosted-git-info/commit/6efd582)), closes [#34](https://github.com/npm/hosted-git-info/issues/34)
* **gitlab docs:** switched to lowercase anchors for readmes ([701bcd1](https://github.com/npm/hosted-git-info/commit/701bcd1))


### Features

* **all:** Support www. prefixes on hostnames ([3349575](https://github.com/npm/hosted-git-info/commit/3349575)), closes [#32](https://github.com/npm/hosted-git-info/issues/32)



<a name="2.6.1"></a>
## [2.6.1](https://github.com/npm/hosted-git-info/compare/v2.6.0...v2.6.1) (2018-06-25)

### Bug Fixes

* **Revert:** "compat: remove Object.assign fallback ([#25](https://github.com/npm/hosted-git-info/issues/25))" ([cce5a62](https://github.com/npm/hosted-git-info/commit/cce5a62))
* **Revert:** "git-host: fix forgotten extend()" ([a815ec9](https://github.com/npm/hosted-git-info/commit/a815ec9))



<a name="2.6.0"></a>
# [2.6.0](https://github.com/npm/hosted-git-info/compare/v2.5.0...v2.6.0) (2018-03-07)


### Bug Fixes

* **compat:** remove Object.assign fallback ([#25](https://github.com/npm/hosted-git-info/issues/25)) ([627ab55](https://github.com/npm/hosted-git-info/commit/627ab55))
* **git-host:** fix forgotten extend() ([eba1f7b](https://github.com/npm/hosted-git-info/commit/eba1f7b))


### Features

* **browse:** fragment support for browse() ([#28](https://github.com/npm/hosted-git-info/issues/28)) ([cd5e5bb](https://github.com/npm/hosted-git-info/commit/cd5e5bb))
