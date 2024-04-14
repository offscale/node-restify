<a name="5.2.0"></a>
## [5.1.0-beta1](https://github.com/offscale/node-restify/compare/v5.0.0-beta1...v5.1.0-beta1) (2024-04-14)


### Features

* create inflightRequestThrottle plugin ([#1431](https://github.com/offscale/node-restify/issues/1431)) ([285faf4](https://github.com/offscale/node-restify/commit/285faf4b6a2e56f0e4d9fc6dfaa3dd5e311530c1))
* revert async formatters ([#1377](https://github.com/offscale/node-restify/issues/1377)) ([a2e300f](https://github.com/offscale/node-restify/commit/a2e300f785edb087da9a52f562bd1f900e9ab47a))


### Bug Fixes

* Add migration guid to website ([#1402](https://github.com/offscale/node-restify/issues/1402)) ([5f053c7](https://github.com/offscale/node-restify/commit/5f053c7efebc414b5a26daac3cc5e89dc0054fe3))
* add node 7-8 travis support ([#1405](https://github.com/offscale/node-restify/issues/1405)) ([536a473](https://github.com/offscale/node-restify/commit/536a4735266a7f56c205be4c6cafaa6adf81f480))
* audit timers of same name should accumulate ([#1435](https://github.com/offscale/node-restify/issues/1435)) ([#1443](https://github.com/offscale/node-restify/issues/1443)) ([a2d34aa](https://github.com/offscale/node-restify/commit/a2d34aaa461cabf47147990a1c2910ea9a53b2d8))
* **audit:** use public APIs for accessing response headers ([5169db7](https://github.com/offscale/node-restify/commit/5169db7b1d2c9979e534b2c27912f5be398bcbca))
* **bodyReader:** Fix memory leak ([#1566](https://github.com/offscale/node-restify/issues/1566)) ([1637ace](https://github.com/offscale/node-restify/commit/1637ace2a94df6c5775a3eace3296ce2602a7341))
* create unit tests for sanitizePath plugin ([#1352](https://github.com/offscale/node-restify/issues/1352)) ([12714cf](https://github.com/offscale/node-restify/commit/12714cfce5048c65b4256df660766e863578b90a))
* doc site ([#1393](https://github.com/offscale/node-restify/issues/1393)) ([76ee548](https://github.com/offscale/node-restify/commit/76ee5480cfcb7f36e39e3e0955102c04abdac867))
* documentation update for restifyError event example ([#1398](https://github.com/offscale/node-restify/issues/1398)) ([94fe715](https://github.com/offscale/node-restify/commit/94fe715173ffcebd8814bed7e17a22a24fac4ae8))
* emit restifyError event even for router errors ([#1420](https://github.com/offscale/node-restify/issues/1420)) ([f9d02d5](https://github.com/offscale/node-restify/commit/f9d02d5b358863b9e067da5d6c89b4e283f420ba))
* GH-1438, error reponse customization documentation incorrect ([#1439](https://github.com/offscale/node-restify/issues/1439)) ([dd66088](https://github.com/offscale/node-restify/commit/dd66088f3067d4b0858a2dd0274c705faf374e0e))
* Honor port for redirect ([#1363](https://github.com/offscale/node-restify/issues/1363)) ([61c0cb5](https://github.com/offscale/node-restify/commit/61c0cb5c697bcd84c2f7255bfe158619694fb73d))
* monkey patch getHeaders for pre-v7 Node.js (GH-1409) ([82088a7](https://github.com/offscale/node-restify/commit/82088a7185331c7de092450ffec52d815c079739))
* package.json version now matches npm ([9944dbd](https://github.com/offscale/node-restify/commit/9944dbd57795fa312c8f35c4734977698d70c895))
* respect when status code is set with res.status (GH-1429) ([#1440](https://github.com/offscale/node-restify/issues/1440)) ([5abc067](https://github.com/offscale/node-restify/commit/5abc06779df3b3ed4faf4d19f0815051a7c3106b))
* test static plugin's handling of sprintf escape sequences ([#1391](https://github.com/offscale/node-restify/issues/1391)) ([5d7039a](https://github.com/offscale/node-restify/commit/5d7039a5b97e158347fbb918b866b7aeebd4a14f))
* update chai (^3.4.1 to ^4.0.0) ([f982d0c](https://github.com/offscale/node-restify/commit/f982d0c71f1b72f79e07f33f6cdf43741242f5d8))
* update http-signature to v1.0.0 ([#1401](https://github.com/offscale/node-restify/issues/1401)) ([ec88737](https://github.com/offscale/node-restify/commit/ec887376a8314edbb623db48e6288d5a352a4efd))
* versioned route matching should not throw TypeError ([#1381](https://github.com/offscale/node-restify/issues/1381)) ([25d10f0](https://github.com/offscale/node-restify/commit/25d10f00a4c9128b87cda0261aa3a041ac652f63))

## 5.2.0 (2017-08-16)


#### Bug Fixes

* package.json version now matches npm ([9944dbd5](git://github.com/restify/node-restify.git/commit/9944dbd5))
* create unit tests for sanitizePath plugin (#1352) ([12714cfc](git://github.com/restify/node-restify.git/commit/12714cfc))
* audit timers of same name should accumulate (#1435) (#1443) ([a2d34aaa](git://github.com/restify/node-restify.git/commit/a2d34aaa))
* respect when status code is set with res.status (GH-1429) (#1440) ([5abc0677](git://github.com/restify/node-restify.git/commit/5abc0677))
* versioned route matching should not throw TypeError (#1381) ([25d10f00](git://github.com/restify/node-restify.git/commit/25d10f00))


<a name="5.0.1"></a>
### 5.0.1 (2017-07-17)


#### Bug Fixes

* monkey patch getHeaders for pre-v7 Node.js (GH-1409) ([82088a71](git://github.com/restify/node-restify.git/commit/82088a71))
* add node 7-8 travis support (#1405) ([536a4735](git://github.com/restify/node-restify.git/commit/536a4735))
* Add migration guid to website (#1402) ([5f053c7e](git://github.com/restify/node-restify.git/commit/5f053c7e))
* update http-signature to v1.0.0 (#1401) ([ec887376](git://github.com/restify/node-restify.git/commit/ec887376))
* documentation update for restifyError event example (#1398) ([94fe7151](git://github.com/restify/node-restify.git/commit/94fe7151))
* doc site (#1393) ([76ee5480](git://github.com/restify/node-restify.git/commit/76ee5480))
* test static plugin's handling of sprintf escape sequences (#1391) ([5d7039a5](git://github.com/restify/node-restify.git/commit/5d7039a5))
