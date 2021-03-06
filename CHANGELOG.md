# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [0.9.1](https://github.com/appcelerator/vscode-appcelerator-titanium/compare/v0.9.0...v0.9.1) (2020-09-16)

## [0.9.0](https://github.com/appcelerator/vscode-appcelerator-titanium/compare/v0.8.0...v0.9.0) (2020-07-02)


### Features

* added ability to output iOS App Store builds to Xcode ([#341](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/341)) ([4d1b9fe](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/4d1b9fe8061a96a9cb97e3e797534e8d47e19fca)), closes [#338](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/338)
* allowed simulatorVersion to be set on iOS tasks ([#327](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/327)) ([ffbb617](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/ffbb617ae4934011210135eac43f28e3ca721f70))


### Bug Fixes

* **packaging:** allow selecting folders during packaging ([c28a02b](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/c28a02b9bc99ce891bbe95ae415a13a996aa8661)), closes [#337](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/337)

## [0.8.0](https://github.com/appcelerator/vscode-appcelerator-titanium/compare/v0.7.1...v0.8.0) (2020-06-18)


### ⚠ BREAKING CHANGES

* **build explorer:** Windows devices and emulators will no longer be detected
* **debugger:** Setting deviceId and target in a launch configurations is no longer supported. Use the preLaunchTask to set targets and device details or use the prompting flow

### Features

* **commands:** add option to rerun build and package commands on error ([#314](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/314)) ([6d80c19](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/6d80c197f7c456df5b99b2cc1cbc442123c6a63d))
* **debugging:** allow starting a debug session from build explorer ([4905f78](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/4905f7859a901fd9a978ddbca2d57ed65bc232c3))
* **tasks:** resolve keystore relative to task folder ([1949670](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/1949670ab8a69598c7306cf63155fd83c5139a98))
* added extra arguments functionality and definitions ([#322](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/322)) ([6640eff](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/6640effedccf5156d524eabd897dcdf2b8ddcaa4))
* contribute task providers ([#257](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/257)) ([4921d29](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/4921d29c159b4ff987cb9731bca9aefffe868a1e))


### Bug Fixes

* **action-provider:** re-enable view code action provider ([#247](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/247)) ([207b952](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/207b9522141cff7e68f167c4cb19a2060c801d33)), closes [#162](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/162)
* **generate:** fixed typo in alloy generate components ([#265](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/265)) ([e4e8822](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/e4e8822cd4a1b4c0753f9226b38fce43be4f4955))
* **tasks:** allow cancelling task using ctrl+c ([cd0352f](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/cd0352f85c41a3e81c901c97b45e64d3a55e4671))
* **tasks:** respect global liveview setting ([172ec8c](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/172ec8c5bda67caa039073923a73d92fd122d5d3))
* **build explorer:** only show right click build on nodes ([faccb35](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/faccb35a892d4d08442e88dbaf355645ba5de7e5))

### [0.7.1](https://github.com/appcelerator/vscode-appcelerator-titanium/compare/v0.7.0...v0.7.1) (2020-04-06)


### Features

* **definition/controller:** fix lookup when path contains app ([#227](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/227)) ([1072455](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/1072455e9cefd3bf40f9f19ab3c741867870cbc6)), closes [#226](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/226)


### Bug Fixes

* **build:** correct logic for prompting ([95a8878](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/95a88789bbdf5b2b584b6d29232e87227b3b4ab4))
* **commands/run:** only do certificate name check when targeting device ([a1961c7](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/a1961c7edc48bcf35fc623b3e7df0c11a4e9e92a))
* **completion/style:** check length of rule results not existence ([37e2980](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/37e298024054ac75965d2079210e4c80bb52197b))
* **debug/ios:** obtain correct certificate name ([83844df](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/83844df8a5146cc672ab3e38ce24209a6a6bc894)), closes [#166](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/166)
* **debugging/android:** correctly assign default port ([0cf2bd7](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/0cf2bd79f61fc941bd0a51d75c75b57f526a89b5))
* **providers:** improve image file path completions ([c02e6cc](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/c02e6cc4611942b16936b1bef299e69b73c1bb88)), closes [#176](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/176)
* **providers:** improve require completions ([1dc2c82](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/1dc2c827c610b672fcf7ffcc47192a70eb466e21))

## [0.7.0](https://github.com/appcelerator/vscode-appcelerator-titanium/compare/v0.6.1...v0.7.0) (2019-11-07)


### Bug Fixes

* **build/ios:** dont prompt for cert info if we already have it ([5439414](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/5439414))
* **debugger:** add support for platform specific breakpoints ([#144](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/144)) ([87ac694](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/87ac694))
* fixed value completions in tss and views with word fragment ([#153](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/153)) ([d43e180](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/d43e180)), closes [#150](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/150) [#155](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/155)


### Features

* add clean to command palette ([#145](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/145)) ([0ea8420](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/0ea8420)), closes [#141](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/141)
* **completions:** added completions for Alloy namespace in cont… ([#134](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/134)) ([578cd8a](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/578cd8a)), closes [#133](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/133)
* **ios:** support usage of Apple certificates ([6192056](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/6192056)), closes [#147](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/147)

### [0.6.1](https://github.com/appcelerator/vscode-appcelerator-titanium/compare/v0.6.0...v0.6.1) (2019-10-01)


### Bug Fixes

* ensure correct drive letter is used when normalizing path ([bac6f8a](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/bac6f8a)), closes [#142](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/142)

## [0.6.0](https://github.com/appcelerator/vscode-appcelerator-titanium/compare/v0.5.0...v0.6.0) (2019-09-27)


### Bug Fixes

* fixed issue where ti.ui.size/fill were missing ([#128](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/128)) ([ae12980](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/ae12980)), closes [#122](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/122)
* **windows:** normalize drive letter before passing path to cli ([d08138a](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/d08138a)), closes [#124](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/124)
* set default publisherID to null ([ebacd90](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/ebacd90))


### Features

* **build:** add support for building to Windows ([2a8e2be](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/2a8e2be))
* **explorer/device:** sort Windows Mobile Emulators by OS version ([191a2f3](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/191a2f3))
* **packaging:** add support for packaging windows apps ([d5d5aa1](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/d5d5aa1))

## [0.5.0](https://github.com/appcelerator/vscode-appcelerator-titanium/compare/v0.4.0...v0.5.0) (2019-08-21)


### Bug Fixes

* **creation:** show output when error occurs during creation ([#121](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/121)) ([f291b26](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/f291b26)), closes [#107](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/107)
* **tmlanguage:** fixed highlighting when using comments in tss ([#120](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/120)) ([6a3ea30](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/6a3ea30)), closes [#114](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/114)


### Features

* add support for debugging Titanium applications ([#116](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/116)) ([5923ae1](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/5923ae1))

## [0.4.0](https://github.com/appcelerator/vscode-appcelerator-titanium/compare/v0.3.2...v0.4.0) (2019-07-17)


### Bug Fixes

* ensure progress notification is continuous ([f78397a](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/f78397a))
* **autocomplete:** check if there are multiple sdks in tiapp ([#91](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/91)) ([47e8f66](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/47e8f66)), closes [#79](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/79)
* **creation:** use fsPath when dealing with selected directory ([17e2be6](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/17e2be6)), closes [#108](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/108)
* **definition:** fixed go to definition for event handlers ([#96](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/96)) ([e70dbdc](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/e70dbdc)), closes [#94](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/94)
* **project:** add feedback for tiapp validation ([#97](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/97)) ([5527dc5](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/5527dc5)), closes [#95](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/95)
* **textmate:** fixed syntax highlight for alloy.cfg ([#104](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/104)) ([da1798c](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/da1798c)), closes [#103](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/103)
* **updates:** fix message on single update message ([71d51fb](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/71d51fb))
* **updates:** handle error properly in update check ([bb527fb](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/bb527fb)), closes [#100](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/100)
* **validation:** correct verbiage on fail message ([0b39031](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/0b39031)), closes [#88](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/88)


### Features

* **explorer:** add update checks for components ([e193754](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/e193754))
* prompt to install apps sdk if not installed ([bec5204](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/bec5204))
* validate environment on startup ([f615f3d](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/f615f3d))
* **explorer/updates:** change explorer text when checking for updates ([96ce5b7](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/96ce5b7))
* **package/android:** prompt for keystore key password ([#92](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/92)) ([73048bd](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/73048bd))



<a name="0.3.2"></a>
## [0.3.2](https://github.com/appcelerator/vscode-appcelerator-titanium/compare/v0.3.1...v0.3.2) (2019-05-01)


### Bug Fixes

* **providers:** added auto close for quotes and brackets for tss ([#76](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/76)) ([bfedfe1](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/bfedfe1))
* **providers:** fix the link for the widget identifier ([#75](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/75)) ([fbd06c6](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/fbd06c6)), closes [#62](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/62)



<a name="0.3.1"></a>
## [0.3.1](https://github.com/appcelerator/vscode-appcelerator-titanium/compare/v0.3.0...v0.3.1) (2019-04-01)


### Bug Fixes

* **package:** pass project directory into package arguments ([#71](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/71)) ([0027ec3](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/0027ec3)), closes [#70](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/70)



<a name="0.3.0"></a>
# [0.3.0](https://github.com/appcelerator/vscode-appcelerator-titanium/compare/v0.2.0...v0.3.0) (2019-03-28)


### Bug Fixes

* **alloy/generate:** handle opening widget files ([#59](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/59)) ([fab426d](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/fab426d)), closes [#55](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/55)
* **build:** last target undefined ([#65](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/65)) ([9471756](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/9471756)), closes [#57](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/57)
* **build/module:** pass project dir and build only on module build ([#68](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/68)) ([4ed8907](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/4ed8907)), closes [#67](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/67)
* **create:** pass in log level to create argument builder ([#61](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/61)) ([9f09ab9](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/9f09ab9)), closes [#60](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/60)
* **create/model:** add adapter type to model creation ([#64](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/64)) ([95b7259](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/95b7259)), closes [#58](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/58)


### Features

* **build:** added the output channel option ([#63](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/63)) ([23e0677](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/23e0677)), closes [#33](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/33)



<a name="0.2.0"></a>
# [0.2.0](https://github.com/appcelerator/vscode-appcelerator-titanium/compare/v0.1.4...v0.2.0) (2019-03-07)


### Bug Fixes

* remove scope from logLevel to add back to preferences menu ([491974c](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/491974c))
* **package:** correct last build state for android ([#52](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/52)) ([26357e0](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/26357e0)), closes [#47](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/47)


### Features

* **config:** add support for setting default keystore path ([#53](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/53)) ([a0832ac](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/a0832ac)), closes [#51](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/51)



<a name="0.1.4"></a>
## [0.1.4](https://github.com/appcelerator/vscode-appcelerator-titanium/compare/v0.1.3...v0.1.4) (2019-02-20)


### Bug Fixes

* do not attempt to generate completions for module projects ([70f34bd](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/70f34bd))
* handle errors from parsing appc info response ([90cc125](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/90cc125))
* **build:** quote all arguments when constructing the build and package args ([c20cb6a](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/c20cb6a)), closes [#41](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/41)
* **Windows Targets:** correct windows target names ([#40](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/40)) ([737edf9](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/737edf9))



<a name="0.1.3"></a>
## [0.1.3](https://github.com/appcelerator/vscode-appcelerator-titanium/compare/v0.1.2...v0.1.3) (2018-12-18)


### Bug Fixes

* **build:** only prompt for cert and provisioning profile when building to ios device ([721609d](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/721609d)), closes [#34](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/34)



<a name="0.1.2"></a>
## [0.1.2](https://github.com/appcelerator/vscode-appcelerator-titanium/compare/v0.1.1...v0.1.2) (2018-12-14)


### Bug Fixes

* **build/ios:** correctly provide cert when building to iOS device ([f4229ae](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/f4229ae))
* **completions:** handle case where project sdk is not installed ([489023f](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/489023f)), closes [#27](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/27)
* **definition:** reinstate hover provider, fix go to definition ([90ae10b](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/90ae10b))
* **package/ios:** do not pass output dir for app store builds ([2ea4346](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/2ea4346))
* add spacing between sim device and version ([#29](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/29)) ([18dfc38](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/18dfc38))



## [0.1.1](https://github.com/appcelerator/vscode-appcelerator-titanium/compare/v0.1.0...v0.1.1) (2018-12-13)


### Bug Fixes

* **completions:** fix bad reference to variable ([ea0cc9e](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/ea0cc9e))
* fix issue when no workspace root, only register alloy when enabled ([6df22b7](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/6df22b7))



# [0.1.0](https://github.com/appcelerator/vscode-appcelerator-titanium/compare/ffa6f61...v0.1.0) (2018-12-13)


### Bug Fixes

* **commands:** handle not logged in error correctly ([79c6432](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/79c6432))
* **completion:** Return all properties if we don't match ([4dd21c8](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/4dd21c8))
* **completions:** only enter necessary text on sdk insertion, show supported platforms for modules ([d3eab43](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/d3eab43))
* **completions/tiapp:** Trigger SDK completion on '.', filter by existing text, cleanup module code ([9249e3c](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/9249e3c))
* **explorer:** Call setContext with liveview state on startup ([ec7005d](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/ec7005d)), closes [#17](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/17)
* **terminal:** Handle no active terminal, handle closing the terminal we create ([7998d74](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/7998d74))
* conform to eslint, remove eslint-react deps ([d6b424d](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/d6b424d))
* remove "moment" dependency ([ffa6f61](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/ffa6f61))
* spacing on status-bar ([f632adf](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/f632adf))


### Features

* **build:** Allow enabling LiveView during build ([a5ce732](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/a5ce732))
* **build:** Start of Windows support ([#18](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/18)) ([728a839](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/728a839)), closes [#12](https://github.com/appcelerator/vscode-appcelerator-titanium/issues/12)
* **creation:** Add application and module project creation ([d69f3ac](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/d69f3ac))
* **explorer:** Add an inline icon for packaging ([e07ac76](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/e07ac76))
* **explorer:** Allow changing log level from explorer ([20afa0b](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/20afa0b))
* **generate:** Add Alloy component generation ([fe41182](https://github.com/appcelerator/vscode-appcelerator-titanium/commit/fe41182))
