## [1.7.16](https://github.com/kolvin/workflows/compare/v1.7.15...v1.7.16) (2022-12-14)


### Bug Fixes

* **terragrunt:** terragrunt cache ([f97e0a1](https://github.com/kolvin/workflows/commit/f97e0a1c94384609e2fb80b6f30f20ca0ebeee3a))

## [1.7.15](https://github.com/kolvin/workflows/compare/v1.7.14...v1.7.15) (2022-12-14)


### Bug Fixes

* **terragrunt:** cache terragrunt build files + tg plan ([97dc1d3](https://github.com/kolvin/workflows/commit/97dc1d30b7beecca023148225fff26d0015270a6))

## [1.7.14](https://github.com/kolvin/workflows/compare/v1.7.13...v1.7.14) (2022-12-14)


### Bug Fixes

* **terragrunt:** formatting cleanup of PR comment ([66d9ebf](https://github.com/kolvin/workflows/commit/66d9ebf6b81f65ff058873ba619bbdb94ae0e59f))

## [1.7.13](https://github.com/kolvin/workflows/compare/v1.7.12...v1.7.13) (2022-12-14)


### Bug Fixes

* **terragrunt:** set working-dir in PR comment stage ([044faea](https://github.com/kolvin/workflows/commit/044faea8c31c5bc7d213dc979dc098c6a53c69b1))

## [1.7.12](https://github.com/kolvin/workflows/compare/v1.7.11...v1.7.12) (2022-12-14)


### Bug Fixes

* **terragrunt:** set no-colour arg for terragrunt plan+validate ([8777822](https://github.com/kolvin/workflows/commit/877782275f20c5eee00eaab9b23866f9a5cb3038))

## [1.7.11](https://github.com/kolvin/workflows/compare/v1.7.10...v1.7.11) (2022-12-14)


### Bug Fixes

* **terragrunt:** reference validate+plan value in PR comment ([bce99ba](https://github.com/kolvin/workflows/commit/bce99baf021275d28b5ae7c3fd931611ad7db062))

## [1.7.10](https://github.com/kolvin/workflows/compare/v1.7.9...v1.7.10) (2022-12-14)


### Bug Fixes

* **terragrunt:** write terragrunt output to env var ([719c908](https://github.com/kolvin/workflows/commit/719c908d09c6b6e9b105692c3fd5510bc1d4be41))

## [1.7.9](https://github.com/kolvin/workflows/compare/v1.7.8...v1.7.9) (2022-12-13)


### Bug Fixes

* **terragrunt:** write terragrunt output to CI ouput ([e394dc2](https://github.com/kolvin/workflows/commit/e394dc2988020d5b2a9171329f9b5d06d23df0e9))

## [1.7.8](https://github.com/kolvin/workflows/compare/v1.7.7...v1.7.8) (2022-12-12)


### Bug Fixes

* **terragrunt:** echo plan output stout into PR comment ([0fef960](https://github.com/kolvin/workflows/commit/0fef960ecb13f5ced36e93ea6af9c2f5b706af67))

## [1.7.7](https://github.com/kolvin/workflows/compare/v1.7.6...v1.7.7) (2022-12-11)


### Bug Fixes

* **ci:** allow ci token pull-request WRITEs, so workflow can post comments ([9cab5a7](https://github.com/kolvin/workflows/commit/9cab5a7f7e4ce55d5de052c7da9cf8f13917f9e0))

## [1.7.6](https://github.com/kolvin/workflows/compare/v1.7.5...v1.7.6) (2022-12-11)


### Bug Fixes

* **ci:** allow ci token write to contents, so workflow can post comments ([7124599](https://github.com/kolvin/workflows/commit/7124599a9d4042c2c5aba36b4e2d56ff82c26eaa))

## [1.7.5](https://github.com/kolvin/workflows/compare/v1.7.4...v1.7.5) (2022-12-11)


### Bug Fixes

* **ci:** default github-script to use default scoped token ([01f7dbe](https://github.com/kolvin/workflows/commit/01f7dbe5631ac00da0542fdd0656bd45cacdd025))

## [1.7.4](https://github.com/kolvin/workflows/compare/v1.7.3...v1.7.4) (2022-12-11)


### Bug Fixes

* **terragrunt:** INCORRECT SYNTAX AGAIN ([29591f6](https://github.com/kolvin/workflows/commit/29591f6feb4c8259419fcb5a892add1fd8879832))

## [1.7.3](https://github.com/kolvin/workflows/compare/v1.7.2...v1.7.3) (2022-12-11)


### Bug Fixes

* **terragrunt:** INCORRECT SYNTAX AGAIN ([e8038a3](https://github.com/kolvin/workflows/commit/e8038a3ff52c13adc21fb9bbe52054cb656f6a15))

## [1.7.2](https://github.com/kolvin/workflows/compare/v1.7.1...v1.7.2) (2022-12-11)


### Bug Fixes

* **terragrunt:** configure AWS creds before terragrunt command ([0ea8b29](https://github.com/kolvin/workflows/commit/0ea8b297f879b0496e214665211eae0af654bb6c))

## [1.7.1](https://github.com/kolvin/workflows/compare/v1.7.0...v1.7.1) (2022-12-11)


### Bug Fixes

* move permissions to job level ([516a5a8](https://github.com/kolvin/workflows/commit/516a5a8abf784eb9f7941ee649410e1650a7f3bd))

# [1.7.0](https://github.com/kolvin/workflows/compare/v1.6.1...v1.7.0) (2022-12-11)


### Features

* **terragrunt:** consolodate terragrunt workflows into one ([c5be6ea](https://github.com/kolvin/workflows/commit/c5be6eaf20d658ebf4d5fd0c5f745215602f1490))

## [1.6.1](https://github.com/kolvin/workflows/compare/v1.6.0...v1.6.1) (2022-12-11)


### Bug Fixes

* set default role name to GITHUB not gitlab... shouldnt be coding this late fs ([c244092](https://github.com/kolvin/workflows/commit/c2440929ce4af12e32ffd906ab8635a882b14a06))

# [1.6.0](https://github.com/kolvin/workflows/compare/v1.5.7...v1.6.0) (2022-12-11)


### Features

* paramterise terragrunt plan target account values ([8416f96](https://github.com/kolvin/workflows/commit/8416f96053671322f3f67bab328af65525fb27eb))

## [1.5.7](https://github.com/kolvin/workflows/compare/v1.5.6...v1.5.7) (2022-12-11)


### Bug Fixes

* **terragrunt, ci:** set token permissionms ([53a3519](https://github.com/kolvin/workflows/commit/53a351914cd106560d48d0bc83eaf4c3b97d7941))

## [1.5.6](https://github.com/kolvin/workflows/compare/v1.5.5...v1.5.6) (2022-12-10)


### Bug Fixes

* **terragrunt:** try using input value on run definitions ([e092812](https://github.com/kolvin/workflows/commit/e092812f476dffe0491796c1d47c1742e990dc00))

## [1.5.5](https://github.com/kolvin/workflows/compare/v1.5.4...v1.5.5) (2022-12-10)


### Bug Fixes

* **terragrunt:** set working-dir to input value ([7b2be24](https://github.com/kolvin/workflows/commit/7b2be24bce44b0b70d51bd9d337f2b0ba1b461fc))

## [1.5.4](https://github.com/kolvin/workflows/compare/v1.5.3...v1.5.4) (2022-12-10)


### Bug Fixes

* **terragrunt:** add working-dir input to terragrunt workflows ([4a396e0](https://github.com/kolvin/workflows/commit/4a396e01da87682679fd0464a9b42824c6fd6977))

## [1.5.3](https://github.com/kolvin/workflows/compare/v1.5.2...v1.5.3) (2022-12-10)


### Bug Fixes

* **terragrunt, cowsay:** resolve bad exit code approach ([c86f2e0](https://github.com/kolvin/workflows/commit/c86f2e0446624ac0fae4f3bc582774483b683e34))

## [1.5.2](https://github.com/kolvin/workflows/compare/v1.5.1...v1.5.2) (2022-12-10)


### Bug Fixes

* remove useless workflows ([32a635b](https://github.com/kolvin/workflows/commit/32a635b36741bc6d75a82c7f936f1eb06e419bbd))

## [1.5.1](https://github.com/kolvin/workflows/compare/v1.5.0...v1.5.1) (2022-12-04)


### Bug Fixes

* **terraform:** add step to setup homebrew ([e25acb7](https://github.com/kolvin/workflows/commit/e25acb762e202f5238d1c67e4bd77842b83645af))

# [1.5.0](https://github.com/kolvin/workflows/compare/v1.4.0...v1.5.0) (2022-08-06)


### Features

* **terragrunt:** reusable workflow for terragrunt apply ([05cf290](https://github.com/kolvin/workflows/commit/05cf2906c1330657d23f794608097dbb59573a2b))

# [1.4.0](https://github.com/kolvin/workflows/compare/v1.3.0...v1.4.0) (2022-08-06)


### Features

* **terragrunt:** reusable workflow for terragrunt plan ([bbf191e](https://github.com/kolvin/workflows/commit/bbf191e75c8c479c6021cca4d831b0868b30191c))

# [1.3.0](https://github.com/kolvin/workflows/compare/v1.2.0...v1.3.0) (2022-08-06)


### Bug Fixes

* **worflows:** resolve bad ci syntax ([83661bf](https://github.com/kolvin/workflows/commit/83661bfce0ffc3403a82715ac3f38f870f74f246))


### Features

* **terragrunt:** reusable workflow for terragrunt lint ([979a1fe](https://github.com/kolvin/workflows/commit/979a1fe4cbcd23a8b15506c741914dd4e623ca9a))

# [1.2.0](https://github.com/kolvin/workflows/compare/v1.1.0...v1.2.0) (2022-08-06)


### Features

* **terraform:** reusable workflow for terraform install using tfenv ([20b1de0](https://github.com/kolvin/workflows/commit/20b1de0ba70727b34778943e83423930c7bd9ba1))

# [1.1.0](https://github.com/kolvin/workflows/compare/v1.0.0...v1.1.0) (2022-08-05)


### Features

* **terraform:** automation workflow for terraform doc generation ([2b0b52f](https://github.com/kolvin/workflows/commit/2b0b52f68717dcb5355c5d2a5fbe8d1ab1350e97))

# 1.0.0 (2022-08-04)


### Bug Fixes

* **semver:** new line EOF ([9394c6f](https://github.com/kolvin/workflows/commit/9394c6ff18c76ab95411b6f6235131388be2cd0c))
* **semver:** setting correct workflow namespace ([45d3e18](https://github.com/kolvin/workflows/commit/45d3e18095783526e05a619294b70d14d8e71f66))


### Features

* **semver:** created workflow file for semantic relesese with deps GPG secret key, Passphrase and discord webhook ([fc061dc](https://github.com/kolvin/workflows/commit/fc061dcdeef85c0267790b2472a65012771e4f89))
