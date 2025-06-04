# Changelog

## 1.0.0 (2025-06-04)


### Features

* Add Ability to Generate History Schemas With Fields Utilizing GoType() ([#68](https://github.com/kopexa-grc/enthistory/issues/68)) ([f3fdbd0](https://github.com/kopexa-grc/enthistory/commit/f3fdbd075d9e99dbf5855edefee5bb16ac1d274b))
* Add go.mod and go.sum for tool dependencies ([d5da363](https://github.com/kopexa-grc/enthistory/commit/d5da3635bcb6e63e66faca7afbbe2046c45d90c6))
* Allow Configurable History Triggers ([#47](https://github.com/kopexa-grc/enthistory/issues/47)) ([bd2980e](https://github.com/kopexa-grc/enthistory/commit/bd2980e26fc0150eed25190c65fdfa934c99f626))
* Custom Annotations & Mixins for History Schemas ([#44](https://github.com/kopexa-grc/enthistory/issues/44)) ([93bf09e](https://github.com/kopexa-grc/enthistory/commit/93bf09e1949b76b6b28d38f6b1d02d4531095b67))
* Refactor Enthistory To Do Schema Generation AOT ([#41](https://github.com/kopexa-grc/enthistory/issues/41)) ([ce4aa4a](https://github.com/kopexa-grc/enthistory/commit/ce4aa4a68f2063ba9baaf7bf90205739310e69c4))
* Required Snyk Updates ([#28](https://github.com/kopexa-grc/enthistory/issues/28)) ([0be0788](https://github.com/kopexa-grc/enthistory/commit/0be0788f7c475f7f360e7094146cb529037af75e))
* Snyk Upgrades ([#29](https://github.com/kopexa-grc/enthistory/issues/29)) ([f4adfc6](https://github.com/kopexa-grc/enthistory/commit/f4adfc67090928c2a71f96c5ffb2c54d30f13fe2))
* Speed Up Enthistory Codegen With Concurrency ([#49](https://github.com/kopexa-grc/enthistory/issues/49)) ([0a1f272](https://github.com/kopexa-grc/enthistory/commit/0a1f272f7faff40b20318998d80458f5635a844c))
* Update Deps for Vulnerabilities ([#25](https://github.com/kopexa-grc/enthistory/issues/25)) ([d661ec3](https://github.com/kopexa-grc/enthistory/commit/d661ec37e67f7cff2417d787fadc3c906ca25047))


### Bug Fixes

* Add Back HistoryHooks Func For Backwards Compatibility ([#48](https://github.com/kopexa-grc/enthistory/issues/48)) ([d31919d](https://github.com/kopexa-grc/enthistory/commit/d31919d76beb5d025b518a1b2530d6fbeac32120))
* Bump Go & Upgrade Dependencies ([#57](https://github.com/kopexa-grc/enthistory/issues/57)) ([09277f7](https://github.com/kopexa-grc/enthistory/commit/09277f7af3253069bb6e9e2d4b861e28773a6162))
* EntQL And GraphQL Codegen Issues ([#38](https://github.com/kopexa-grc/enthistory/issues/38)) ([a2f20cf](https://github.com/kopexa-grc/enthistory/commit/a2f20cf17c558f3102db038fd2ccf8b6776ffd78))
* generate examples for tests ([104d0ea](https://github.com/kopexa-grc/enthistory/commit/104d0ea12f45b078a887b071de60396d7fd3293f))
* generated schema snapshot now includes history annotations ([#34](https://github.com/kopexa-grc/enthistory/issues/34)) ([75b59b9](https://github.com/kopexa-grc/enthistory/commit/75b59b9c36fb40c0afeb197719949acca0b8853f))
* go upgrade and package upgrades ([#59](https://github.com/kopexa-grc/enthistory/issues/59)) ([8c53fdb](https://github.com/kopexa-grc/enthistory/commit/8c53fdbfdb6f501a4489918a98d7c682d3e64d23))
* Handle GQL Integrations Properly ([#42](https://github.com/kopexa-grc/enthistory/issues/42)) ([1983658](https://github.com/kopexa-grc/enthistory/commit/19836584273b6f9209d7a60a9f8d9d3dfec52468))
* History Models Should Inherit Most Annotations ([#40](https://github.com/kopexa-grc/enthistory/issues/40)) ([53965f9](https://github.com/kopexa-grc/enthistory/commit/53965f9ae95e58e33d5fbe75e2d1019448aef9c8))
* history schema fields now get the correct position index when updatedby is disabled ([#36](https://github.com/kopexa-grc/enthistory/issues/36)) ([fd7c564](https://github.com/kopexa-grc/enthistory/commit/fd7c564d059657a571e1cd132710f568758d5c6b))
* Mixins Containing Non-Int ID Fields Fail To Be Recognized ([#63](https://github.com/kopexa-grc/enthistory/issues/63)) ([eb53764](https://github.com/kopexa-grc/enthistory/commit/eb5376428c6a88b2251f718bddd313267d4bf30d))
* only set nillable field to previous value if it was not cleared ([#50](https://github.com/kopexa-grc/enthistory/issues/50)) ([10b1239](https://github.com/kopexa-grc/enthistory/commit/10b1239bb73d14dd0d9d31c21b22b86773463b29))
* Resolve Panics In Code Gen When Schema Fields Use DefaultFunc ([#71](https://github.com/kopexa-grc/enthistory/issues/71)) ([18fd7e1](https://github.com/kopexa-grc/enthistory/commit/18fd7e1a8301151753486bcbe926c91462ff9412))
* Update Dependencies ([#72](https://github.com/kopexa-grc/enthistory/issues/72)) ([77ab9f2](https://github.com/kopexa-grc/enthistory/commit/77ab9f21f7dc55e70e0916ce079a41cde22a104d))
* Update various templates and configuration files for improved functionality and consistency ([763a9a1](https://github.com/kopexa-grc/enthistory/commit/763a9a1551c7b2f402f36b253fbb5f2044143042))
* Upgrade Dependencies ([#46](https://github.com/kopexa-grc/enthistory/issues/46)) ([81eea34](https://github.com/kopexa-grc/enthistory/commit/81eea34219411018031d987a5e8fd4b0cfc9df39))
* Upgrade Dependencies ([#51](https://github.com/kopexa-grc/enthistory/issues/51)) ([4f6d0cf](https://github.com/kopexa-grc/enthistory/commit/4f6d0cf9fd291c9a6baad028e24306459a4e2ca2))
* Upgrade Dependencies For Snyk Resolutions ([#69](https://github.com/kopexa-grc/enthistory/issues/69)) ([46c195c](https://github.com/kopexa-grc/enthistory/commit/46c195c5735de93042ce78ad5297623be849b09e))
* Upgrade Go and Go Dependencies ([#66](https://github.com/kopexa-grc/enthistory/issues/66)) ([49087d6](https://github.com/kopexa-grc/enthistory/commit/49087d678efd3f55b73ab1d3cc579f4822993e62))
