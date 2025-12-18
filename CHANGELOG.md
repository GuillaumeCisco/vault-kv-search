# Changelog

## [0.4.0](https://github.com/GuillaumeCisco/vault-kv-search/compare/v0.3.8...v0.4.0) (2025-12-18)


### Features

* add json output `--json` ([538da23](https://github.com/GuillaumeCisco/vault-kv-search/commit/538da23f9c175ff109c7a3949a1e3abba57a3c48))
* add regex search test ([b494546](https://github.com/GuillaumeCisco/vault-kv-search/commit/b49454627b0e6c0e54fced6fdbdd8500c45d7ef5))
* allow to specify kv version to avoid autodetection ([88a7584](https://github.com/GuillaumeCisco/vault-kv-search/commit/88a7584991e6773e962d2d5643d72e21402d899f))
* crawling delay as parameter `--delay` ([4c05ed0](https://github.com/GuillaumeCisco/vault-kv-search/commit/4c05ed0367a797449d5635ee3c7fa4ab0e5ff36f))
* initial support for secret kv2 ([4c05ed0](https://github.com/GuillaumeCisco/vault-kv-search/commit/4c05ed0367a797449d5635ee3c7fa4ab0e5ff36f))
* regex support ([4c05ed0](https://github.com/GuillaumeCisco/vault-kv-search/commit/4c05ed0367a797449d5635ee3c7fa4ab0e5ff36f))
* **token:** Allow .vault_token for handling token like does vault binary ([f9bf84e](https://github.com/GuillaumeCisco/vault-kv-search/commit/f9bf84e489b28ecd37f0d06436935c3c726fdde9))


### Bug Fixes

* add configurable timeout to resolve context deadline exceeded error ([376cb96](https://github.com/GuillaumeCisco/vault-kv-search/commit/376cb9679c1ab8b16b1810c13e308066bb82761b)), closes [#120](https://github.com/GuillaumeCisco/vault-kv-search/issues/120)
* **ci:** remove race flag from coverage to fix testcontainer conflict ([ec54c40](https://github.com/GuillaumeCisco/vault-kv-search/commit/ec54c40788e4d06dd7c7f112e82fe3581f64809e))
* **deps:** update module github.com/hashicorp/go-hclog to v1.6.2 ([ccf062a](https://github.com/GuillaumeCisco/vault-kv-search/commit/ccf062a600e9ed4e62f9659c84a57f6ab5ba1a39))
* **deps:** update module github.com/hashicorp/vault to v1.17.1 ([37d0683](https://github.com/GuillaumeCisco/vault-kv-search/commit/37d0683b79bbdc7b8549663af519aa2c857deff9))
* **deps:** update module github.com/hashicorp/vault to v1.18.1 [security] ([f22e357](https://github.com/GuillaumeCisco/vault-kv-search/commit/f22e3579f17a47a5ea74105e3efb64b9f2551142))
* **deps:** update module github.com/hashicorp/vault to v1.19.0 ([a11e3bd](https://github.com/GuillaumeCisco/vault-kv-search/commit/a11e3bda42c323bf57097b8d559402594bb03173))
* **deps:** update module github.com/hashicorp/vault to v1.19.1 ([749f220](https://github.com/GuillaumeCisco/vault-kv-search/commit/749f2206bfa3fb15ee3815c2ecca522814d9c442))
* **deps:** update module github.com/hashicorp/vault to v1.19.5 ([4cddf75](https://github.com/GuillaumeCisco/vault-kv-search/commit/4cddf753e53a38b2ac91902e4142f14aefbae841))
* **deps:** update module github.com/hashicorp/vault-plugin-secrets-kv to v0.16.2 ([b902541](https://github.com/GuillaumeCisco/vault-kv-search/commit/b902541564ed449632ddb655e85268568576deb4))
* **deps:** update module github.com/hashicorp/vault-plugin-secrets-kv to v0.17.0 ([b1ea819](https://github.com/GuillaumeCisco/vault-kv-search/commit/b1ea81969e96d9bbe9019e9c09a382fd68fe86cc))
* **deps:** update module github.com/hashicorp/vault-plugin-secrets-kv to v0.18.0 ([4f08d4e](https://github.com/GuillaumeCisco/vault-kv-search/commit/4f08d4e2406aec261be7552aa76009042a185ff5))
* **deps:** update module github.com/hashicorp/vault-plugin-secrets-kv to v0.23.0 ([033c47d](https://github.com/GuillaumeCisco/vault-kv-search/commit/033c47d53abf5d48014de18340a9eb1b547051a5))
* **deps:** update module github.com/hashicorp/vault-plugin-secrets-kv to v0.24.0 ([c871563](https://github.com/GuillaumeCisco/vault-kv-search/commit/c871563937aad25b635fd7fa853b0d5cbda349cc))
* **deps:** update module github.com/hashicorp/vault-plugin-secrets-kv to v0.24.1 ([4c1b390](https://github.com/GuillaumeCisco/vault-kv-search/commit/4c1b390c420ccfaf7fd48a4dd380b45aba0af6b6))
* **deps:** update module github.com/hashicorp/vault/api to v1.10.0 ([2705f53](https://github.com/GuillaumeCisco/vault-kv-search/commit/2705f5329227fdb4afeab36dbe3037d9107d7fa1))
* **deps:** update module github.com/hashicorp/vault/api to v1.11.0 ([a73d74c](https://github.com/GuillaumeCisco/vault-kv-search/commit/a73d74cbf687d285d49a1273fa9bfc29b2dbbd1f))
* **deps:** update module github.com/hashicorp/vault/api to v1.11.0 ([079de3e](https://github.com/GuillaumeCisco/vault-kv-search/commit/079de3ea9e6b3e4ef764da19d916281ebc2a7998))
* **deps:** update module github.com/hashicorp/vault/api to v1.12.0 ([e4129f2](https://github.com/GuillaumeCisco/vault-kv-search/commit/e4129f22a4f8463323f90a8e5894b582f2cd0b5a))
* **deps:** update module github.com/hashicorp/vault/api to v1.12.1 ([1cb4487](https://github.com/GuillaumeCisco/vault-kv-search/commit/1cb4487c2bfbe3f9ef26f21c45cd7a36b93c00e0))
* **deps:** update module github.com/hashicorp/vault/api to v1.12.2 ([b9e2f0f](https://github.com/GuillaumeCisco/vault-kv-search/commit/b9e2f0f7633ad7bb4e5093f7eeb1f6d9efceb4ed))
* **deps:** update module github.com/hashicorp/vault/api to v1.13.0 ([9060dda](https://github.com/GuillaumeCisco/vault-kv-search/commit/9060dda018fd6abb39f372c6a1d53fcbd395ccc3))
* **deps:** update module github.com/hashicorp/vault/api to v1.14.0 ([4067a44](https://github.com/GuillaumeCisco/vault-kv-search/commit/4067a44aad29b1cd4bfde1a63fd98b51796c1764))
* **deps:** update module github.com/hashicorp/vault/api to v1.20.0 ([8fa8d56](https://github.com/GuillaumeCisco/vault-kv-search/commit/8fa8d56f00c949a511026a71589c3f80fa9ebe4a))
* **deps:** update module github.com/hashicorp/vault/api to v1.21.0 ([bd3742d](https://github.com/GuillaumeCisco/vault-kv-search/commit/bd3742d43fc240704de3c0b8d288042bc97f0865))
* **deps:** update module github.com/hashicorp/vault/api to v1.22.0 ([1c44389](https://github.com/GuillaumeCisco/vault-kv-search/commit/1c44389f1e1bd3eb412633ae9e7f2045a42bd1c9))
* **deps:** update module github.com/hashicorp/vault/api to v1.9.1 ([ff933e3](https://github.com/GuillaumeCisco/vault-kv-search/commit/ff933e3597ed2141311a8c488eb3778ee69ead2d))
* **deps:** update module github.com/hashicorp/vault/api to v1.9.2 ([2ab904c](https://github.com/GuillaumeCisco/vault-kv-search/commit/2ab904cbbabda9bc0e00e8e20c01390e9619366c))
* **deps:** update module github.com/hashicorp/vault/sdk to v0.17.0 ([8a7616d](https://github.com/GuillaumeCisco/vault-kv-search/commit/8a7616d044aa90cb59c73aa718912f3d7b99b242))
* **deps:** update module github.com/hashicorp/vault/sdk to v0.18.0 ([81adc21](https://github.com/GuillaumeCisco/vault-kv-search/commit/81adc213d950282bb4729bd145e847479d76ad48))
* **deps:** update module github.com/spf13/cobra to v1.10.1 ([588b97e](https://github.com/GuillaumeCisco/vault-kv-search/commit/588b97e822157ecc06affe69ca2182631d8ff46b))
* **deps:** update module github.com/spf13/cobra to v1.10.2 ([730e21c](https://github.com/GuillaumeCisco/vault-kv-search/commit/730e21cd92e68fbd277ef87d4979b0f22ecf354c))
* **deps:** update module github.com/spf13/cobra to v1.7.0 ([e07088e](https://github.com/GuillaumeCisco/vault-kv-search/commit/e07088ed88ff9c44ce61bde4440d6e1382313aad))
* **deps:** update module github.com/spf13/cobra to v1.8.0 ([66c3570](https://github.com/GuillaumeCisco/vault-kv-search/commit/66c35708b9319065810fe137b9e51c36ee301359))
* **deps:** update module github.com/spf13/cobra to v1.8.1 ([58af9ec](https://github.com/GuillaumeCisco/vault-kv-search/commit/58af9ecaa3b3a36f7ea7a3c941c50cc74512fab0))
* **deps:** update module github.com/spf13/cobra to v1.9.1 ([6e25deb](https://github.com/GuillaumeCisco/vault-kv-search/commit/6e25debbf31ec2a65e936307b81e01a08c483d38))
* **deps:** update module github.com/testcontainers/testcontainers-go to v0.38.0 ([8ad1a01](https://github.com/GuillaumeCisco/vault-kv-search/commit/8ad1a0125fb826ba959961115cef1a6d2f48c713))
* **deps:** update module github.com/testcontainers/testcontainers-go to v0.39.0 ([3542de7](https://github.com/GuillaumeCisco/vault-kv-search/commit/3542de78af1f6aeb206ac70cf70c7b24831c5a4e))
* **deps:** update module github.com/testcontainers/testcontainers-go to v0.40.0 ([cebfe14](https://github.com/GuillaumeCisco/vault-kv-search/commit/cebfe145e62fabc21bbc8d8bdce0618b18c629cc))
* **deps:** update module golang.org/x/text to v0.15.0 ([7803d0b](https://github.com/GuillaumeCisco/vault-kv-search/commit/7803d0ba2990ff159f74e4659b2d203277ac65a5))
* **deps:** update module golang.org/x/text to v0.16.0 ([aad4584](https://github.com/GuillaumeCisco/vault-kv-search/commit/aad458426be03f28391be58811616794af11193c))
* **deps:** update module golang.org/x/text to v0.17.0 ([f1401af](https://github.com/GuillaumeCisco/vault-kv-search/commit/f1401afa058a80346a7cd3484647e57d2f6f85a1))
* **deps:** update module golang.org/x/text to v0.23.0 ([fe344b5](https://github.com/GuillaumeCisco/vault-kv-search/commit/fe344b53f5184ab3fa430fe4a540d13a36ead80c))
* **deps:** update module golang.org/x/text to v0.24.0 ([b473d6b](https://github.com/GuillaumeCisco/vault-kv-search/commit/b473d6b03328cc829599cc4eb80d4686ad3d8921))
* **deps:** update module golang.org/x/text to v0.25.0 ([1c21c6c](https://github.com/GuillaumeCisco/vault-kv-search/commit/1c21c6cf3e9ebc218dba4097b199951a959013ef))
* **deps:** update module golang.org/x/text to v0.26.0 ([cd99e01](https://github.com/GuillaumeCisco/vault-kv-search/commit/cd99e019ad9c0531fb6d8f9173be88d201993877))
* **deps:** update module golang.org/x/text to v0.27.0 ([e481458](https://github.com/GuillaumeCisco/vault-kv-search/commit/e481458469894988a46a04ad575d486e8778cbc4))
* **deps:** update module golang.org/x/text to v0.28.0 ([7b045db](https://github.com/GuillaumeCisco/vault-kv-search/commit/7b045db531257824a00b93b3300d5ce6128e4097))
* **deps:** update module golang.org/x/text to v0.29.0 ([a9f457b](https://github.com/GuillaumeCisco/vault-kv-search/commit/a9f457bee633f419d2373a3e6e8ceb348bc204bf))
* **deps:** update module golang.org/x/text to v0.30.0 ([19b66bc](https://github.com/GuillaumeCisco/vault-kv-search/commit/19b66bcc74971e2edce2a5727a0935b55bd99072))
* **deps:** update module golang.org/x/text to v0.31.0 ([72f9c4e](https://github.com/GuillaumeCisco/vault-kv-search/commit/72f9c4e90268e1f144c65a537fb1ea6d0657ffc6))
* **deps:** update module golang.org/x/text to v0.32.0 ([baac5d8](https://github.com/GuillaumeCisco/vault-kv-search/commit/baac5d88385d6c4d8c755fcce7a503e10abd2912))
* search in fullpath ([6afa8a0](https://github.com/GuillaumeCisco/vault-kv-search/commit/6afa8a0e55e8f512e8472859496644cbb39199bd))
* **search:** resolve nested map search in digDeeper function ([bddd5ff](https://github.com/GuillaumeCisco/vault-kv-search/commit/bddd5ff231140eaebbebd9e7ce15e480814c90aa)), closes [#111](https://github.com/GuillaumeCisco/vault-kv-search/issues/111)
* some forgotten cyrinux here ([1add8cd](https://github.com/GuillaumeCisco/vault-kv-search/commit/1add8cd63a1c674cc3e4d8fae1910096df252e26))

## [0.3.8](https://github.com/xbglowx/vault-kv-search/compare/v0.3.7...v0.3.8) (2025-12-09)


### Bug Fixes

* **deps:** update module github.com/spf13/cobra to v1.10.2 ([730e21c](https://github.com/xbglowx/vault-kv-search/commit/730e21cd92e68fbd277ef87d4979b0f22ecf354c))
* **deps:** update module golang.org/x/text to v0.32.0 ([baac5d8](https://github.com/xbglowx/vault-kv-search/commit/baac5d88385d6c4d8c755fcce7a503e10abd2912))

## [0.3.7](https://github.com/xbglowx/vault-kv-search/compare/v0.3.6...v0.3.7) (2025-11-20)


### Bug Fixes

* **deps:** update module github.com/testcontainers/testcontainers-go to v0.40.0 ([cebfe14](https://github.com/xbglowx/vault-kv-search/commit/cebfe145e62fabc21bbc8d8bdce0618b18c629cc))
* **deps:** update module golang.org/x/text to v0.31.0 ([72f9c4e](https://github.com/xbglowx/vault-kv-search/commit/72f9c4e90268e1f144c65a537fb1ea6d0657ffc6))

## [0.3.6](https://github.com/xbglowx/vault-kv-search/compare/v0.3.5...v0.3.6) (2025-10-24)


### Bug Fixes

* **deps:** update module golang.org/x/text to v0.30.0 ([19b66bc](https://github.com/xbglowx/vault-kv-search/commit/19b66bcc74971e2edce2a5727a0935b55bd99072))

## [0.3.5](https://github.com/xbglowx/vault-kv-search/compare/v0.3.4...v0.3.5) (2025-10-03)


### Bug Fixes

* **deps:** update module github.com/hashicorp/vault/api to v1.22.0 ([1c44389](https://github.com/xbglowx/vault-kv-search/commit/1c44389f1e1bd3eb412633ae9e7f2045a42bd1c9))

## [0.3.4](https://github.com/xbglowx/vault-kv-search/compare/v0.3.3...v0.3.4) (2025-09-19)


### Bug Fixes

* **deps:** update module github.com/testcontainers/testcontainers-go to v0.39.0 ([3542de7](https://github.com/xbglowx/vault-kv-search/commit/3542de78af1f6aeb206ac70cf70c7b24831c5a4e))

## [0.3.3](https://github.com/xbglowx/vault-kv-search/compare/v0.3.2...v0.3.3) (2025-09-10)


### Bug Fixes

* **deps:** update module github.com/hashicorp/vault/api to v1.21.0 ([bd3742d](https://github.com/xbglowx/vault-kv-search/commit/bd3742d43fc240704de3c0b8d288042bc97f0865))

## [0.3.2](https://github.com/xbglowx/vault-kv-search/compare/v0.3.1...v0.3.2) (2025-09-08)


### Bug Fixes

* **deps:** update module golang.org/x/text to v0.29.0 ([a9f457b](https://github.com/xbglowx/vault-kv-search/commit/a9f457bee633f419d2373a3e6e8ceb348bc204bf))

## [0.3.1](https://github.com/xbglowx/vault-kv-search/compare/v0.3.0...v0.3.1) (2025-09-01)


### Bug Fixes

* **deps:** update module github.com/spf13/cobra to v1.10.1 ([588b97e](https://github.com/xbglowx/vault-kv-search/commit/588b97e822157ecc06affe69ca2182631d8ff46b))
* **deps:** update module github.com/testcontainers/testcontainers-go to v0.38.0 ([8ad1a01](https://github.com/xbglowx/vault-kv-search/commit/8ad1a0125fb826ba959961115cef1a6d2f48c713))

## [0.3.0](https://github.com/xbglowx/vault-kv-search/compare/v0.2.1...v0.3.0) (2025-08-23)


### Features

* add regex search test ([b494546](https://github.com/xbglowx/vault-kv-search/commit/b49454627b0e6c0e54fced6fdbdd8500c45d7ef5))


### Bug Fixes

* add configurable timeout to resolve context deadline exceeded error ([376cb96](https://github.com/xbglowx/vault-kv-search/commit/376cb9679c1ab8b16b1810c13e308066bb82761b)), closes [#120](https://github.com/xbglowx/vault-kv-search/issues/120)
* **deps:** update module github.com/hashicorp/vault to v1.17.1 ([37d0683](https://github.com/xbglowx/vault-kv-search/commit/37d0683b79bbdc7b8549663af519aa2c857deff9))
* **deps:** update module github.com/hashicorp/vault to v1.18.1 [security] ([f22e357](https://github.com/xbglowx/vault-kv-search/commit/f22e3579f17a47a5ea74105e3efb64b9f2551142))
* **deps:** update module github.com/hashicorp/vault to v1.19.0 ([a11e3bd](https://github.com/xbglowx/vault-kv-search/commit/a11e3bda42c323bf57097b8d559402594bb03173))
* **deps:** update module github.com/hashicorp/vault to v1.19.1 ([749f220](https://github.com/xbglowx/vault-kv-search/commit/749f2206bfa3fb15ee3815c2ecca522814d9c442))
* **deps:** update module github.com/hashicorp/vault to v1.19.5 ([4cddf75](https://github.com/xbglowx/vault-kv-search/commit/4cddf753e53a38b2ac91902e4142f14aefbae841))
* **deps:** update module github.com/hashicorp/vault-plugin-secrets-kv to v0.18.0 ([4f08d4e](https://github.com/xbglowx/vault-kv-search/commit/4f08d4e2406aec261be7552aa76009042a185ff5))
* **deps:** update module github.com/hashicorp/vault-plugin-secrets-kv to v0.23.0 ([033c47d](https://github.com/xbglowx/vault-kv-search/commit/033c47d53abf5d48014de18340a9eb1b547051a5))
* **deps:** update module github.com/hashicorp/vault-plugin-secrets-kv to v0.24.0 ([c871563](https://github.com/xbglowx/vault-kv-search/commit/c871563937aad25b635fd7fa853b0d5cbda349cc))
* **deps:** update module github.com/hashicorp/vault-plugin-secrets-kv to v0.24.1 ([4c1b390](https://github.com/xbglowx/vault-kv-search/commit/4c1b390c420ccfaf7fd48a4dd380b45aba0af6b6))
* **deps:** update module github.com/hashicorp/vault/api to v1.13.0 ([9060dda](https://github.com/xbglowx/vault-kv-search/commit/9060dda018fd6abb39f372c6a1d53fcbd395ccc3))
* **deps:** update module github.com/hashicorp/vault/api to v1.14.0 ([4067a44](https://github.com/xbglowx/vault-kv-search/commit/4067a44aad29b1cd4bfde1a63fd98b51796c1764))
* **deps:** update module github.com/hashicorp/vault/api to v1.20.0 ([8fa8d56](https://github.com/xbglowx/vault-kv-search/commit/8fa8d56f00c949a511026a71589c3f80fa9ebe4a))
* **deps:** update module github.com/hashicorp/vault/sdk to v0.17.0 ([8a7616d](https://github.com/xbglowx/vault-kv-search/commit/8a7616d044aa90cb59c73aa718912f3d7b99b242))
* **deps:** update module github.com/hashicorp/vault/sdk to v0.18.0 ([81adc21](https://github.com/xbglowx/vault-kv-search/commit/81adc213d950282bb4729bd145e847479d76ad48))
* **deps:** update module github.com/spf13/cobra to v1.8.1 ([58af9ec](https://github.com/xbglowx/vault-kv-search/commit/58af9ecaa3b3a36f7ea7a3c941c50cc74512fab0))
* **deps:** update module github.com/spf13/cobra to v1.9.1 ([6e25deb](https://github.com/xbglowx/vault-kv-search/commit/6e25debbf31ec2a65e936307b81e01a08c483d38))
* **deps:** update module golang.org/x/text to v0.15.0 ([7803d0b](https://github.com/xbglowx/vault-kv-search/commit/7803d0ba2990ff159f74e4659b2d203277ac65a5))
* **deps:** update module golang.org/x/text to v0.16.0 ([aad4584](https://github.com/xbglowx/vault-kv-search/commit/aad458426be03f28391be58811616794af11193c))
* **deps:** update module golang.org/x/text to v0.17.0 ([f1401af](https://github.com/xbglowx/vault-kv-search/commit/f1401afa058a80346a7cd3484647e57d2f6f85a1))
* **deps:** update module golang.org/x/text to v0.23.0 ([fe344b5](https://github.com/xbglowx/vault-kv-search/commit/fe344b53f5184ab3fa430fe4a540d13a36ead80c))
* **deps:** update module golang.org/x/text to v0.24.0 ([b473d6b](https://github.com/xbglowx/vault-kv-search/commit/b473d6b03328cc829599cc4eb80d4686ad3d8921))
* **deps:** update module golang.org/x/text to v0.25.0 ([1c21c6c](https://github.com/xbglowx/vault-kv-search/commit/1c21c6cf3e9ebc218dba4097b199951a959013ef))
* **deps:** update module golang.org/x/text to v0.26.0 ([cd99e01](https://github.com/xbglowx/vault-kv-search/commit/cd99e019ad9c0531fb6d8f9173be88d201993877))
* **deps:** update module golang.org/x/text to v0.27.0 ([e481458](https://github.com/xbglowx/vault-kv-search/commit/e481458469894988a46a04ad575d486e8778cbc4))
* **deps:** update module golang.org/x/text to v0.28.0 ([7b045db](https://github.com/xbglowx/vault-kv-search/commit/7b045db531257824a00b93b3300d5ce6128e4097))
* **search:** resolve nested map search in digDeeper function ([bddd5ff](https://github.com/xbglowx/vault-kv-search/commit/bddd5ff231140eaebbebd9e7ce15e480814c90aa)), closes [#111](https://github.com/xbglowx/vault-kv-search/issues/111)
