# Changes

## [1.50.0](https://github.com/googleapis/google-cloud-go/compare/spanner/v1.49.0...spanner/v1.50.0) (2023-10-03)


### Features

* **spanner/spansql:** Add support for aggregate functions ([#8498](https://github.com/googleapis/google-cloud-go/issues/8498)) ([d440d75](https://github.com/googleapis/google-cloud-go/commit/d440d75f19286653afe4bc81a5f2efcfc4fa152c))
* **spanner/spansql:** Add support for bit functions, sequence functions and GENERATE_UUID ([#8482](https://github.com/googleapis/google-cloud-go/issues/8482)) ([3789882](https://github.com/googleapis/google-cloud-go/commit/3789882c8b30a6d3100a56c1dcc8844952605637))
* **spanner/spansql:** Add support for SEQUENCE statements ([#8481](https://github.com/googleapis/google-cloud-go/issues/8481)) ([ccd0205](https://github.com/googleapis/google-cloud-go/commit/ccd020598921f1b5550587c95b4ceddf580705bb))
* **spanner:** Add BatchWrite API ([02a899c](https://github.com/googleapis/google-cloud-go/commit/02a899c95eb9660128506cf94525c5a75bedb308))
* **spanner:** Allow non-default service accounts ([#8488](https://github.com/googleapis/google-cloud-go/issues/8488)) ([c90dd00](https://github.com/googleapis/google-cloud-go/commit/c90dd00350fa018dbc5f0af5aabce80e80be0b90))

## [1.49.0](https://github.com/googleapis/google-cloud-go/compare/spanner/v1.48.0...spanner/v1.49.0) (2023-08-24)


### Features

* **spanner/spannertest:** Support INSERT DML ([#7820](https://github.com/googleapis/google-cloud-go/issues/7820)) ([3dda7b2](https://github.com/googleapis/google-cloud-go/commit/3dda7b27ec536637d8ebaa20937fc8019c930481))


### Bug Fixes

* **spanner:** Transaction was started in a different session ([#8467](https://github.com/googleapis/google-cloud-go/issues/8467)) ([6c21558](https://github.com/googleapis/google-cloud-go/commit/6c21558f75628908a70de79c62aff2851e756e7b))

## [1.48.0](https://github.com/googleapis/google-cloud-go/compare/spanner/v1.47.0...spanner/v1.48.0) (2023-08-18)


### Features

* **spanner/spansql:** Add complete set of math functions ([#8246](https://github.com/googleapis/google-cloud-go/issues/8246)) ([d7a238e](https://github.com/googleapis/google-cloud-go/commit/d7a238eca2a9b08e968cea57edc3708694673e22))
* **spanner/spansql:** Add support for foreign key actions ([#8296](https://github.com/googleapis/google-cloud-go/issues/8296)) ([d78b851](https://github.com/googleapis/google-cloud-go/commit/d78b8513b13a9a2c04b8097f0d89f85dcfd73797))
* **spanner/spansql:** Add support for IF NOT EXISTS and IF EXISTS clause ([#8245](https://github.com/googleapis/google-cloud-go/issues/8245)) ([96840ab](https://github.com/googleapis/google-cloud-go/commit/96840ab1232bbdb788e37f81cf113ee0f1b4e8e7))
* **spanner:** Add integration tests for Bit Reversed Sequences ([#7924](https://github.com/googleapis/google-cloud-go/issues/7924)) ([9b6e7c6](https://github.com/googleapis/google-cloud-go/commit/9b6e7c6061dc69683d7f558faed7f4249da5b7cb))


### Bug Fixes

* **spanner:** Reset buffer after abort on first SQL statement ([#8440](https://github.com/googleapis/google-cloud-go/issues/8440)) ([d980b42](https://github.com/googleapis/google-cloud-go/commit/d980b42f33968ef25061be50e18038d73b0503b6))
* **spanner:** REST query UpdateMask bug ([df52820](https://github.com/googleapis/google-cloud-go/commit/df52820b0e7721954809a8aa8700b93c5662dc9b))

## [1.47.0](https://github.com/googleapis/google-cloud-go/compare/spanner/v1.46.0...spanner/v1.47.0) (2023-06-20)


### Features

* **spanner/admin/database:** Add DdlStatementActionInfo and add actions to UpdateDatabaseDdlMetadata ([01eff11](https://github.com/googleapis/google-cloud-go/commit/01eff11eedb3edde69cc33db23e26be6a7e42f10))
* **spanner:** Add databoost property for batch transactions ([#8152](https://github.com/googleapis/google-cloud-go/issues/8152)) ([fc49c78](https://github.com/googleapis/google-cloud-go/commit/fc49c78c9503c6dd4cbcba8c15e887415a744136))
* **spanner:** Add tests for database roles in PG dialect ([#7898](https://github.com/googleapis/google-cloud-go/issues/7898)) ([dc84649](https://github.com/googleapis/google-cloud-go/commit/dc84649c546fe09b0bab09991086c156bd78cb3f))
* **spanner:** Enable client to server compression ([#7899](https://github.com/googleapis/google-cloud-go/issues/7899)) ([3a047d2](https://github.com/googleapis/google-cloud-go/commit/3a047d2a449b0316a9000539ec9797e47cdd5c91))
* **spanner:** Update all direct dependencies ([b340d03](https://github.com/googleapis/google-cloud-go/commit/b340d030f2b52a4ce48846ce63984b28583abde6))


### Bug Fixes

* **spanner:** Fix TestRetryInfoTransactionOutcomeUnknownError flaky behaviour ([#7959](https://github.com/googleapis/google-cloud-go/issues/7959)) ([f037795](https://github.com/googleapis/google-cloud-go/commit/f03779538f949fb4ad93d5247d3c6b3e5b21091a))

## [1.46.0](https://github.com/googleapis/google-cloud-go/compare/spanner/v1.45.1...spanner/v1.46.0) (2023-05-12)


### Features

* **spanner/admin/database:** Add support for UpdateDatabase in Cloud Spanner ([#7917](https://github.com/googleapis/google-cloud-go/issues/7917)) ([83870f5](https://github.com/googleapis/google-cloud-go/commit/83870f55035d6692e22264b209e39e07fe2823b9))
* **spanner:** Make leader aware routing default enabled for supported RPC requests. ([#7912](https://github.com/googleapis/google-cloud-go/issues/7912)) ([d0d3755](https://github.com/googleapis/google-cloud-go/commit/d0d37550911f37e09ea9204d0648fb64ff3204ff))


### Bug Fixes

* **spanner:** Update grpc to v1.55.0 ([1147ce0](https://github.com/googleapis/google-cloud-go/commit/1147ce02a990276ca4f8ab7a1ab65c14da4450ef))

## [1.45.1](https://github.com/googleapis/google-cloud-go/compare/spanner/v1.45.0...spanner/v1.45.1) (2023-04-21)


### Bug Fixes

* **spanner/spannertest:** Send transaction id in result metadata ([#7809](https://github.com/googleapis/google-cloud-go/issues/7809)) ([e3bbd5f](https://github.com/googleapis/google-cloud-go/commit/e3bbd5f10b3922ab2eb50cb39daccd7bc1891892))
* **spanner:** Context timeout should be wrapped correctly ([#7744](https://github.com/googleapis/google-cloud-go/issues/7744)) ([f8e22f6](https://github.com/googleapis/google-cloud-go/commit/f8e22f6cbba10fc262e87b4d06d5c1289d877503))

## [1.45.0](https://github.com/googleapis/google-cloud-go/compare/spanner/v1.44.0...spanner/v1.45.0) (2023-04-10)


### Features

* **spanner/spansql:** Add support for missing DDL syntax for ALTER CHANGE STREAM ([#7429](https://github.com/googleapis/google-cloud-go/issues/7429)) ([d34fe02](https://github.com/googleapis/google-cloud-go/commit/d34fe02cfa31520f88dedbd41bbc887e8faa857f))
* **spanner/spansql:** Support fine-grained access control DDL syntax ([#6691](https://github.com/googleapis/google-cloud-go/issues/6691)) ([a7edf6b](https://github.com/googleapis/google-cloud-go/commit/a7edf6b5c62d02b7d5199fc83d435f6a37a8eac5))
* **spanner/spansql:** Support grant/revoke view, change stream, table function ([#7533](https://github.com/googleapis/google-cloud-go/issues/7533)) ([9c61215](https://github.com/googleapis/google-cloud-go/commit/9c612159647d540e694ec9e84cab5cdd1c94d2b8))
* **spanner:** Add x-goog-spanner-route-to-leader header to Spanner RPC contexts for RW/PDML transactions. ([#7500](https://github.com/googleapis/google-cloud-go/issues/7500)) ([fcab05f](https://github.com/googleapis/google-cloud-go/commit/fcab05faa5026896af76b762eed5b7b6b2e7ee07))
* **spanner:** Adding new fields for Serverless analytics ([69067f8](https://github.com/googleapis/google-cloud-go/commit/69067f8c0075099a84dd9d40e438711881710784))
* **spanner:** Enable custom decoding for list value ([#7463](https://github.com/googleapis/google-cloud-go/issues/7463)) ([3aeadcd](https://github.com/googleapis/google-cloud-go/commit/3aeadcd97eaf2707c2f6e288c8b72ef29f49a185))
* **spanner:** Update iam and longrunning deps ([91a1f78](https://github.com/googleapis/google-cloud-go/commit/91a1f784a109da70f63b96414bba8a9b4254cddd))


### Bug Fixes

* **spanner/spansql:** Fix SQL for CREATE CHANGE STREAM TableName; case ([#7514](https://github.com/googleapis/google-cloud-go/issues/7514)) ([fc5fd86](https://github.com/googleapis/google-cloud-go/commit/fc5fd8652771aeca73e7a28ee68134155a5a9499))
* **spanner:** Correcting the proto field Id for field data_boost_enabled ([00fff3a](https://github.com/googleapis/google-cloud-go/commit/00fff3a58bed31274ab39af575876dab91d708c9))

## [1.44.0](https://github.com/googleapis/google-cloud-go/compare/spanner/v1.43.0...spanner/v1.44.0) (2023-02-01)


### Features

* **spanner/spansql:** Add support for ALTER INDEX statement ([#7287](https://github.com/googleapis/google-cloud-go/issues/7287)) ([fbe1bd4](https://github.com/googleapis/google-cloud-go/commit/fbe1bd4d0806302a48ff4a5822867757893a5f2d))
* **spanner/spansql:** Add support for managing the optimizer statistics package ([#7283](https://github.com/googleapis/google-cloud-go/issues/7283)) ([e528221](https://github.com/googleapis/google-cloud-go/commit/e52822139e2821a11873c2d6af85a5fea07700e8))
* **spanner:** Add support for Optimistic Concurrency Control ([#7332](https://github.com/googleapis/google-cloud-go/issues/7332)) ([48ba16f](https://github.com/googleapis/google-cloud-go/commit/48ba16f3a09893a3527a22838ad1e9ff829da15b))

## [1.43.0](https://github.com/googleapis/google-cloud-go/compare/spanner/v1.42.0...spanner/v1.43.0) (2023-01-19)


### Features

* **spanner/spansql:** Add support for change stream value_capture_type option ([#7201](https://github.com/googleapis/google-cloud-go/issues/7201)) ([27b3398](https://github.com/googleapis/google-cloud-go/commit/27b33988f078779c2d641f776a11b2095a5ccc51))
* **spanner/spansql:** Support `default_leader` database option ([#7187](https://github.com/googleapis/google-cloud-go/issues/7187)) ([88adaa2](https://github.com/googleapis/google-cloud-go/commit/88adaa216832467560c19e61528b5ce5f1e5ff76))
* **spanner:** Add REST client ([06a54a1](https://github.com/googleapis/google-cloud-go/commit/06a54a16a5866cce966547c51e203b9e09a25bc0))
* **spanner:** Inline begin transaction for ReadWriteTransactions ([#7149](https://github.com/googleapis/google-cloud-go/issues/7149)) ([2ce3606](https://github.com/googleapis/google-cloud-go/commit/2ce360644439a386aeaad7df5f47541667bd621b))


### Bug Fixes

* **spanner:** Fix integration tests data race ([#7229](https://github.com/googleapis/google-cloud-go/issues/7229)) ([a741024](https://github.com/googleapis/google-cloud-go/commit/a741024abd6fb1f073831503c2717b2a44226a59))

## [1.42.0](https://github.com/googleapis/google-cloud-go/compare/spanner/v1.41.0...spanner/v1.42.0) (2022-12-14)


### Features

* **spanner:** Add database roles ([#5701](https://github.com/googleapis/google-cloud-go/issues/5701)) ([6bb95ef](https://github.com/googleapis/google-cloud-go/commit/6bb95efb7997692a52c321e787e633a5045b21f8))
* **spanner:** Rewrite signatures and type in terms of new location ([620e6d8](https://github.com/googleapis/google-cloud-go/commit/620e6d828ad8641663ae351bfccfe46281e817ad))


### Bug Fixes

* **spanner:** Fallback to check grpc error message if ResourceType is nil for checking sessionNotFound errors ([#7163](https://github.com/googleapis/google-cloud-go/issues/7163)) ([2552e09](https://github.com/googleapis/google-cloud-go/commit/2552e092cff01e0d6b80fefaa7877f77e36db6be))

## [1.41.0](https://github.com/googleapis/google-cloud-go/compare/spanner/v1.40.0...spanner/v1.41.0) (2022-12-01)


### Features

* **spanner:** Start generating proto stubs ([#7030](https://github.com/googleapis/google-cloud-go/issues/7030)) ([41f446f](https://github.com/googleapis/google-cloud-go/commit/41f446f891a17c97278879f2207fd58996fd038c))

## [1.40.0](https://github.com/googleapis/google-cloud-go/compare/spanner/v1.39.0...spanner/v1.40.0) (2022-11-03)


### Features

* **spanner/spansql:** Add support for interval arg of some date/timestamp functions ([#6950](https://github.com/googleapis/google-cloud-go/issues/6950)) ([1ce0f7d](https://github.com/googleapis/google-cloud-go/commit/1ce0f7d38778068fd1d9a171377067739f4ea8d6))
* **spanner:** Configurable logger ([#6958](https://github.com/googleapis/google-cloud-go/issues/6958)) ([bd85442](https://github.com/googleapis/google-cloud-go/commit/bd85442bc6fb8c18d1a7c6d73850d220c3973c46)), refs [#6957](https://github.com/googleapis/google-cloud-go/issues/6957)
* **spanner:** PG JSONB support ([#6874](https://github.com/googleapis/google-cloud-go/issues/6874)) ([5b14658](https://github.com/googleapis/google-cloud-go/commit/5b146587939ccc3403945c756cbf68e6f2d41fda))
* **spanner:** Update result_set.proto to return undeclared parameters in ExecuteSql API ([de4e16a](https://github.com/googleapis/google-cloud-go/commit/de4e16a498354ea7271f5b396f7cb2bb430052aa))
* **spanner:** Update transaction.proto to include different lock modes ([caf4afa](https://github.com/googleapis/google-cloud-go/commit/caf4afa139ad7b38b6df3e3b17b8357c81e1fd6c))

## [1.39.0](https://github.com/googleapis/google-cloud-go/compare/spanner/v1.38.0...spanner/v1.39.0) (2022-09-21)


### Features

* **spanner/admin/database:** Add custom instance config operations ([ec1a190](https://github.com/googleapis/google-cloud-go/commit/ec1a190abbc4436fcaeaa1421c7d9df624042752))
* **spanner/admin/instance:** Add custom instance config operations ([ef2b0b1](https://github.com/googleapis/google-cloud-go/commit/ef2b0b1d4de9beb9005537ae48d7d8e1c0f23b98))
* **spanner/spannersql:** Add backticks when name contains a hypen ([#6621](https://github.com/googleapis/google-cloud-go/issues/6621)) ([e88ca66](https://github.com/googleapis/google-cloud-go/commit/e88ca66ca950e15d9011322dbfca3c88ccceb0ec))
* **spanner/spansql:** Add support for create, alter and drop change … ([#6669](https://github.com/googleapis/google-cloud-go/issues/6669)) ([cc4620a](https://github.com/googleapis/google-cloud-go/commit/cc4620a5ee3a9129a4cdd48d90d4060ba0bbcd58))
* **spanner:** Retry spanner transactions and mutations when RST_STREAM error ([#6699](https://github.com/googleapis/google-cloud-go/issues/6699)) ([1b56cd0](https://github.com/googleapis/google-cloud-go/commit/1b56cd0ec31bc32362259fc722907e092bae081a))


### Bug Fixes

* **spanner/admin/database:** Revert add custom instance config operations (change broke client libraries; reverting before any are released) ([ec1a190](https://github.com/googleapis/google-cloud-go/commit/ec1a190abbc4436fcaeaa1421c7d9df624042752))
* **spanner:** Destroy session when client is closing ([#6700](https://github.com/googleapis/google-cloud-go/issues/6700)) ([a1ce541](https://github.com/googleapis/google-cloud-go/commit/a1ce5410f1e0f4d68dae0ddc790518e9978faf0c))
* **spanner:** Spanner sessions will be cleaned up from the backend ([#6679](https://github.com/googleapis/google-cloud-go/issues/6679)) ([c27097e](https://github.com/googleapis/google-cloud-go/commit/c27097e236abeb8439a67ad9b716d05c001aea2e))

## [1.38.0](https://github.com/googleapis/google-cloud-go/compare/spanner/v1.37.0...spanner/v1.38.0) (2022-09-03)


### Features

* **spanner/spannertest:** add support for adding and dropping Foreign Keys ([#6608](https://github.com/googleapis/google-cloud-go/issues/6608)) ([ccd3614](https://github.com/googleapis/google-cloud-go/commit/ccd3614f6edbaf3d7d202feb4df220f244550a78))
* **spanner/spansql:** add support for coalesce expressions ([#6461](https://github.com/googleapis/google-cloud-go/issues/6461)) ([bff16a7](https://github.com/googleapis/google-cloud-go/commit/bff16a783c1fd4d7e888d4ee3b5420c1bbf10da1))
* **spanner:** Adds auto-generated CL for googleapis for jsonb ([3bc37e2](https://github.com/googleapis/google-cloud-go/commit/3bc37e28626df5f7ec37b00c0c2f0bfb91c30495))


### Bug Fixes

* **spanner:** pass userAgent to cloud spanner requests ([#6598](https://github.com/googleapis/google-cloud-go/issues/6598)) ([59d162b](https://github.com/googleapis/google-cloud-go/commit/59d162bdfcbe00a060a52930be7185f00e8df2c1))

## [1.37.0](https://github.com/googleapis/google-cloud-go/compare/spanner/v1.36.0...spanner/v1.37.0) (2022-08-28)


### Features

* **spanner/admin/database:** Add ListDatabaseRoles API to support role based access control ([1ffeb95](https://github.com/googleapis/google-cloud-go/commit/1ffeb9557bf1f18cc131aff40ec7e0e15a9f4ead))
* **spanner/spansql:** add support for nullif expressions ([#6423](https://github.com/googleapis/google-cloud-go/issues/6423)) ([5b7bfeb](https://github.com/googleapis/google-cloud-go/commit/5b7bfebcd4a0fd3cbe355d9d290e6b5101810b7e))
* **spanner:** install grpc rls and xds by default ([#6007](https://github.com/googleapis/google-cloud-go/issues/6007)) ([70d562f](https://github.com/googleapis/google-cloud-go/commit/70d562f25738052e833a46daf6ff7fa1f4a0a746))
* **spanner:** set client wide ReadOptions, ApplyOptions, and TransactionOptions ([#6486](https://github.com/googleapis/google-cloud-go/issues/6486)) ([757f1ca](https://github.com/googleapis/google-cloud-go/commit/757f1cac7a765fe2e7ead872d07eb24baad61c28))


### Bug Fixes

* **spanner/admin/database:** target new spanner db admin service config ([1d6fbcc](https://github.com/googleapis/google-cloud-go/commit/1d6fbcc6406e2063201ef5a98de560bf32f7fb73))

## [1.36.0](https://github.com/googleapis/google-cloud-go/compare/spanner/v1.35.0...spanner/v1.36.0) (2022-07-23)


### Features

* **spanner/spansql:** add support for IFNULL expressions ([#6389](https://github.com/googleapis/google-cloud-go/issues/6389)) ([09e96ce](https://github.com/googleapis/google-cloud-go/commit/09e96ce1076df4b41d45c3676b7506b318da6b9c))
* **spanner/spansql:** support for parsing a DML file ([#6349](https://github.com/googleapis/google-cloud-go/issues/6349)) ([267a9bb](https://github.com/googleapis/google-cloud-go/commit/267a9bbec55ee8fe885354efc8db8a61a17a8374))

## [1.35.0](https://github.com/googleapis/google-cloud-go/compare/spanner/v1.34.1...spanner/v1.35.0) (2022-07-19)


### Features

* **spanner/admin/instance:** Adding two new fields for Instance create_time and update_time ([8a1ad06](https://github.com/googleapis/google-cloud-go/commit/8a1ad06572a65afa91a0a77a85b849e766876671))
* **spanner/spansql:** add support for if expressions ([#6341](https://github.com/googleapis/google-cloud-go/issues/6341)) ([56c858c](https://github.com/googleapis/google-cloud-go/commit/56c858cebd683e45d1dd5ab8ae98ef9bfd767edc))


### Bug Fixes

* **spanner:** fix pool.numInUse exceeding MaxOpened ([#6344](https://github.com/googleapis/google-cloud-go/issues/6344)) ([882b325](https://github.com/googleapis/google-cloud-go/commit/882b32593e8c7bff8369b1ff9259c7b408fad661))

## [1.34.1](https://github.com/googleapis/google-cloud-go/compare/spanner/v1.34.0...spanner/v1.34.1) (2022-07-06)


### Bug Fixes

* **spanner/spansql:** Add tests for INSERT parsing ([#6303](https://github.com/googleapis/google-cloud-go/issues/6303)) ([0d19fb5](https://github.com/googleapis/google-cloud-go/commit/0d19fb5d60554b9a90fac52918f784e6c3e13918))

## [1.34.0](https://github.com/googleapis/google-cloud-go/compare/spanner/v1.33.0...spanner/v1.34.0) (2022-06-17)


### Features

* **spanner/spansql:** add a support for parsing INSERT statement ([#6148](https://github.com/googleapis/google-cloud-go/issues/6148)) ([c6185cf](https://github.com/googleapis/google-cloud-go/commit/c6185cffc7f23741ac4a230aadee74b3def85ced))
* **spanner:** add Session creator role docs: clarify transaction semantics ([4134941](https://github.com/googleapis/google-cloud-go/commit/41349411e601f57dc6d9e246f1748fd86d17bb15))

## [1.33.0](https://github.com/googleapis/google-cloud-go/compare/spanner/v1.32.0...spanner/v1.33.0) (2022-05-28)


### Bug Fixes

* **spanner/spansql:** fix invalid timestamp literal formats ([#6077](https://github.com/googleapis/google-cloud-go/issues/6077)) ([6ab8bed](https://github.com/googleapis/google-cloud-go/commit/6ab8bed93a978e00a6c195d8cb4d574ca6db27c3))


### Miscellaneous Chores

* **spanner:** release 1.33.0 ([#6104](https://github.com/googleapis/google-cloud-go/issues/6104)) ([54bc54e](https://github.com/googleapis/google-cloud-go/commit/54bc54e9bbdc22e2bbfd9f315885f95987e2c3f2))

## [1.32.0](https://github.com/googleapis/google-cloud-go/compare/spanner/v1.31.0...spanner/v1.32.0) (2022-05-09)


### Features

* **spanner/spansql:** support DEFAULT keyword ([#5932](https://github.com/googleapis/google-cloud-go/issues/5932)) ([49c19a9](https://github.com/googleapis/google-cloud-go/commit/49c19a956031fa889d024bd57fa34681bc79e743))
* **spanner/spansql:** support JSON literals ([#5968](https://github.com/googleapis/google-cloud-go/issues/5968)) ([b500120](https://github.com/googleapis/google-cloud-go/commit/b500120f3cc5c7b5717f6525a24de72fd317ba66))
* **spanner:** enable row.ToStructLenient to work with STRUCT data type ([#5944](https://github.com/googleapis/google-cloud-go/issues/5944)) ([bca8d50](https://github.com/googleapis/google-cloud-go/commit/bca8d50533115b9995f7b4a63d5d1f9abaf6a753))

## [1.31.0](https://github.com/googleapis/google-cloud-go/compare/spanner/v1.30.1...spanner/v1.31.0) (2022-04-08)


### Features

* **spanner/spansql:** support case expression ([#5836](https://github.com/googleapis/google-cloud-go/issues/5836)) ([3ffdd62](https://github.com/googleapis/google-cloud-go/commit/3ffdd626e72c6472f337a423b9702baf0c298185))


### Bug Fixes

* **spanner/spannertest:** Improve DDL application delay cancellation. ([#5874](https://github.com/googleapis/google-cloud-go/issues/5874)) ([08f1e72](https://github.com/googleapis/google-cloud-go/commit/08f1e72dbf2ef5a06425f71500d061af246bd490))

### [1.30.1](https://github.com/googleapis/google-cloud-go/compare/spanner/v1.30.0...spanner/v1.30.1) (2022-03-28)


### Bug Fixes

* **spanner:** early unlock of session pool lock during dumping the tracked session handles to avoid deadlock ([#5777](https://github.com/googleapis/google-cloud-go/issues/5777)) ([b007836](https://github.com/googleapis/google-cloud-go/commit/b0078362865159b87bc34c1a7f990a361f1cafcf))

## [1.30.0](https://github.com/googleapis/google-cloud-go/compare/spanner/v1.29.0...spanner/v1.30.0) (2022-03-04)


### Features

* **spanner:** add better version metadata to calls ([#5515](https://github.com/googleapis/google-cloud-go/issues/5515)) ([dcab7c4](https://github.com/googleapis/google-cloud-go/commit/dcab7c4a98ebecfef1f75ec5bddfd7782b28a7c5)), refs [#2749](https://github.com/googleapis/google-cloud-go/issues/2749)
* **spanner:** add file for tracking version ([17b36ea](https://github.com/googleapis/google-cloud-go/commit/17b36ead42a96b1a01105122074e65164357519e))
* **spanner:** add support of PGNumeric with integration tests for PG dialect ([#5700](https://github.com/googleapis/google-cloud-go/issues/5700)) ([f7e02e1](https://github.com/googleapis/google-cloud-go/commit/f7e02e11064d14c04eca18ab808e8fe5194ac355))
* **spanner:** set versionClient to module version ([55f0d92](https://github.com/googleapis/google-cloud-go/commit/55f0d92bf112f14b024b4ab0076c9875a17423c9))

### Bug Fixes

* **spanner/spansql:** support GROUP BY without an aggregation function ([#5717](https://github.com/googleapis/google-cloud-go/issues/5717)) ([c819ee9](https://github.com/googleapis/google-cloud-go/commit/c819ee9ad4695afa31eddcb4bf87764762555cd5))


### Miscellaneous Chores

* **spanner:** release 1.30.0 ([#5715](https://github.com/googleapis/google-cloud-go/issues/5715)) ([a19d182](https://github.com/googleapis/google-cloud-go/commit/a19d182dab5476cf01e719c751e94a73a98c6c4a))

## [1.29.0](https://www.github.com/googleapis/google-cloud-go/compare/spanner/v1.28.0...spanner/v1.29.0) (2022-01-06)


### ⚠ BREAKING CHANGES

* **spanner:** fix data race in spanner integration tests (#5276)

### Features

* **spanner/spansql:** support EXTRACT ([#5218](https://www.github.com/googleapis/google-cloud-go/issues/5218)) ([81b7c85](https://www.github.com/googleapis/google-cloud-go/commit/81b7c85a8993a36557ea4eb4ec0c47d1f93c4960))
* **spanner/spansql:** support MOD function ([#5231](https://www.github.com/googleapis/google-cloud-go/issues/5231)) ([0a81fbc](https://www.github.com/googleapis/google-cloud-go/commit/0a81fbc0171af7e828f3e606cbe7b3905ac32213))
* **spanner:** add google-c2p dependence ([5343756](https://www.github.com/googleapis/google-cloud-go/commit/534375668b5b81bae5ef750c96856bef027f9d1e))
* **spanner:** Add ReadRowWithOptions method ([#5240](https://www.github.com/googleapis/google-cloud-go/issues/5240)) ([c276428](https://www.github.com/googleapis/google-cloud-go/commit/c276428bca79702245d422849af6472bb2e74171))
* **spanner:** Adding GFE Latency and Header Missing Count Metrics ([#5199](https://www.github.com/googleapis/google-cloud-go/issues/5199)) ([3d8a9ea](https://www.github.com/googleapis/google-cloud-go/commit/3d8a9ead8d73a4f38524a424a98362c32f56954b))


### Bug Fixes

* **spanner:** result from unmarshal of string and spanner.NullString type from json should be consistent. ([#5263](https://www.github.com/googleapis/google-cloud-go/issues/5263)) ([7eaaa47](https://www.github.com/googleapis/google-cloud-go/commit/7eaaa470fda5dc7cd1ff041d6a898e35fb54920e))


### Tests

* **spanner:** fix data race in spanner integration tests ([#5276](https://www.github.com/googleapis/google-cloud-go/issues/5276)) ([22df34b](https://www.github.com/googleapis/google-cloud-go/commit/22df34b8e7d0d003b3eeaf1c069aee58f30a8dfe))


### Miscellaneous Chores

* **spanner:** release 1.29.0 ([#5292](https://www.github.com/googleapis/google-cloud-go/issues/5292)) ([9f0b900](https://www.github.com/googleapis/google-cloud-go/commit/9f0b9003686d26c66a10c3b54e67b59c2a6327ff))

## [1.28.0](https://www.github.com/googleapis/google-cloud-go/compare/spanner/v1.27.0...spanner/v1.28.0) (2021-12-03)


### Features

* **spanner/spannertest:** support JSON_VALUE function ([#5173](https://www.github.com/googleapis/google-cloud-go/issues/5173)) ([ac98735](https://www.github.com/googleapis/google-cloud-go/commit/ac98735cb1adc9384c5b2caeb9aac938db275bf7))
* **spanner/spansql:** support CAST and SAFE_CAST ([#5057](https://www.github.com/googleapis/google-cloud-go/issues/5057)) ([54cbf4c](https://www.github.com/googleapis/google-cloud-go/commit/54cbf4c0a0305e680b213f84487110dfeaf8e7e1))
* **spanner:** add ToStructLenient method to decode to struct fields with no error return with un-matched row's column with struct's exported fields. ([#5153](https://www.github.com/googleapis/google-cloud-go/issues/5153)) ([899ffbf](https://www.github.com/googleapis/google-cloud-go/commit/899ffbf8ce42b1597ca3cd59bfd9f042054b8ae2))

## [1.27.0](https://www.github.com/googleapis/google-cloud-go/compare/spanner/v1.26.0...spanner/v1.27.0) (2021-10-19)


### Features

* **spanner:** implement valuer and scanner interfaces ([#4936](https://www.github.com/googleapis/google-cloud-go/issues/4936)) ([4537b45](https://www.github.com/googleapis/google-cloud-go/commit/4537b45d2611ce480abfb5d186b59e7258ec872c))

## [1.26.0](https://www.github.com/googleapis/google-cloud-go/compare/spanner/v1.25.0...spanner/v1.26.0) (2021-10-11)


### Features

* **spanner/spannertest:** implement RowDeletionPolicy in spannertest ([#4961](https://www.github.com/googleapis/google-cloud-go/issues/4961)) ([7800a33](https://www.github.com/googleapis/google-cloud-go/commit/7800a3303b97204a0573780786388437bbbf2673)), refs [#4782](https://www.github.com/googleapis/google-cloud-go/issues/4782)
* **spanner/spannertest:** Support generated columns ([#4742](https://www.github.com/googleapis/google-cloud-go/issues/4742)) ([324d11d](https://www.github.com/googleapis/google-cloud-go/commit/324d11d3c19ffbd77848c8e19c972b70ff5e9268))
* **spanner/spansql:** fill in missing hash functions ([#4808](https://www.github.com/googleapis/google-cloud-go/issues/4808)) ([37ee2d9](https://www.github.com/googleapis/google-cloud-go/commit/37ee2d95220efc1aaf0280d0aa2c01ae4b9d4c1b))
* **spanner/spansql:** support JSON data type ([#4959](https://www.github.com/googleapis/google-cloud-go/issues/4959)) ([e84e408](https://www.github.com/googleapis/google-cloud-go/commit/e84e40830752fc8bc0ccdd869fa7b8fd0c80f306))
* **spanner/spansql:** Support multiple joins in query ([#4743](https://www.github.com/googleapis/google-cloud-go/issues/4743)) ([81a308e](https://www.github.com/googleapis/google-cloud-go/commit/81a308e909a3ae97504a49fbc9982f7eeb6be80c))

## [1.25.0](https://www.github.com/googleapis/google-cloud-go/compare/spanner/v1.24.1...spanner/v1.25.0) (2021-08-25)


### Features

* **spanner/spansql:** add support for STARTS_WITH function ([#4670](https://www.github.com/googleapis/google-cloud-go/issues/4670)) ([7a56af0](https://www.github.com/googleapis/google-cloud-go/commit/7a56af03d1505d9a29d1185a50e261c0e90fdb1a)), refs [#4661](https://www.github.com/googleapis/google-cloud-go/issues/4661)
* **spanner:** add support for JSON data type ([#4104](https://www.github.com/googleapis/google-cloud-go/issues/4104)) ([ade8ab1](https://www.github.com/googleapis/google-cloud-go/commit/ade8ab111315d84fa140ddde020387a78668dfa4))


### Bug Fixes

* **spanner/spannertest:** Fix the "LIKE" clause handling for prefix and suffix matches ([#4655](https://www.github.com/googleapis/google-cloud-go/issues/4655)) ([a2118f0](https://www.github.com/googleapis/google-cloud-go/commit/a2118f02fb03bfc50952699318f35c23dc234c41))
* **spanner:** invalid numeric should throw an error ([#3926](https://www.github.com/googleapis/google-cloud-go/issues/3926)) ([cde8697](https://www.github.com/googleapis/google-cloud-go/commit/cde8697be01f1ef57806275c0ddf54f87bb9a571))

### [1.24.1](https://www.github.com/googleapis/google-cloud-go/compare/spanner/v1.24.0...spanner/v1.24.1) (2021-08-11)


### Bug Fixes

* **spanner/spansql:** only add comma after other option ([#4551](https://www.github.com/googleapis/google-cloud-go/issues/4551)) ([3ac1e00](https://www.github.com/googleapis/google-cloud-go/commit/3ac1e007163803d315dcf5db612fe003f6eab978))
* **spanner:** allow decoding null values to spanner.Decoder ([#4558](https://www.github.com/googleapis/google-cloud-go/issues/4558)) ([45ddaca](https://www.github.com/googleapis/google-cloud-go/commit/45ddaca606a372d9293bf2e2b3dc6d4398166c43)), refs [#4552](https://www.github.com/googleapis/google-cloud-go/issues/4552)

## [1.24.0](https://www.github.com/googleapis/google-cloud-go/compare/spanner/v1.23.0...spanner/v1.24.0) (2021-07-29)


### Features

* **spanner/spansql:** add ROW DELETION POLICY parsing ([#4496](https://www.github.com/googleapis/google-cloud-go/issues/4496)) ([3d6c6c7](https://www.github.com/googleapis/google-cloud-go/commit/3d6c6c7873e1b75e8b492ede2e561411dc40536a))
* **spanner/spansql:** fix unstable SelectFromTable SQL ([#4473](https://www.github.com/googleapis/google-cloud-go/issues/4473)) ([39bc4ec](https://www.github.com/googleapis/google-cloud-go/commit/39bc4eca655d0180b18378c175d4a9a77fe1602f))
* **spanner/spansql:** support ALTER DATABASE ([#4403](https://www.github.com/googleapis/google-cloud-go/issues/4403)) ([1458dc9](https://www.github.com/googleapis/google-cloud-go/commit/1458dc9c21d98ffffb871943f178678cc3c21306))
* **spanner/spansql:** support table_hint_expr at from_clause on query_statement ([#4457](https://www.github.com/googleapis/google-cloud-go/issues/4457)) ([7047808](https://www.github.com/googleapis/google-cloud-go/commit/7047808794cf463c6a96d7b59ef5af3ed94fd7cf))
* **spanner:** add row.String() and refine error message for decoding a struct array ([#4431](https://www.github.com/googleapis/google-cloud-go/issues/4431)) ([f6258a4](https://www.github.com/googleapis/google-cloud-go/commit/f6258a47a4dfadc02dcdd75b53fd5f88c5dcca30))
* **spanner:** allow untyped nil values in parameterized queries ([#4482](https://www.github.com/googleapis/google-cloud-go/issues/4482)) ([c1ba18b](https://www.github.com/googleapis/google-cloud-go/commit/c1ba18b1b1fc45de6e959cc22a5c222cc80433ee))


### Bug Fixes

* **spanner/spansql:** fix DATE and TIMESTAMP parsing. ([#4480](https://www.github.com/googleapis/google-cloud-go/issues/4480)) ([dec7a67](https://www.github.com/googleapis/google-cloud-go/commit/dec7a67a3e980f6f5e0d170919da87e1bffe923f))

## [1.23.0](https://www.github.com/googleapis/google-cloud-go/compare/spanner/v1.22.0...spanner/v1.23.0) (2021-07-08)


### Features

* **spanner/admin/database:** add leader_options to InstanceConfig and default_leader to Database ([7aa0e19](https://www.github.com/googleapis/google-cloud-go/commit/7aa0e195a5536dd060a1fca871bd3c6f946d935e))

## [1.22.0](https://www.github.com/googleapis/google-cloud-go/compare/spanner/v1.21.0...spanner/v1.22.0) (2021-06-30)


### Features

* **spanner:** support request and transaction tags ([#4336](https://www.github.com/googleapis/google-cloud-go/issues/4336)) ([f08c73a](https://www.github.com/googleapis/google-cloud-go/commit/f08c73a75e2d2a8b9a0b184179346cb97c82e9e5))
* **spanner:** enable request options for batch read ([#4337](https://www.github.com/googleapis/google-cloud-go/issues/4337)) ([b9081c3](https://www.github.com/googleapis/google-cloud-go/commit/b9081c36ed6495a67f8e458ad884bdb8da5b7fbc))

## [1.21.0](https://www.github.com/googleapis/google-cloud-go/compare/spanner/v1.20.0...spanner/v1.21.0) (2021-06-23)


### Miscellaneous Chores

* **spanner:** trigger a release for low cost instance ([#4264](https://www.github.com/googleapis/google-cloud-go/issues/4264)) ([24c4451](https://www.github.com/googleapis/google-cloud-go/commit/24c4451404cdf4a83cc7a35ee1911d654d2ba132))

## [1.20.0](https://www.github.com/googleapis/google-cloud-go/compare/spanner/v1.19.0...spanner/v1.20.0) (2021-06-08)


### Features

* **spanner:** add the support of optimizer statistics package ([#2717](https://www.github.com/googleapis/google-cloud-go/issues/2717)) ([29c7247](https://www.github.com/googleapis/google-cloud-go/commit/29c724771f0b19849c76e62d4bc8e9342922bf75))

## [1.19.0](https://www.github.com/googleapis/google-cloud-go/compare/spanner/v1.18.0...spanner/v1.19.0) (2021-06-03)


### Features

* **spanner/spannertest:** support multiple aggregations ([#3965](https://www.github.com/googleapis/google-cloud-go/issues/3965)) ([1265dc3](https://www.github.com/googleapis/google-cloud-go/commit/1265dc3289693f79fcb9c5785a424eb510a50007))
* **spanner/spansql:** case insensitive parsing of keywords and functions ([#4034](https://www.github.com/googleapis/google-cloud-go/issues/4034)) ([ddb09d2](https://www.github.com/googleapis/google-cloud-go/commit/ddb09d22a737deea0d0a9ab58cd5d337164bbbfe))
* **spanner:** add a database name getter to client ([#4190](https://www.github.com/googleapis/google-cloud-go/issues/4190)) ([7fce29a](https://www.github.com/googleapis/google-cloud-go/commit/7fce29af404f0623b483ca6d6f2af4c726105fa6))
* **spanner:** add custom instance config to tests ([#4194](https://www.github.com/googleapis/google-cloud-go/issues/4194)) ([e935345](https://www.github.com/googleapis/google-cloud-go/commit/e9353451237e658bde2e41b30e8270fbc5987b39))


### Bug Fixes

* **spanner:** add missing NUMERIC type to the doc for Row ([#4116](https://www.github.com/googleapis/google-cloud-go/issues/4116)) ([9a3b416](https://www.github.com/googleapis/google-cloud-go/commit/9a3b416221f3c8b3793837e2a459b1d7cd9c479f))
* **spanner:** indent code example for Encoder and Decoder ([#4128](https://www.github.com/googleapis/google-cloud-go/issues/4128)) ([7c1f48f](https://www.github.com/googleapis/google-cloud-go/commit/7c1f48f307284c26c10cd5787dbc94136a2a36a6))
* **spanner:** mark SessionPoolConfig.MaxBurst deprecated ([#4115](https://www.github.com/googleapis/google-cloud-go/issues/4115)) ([d60a686](https://www.github.com/googleapis/google-cloud-go/commit/d60a68649f85f1edfbd8f11673bb280813c2b771))

## [1.18.0](https://www.github.com/googleapis/google-cloud-go/compare/spanner/v1.17.0...spanner/v1.18.0) (2021-04-29)


### Features

* **spanner/admin/database:** add `progress` field to `UpdateDatabaseDdlMetadata` ([9029071](https://www.github.com/googleapis/google-cloud-go/commit/90290710158cf63de918c2d790df48f55a23adc5))

## [1.17.0](https://www.github.com/googleapis/google-cloud-go/compare/spanner/v1.16.0...spanner/v1.17.0) (2021-03-31)


### Features

* **spanner/admin/database:** add tagging request options ([2b02a03](https://www.github.com/googleapis/google-cloud-go/commit/2b02a03ff9f78884da5a8e7b64a336014c61bde7))
* **spanner:** add RPC Priority request options ([b5b4da6](https://www.github.com/googleapis/google-cloud-go/commit/b5b4da6952922440d03051f629f3166f731dfaa3))
* **spanner:** Add support for RPC priority ([#3341](https://www.github.com/googleapis/google-cloud-go/issues/3341)) ([88cf097](https://www.github.com/googleapis/google-cloud-go/commit/88cf097649f1cdf01cab531eabdff7fbf2be3f8f))

## [1.16.0](https://www.github.com/googleapis/google-cloud-go/compare/v1.15.0...v1.16.0) (2021-03-17)


### Features

* **spanner:** add `optimizer_statistics_package` field in `QueryOptions` ([18c88c4](https://www.github.com/googleapis/google-cloud-go/commit/18c88c437bd1741eaf5bf5911b9da6f6ea7cd75d))
* **spanner/admin/database:** add CMEK fields to backup and database ([16597fa](https://github.com/googleapis/google-cloud-go/commit/16597fa1ce549053c7183e8456e23f554a5501de))


### Bug Fixes

* **spanner/spansql:** fix parsing of NOT IN operator ([#3724](https://www.github.com/googleapis/google-cloud-go/issues/3724)) ([7636478](https://www.github.com/googleapis/google-cloud-go/commit/76364784d82073b80929ae60fd42da34c8050820))

## [1.15.0](https://www.github.com/googleapis/google-cloud-go/compare/v1.14.1...v1.15.0) (2021-02-24)


### Features

* **spanner/admin/database:** add CMEK fields to backup and database ([47037ed](https://www.github.com/googleapis/google-cloud-go/commit/47037ed33cd36edfff4ba7c4a4ea332140d5e67b))
* **spanner/admin/database:** add CMEK fields to backup and database ([16597fa](https://www.github.com/googleapis/google-cloud-go/commit/16597fa1ce549053c7183e8456e23f554a5501de))


### Bug Fixes

* **spanner:** parallelize session deletion when closing pool ([#3701](https://www.github.com/googleapis/google-cloud-go/issues/3701)) ([75ac7d2](https://www.github.com/googleapis/google-cloud-go/commit/75ac7d2506e706869ae41cf186b0c873b146e926)), refs [#3685](https://www.github.com/googleapis/google-cloud-go/issues/3685)

### [1.14.1](https://www.github.com/googleapis/google-cloud-go/compare/v1.14.0...v1.14.1) (2021-02-09)


### Bug Fixes

* **spanner:** restore removed scopes ([#3684](https://www.github.com/googleapis/google-cloud-go/issues/3684)) ([232d3a1](https://www.github.com/googleapis/google-cloud-go/commit/232d3a17bdadb92864592351a335ec920a68f9bf))

## [1.14.0](https://www.github.com/googleapis/google-cloud-go/compare/spanner/v1.13.0...v1.14.0) (2021-02-09)


### Features

* **spanner/admin/database:** adds PITR fields to backup and database ([0959f27](https://www.github.com/googleapis/google-cloud-go/commit/0959f27e85efe94d39437ceef0ff62ddceb8e7a7))
* **spanner/spannertest:** restructure column alteration implementation ([#3616](https://www.github.com/googleapis/google-cloud-go/issues/3616)) ([176400b](https://www.github.com/googleapis/google-cloud-go/commit/176400be9ab485fb343b8994bc49ac2291d8eea9))
* **spanner/spansql:** add complete set of array functions ([#3633](https://www.github.com/googleapis/google-cloud-go/issues/3633)) ([13d50b9](https://www.github.com/googleapis/google-cloud-go/commit/13d50b93cc8348c54641b594371a96ecdb1bcabc))
* **spanner/spansql:** add complete set of string functions ([#3625](https://www.github.com/googleapis/google-cloud-go/issues/3625)) ([34027ad](https://www.github.com/googleapis/google-cloud-go/commit/34027ada6a718603be2987b4084ce5e0ead6413c))
* **spanner:** add option for returning Spanner commit stats ([c7ecf0f](https://www.github.com/googleapis/google-cloud-go/commit/c7ecf0f3f454606b124e52d20af2545b2c68646f))
* **spanner:** add option for returning Spanner commit stats ([7bdebad](https://www.github.com/googleapis/google-cloud-go/commit/7bdebadbe06774c94ab745dfef4ce58ce40a5582))
* **spanner:** support CommitStats ([#3444](https://www.github.com/googleapis/google-cloud-go/issues/3444)) ([b7c3ca6](https://www.github.com/googleapis/google-cloud-go/commit/b7c3ca6c83cbdca95d734df8aa07c5ddb8ab3db0))


### Bug Fixes

* **spanner/spannertest:** support queries in ExecuteSql ([#3640](https://www.github.com/googleapis/google-cloud-go/issues/3640)) ([8eede84](https://www.github.com/googleapis/google-cloud-go/commit/8eede8411a5521f45a5c3f8091c42b3c5407ea90)), refs [#3639](https://www.github.com/googleapis/google-cloud-go/issues/3639)
* **spanner/spansql:** fix SelectFromJoin behavior ([#3571](https://www.github.com/googleapis/google-cloud-go/issues/3571)) ([e0887c7](https://www.github.com/googleapis/google-cloud-go/commit/e0887c762a4c58f29b3e5b49ee163a36a065463c))

## [1.13.0](https://www.github.com/googleapis/google-cloud-go/compare/spanner/v1.12.0...v1.13.0) (2021-01-15)


### Features

* **spanner/spannertest:** implement ANY_VALUE aggregation function ([#3428](https://www.github.com/googleapis/google-cloud-go/issues/3428)) ([e16c3e9](https://www.github.com/googleapis/google-cloud-go/commit/e16c3e9b412762b85483f3831ee586a5e6631313))
* **spanner/spannertest:** implement FULL JOIN ([#3218](https://www.github.com/googleapis/google-cloud-go/issues/3218)) ([99f7212](https://www.github.com/googleapis/google-cloud-go/commit/99f7212bd70bb333c1aa1c7a57348b4dfd80d31b))
* **spanner/spannertest:** implement SELECT ... FROM UNNEST(...) ([#3431](https://www.github.com/googleapis/google-cloud-go/issues/3431)) ([deb466f](https://www.github.com/googleapis/google-cloud-go/commit/deb466f497a1e6df78fcad57c3b90b1a4ccd93b4))
* **spanner/spannertest:** support array literals ([#3438](https://www.github.com/googleapis/google-cloud-go/issues/3438)) ([69e0110](https://www.github.com/googleapis/google-cloud-go/commit/69e0110f4977035cd1a705c3034c3ba96cadf36f))
* **spanner/spannertest:** support AVG aggregation function ([#3286](https://www.github.com/googleapis/google-cloud-go/issues/3286)) ([4788415](https://www.github.com/googleapis/google-cloud-go/commit/4788415c908f58c1cc08c951f1a7f17cdaf35aa2))
* **spanner/spannertest:** support Not Null constraint ([#3491](https://www.github.com/googleapis/google-cloud-go/issues/3491)) ([c36aa07](https://www.github.com/googleapis/google-cloud-go/commit/c36aa0785e798b9339d540e691850ca3c474a288))
* **spanner/spannertest:** support UPDATE DML ([#3201](https://www.github.com/googleapis/google-cloud-go/issues/3201)) ([1dec6f6](https://www.github.com/googleapis/google-cloud-go/commit/1dec6f6a31768a3f70bfec7274828301c22ea10b))
* **spanner/spansql:** define structures and parse UPDATE DML statements ([#3192](https://www.github.com/googleapis/google-cloud-go/issues/3192)) ([23b6904](https://www.github.com/googleapis/google-cloud-go/commit/23b69042c58489df512703259f54d075ba0c0722))
* **spanner/spansql:** support DATE and TIMESTAMP literals ([#3557](https://www.github.com/googleapis/google-cloud-go/issues/3557)) ([1961930](https://www.github.com/googleapis/google-cloud-go/commit/196193034a15f84dc3d3c27901990e8be77fca85))
* **spanner/spansql:** support for parsing generated columns ([#3373](https://www.github.com/googleapis/google-cloud-go/issues/3373)) ([9b1d06f](https://www.github.com/googleapis/google-cloud-go/commit/9b1d06fc90a4c07899c641a893dba0b47a1cead9))
* **spanner/spansql:** support NUMERIC data type ([#3411](https://www.github.com/googleapis/google-cloud-go/issues/3411)) ([1bc65d9](https://www.github.com/googleapis/google-cloud-go/commit/1bc65d9124ba22db5bec4c71b6378c27dfc04724))
* **spanner:** Add a DirectPath fallback integration test ([#3487](https://www.github.com/googleapis/google-cloud-go/issues/3487)) ([de821c5](https://www.github.com/googleapis/google-cloud-go/commit/de821c59fb81e9946216d205162b59de8b5ce71c))
* **spanner:** attempt DirectPath by default ([#3516](https://www.github.com/googleapis/google-cloud-go/issues/3516)) ([bbc61ed](https://www.github.com/googleapis/google-cloud-go/commit/bbc61ed368453b28aaf5bed627ca2499a3591f63))
* **spanner:** include User agent ([#3465](https://www.github.com/googleapis/google-cloud-go/issues/3465)) ([4e1ef1b](https://www.github.com/googleapis/google-cloud-go/commit/4e1ef1b3fb536ef950249cdee02cc0b6c2b56e86))
* **spanner:** run E2E test over DirectPath ([#3466](https://www.github.com/googleapis/google-cloud-go/issues/3466)) ([18e3a4f](https://www.github.com/googleapis/google-cloud-go/commit/18e3a4fe2a0c59c6295db2d85c7893ac51688083))
* **spanner:** support NUMERIC in mutations ([#3328](https://www.github.com/googleapis/google-cloud-go/issues/3328)) ([fa90737](https://www.github.com/googleapis/google-cloud-go/commit/fa90737a2adbe0cefbaba4aa1046a6efbba2a0e9))


### Bug Fixes

* **spanner:** fix session leak ([#3461](https://www.github.com/googleapis/google-cloud-go/issues/3461)) ([11fb917](https://www.github.com/googleapis/google-cloud-go/commit/11fb91711db5b941995737980cef7b48b611fefd)), refs [#3460](https://www.github.com/googleapis/google-cloud-go/issues/3460)

## [1.12.0](https://www.github.com/googleapis/google-cloud-go/compare/spanner/v1.11.0...v1.12.0) (2020-11-10)


### Features

* **spanner:** add metadata to RowIterator ([#3050](https://www.github.com/googleapis/google-cloud-go/issues/3050)) ([9a2289c](https://www.github.com/googleapis/google-cloud-go/commit/9a2289c3a38492bc2e84e0f4000c68a8718f5c11)), closes [#1805](https://www.github.com/googleapis/google-cloud-go/issues/1805)
* **spanner:** export ToSpannerError ([#3133](https://www.github.com/googleapis/google-cloud-go/issues/3133)) ([b951d8b](https://www.github.com/googleapis/google-cloud-go/commit/b951d8bd194b76da0a8bf2ce7cf85b546d2e051c)), closes [#3122](https://www.github.com/googleapis/google-cloud-go/issues/3122)
* **spanner:** support rw-transaction with options ([#3058](https://www.github.com/googleapis/google-cloud-go/issues/3058)) ([5130694](https://www.github.com/googleapis/google-cloud-go/commit/51306948eef9d26cff70453efc3eb500ddef9117))
* **spanner/spannertest:** make SELECT list aliases visible to ORDER BY ([#3054](https://www.github.com/googleapis/google-cloud-go/issues/3054)) ([7d2d83e](https://www.github.com/googleapis/google-cloud-go/commit/7d2d83ee1cce58d4014d5570bc599bcef1ed9c22)), closes [#3043](https://www.github.com/googleapis/google-cloud-go/issues/3043)

## v1.11.0

* Features:
  - feat(spanner): add KeySetFromKeys function (#2837)
* Misc:
  - test(spanner): check for Aborted error (#3039)
  - test(spanner): fix potential race condition in TestRsdBlockingStates (#3017)
  - test(spanner): compare data instead of struct (#3013)
  - test(spanner): fix flaky oc_test.go (#2838)
  - docs(spanner): document NULL value (#2885)
* spansql/spannertest:
  - Support JOINs (all but FULL JOIN) (#2936, #2924, #2896, #3042, #3037, #2995, #2945, #2931)
  - feat(spanner/spansql): parse CHECK constraints (#3046)
  - fix(spanner/spansql): fix parsing of unary minus and plus (#2997)
  - fix(spanner/spansql): fix parsing of adjacent inline and leading comments (#2851)
  - fix(spanner/spannertest): fix ORDER BY combined with SELECT aliases (#3043)
  - fix(spanner/spannertest): generate query output columns in construction order (#2990)
  - fix(spanner/spannertest): correct handling of NULL AND FALSE (#2991)
  - fix(spanner/spannertest): correct handling of tri-state boolean expression evaluation (#2983)
  - fix(spanner/spannertest): fix handling of NULL with LIKE operator (#2982)
  - test(spanner/spannertest): migrate most test code to integration_test.go (#2977)
  - test(spanner/spansql): add fuzz target for ParseQuery (#2909)
  - doc(spanner/spannertest): document the implementation (#2996)
  - perf(spanner/spannertest): speed up no-wait DDL changes (#2994)
  - perf(spanner/spansql): make fewer allocations during SQL (#2969)
* Backward Incompatible Changes
  - chore(spanner/spansql): use ID type for identifiers throughout (#2889)
  - chore(spanner/spansql): restructure FROM, TABLESAMPLE (#2888)

## v1.10.0

* feat(spanner): add support for NUMERIC data type (#2415)
* feat(spanner): add custom type support to spanner.Key (#2748)
* feat(spanner/spannertest): add support for bool parameter types (#2674)
* fix(spanner): update PDML to take sessions from pool (#2736)
* spanner/spansql: update docs on TableAlteration, ColumnAlteration (#2825)
* spanner/spannertest: support dropping columns (#2823)
* spanner/spannertest: implement GetDatabase (#2802)
* spanner/spannertest: fix aggregation in query evaluation for empty inputs (#2803)

## v1.9.0

* Features:
  - feat(spanner): support custom field type (#2614)
* Bugfixes:
  - fix(spanner): call ctx.cancel after stats have been recorded (#2728)
  - fix(spanner): retry session not found for read (#2724)
  - fix(spanner): specify credentials with SPANNER_EMULATOR_HOST (#2701)
  - fix(spanner): update pdml to retry EOS internal error (#2678)
* Misc:
  - test(spanner): unskip tests for emulator (#2675)
* spansql/spannertest:
  - spanner/spansql: restructure types and parsing for column options (#2656)
  - spanner/spannertest: return error for Read with no keys (#2655)

## v1.8.0

* Features:
  - feat(spanner): support of client-level custom retry settings (#2599)
  - feat(spanner): add a statement-based way to run read-write transaction. (#2545)
* Bugfixes:
  - fix(spanner): set 'gccl' to the request header. (#2609)
  - fix(spanner): add the missing resource prefix (#2605)
  - fix(spanner): fix the upgrade of protobuf. (#2583)
  - fix(spanner): do not copy protobuf messages by value. (#2581)
  - fix(spanner): fix the required resource prefix. (#2580)
  - fix(spanner): add extra field to ignore with cmp (#2577)
  - fix(spanner): remove appengine-specific numChannels. (#2513)
* Misc:
  - test(spanner): log warning instead of fail for stress test (#2559)
  - test(spanner): fix failed TestRsdBlockingStates test (#2597)
  - chore(spanner): cleanup mockserver and mockclient (#2414)

## v1.7.0

* Retry:
  - Only retry certain types of internal errors. (#2460)
* Tracing/metrics:
  - Never sample `ping()` trace spans (#2520)
  - Add oc tests for session pool metrics. (#2416)
* Encoding:
  - Allow encoding struct with custom types to mutation (#2529)
* spannertest:
  - Fix evaluation on IN (#2479)
  - Support MIN/MAX aggregation functions (#2411)
* Misc:
  - Fix TestClient_WithGRPCConnectionPoolAndNumChannels_Misconfigured test (#2539)
  - Cleanup backoff files and rename a variable (#2526)
  - Fix TestIntegration_DML test to return err from tx (#2509)
  - Unskip tests for emulator 0.8.0. (#2494)
  - Fix TestIntegration_StartBackupOperation test. (#2418)
  - Fix flakiness in TestIntegration_BatchDML_Error
  - Unskip TestIntegration_BatchDML and TestIntegration_BatchDML_TwoStatements
    for emulator by checking the existence of status.
  - Fix TestStressSessionPool test by taking lock while getting sessions from
    hc.

## v1.6.0

* Sessions:
  - Increase the number of sessions in batches instead of one by one when
    additional sessions are needed. The step size is set to 25, which means
    that whenever the session pool needs at least one more session, it will
    create a batch of 25 sessions.
* Emulator:
  - Run integration tests against the emulator in Kokoro Presubmit.
* RPC retrying:
  - Retry CreateDatabase on retryable codes.
* spannertest:
  - Change internal representation of DATE/TIMESTAMP values.
* spansql:
  - Cleanly parse adjacent comment marker/terminator.
  - Support FROM aliases in SELECT statements.
* Misc:
  - Fix comparing errors in tests.
  - Fix flaky session pool test.
  - Increase timeout in TestIntegration_ReadOnlyTransaction.
  - Fix incorrect instance IDs when deleting instances in tests.
  - Clean up test instances.
  - Clearify docs on Aborted transaction.
  - Fix timeout+staleness bound for test
  - Remove the support for resource-based routing.
  - Fix TestTransaction_SessionNotFound test.

## v1.5.1

* Fix incorrect decreasing metrics, numReads and numWrites.
* Fix an issue that XXX fields/methods are internal to proto and may change
  at any time. XXX_Merge panics in proto v1.4.0. Use proto.Merge instead of
  XXX_Merge.
* spannertest: handle list parameters in RPC interfacea.

## v1.5.0

* Metrics
  - Instrument client library with adding OpenCensus metrics. This allows for
    better monitoring of the session pool.
* Session management
  - Switch the session keepalive method from GetSession to SELECT 1.
* Emulator
  - Use client hooks for admin clients running against an emulator. With
    this change, users can use SPANNER_EMULATOR_HOST for initializing admin
    clients when running against an emulator.
* spansql
  - Add space between constraint name and foreign key def.
* Misc
  - Fix segfault when a non-existent credentials file had been specified.
  - Fix cleaning up instances in integration tests.
  - Fix race condition in batch read-only transaction.
  - Fix the flaky TestLIFOTakeWriteSessionOrder test.
  - Fix ITs to order results in SELECT queries.
  - Fix the documentation of timestamp bounds.
  - Fix the regex issue in managing backups.

## v1.4.0

- Support managed backups. This includes the API methods for CreateBackup,
  GetBackup, UpdateBackup, DeleteBackup and others. Also includes a simple
  wrapper in DatabaseAdminClient to create a backup.
- Update the healthcheck interval. The default interval is updated to 50 mins.
  By default, the first healthcheck is scheduled between 10 and 55 mins and
  the subsequent healthchecks are between 45 and 55 mins. This update avoids
  overloading the backend service with frequent healthchecking.

## v1.3.0

* Query options:
  - Adds the support of providing query options (optimizer version) via
    three ways (precedence follows the order):
    `client-level < environment variables < query-level`. The environment
    variable is set by "SPANNER_OPTIMIZER_VERSION".
* Connection pooling:
  - Use the new connection pooling in gRPC. This change deprecates
    `ClientConfig.numChannels` and users should move to
    `WithGRPCConnectionPool(numChannels)` at their earliest convenience.
    Example:
    ```go
    // numChannels (deprecated):
    err, client := NewClientWithConfig(ctx, database, ClientConfig{NumChannels: 8})

    // gRPC connection pool:
    err, client := NewClientWithConfig(ctx, database, ClientConfig{}, option.WithGRPCConnectionPool(8))
    ```
* Error handling:
  - Do not rollback after failed commit.
  - Return TransactionOutcomeUnknownError if a DEADLINE_EXCEEDED or CANCELED
    error occurs while a COMMIT request is in flight.
* spansql:
  - Added support for IN expressions and OFFSET clauses.
  - Fixed parsing of table constraints.
  - Added support for foreign key constraints in ALTER TABLE and CREATE TABLE.
  - Added support for GROUP BY clauses.
* spannertest:
  - Added support for IN expressions and OFFSET clauses.
  - Added support for GROUP BY clauses.
  - Fixed data race in query execution.
  - No longer rejects reads specifying an index to use.
  - Return last commit timestamp as read timestamp when requested.
  - Evaluate add, subtract, multiply, divide, unary
    negation, unary not, bitwise and/xor/or operations, as well as reporting
    column types for expressions involving any possible arithmetic
    operator.arithmetic expressions.
  - Fixed handling of descending primary keys.
* Misc:
  - Change default healthcheck interval to 30 mins to reduce the GetSession
    calls made to the backend.
  - Add marshal/unmarshal json for nullable types to support NullString,
    NullInt64, NullFloat64, NullBool, NullTime, NullDate.
  - Use ResourceInfo to extract error.
  - Extract retry info from status.

## v1.2.1

- Fix session leakage for ApplyAtLeastOnce. Previously session handles where
  leaked whenever Commit() returned a non-abort, non-session-not-found error,
  due to a missing recycle() call.
- Fix error for WriteStruct with pointers. This fixes a specific check for
  encoding and decoding to pointer types.
- Fix a GRPCStatus issue that returns a Status that has Unknown code if the
  base error is nil. Now, it always returns a Status based on Code field of
  current error.

## v1.2.0

- Support tracking stacktrace of sessionPool.take() that allows the user
  to instruct the session pool to keep track of the stacktrace of each
  goroutine that checks out a session from the pool. This is disabled by
  default, but it can be enabled by setting
  `SessionPoolConfig.TrackSessionHandles: true`.
- Add resource-based routing that includes a step to retrieve the
  instance-specific endpoint before creating the session client when
  creating a new spanner client. This is disabled by default, but it can
  be enabled by setting `GOOGLE_CLOUD_SPANNER_ENABLE_RESOURCE_BASED_ROUTING`.
- Make logger configurable so that the Spanner client can now be configured to
  use a specific logger instead of the standard logger.
- Support encoding custom types that point back to supported basic types.
- Allow decoding Spanner values to custom types that point back to supported
  types.

## v1.1.0

- The String() method of NullString, NullTime and NullDate will now return
  an unquoted string instead of a quoted string. This is a BREAKING CHANGE.
  If you relied on the old behavior, please use fmt.Sprintf("%q", T).
- The Spanner client will now use the new BatchCreateSessions RPC to initialize
  the session pool. This will improve the startup time of clients that are
  initialized with a minimum number of sessions greater than zero
  (i.e. SessionPoolConfig.MinOpened>0).
- Spanner clients that are created with the NewClient method will now default
  to a minimum of 100 opened sessions in the pool
  (i.e. SessionPoolConfig.MinOpened=100). This will improve the performance
  of the first transaction/query that is executed by an application, as a
  session will normally not have to be created as part of the transaction.
  Spanner clients that are created with the NewClientWithConfig method are
  not affected by this change.
- Spanner clients that are created with the NewClient method will now default
  to a write sessions fraction of 0.2 in the pool
  (i.e. SessionPoolConfig.WriteSessions=0.2).
  Spanner clients that are created with the NewClientWithConfig method are
  not affected by this change.
- The session pool maintenance worker has been improved so it keeps better
  track of the actual number of sessions needed. It will now less often delete
  and re-create sessions. This can improve the overall performance of
  applications with a low transaction rate.

## v1.0.0

This is the first tag to carve out spanner as its own module. See:
https://github.com/golang/go/wiki/Modules#is-it-possible-to-add-a-module-to-a-multi-module-repository.
