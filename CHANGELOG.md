# [7.3.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v7.2.0...v7.3.0) (2023-07-12)


### Bug Fixes

* yaml parsing build_image_version default as double ([df23a73](https://github.com/react-native-community/react-native-circleci-orb/commit/df23a73))
* yaml parsing build_image_version default as double ([#170](https://github.com/react-native-community/react-native-circleci-orb/issues/170)) ([3c8cb0f](https://github.com/react-native-community/react-native-circleci-orb/commit/3c8cb0f))


### Features

* allow specifying build image version for android build & executor ([ee50537](https://github.com/react-native-community/react-native-circleci-orb/commit/ee50537))

# [7.2.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v7.1.1...v7.2.0) (2023-07-11)


### Features

* Skip Detox setup in ios_build job ([3fc5c53](https://github.com/react-native-community/react-native-circleci-orb/commit/3fc5c53))

## [7.1.1](https://github.com/react-native-community/react-native-circleci-orb/compare/v7.1.0...v7.1.1) (2022-08-03)


### Bug Fixes

* update XCode version to 12.5.1 ([#158](https://github.com/react-native-community/react-native-circleci-orb/issues/158)) ([4bbdb75](https://github.com/react-native-community/react-native-circleci-orb/commit/4bbdb75))

# [7.1.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v7.0.1...v7.1.0) (2022-06-18)


### Bug Fixes

* **android_test:** node v12 to v16 ([a9956b7](https://github.com/react-native-community/react-native-circleci-orb/commit/a9956b7))
* **ios_build:** node v12 to v16 ([f0ea6b4](https://github.com/react-native-community/react-native-circleci-orb/commit/f0ea6b4))
* **ios_build_and_test:** node v12 to v16 ([6347597](https://github.com/react-native-community/react-native-circleci-orb/commit/6347597))
* **setup_macos_executor:** bump node v12 to v16 ([a34ccec](https://github.com/react-native-community/react-native-circleci-orb/commit/a34ccec))


### Features

* **node:** bump from node 12 to node 16 default ([0acc6f9](https://github.com/react-native-community/react-native-circleci-orb/commit/0acc6f9))

## [7.0.1](https://github.com/react-native-community/react-native-circleci-orb/compare/v7.0.0...v7.0.1) (2022-06-10)


### Bug Fixes

* 'an unexpected storage error occurred' on multiline keys ([b9fb1bb](https://github.com/react-native-community/react-native-circleci-orb/commit/b9fb1bb))

# [7.0.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v6.8.1...v7.0.0) (2022-04-26)


### Bug Fixes

* removing old yarn version from PATH which hopefully fixes the issue ([cc25fff](https://github.com/react-native-community/react-native-circleci-orb/commit/cc25fff))


* fix!: using supported Node version with cimg/node and updating comments ([1186c41](https://github.com/react-native-community/react-native-circleci-orb/commit/1186c41))


### BREAKING CHANGES

* cimg/node doesn't support major Node version aliases the same way circleci/node did

## [6.8.1](https://github.com/react-native-community/react-native-circleci-orb/compare/v6.8.0...v6.8.1) (2022-02-27)


### Bug Fixes

* add missing CACHE_VERSION in pod_install ([b6c7e99](https://github.com/react-native-community/react-native-circleci-orb/commit/b6c7e99))
* quote cache keys that start with special characters ([b217d8c](https://github.com/react-native-community/react-native-circleci-orb/commit/b217d8c))

# [6.8.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v6.7.0...v6.8.0) (2022-02-15)


### Features

* allow passing executor parameters to test jobs ([#141](https://github.com/react-native-community/react-native-circleci-orb/issues/141)) ([eea6098](https://github.com/react-native-community/react-native-circleci-orb/commit/eea6098)), closes [#112](https://github.com/react-native-community/react-native-circleci-orb/issues/112)

# [6.7.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v6.6.0...v6.7.0) (2022-02-15)


### Features

* add pod_cache param to ios_build job ([#140](https://github.com/react-native-community/react-native-circleci-orb/issues/140)) ([f18183f](https://github.com/react-native-community/react-native-circleci-orb/commit/f18183f))

# [6.6.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v6.5.0...v6.6.0) (2022-02-14)


### Features

* allow passing executor parameters to jobs ([#133](https://github.com/react-native-community/react-native-circleci-orb/issues/133)) ([4a199fd](https://github.com/react-native-community/react-native-circleci-orb/commit/4a199fd))

# [6.5.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v6.4.0...v6.5.0) (2022-02-14)


### Features

* allow passing pod_install_directory during ios_build job ([#136](https://github.com/react-native-community/react-native-circleci-orb/issues/136)) ([faa7a01](https://github.com/react-native-community/react-native-circleci-orb/commit/faa7a01))

# [6.4.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v6.3.0...v6.4.0) (2022-02-14)


### Features

* pass through pod cache param from job to command ([#138](https://github.com/react-native-community/react-native-circleci-orb/issues/138)) ([b156c1b](https://github.com/react-native-community/react-native-circleci-orb/commit/b156c1b))

# [6.3.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v6.2.2...v6.3.0) (2022-01-30)


### Features

* add homebrew_update parameter to toggle brew update ([#131](https://github.com/react-native-community/react-native-circleci-orb/issues/131)) ([6a7d635](https://github.com/react-native-community/react-native-circleci-orb/commit/6a7d635))

## [6.2.2](https://github.com/react-native-community/react-native-circleci-orb/compare/v6.2.1...v6.2.2) (2022-01-28)


### Bug Fixes

* **android:** fix gradle build cache key ([#130](https://github.com/react-native-community/react-native-circleci-orb/issues/130) by [@fotos](https://github.com/fotos)) ([acadf02](https://github.com/react-native-community/react-native-circleci-orb/commit/acadf02))

## [6.2.1](https://github.com/react-native-community/react-native-circleci-orb/compare/v6.2.0...v6.2.1) (2022-01-27)


### Bug Fixes

* **ios:** update default ios device to iPhone 11 ([#127](https://github.com/react-native-community/react-native-circleci-orb/issues/127)) ([2e3b1e0](https://github.com/react-native-community/react-native-circleci-orb/commit/2e3b1e0))

# [6.2.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v6.1.0...v6.2.0) (2022-01-17)


### Features

* **ios:** control if simulator starts in background ([#126](https://github.com/react-native-community/react-native-circleci-orb/issues/126)) ([08338f9](https://github.com/react-native-community/react-native-circleci-orb/commit/08338f9))

# [6.1.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v6.0.1...v6.1.0) (2022-01-04)


### Features

* add optional yarn_install_directory parameter ([#124](https://github.com/react-native-community/react-native-circleci-orb/issues/124)) ([3c659f9](https://github.com/react-native-community/react-native-circleci-orb/commit/3c659f9))

## [6.0.1](https://github.com/react-native-community/react-native-circleci-orb/compare/v6.0.0...v6.0.1) (2021-11-19)


### Bug Fixes

* **android:** move docker android pin to JDK11 version ([#123](https://github.com/react-native-community/react-native-circleci-orb/issues/123)) ([d74d427](https://github.com/react-native-community/react-native-circleci-orb/commit/d74d427)), closes [#122](https://github.com/react-native-community/react-native-circleci-orb/issues/122)

# [6.0.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v5.6.2...v6.0.0) (2021-11-19)


### Bug Fixes

* **android:** use JDK11 compatible JVM options ([#122](https://github.com/react-native-community/react-native-circleci-orb/issues/122)) ([1923bcd](https://github.com/react-native-community/react-native-circleci-orb/commit/1923bcd)), closes [#120](https://github.com/react-native-community/react-native-circleci-orb/issues/120)


### BREAKING CHANGES

* **android:** this orb is now using JDK11

See JDK8-->JDK11 migration notes here:
https://discuss.circleci.com/t/android-convenience-image-moving-to-java-v11-on-august-17th/36601/4

## [5.6.2](https://github.com/react-native-community/react-native-circleci-orb/compare/v5.6.1...v5.6.2) (2021-11-19)


### Bug Fixes

* **android:** pin docker image to 4.2 for JDK8 ([#121](https://github.com/react-native-community/react-native-circleci-orb/issues/121)) ([fe2898a](https://github.com/react-native-community/react-native-circleci-orb/commit/fe2898a)), closes [#120](https://github.com/react-native-community/react-native-circleci-orb/issues/120)

## [5.6.1](https://github.com/react-native-community/react-native-circleci-orb/compare/v5.6.0...v5.6.1) (2021-11-19)


### Bug Fixes

* do not cache /usr/local/Homebrew ([#119](https://github.com/react-native-community/react-native-circleci-orb/issues/119)) ([597e597](https://github.com/react-native-community/react-native-circleci-orb/commit/597e597))

# [5.6.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v5.5.1...v5.6.0) (2021-10-22)


### Features

* **android:** Pass through the `assemble_android_test` parameter from the `android_build` job to the command ([#109](https://github.com/react-native-community/react-native-circleci-orb/issues/109) by [@ronwsmith](https://github.com/ronwsmith)) ([9f2e7fa](https://github.com/react-native-community/react-native-circleci-orb/commit/9f2e7fa))

## [5.5.1](https://github.com/react-native-community/react-native-circleci-orb/compare/v5.5.0...v5.5.1) (2021-10-22)


### Bug Fixes

* **android:** Added new Android Command Line Tools for MacOS 12+ and Java 9, 10, 11 ([#114](https://github.com/react-native-community/react-native-circleci-orb/issues/114) by [@lukebrandonfarrell](https://github.com/lukebrandonfarrell)) ([aeb45fe](https://github.com/react-native-community/react-native-circleci-orb/commit/aeb45fe))

# [5.5.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v5.4.0...v5.5.0) (2021-07-28)


### Features

* **Android:** Add optional command-running step after the emulator starts ([#110](https://github.com/react-native-community/react-native-circleci-orb/issues/110) by [@ronwsmith](https://github.com/ronwsmith)) ([5ee8a30](https://github.com/react-native-community/react-native-circleci-orb/commit/5ee8a30))

# [5.4.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v5.3.0...v5.4.0) (2021-07-13)


### Features

* Make yarn cache folder configurable ([#103](https://github.com/react-native-community/react-native-circleci-orb/issues/103) by [@ronwsmith](https://github.com/ronwsmith)) ([c6ccaa1](https://github.com/react-native-community/react-native-circleci-orb/commit/c6ccaa1))

# [5.3.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v5.2.0...v5.3.0) (2021-06-02)


### Features

* **android:** Add command to update the NDK to a given version ([#91](https://github.com/react-native-community/react-native-circleci-orb/issues/91) by @CHNB128) ([64eac35](https://github.com/react-native-community/react-native-circleci-orb/commit/64eac35))
* **android:** Add hombrew cache param to android test job ([#96](https://github.com/react-native-community/react-native-circleci-orb/issues/96) by @Kyonru) ([8314b6e](https://github.com/react-native-community/react-native-circleci-orb/commit/8314b6e))

# [5.2.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v5.1.0...v5.2.0) (2021-06-02)


### Features

* add parameter to allow configuring the android tests on build ([0569d66](https://github.com/react-native-community/react-native-circleci-orb/commit/0569d66))

# [5.1.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v5.0.0...v5.1.0) (2021-03-24)


### Features

* Add parameters to disable caching ([ad81e99](https://github.com/react-native-community/react-native-circleci-orb/commit/ad81e99))

# [5.0.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v4.5.3...v5.0.0) (2021-03-18)


### Features

* Update default dependencies to meet React Native 0.64 requirements ([34ca501](https://github.com/react-native-community/react-native-circleci-orb/commit/34ca501))


### BREAKING CHANGES

* The default dependencies used are now Xcode 12, CocoaPods 1.10.1, Node.js 12

## [4.5.3](https://github.com/react-native-community/react-native-circleci-orb/compare/v4.5.2...v4.5.3) (2021-03-18)


### Bug Fixes

* Remove Deprecated CircleCI Spec Repo Cache ([#82](https://github.com/react-native-community/react-native-circleci-orb/issues/82) by @BytesGuy) ([f45fcfe](https://github.com/react-native-community/react-native-circleci-orb/commit/f45fcfe))

## [4.5.2](https://github.com/react-native-community/react-native-circleci-orb/compare/v4.5.1...v4.5.2) (2021-03-18)


### Bug Fixes

* **android:** Fix Permission denied issues when running gradlew ([#72](https://github.com/react-native-community/react-native-circleci-orb/issues/72) by [@zpd106](https://github.com/zpd106)) ([0e22ef8](https://github.com/react-native-community/react-native-circleci-orb/commit/0e22ef8))

## [4.5.1](https://github.com/react-native-community/react-native-circleci-orb/compare/v4.5.0...v4.5.1) (2021-03-18)


### Bug Fixes

* Remove deprecated cask usage from brew install ([#85](https://github.com/react-native-community/react-native-circleci-orb/issues/85) by @CHNB128) ([de4ef76](https://github.com/react-native-community/react-native-circleci-orb/commit/de4ef76))

# [4.5.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v4.4.2...v4.5.0) (2021-03-18)


### Bug Fixes

* duplicated on_after_initialize  param ([#78](https://github.com/react-native-community/react-native-circleci-orb/issues/78)) ([33ffc6b](https://github.com/react-native-community/react-native-circleci-orb/commit/33ffc6b))


### Features

* Add pod cache ([#67](https://github.com/react-native-community/react-native-circleci-orb/issues/67)) ([96b0f3f](https://github.com/react-native-community/react-native-circleci-orb/commit/96b0f3f))

## [4.4.2](https://github.com/react-native-community/react-native-circleci-orb/compare/v4.4.1...v4.4.2) (2020-05-18)


### Bug Fixes

* **android:** Ensure the Android emulator looks correct ([#65](https://github.com/react-native-community/react-native-circleci-orb/issues/65) by [@vonovak](https://github.com/vonovak)) ([57744a4](https://github.com/react-native-community/react-native-circleci-orb/commit/57744a4))

## [4.4.1](https://github.com/react-native-community/react-native-circleci-orb/compare/v4.4.0...v4.4.1) (2020-05-18)


### Bug Fixes

* **android:** Update android_emulator_start.yml to use the new  emulator ([#64](https://github.com/react-native-community/react-native-circleci-orb/issues/64) by [@vonovak](https://github.com/vonovak)) ([73d27e2](https://github.com/react-native-community/react-native-circleci-orb/commit/73d27e2))

# [4.4.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v4.3.0...v4.4.0) (2020-05-09)


### Features

* Add a `store_artifact_path` to the Android and iOS test jobs which allow storing artifacts after a job runs ([#54](https://github.com/react-native-community/react-native-circleci-orb/issues/54) by @MateusAndrade) ([19edf8a](https://github.com/react-native-community/react-native-circleci-orb/commit/19edf8a))

# [4.3.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v4.2.3...v4.3.0) (2020-05-09)


### Features

* follow emulator best practices ([a5765a2](https://github.com/react-native-community/react-native-circleci-orb/commit/a5765a2))
* follow emulator best practices ([#62](https://github.com/react-native-community/react-native-circleci-orb/issues/62)) ([ac709c1](https://github.com/react-native-community/react-native-circleci-orb/commit/ac709c1))

## [4.2.3](https://github.com/react-native-community/react-native-circleci-orb/compare/v4.2.2...v4.2.3) (2020-05-09)


### Bug Fixes

* **android:** fix JAVA_HOME path ([#61](https://github.com/react-native-community/react-native-circleci-orb/issues/61) by [@vonovak](https://github.com/vonovak)) ([e4fa01f](https://github.com/react-native-community/react-native-circleci-orb/commit/e4fa01f))
* **android:** fix path to emulator ([#60](https://github.com/react-native-community/react-native-circleci-orb/issues/60) by [@vonovak](https://github.com/vonovak)) ([8621ec9](https://github.com/react-native-community/react-native-circleci-orb/commit/8621ec9))
* Move cache directory to the system temp folder to avoid permission issues ([#59](https://github.com/react-native-community/react-native-circleci-orb/issues/59) by @Naturalclar) ([15f0d90](https://github.com/react-native-community/react-native-circleci-orb/commit/15f0d90))

## [4.2.2](https://github.com/react-native-community/react-native-circleci-orb/compare/v4.2.1...v4.2.2) (2020-04-23)


### Bug Fixes

* **ios:** Revert changes from 4.2.0 ([2c3fa5e](https://github.com/react-native-community/react-native-circleci-orb/commit/2c3fa5e))

## [4.2.1](https://github.com/react-native-community/react-native-circleci-orb/compare/v4.2.0...v4.2.1) (2020-04-22)


### Bug Fixes

* **ios:** Fix syntax errors ([aff9136](https://github.com/react-native-community/react-native-circleci-orb/commit/aff9136))

# [4.2.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v4.1.1...v4.2.0) (2020-04-21)


### Features

* **ios:** Ensure a simulator with the latest iOS version exists for the given name when testing ([2d614fa](https://github.com/react-native-community/react-native-circleci-orb/commit/2d614fa))

## [4.1.1](https://github.com/react-native-community/react-native-circleci-orb/compare/v4.1.0...v4.1.1) (2020-04-20)


### Bug Fixes

* **ios:** Possible fix for the NVM node version not carrying over between steps ([#51](https://github.com/react-native-community/react-native-circleci-orb/issues/51)) ([ae71c53](https://github.com/react-native-community/react-native-circleci-orb/commit/ae71c53))

# [4.1.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v4.0.4...v4.1.0) (2020-04-03)


### Features

* **ios:** Add Cocoapods Install Command ([#48](https://github.com/react-native-community/react-native-circleci-orb/issues/48) by [@vonovak](https://github.com/vonovak)) ([a743bbc](https://github.com/react-native-community/react-native-circleci-orb/commit/a743bbc))

## [4.0.4](https://github.com/react-native-community/react-native-circleci-orb/compare/v4.0.3...v4.0.4) (2020-04-03)


### Bug Fixes

* Mac node install ([#47](https://github.com/react-native-community/react-native-circleci-orb/issues/47) by [@vonovak](https://github.com/vonovak)) ([4a4b619](https://github.com/react-native-community/react-native-circleci-orb/commit/4a4b619))

## [4.0.3](https://github.com/react-native-community/react-native-circleci-orb/compare/v4.0.2...v4.0.3) (2020-04-02)


### Bug Fixes

* Ensure that the publish steps works correctly ([7e6c289](https://github.com/react-native-community/react-native-circleci-orb/commit/7e6c289))

## [4.0.2](https://github.com/react-native-community/react-native-circleci-orb/compare/v4.0.1...v4.0.2) (2020-04-02)


### Bug Fixes

* Ensure the CI works correctly ([51d7f49](https://github.com/react-native-community/react-native-circleci-orb/commit/51d7f49))

## [4.0.1](https://github.com/react-native-community/react-native-circleci-orb/compare/v4.0.0...v4.0.1) (2020-04-02)


### Bug Fixes

* **android:** Define a max heap size for linux_android ([#46](https://github.com/react-native-community/react-native-circleci-orb/issues/46) by [@vabanagas](https://github.com/vabanagas)) ([d029e0b](https://github.com/react-native-community/react-native-circleci-orb/commit/d029e0b))

# [4.0.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v3.0.1...v4.0.0) (2020-03-31)


### Features

* **ios:** Upgrading Xcode to 11.0 ([#45](https://github.com/react-native-community/react-native-circleci-orb/issues/45) by [@springcoil](https://github.com/springcoil)) ([78aad72](https://github.com/react-native-community/react-native-circleci-orb/commit/78aad72))


### BREAKING CHANGES

* **ios:** You should confirm that your app is able to build on Xcode 11 before upgrade, however, most app will already support this.

## [3.0.1](https://github.com/react-native-community/react-native-circleci-orb/compare/v3.0.0...v3.0.1) (2020-02-03)


### Bug Fixes

* Fix errors when installing NodeJS on MacOS executor ([#40](https://github.com/react-native-community/react-native-circleci-orb/issues/40) by [@roni-castro](https://github.com/roni-castro)) ([19ac8f7](https://github.com/react-native-community/react-native-circleci-orb/commit/19ac8f7))

# [3.0.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v2.0.1...v3.0.0) (2020-01-26)


### Features

* Use Node 10 by default ([#37](https://github.com/react-native-community/react-native-circleci-orb/issues/37) by [@roni-castro](https://github.com/roni-castro)) ([3e7efc6](https://github.com/react-native-community/react-native-circleci-orb/commit/3e7efc6))


### BREAKING CHANGES

* Node 10 is now the default version. The previous default of Node 8 is now end-of-life. Most users will have no issues with upgrading unless they use modules which rely on Node 8 behaviour. You can also now use the `node_version` parameter to set the Node version you require.

## [2.0.1](https://github.com/react-native-community/react-native-circleci-orb/compare/v2.0.0...v2.0.1) (2020-01-04)


### Bug Fixes

* Removed the unused `build_threads` parameter in the `linux_android` executor ([97720b9](https://github.com/react-native-community/react-native-circleci-orb/commit/97720b9)), closes [#19](https://github.com/react-native-community/react-native-circleci-orb/issues/19)

# [2.0.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v1.5.0...v2.0.0) (2020-01-04)


### Features

* Added the `--frozen-lockfile` flag to the `yarn_install` command ([e4676c4](https://github.com/react-native-community/react-native-circleci-orb/commit/e4676c4)), closes [#28](https://github.com/react-native-community/react-native-circleci-orb/issues/28)


### BREAKING CHANGES

* The `yarn_install` command will now fail if there need to be changes made to your `yarn.lock` file. See [the Yarn documentation](https://yarnpkg.com/en/docs/cli/install#toc-yarn-install-frozen-lockfile) for details on this flag.

# [1.5.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v1.4.0...v1.5.0) (2020-01-04)


### Features

* Add `on_after_initialize` parameter to the jobs ([#26](https://github.com/react-native-community/react-native-circleci-orb/issues/26) by [@compojoom](https://github.com/compojoom)) ([0ff6621](https://github.com/react-native-community/react-native-circleci-orb/commit/0ff6621))
* Add a `bundle` command ([#8](https://github.com/react-native-community/react-native-circleci-orb/issues/8) by [@sunilchalla](https://github.com/sunilchalla)) ([464d661](https://github.com/react-native-community/react-native-circleci-orb/commit/464d661))

# [1.4.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v1.3.0...v1.4.0) (2020-01-04)


### Features

* **ios:** Added an `ios_build` job ([#30](https://github.com/react-native-community/react-native-circleci-orb/issues/30) by [@roni-castro](https://github.com/roni-castro)) ([b607782](https://github.com/react-native-community/react-native-circleci-orb/commit/b607782))

# [1.3.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v1.2.1...v1.3.0) (2019-11-20)


### Bug Fixes

* **android:** Update gradle cache keys to match on save and restore ([#17](https://github.com/react-native-community/react-native-circleci-orb/issues/17)) ([6e52052](https://github.com/react-native-community/react-native-circleci-orb/commit/6e52052))
* **docs:** include the code repo link in the orb description ([6d97ca9](https://github.com/react-native-community/react-native-circleci-orb/commit/6d97ca9))
* Remove FBSimulatorControl ([#24](https://github.com/react-native-community/react-native-circleci-orb/issues/24) by [@compojoom](https://github.com/compojoom)) ([7c5b51a](https://github.com/react-native-community/react-native-circleci-orb/commit/7c5b51a))
* remove haxm the lack hardware acceleration support causes a crash ([9d0bb42](https://github.com/react-native-community/react-native-circleci-orb/commit/9d0bb42))
* remove haxm the lack hardware acceleration support causes a crash ([38ef88e](https://github.com/react-native-community/react-native-circleci-orb/commit/38ef88e)), closes [#3](https://github.com/react-native-community/react-native-circleci-orb/issues/3)


### Features

* Minor release ([5f401d7](https://github.com/react-native-community/react-native-circleci-orb/commit/5f401d7))

## [1.2.2](https://github.com/react-native-community/react-native-circleci-orb/compare/v1.2.1...v1.2.2) (2019-10-25)


### Bug Fixes

* remove haxm the lack hardware acceleration support causes a crash ([9d0bb42](https://github.com/react-native-community/react-native-circleci-orb/commit/9d0bb42))
* remove haxm the lack hardware acceleration support causes a crash ([38ef88e](https://github.com/react-native-community/react-native-circleci-orb/commit/38ef88e)), closes [#3](https://github.com/react-native-community/react-native-circleci-orb/issues/3)

## [1.2.1](https://github.com/react-native-community/react-native-circleci-orb/compare/v1.2.0...v1.2.1) (2019-06-03)


### Bug Fixes

* Use project_type in ios_build_and_test job ([25c7948](https://github.com/react-native-community/react-native-circleci-orb/commit/25c7948))

# [1.2.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v1.1.2...v1.2.0) (2019-05-14)


### Features

* Allow the metro packager to be started from the test jobs ([68846df](https://github.com/react-native-community/react-native-circleci-orb/commit/68846df))

## [1.1.2](https://github.com/react-native-community/react-native-circleci-orb/compare/v1.1.1...v1.1.2) (2019-05-14)


### Bug Fixes

* Correct the Android java environment variables ([917129a](https://github.com/react-native-community/react-native-circleci-orb/commit/917129a))

## [1.1.1](https://github.com/react-native-community/react-native-circleci-orb/compare/v1.1.0...v1.1.1) (2019-05-14)


### Bug Fixes

* Increase the amount of memory for Android builds ([22e8279](https://github.com/react-native-community/react-native-circleci-orb/commit/22e8279))

# [1.1.0](https://github.com/react-native-community/react-native-circleci-orb/compare/v1.0.0...v1.1.0) (2019-04-25)


### Features

* Add parameters to configure the executors ([7c044cb](https://github.com/react-native-community/react-native-circleci-orb/commit/7c044cb))
