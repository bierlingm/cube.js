# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [0.26.52](https://github.com/cube-js/cube.js/compare/v0.26.51...v0.26.52) (2021-03-07)


### Bug Fixes

* **@cubejs-backend/cubestore-driver:** Error: connect ECONNREFUSED 127.0.0.1:3030 ([74f4683](https://github.com/cube-js/cube.js/commit/74f468362b34f0decac67e48f52d3756ba4dc647))





## [0.26.50](https://github.com/cube-js/cube.js/compare/v0.26.49...v0.26.50) (2021-03-07)


### Bug Fixes

* **cubestore:** Group by without aggregates returns empty results ([82902dd](https://github.com/cube-js/cube.js/commit/82902ddb894dc0a0d30e88bde33b0308136789b9))





## [0.26.49](https://github.com/cube-js/cube.js/compare/v0.26.48...v0.26.49) (2021-03-05)


### Bug Fixes

* **cubestore:** fully execute a single-node query on a worker ([#2288](https://github.com/cube-js/cube.js/issues/2288)) ([00156d0](https://github.com/cube-js/cube.js/commit/00156d03b38becbb472f0b93bfb1617506caa941))
* **cubestore:** Merge aggregate performance improvements ([a0dbb1a](https://github.com/cube-js/cube.js/commit/a0dbb1ab492f5da40216435b8bf9b98f1ffda5e5))
* **cubestore:** update arrow, provide hints for default index of CubeTableExec ([#2304](https://github.com/cube-js/cube.js/issues/2304)) ([e27b8a4](https://github.com/cube-js/cube.js/commit/e27b8a4bb9b35b77625103a72a73f98ccca225e0))


### Features

* **cubestore:** Merge aggregate ([#2297](https://github.com/cube-js/cube.js/issues/2297)) ([31ebbbc](https://github.com/cube-js/cube.js/commit/31ebbbcb8a1ca2bc145b55fac00838cdeca0ea87))





## [0.26.48](https://github.com/cube-js/cube.js/compare/v0.26.47...v0.26.48) (2021-03-04)


### Bug Fixes

* **cubestore:** publish issue ([5bd1c3b](https://github.com/cube-js/cube.js/commit/5bd1c3bb74d49a4f6c363f18c6b5bb4822a543cc))





## [0.26.47](https://github.com/cube-js/cube.js/compare/v0.26.46...v0.26.47) (2021-03-04)


### Bug Fixes

* **cubestore:** post-install - compatbility with non bash env ([4b0c9ef](https://github.com/cube-js/cube.js/commit/4b0c9ef19b20d4cbfaee63337b7a0025bb31e6e9))





## [0.26.45](https://github.com/cube-js/cube.js/compare/v0.26.44...v0.26.45) (2021-03-04)


### Bug Fixes

* **cubestore:** attempt to exit gracefully on sigint (ctrl+c) ([#2255](https://github.com/cube-js/cube.js/issues/2255)) ([2b006f8](https://github.com/cube-js/cube.js/commit/2b006f80428a7202da06a9bded1b42c3d2753ced))


### Features

* **cubestore:** Extract transport to separate service ([#2236](https://github.com/cube-js/cube.js/issues/2236)) ([921786b](https://github.com/cube-js/cube.js/commit/921786b8a80bc0b2ed3e50d798a0c5bab435ec5c))





## [0.26.43](https://github.com/cube-js/cube.js/compare/v0.26.42...v0.26.43) (2021-03-02)


### Bug Fixes

* **cubestore:** post-install - right path ([fc77c8f](https://github.com/cube-js/cube.js/commit/fc77c8f1672a36205dadd90e2f33cfdf89eb330c))


### Features

* **cli:** Install Cube Store driver ([6153add](https://github.com/cube-js/cube.js/commit/6153add82ebb6abdd29424d773f8f3256ae3508e))





## [0.26.42](https://github.com/cube-js/cube.js/compare/v0.26.41...v0.26.42) (2021-03-02)


### Bug Fixes

* **cubestore:** allow to prune partitions with unbounded min or max ([#2213](https://github.com/cube-js/cube.js/issues/2213)) ([1649c09](https://github.com/cube-js/cube.js/commit/1649c094e24f9cdd00bbaef9693e9e623cbdd523))


### Features

* **cubestore:** post-install - improvements ([871cadb](https://github.com/cube-js/cube.js/commit/871cadb57109b79f1f792bc2843983aa0712e648))





## [0.26.40](https://github.com/cube-js/cube.js/compare/v0.26.39...v0.26.40) (2021-03-01)


### Bug Fixes

* **cubestore:** CubeStoreHandler - startup timeout, delay execution before start ([db9a8bd](https://github.com/cube-js/cube.js/commit/db9a8bd19f2b892151dcc051e962d9c5bedb4669))





## [0.26.39](https://github.com/cube-js/cube.js/compare/v0.26.38...v0.26.39) (2021-02-28)


### Bug Fixes

* **cubestore:** Malloc trim is broken for docker ([#2223](https://github.com/cube-js/cube.js/issues/2223)) ([5702cc4](https://github.com/cube-js/cube.js/commit/5702cc432c63d8db19a45d0938f4bbc073d05542))
* **cubestore:** use `spawn_blocking` on potentially expensive operations ([#2219](https://github.com/cube-js/cube.js/issues/2219)) ([a0f92e3](https://github.com/cube-js/cube.js/commit/a0f92e378f3c9531d4112f69a997ba32b8d09187))


### Features

* **cubestore:** Bump OpenSSL to 1.1.1h ([a1d091e](https://github.com/cube-js/cube.js/commit/a1d091e411933ed68ee823e31d5bce8703c83d06))
* **cubestore:** Web Socket transport ([#2227](https://github.com/cube-js/cube.js/issues/2227)) ([8821b9e](https://github.com/cube-js/cube.js/commit/8821b9e1378c17c54441bfb54a9ab387ae1e7044))
* Use single instance for Cube Store handler ([#2229](https://github.com/cube-js/cube.js/issues/2229)) ([35c140c](https://github.com/cube-js/cube.js/commit/35c140cac864b5b588fa88e90fec3d8b7de6acda))





## [0.26.38](https://github.com/cube-js/cube.js/compare/v0.26.37...v0.26.38) (2021-02-26)


### Bug Fixes

* **cubestore:** Reduce too verbose logging on slow queries ([1d62a47](https://github.com/cube-js/cube.js/commit/1d62a470bacf6b254b5f04f80ad44f24e84d6fb7))





## [0.26.36](https://github.com/cube-js/cube.js/compare/v0.26.35...v0.26.36) (2021-02-25)


### Bug Fixes

* **cubestore:** speed up ingestion ([#2205](https://github.com/cube-js/cube.js/issues/2205)) ([22685ea](https://github.com/cube-js/cube.js/commit/22685ea2d313893479ee9eaf88073158b0059c91))





## [0.26.35](https://github.com/cube-js/cube.js/compare/v0.26.34...v0.26.35) (2021-02-25)


### Features

* Use Cube Store as default external storage for CUBEJS_DEV_MODE ([e526676](https://github.com/cube-js/cube.js/commit/e52667617e5e687c92d383045fb1a8d5fd19cab6))





## [0.26.34](https://github.com/cube-js/cube.js/compare/v0.26.33...v0.26.34) (2021-02-25)


### Features

* **cubestore:** speed up import with faster timestamp parsing ([#2203](https://github.com/cube-js/cube.js/issues/2203)) ([18958aa](https://github.com/cube-js/cube.js/commit/18958aab4597930111211de3e8497040bce9432e))





## [0.26.33](https://github.com/cube-js/cube.js/compare/v0.26.32...v0.26.33) (2021-02-24)


### Bug Fixes

* **docker:** Move back to scretch + build linux (gnu) via cross ([4e48acc](https://github.com/cube-js/cube.js/commit/4e48acc626abce800be27b234651cc22778e1b9a))


### Features

* **cubestore:** Wait for processing loops and MySQL password support ([#2186](https://github.com/cube-js/cube.js/issues/2186)) ([f3649f5](https://github.com/cube-js/cube.js/commit/f3649f536ef7d645c686c0a5c30ca2e570790d73))





## [0.26.32](https://github.com/cube-js/cube.js/compare/v0.26.31...v0.26.32) (2021-02-24)


### Features

* **cubestore:** installer - detect musl + support windows ([9af0d34](https://github.com/cube-js/cube.js/commit/9af0d34512ef01c108ce843929009316eed51f4b))





## [0.26.31](https://github.com/cube-js/cube.js/compare/v0.26.30...v0.26.31) (2021-02-23)


### Features

* **cubestore:** Build binary for Linux (Musl) :feelsgood: ([594956c](https://github.com/cube-js/cube.js/commit/594956c9ec685d8939bfae0221c8ad6537194ab1))
* **cubestore:** Build binary for Windows :neckbeard: ([3e64d03](https://github.com/cube-js/cube.js/commit/3e64d0362f392a0461c9dc31ea7aac1d1ac0f901))





## [0.26.29](https://github.com/cube-js/cube.js/compare/v0.26.28...v0.26.29) (2021-02-22)


### Bug Fixes

* **cubestore:** switch from string to float in table value ([#2175](https://github.com/cube-js/cube.js/issues/2175)) ([05dc7d2](https://github.com/cube-js/cube.js/commit/05dc7d2174bee767ecff26acc6d4047a82f5f70d))


### Features

* **cubestore:** Ability to control process in Node.js ([f45e875](https://github.com/cube-js/cube.js/commit/f45e87560139beff1fc013f4a82b4b6a16799c1e))
* **cubestore:** installer - extract on fly ([290e264](https://github.com/cube-js/cube.js/commit/290e264a935a81a3c8181ec9a79730bf580232be))





## [0.26.27](https://github.com/cube-js/cube.js/compare/v0.26.26...v0.26.27) (2021-02-20)


### Bug Fixes

* **cubestore:** Check CUBESTORE_SKIP_POST_INSTALL before calling script ([fd2cebb](https://github.com/cube-js/cube.js/commit/fd2cebb8d4e0c91b22ffcd3f78ad15db225e6fad))





## [0.26.26](https://github.com/cube-js/cube.js/compare/v0.26.25...v0.26.26) (2021-02-20)


### Bug Fixes

* docker build ([8661acd](https://github.com/cube-js/cube.js/commit/8661acdff2b88eabeb855b25e8395815c9ecfa26))





## [0.26.24](https://github.com/cube-js/cube.js/compare/v0.26.23...v0.26.24) (2021-02-20)


### Features

* **cubestore:** Improve installer error reporting ([76dd651](https://github.com/cube-js/cube.js/commit/76dd6515fec8e809cd3b188e4c1c437707ff79a4))





## [0.26.23](https://github.com/cube-js/cube.js/compare/v0.26.22...v0.26.23) (2021-02-20)


### Features

* **cubestore:** Download binary from GitHub release. ([#2167](https://github.com/cube-js/cube.js/issues/2167)) ([9f90d2b](https://github.com/cube-js/cube.js/commit/9f90d2b27e480231c119af7b4e7039d0659b7b75))





## [0.26.22](https://github.com/cube-js/cube.js/compare/v0.26.21...v0.26.22) (2021-02-20)


### Features

* **cubestore:** Return success for create table only after table has been warmed up ([991a538](https://github.com/cube-js/cube.js/commit/991a538968b59104729a95a5be5d6b55a0aa6dcc))





## [0.26.21](https://github.com/cube-js/cube.js/compare/v0.26.20...v0.26.21) (2021-02-19)


### Bug Fixes

* **cubestore:** Cleanup memory after selects as well ([d9fd460](https://github.com/cube-js/cube.js/commit/d9fd46004caabc68145fa916a30b22b08c486a29))





## [0.26.20](https://github.com/cube-js/cube.js/compare/v0.26.19...v0.26.20) (2021-02-19)


### Bug Fixes

* **cubestore:** publish package ([60496e5](https://github.com/cube-js/cube.js/commit/60496e52e63e12b96bf750b468dc02686ddcdf5e))





## [0.26.19](https://github.com/cube-js/cube.js/compare/v0.26.18...v0.26.19) (2021-02-19)

**Note:** Version bump only for package @cubejs-backend/cubestore
