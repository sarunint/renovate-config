# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [6.3.1](https://github.com/sarunint/renovate-config/compare/v6.3.0...v6.3.1) (2021-02-26)


### Bug Fixes

* use new template variables ([1dfb70f](https://github.com/sarunint/renovate-config/commit/1dfb70f335eb8823c6104957f1ac2a98bb5204df))
* use snake-case for Angular CLI options ([1a84fdd](https://github.com/sarunint/renovate-config/commit/1a84fddf8f2ba0b08e195c0ca4051c66452019f5))

## [6.3.0](https://github.com/sarunint/renovate-config/compare/v6.2.2...v6.3.0) (2021-02-26)


### Features

* allow @types/node@^14 ([21208db](https://github.com/sarunint/renovate-config/commit/21208dbfdac50d3e22d61950c1a0ba95eeb05b85))

### [6.2.2](https://github.com/sarunint/renovate-config/compare/v6.2.1...v6.2.2) (2020-11-27)


### Bug Fixes

* run migrations only on version updates ([dd37d6d](https://github.com/sarunint/renovate-config/commit/dd37d6d9b3dfe5dfe69079d4e1dce85a7a377860))

### [6.2.1](https://github.com/sarunint/renovate-config/compare/v6.2.0...v6.2.1) (2020-11-15)


### Bug Fixes

* do not separate major and minor releases for Angular ([3235766](https://github.com/sarunint/renovate-config/commit/3235766c180e9dea163c63feacd1a011cc4382a0))

## [6.2.0](https://github.com/sarunint/renovate-config/compare/v6.1.0...v6.2.0) (2020-11-14)


### Features

* group Angular and Angular CLI update together ([09509a3](https://github.com/sarunint/renovate-config/commit/09509a34f8fccb897374cb3194ee4904914e53bb))

## [6.1.0](https://github.com/sarunint/renovate-config/compare/v6.0.0...v6.1.0) (2020-11-14)


### Features

* add post-upgrade commands for `angular-v11` ([97c746b](https://github.com/sarunint/renovate-config/commit/97c746b0361f0a9f0d35372fd179258e63a081c7))

## [6.0.0](https://github.com/sarunint/renovate-config/compare/v5.0.0...v6.0.0) (2020-11-13)


### ⚠ BREAKING CHANGES

* `angular` now extends `angular-v11`
* `angular-v9` preset is no longer available

### Features

* add `angular-v11` preset ([56a2599](https://github.com/sarunint/renovate-config/commit/56a2599f93853cf3642f81ca58c28b7db5dc3620))
* change `angular` preset to extend `angular-v11` ([2843360](https://github.com/sarunint/renovate-config/commit/2843360c50b2cb7ff3a8a6b9ed037e7a6bd2398c))
* remove `angular-v9` preset ([d62e3f6](https://github.com/sarunint/renovate-config/commit/d62e3f6dca1623cfede80d425bb1efbb8a7a6521))

## [5.0.0](https://github.com/sarunint/renovate-config/compare/v4.1.0...v5.0.0) (2020-11-01)


### ⚠ BREAKING CHANGES

* NestJS monprepo no longer uses custom configuration.

### Features

* use Renovate's internal NestJS monorepo ([8c669a6](https://github.com/sarunint/renovate-config/commit/8c669a6ee7a5190b567c3347d7206f4e79a6221c))

## [4.1.0](https://github.com/sarunint/renovate-config/compare/v4.0.0...v4.1.0) (2020-11-01)


### Features

* expand TypeScript version for Angular v10 preset to < 4.1 ([79cc21a](https://github.com/sarunint/renovate-config/commit/79cc21a7e302810cb85990414615e20b07dcee91))

## [4.0.0](https://github.com/sarunint/renovate-config/compare/v3.1.0...v4.0.0) (2020-06-25)


### ⚠ BREAKING CHANGES

* Preset `angular-v8` is no longer available.

### Features

* add `angular-v10` preset ([0dcf7c4](https://github.com/sarunint/renovate-config/commit/0dcf7c48a1cc82fb39ab257c39b77824ec9b4426))
* fix `@types/node` to v12 ([c345e9c](https://github.com/sarunint/renovate-config/commit/c345e9c339c941197bacc60e99cffd60f1dd866b))
* remove `angular-v8` preset ([6794bd1](https://github.com/sarunint/renovate-config/commit/6794bd1bbe5291fccba9707ac042520895fa0e30))

## [3.1.0](https://github.com/sarunint/renovate-config/compare/v3.0.2...v3.1.0) (2020-04-10)


### Features

* expand TypeScript version for Angular v9 preset to < 3.9 ([7090fda](https://github.com/sarunint/renovate-config/commit/7090fdab6705ded246b61bb019a24f6a0ee6b031))

### [3.0.2](https://github.com/sarunint/renovate-config/compare/v3.0.1...v3.0.2) (2020-02-16)


### Bug Fixes

* change `extends` to be an array ([b13569b](https://github.com/sarunint/renovate-config/commit/b13569b35fd0c8df57d5c2d8a04541a06f9a943a))

### [3.0.1](https://github.com/sarunint/renovate-config/compare/v3.0.0...v3.0.1) (2020-02-07)


### Bug Fixes

* **angular:** fix misspelled angularcli ([d23a2e0](https://github.com/sarunint/renovate-config/commit/d23a2e0a53d65b9ba0b6ac1bd363e5314bc6354a))

## [3.0.0](https://github.com/sarunint/renovate-config/compare/v2.1.1...v3.0.0) (2020-02-07)


### ⚠ BREAKING CHANGES

* **angular:** The `angular` preset will now update Angular packages to be compatible with Angular v9. If you want to remain with v8, use `angular-v8` preset instead.

### Features

* **angular:** update for Angular v9 ([015e589](https://github.com/sarunint/renovate-config/commit/015e589a56b629131cc90454bf4a5efbfd550a20))

### [2.1.1](https://github.com/sarunint/renovate-config/compare/v2.1.0...v2.1.1) (2020-02-07)


### Bug Fixes

* **angular:** fix the misspelled package name ([706f972](https://github.com/sarunint/renovate-config/commit/706f972276efc00419638b4d91759cbc64aaa2b9))

## [2.1.0](https://github.com/sarunint/renovate-config/compare/v2.0.0...v2.1.0) (2020-02-07)


### Features

* **angular:** restrict Angular CLI packages that hasn't reached 1.0.0 yet ([c5cc5d8](https://github.com/sarunint/renovate-config/commit/c5cc5d81420b6935d80b81c243345b630b48ce02))

## [2.0.0](https://github.com/sarunint/renovate-config/compare/v1.2.1...v2.0.0) (2019-09-29)


### ⚠ BREAKING CHANGES

* Lock file maintenance are now automatically merged, if the bot has merge permission.

### Features

* automerge lock file maintenances ([1e160d1](https://github.com/sarunint/renovate-config/commit/1e160d1))

### [1.2.1](https://github.com/sarunint/renovate-config/compare/v1.2.0...v1.2.1) (2019-09-01)


### Bug Fixes

* change errorneous `allowedVersion` to `allowedVersions` ([6476036](https://github.com/sarunint/renovate-config/commit/6476036))



## [1.2.0](https://github.com/sarunint/renovate-config/compare/v1.0.0...v1.2.0) (2019-08-02)


### Bug Fixes

* change allowedVersion to allowedVersions ([46dec31](https://github.com/sarunint/renovate-config/commit/46dec31))


### Features

* expand TypeScript version range ([5c8756b](https://github.com/sarunint/renovate-config/commit/5c8756b))
* extend TypeScript version ([f2355f3](https://github.com/sarunint/renovate-config/commit/f2355f3))



## [1.1.0](https://github.com/sarunint/renovate-config/compare/v1.0.1...v1.1.0) (2019-05-29)


### Features

* expand TypeScript version range ([5c8756b](https://github.com/sarunint/renovate-config/commit/5c8756b))



### [1.0.1](https://github.com/sarunint/renovate-config/compare/v1.0.0...v1.0.1) (2019-05-29)


### Bug Fixes

* change allowedVersion to allowedVersions ([46dec31](https://github.com/sarunint/renovate-config/commit/46dec31))



## 1.0.0 (2019-05-26)
