# [1.0.0-beta.4](https://gitlab.com/team-enigma/api/compare/v1.0.0-beta.3...v1.0.0-beta.4) (2020-10-13)


### Bug Fixes

* ensure that there are drivers available for optimization ([59dcfb3](https://gitlab.com/team-enigma/api/commit/59dcfb3dc1e33c1c62f0f5c4f8274a8a5ecfd2f7)), closes [#89](https://gitlab.com/team-enigma/api/issues/89)

# [1.0.0-beta.3](https://gitlab.com/team-enigma/api/compare/v1.0.0-beta.2...v1.0.0-beta.3) (2020-10-09)


### Bug Fixes

* convert usernames to lowercase before creation ([53e444e](https://gitlab.com/team-enigma/api/commit/53e444e2398a62a3e4a19bf41c9e8e85602fa361)), closes [#88](https://gitlab.com/team-enigma/api/issues/88)

# [1.0.0-beta.2](https://gitlab.com/team-enigma/api/compare/v1.0.0-beta.1...v1.0.0-beta.2) (2020-10-05)


### Bug Fixes

* remove driver from previously assigned truck ([9f40211](https://gitlab.com/team-enigma/api/commit/9f40211872cdf5e3752e3dab6386bd66b8721e98)), closes [#87](https://gitlab.com/team-enigma/api/issues/87)

# 1.0.0-beta.1 (2020-09-18)


### Bug Fixes

* absolute path error for h2 db ([e295fa4](https://gitlab.com/team-enigma/api/commit/e295fa45692b9eaab9d8e795e59c6111f395ff45)), closes [#13](https://gitlab.com/team-enigma/api/issues/13)
* add user subscribers to communication-channel entity ([85a6c2e](https://gitlab.com/team-enigma/api/commit/85a6c2e9b211c29f52f6c6400048c53fb30d2e4c)), closes [#2](https://gitlab.com/team-enigma/api/issues/2)
* allow trucker to view tender ([3182f00](https://gitlab.com/team-enigma/api/commit/3182f009c2ad09290feefe9cdae6126e835c499c))
* change related entities of trucker to nullable ([0c62208](https://gitlab.com/team-enigma/api/commit/0c62208af6a5d4753869ea7b04fee3d874edf3f5))
* enable users by default on keycloak ([0fd4fe4](https://gitlab.com/team-enigma/api/commit/0fd4fe4665121c927ddaf391898644f3c95bd3f3))
* make user 'role' visible for json subtypes ([d882d8e](https://gitlab.com/team-enigma/api/commit/d882d8e1924db4548132de92097792e3233fa5fd))
* prevent bid total weight exceeding tender remaining weight ([a1cdf28](https://gitlab.com/team-enigma/api/commit/a1cdf2850dd2979ab069ad07d3fc8269aee0a3aa))
* prevent deleting tender when bid is accepted ([a47d156](https://gitlab.com/team-enigma/api/commit/a47d1562a082d1911343809e5e173708b615e3f2))
* remove incorrect prod configurations ([45d6078](https://gitlab.com/team-enigma/api/commit/45d60783597f8742723474b848117b7696b5c09e))
* remove the relationship with a review on the bid entity ([6d935a2](https://gitlab.com/team-enigma/api/commit/6d935a22efcfb46bee99a2b74dbdc5e3075149fc))
* resolve minor bugs and issues ([adf2375](https://gitlab.com/team-enigma/api/commit/adf23753d07159992f75dbcb6f6da0da37dd28f3))
* update incorrect bid filter mappings in controller ([6bbb0b4](https://gitlab.com/team-enigma/api/commit/6bbb0b440feeca3739d8f1277708e329bd1c084c)), closes [#85](https://gitlab.com/team-enigma/api/issues/85)
* update incorrect job filter mappings in controller ([2dd4f1a](https://gitlab.com/team-enigma/api/commit/2dd4f1a7436fe98f345dd376b33f8b3e394f70b1)), closes [#86](https://gitlab.com/team-enigma/api/issues/86)
* update incorrect tender filter mappings in controller ([4647602](https://gitlab.com/team-enigma/api/commit/46476029f7e1baa365686166d3be51e69dd1c84c)), closes [#84](https://gitlab.com/team-enigma/api/issues/84)
* update trucker status ([3ab4548](https://gitlab.com/team-enigma/api/commit/3ab4548de25f1efebb1b3c38215c442e0c44e72c)), closes [#58](https://gitlab.com/team-enigma/api/issues/58)
* validate new companies ([719775e](https://gitlab.com/team-enigma/api/commit/719775e853147bd2951fc4f57aabb430488e67a3))
* validate new users ([4753ddb](https://gitlab.com/team-enigma/api/commit/4753ddb3030e741e384a87a8c1fc58a5b8b11f00))
* validations for updating a job ([8e4362b](https://gitlab.com/team-enigma/api/commit/8e4362bcbec03f80331c11b80d46b57f225f09c5))


### Features

* add ability for a user to view another users' profile information ([de0bae4](https://gitlab.com/team-enigma/api/commit/de0bae4c30de82a44c2aa877ea808070fc65744e)), closes [#66](https://gitlab.com/team-enigma/api/issues/66)
* add ability for customers and fleet managers to review bids ([7722b1d](https://gitlab.com/team-enigma/api/commit/7722b1d2e0b59cd939a8bda079b95aff9ec3f81f)), closes [#20](https://gitlab.com/team-enigma/api/issues/20)
* add ability for fleet managers and truckers to get errands ([35fabc9](https://gitlab.com/team-enigma/api/commit/35fabc9241330c15f0a6b58815d310cdf7615a9e)), closes [#73](https://gitlab.com/team-enigma/api/issues/73)
* add ability for truckers to start and complete errands ([689d042](https://gitlab.com/team-enigma/api/commit/689d0423035c328354d8726b2555d62c57cd0064)), closes [#83](https://gitlab.com/team-enigma/api/issues/83)
* add ability for users to get profile information ([c37cf06](https://gitlab.com/team-enigma/api/commit/c37cf06ca5bc4b1ef730b04a41789b318e395e9e)), closes [#17](https://gitlab.com/team-enigma/api/issues/17)
* add ability for users to reset their avatar ([56b017b](https://gitlab.com/team-enigma/api/commit/56b017b53e352c6d265dac6bc20e3f16cd965512)), closes [#69](https://gitlab.com/team-enigma/api/issues/69)
* add ability for users to update profile information ([a02b7ba](https://gitlab.com/team-enigma/api/commit/a02b7baf99103eb0a102ff90c709848e937500c5)), closes [#19](https://gitlab.com/team-enigma/api/issues/19)
* add ability for users to upload profile image ([b741506](https://gitlab.com/team-enigma/api/commit/b7415067ce122eb0d9af2044ddd2f7dd2bc079ef)), closes [#68](https://gitlab.com/team-enigma/api/issues/68)
* add ability for users to view customer and company reviews ([44a84cf](https://gitlab.com/team-enigma/api/commit/44a84cf62e0a530eae3754dfac8e3ead88983ccc)), closes [#22](https://gitlab.com/team-enigma/api/issues/22)
* add ability to automatically create jobs ([6591a5d](https://gitlab.com/team-enigma/api/commit/6591a5d55732cbc148a6568bfaabc46689f0067d))
* add ability to create a company ([ecd842b](https://gitlab.com/team-enigma/api/commit/ecd842b21196844d4e1f8db70c9914262152d288)), closes [#52](https://gitlab.com/team-enigma/api/issues/52)
* add ability to create company truck ([ba27b6a](https://gitlab.com/team-enigma/api/commit/ba27b6a48b05e0bbc76d9a073246c5b70fab56c4)), closes [#40](https://gitlab.com/team-enigma/api/issues/40)
* add ability to create employees ([ac3d275](https://gitlab.com/team-enigma/api/commit/ac3d2752b7ced5a231826d09bdfe98f1e57a507d)), closes [#49](https://gitlab.com/team-enigma/api/issues/49)
* add ability to create errands ([451f683](https://gitlab.com/team-enigma/api/commit/451f6831302c120ddf38f17be374b47fe643fcb0)), closes [#70](https://gitlab.com/team-enigma/api/issues/70)
* add ability to create jobs ([20d6239](https://gitlab.com/team-enigma/api/commit/20d6239d6f8ce94606d28bee28347240182624d3))
* add ability to create tender ([d01063d](https://gitlab.com/team-enigma/api/commit/d01063d4f32d6c597e4292b9c2edbcbac9051bad)), closes [#35](https://gitlab.com/team-enigma/api/issues/35)
* add ability to delete a job ([a0286e0](https://gitlab.com/team-enigma/api/commit/a0286e0b9b135c15c289beda20d75f053598be86)), closes [#47](https://gitlab.com/team-enigma/api/issues/47)
* add ability to delete bid ([b9ddfaf](https://gitlab.com/team-enigma/api/commit/b9ddfaf807cf2f39ecfe9ee1e76bd56cfddba945)), closes [#63](https://gitlab.com/team-enigma/api/issues/63)
* add ability to delete errands ([e8eb759](https://gitlab.com/team-enigma/api/commit/e8eb75915ef453b60154c2674fc3cd555dbe0c62)), closes [#72](https://gitlab.com/team-enigma/api/issues/72)
* add ability to delete tender ([d100275](https://gitlab.com/team-enigma/api/commit/d100275e8ea9a692183621a30e0c200559fba998)), closes [#38](https://gitlab.com/team-enigma/api/issues/38)
* add ability to filter employees based on job and errand availability ([1230619](https://gitlab.com/team-enigma/api/commit/12306194074f710ccfc42293cd7345b5f28e2858)), closes [#76](https://gitlab.com/team-enigma/api/issues/76)
* add ability to post messages ([b215642](https://gitlab.com/team-enigma/api/commit/b215642cf80eafa9face24b1a48b6b8650c7c9d3)), closes [#25](https://gitlab.com/team-enigma/api/issues/25)
* add ability to register users ([0405745](https://gitlab.com/team-enigma/api/commit/04057456c59a5d13af77f5fc5e403faf79a7ea1a)), closes [#15](https://gitlab.com/team-enigma/api/issues/15)
* add ability to retrieve a review for a bid ([901a548](https://gitlab.com/team-enigma/api/commit/901a54872f96ada3d26ea343d745c3b85d6f1038)), closes [#81](https://gitlab.com/team-enigma/api/issues/81)
* add ability to retrieve access token ([6ab963e](https://gitlab.com/team-enigma/api/commit/6ab963e41fe0a35f2ed7e28d9187f693f95b635d)), closes [#16](https://gitlab.com/team-enigma/api/issues/16)
* add ability to retrieve messages ([6552fcd](https://gitlab.com/team-enigma/api/commit/6552fcd7228ab9cdad5d0c406b2ab140388badda)), closes [#26](https://gitlab.com/team-enigma/api/issues/26)
* add ability to retrieve tender(s) ([22b1f9f](https://gitlab.com/team-enigma/api/commit/22b1f9f21b24558cb886824f28ba90128160b5e8)), closes [#39](https://gitlab.com/team-enigma/api/issues/39)
* add ability to update a company ([570d7ff](https://gitlab.com/team-enigma/api/commit/570d7ff61bdd9b61e79ba87fa8444f14e941d90b)), closes [#53](https://gitlab.com/team-enigma/api/issues/53)
* add ability to update a job status ([a676ce5](https://gitlab.com/team-enigma/api/commit/a676ce505c599bd7b42c3dba6cfbac489900d62e)), closes [#75](https://gitlab.com/team-enigma/api/issues/75)
* add ability to update bid (negotiate) ([9fe25aa](https://gitlab.com/team-enigma/api/commit/9fe25aa321e080038064f3425ec4aeb498731b11))
* add ability to update company trucks ([0524c2b](https://gitlab.com/team-enigma/api/commit/0524c2bf3bcb058f1bbaa969f6862d01a3b14b30)), closes [#41](https://gitlab.com/team-enigma/api/issues/41)
* add ability to update employees ([42a968b](https://gitlab.com/team-enigma/api/commit/42a968b7e5127097a0e4fc2d46544973f95e65dd)), closes [#50](https://gitlab.com/team-enigma/api/issues/50)
* add ability to update errands ([5b31618](https://gitlab.com/team-enigma/api/commit/5b31618a3524b4108b7a1be01e35424169d0f6fa)), closes [#71](https://gitlab.com/team-enigma/api/issues/71)
* add ability to update job ([6420b96](https://gitlab.com/team-enigma/api/commit/6420b9687fb9fb6d74b12f34a58128e6f7c3c1be)), closes [#48](https://gitlab.com/team-enigma/api/issues/48)
* add ability to use refresh token ([2735d75](https://gitlab.com/team-enigma/api/commit/2735d752b69961b008d84e6cd5f7d358dc43509e)), closes [#55](https://gitlab.com/team-enigma/api/issues/55)
* add ability to version endpoints ([5632e28](https://gitlab.com/team-enigma/api/commit/5632e28bd63ee5702a544a6aea514d8cbd6f4a66)), closes [#10](https://gitlab.com/team-enigma/api/issues/10)
* add ability to view bid(s) ([4b8177c](https://gitlab.com/team-enigma/api/commit/4b8177cf2cb7d755d69c59526cb86df0fb6795bf)), closes [#61](https://gitlab.com/team-enigma/api/issues/61)
* add ability to view company trucks ([41c9a34](https://gitlab.com/team-enigma/api/commit/41c9a34da990220984cbf9e63583fcd9cd98b202)), closes [#43](https://gitlab.com/team-enigma/api/issues/43)
* add ability to view customer and company ratings ([379a35e](https://gitlab.com/team-enigma/api/commit/379a35eb508060353a0e5396166889aee9675582)), closes [#21](https://gitlab.com/team-enigma/api/issues/21)
* add ability to view employees ([4c80e8b](https://gitlab.com/team-enigma/api/commit/4c80e8b4ec4a80a173ed70c0035901a9e2a00d42)), closes [#56](https://gitlab.com/team-enigma/api/issues/56)
* add ability to view job(s) ([7a71238](https://gitlab.com/team-enigma/api/commit/7a7123845a9c2e40e9e976e58146c3b3242d8629))
* add additional bid filters ([dafa82f](https://gitlab.com/team-enigma/api/commit/dafa82fad4631ef3e4dd7841b255645ce7252f9a)), closes [#80](https://gitlab.com/team-enigma/api/issues/80)
* add additional job filters ([2377d0b](https://gitlab.com/team-enigma/api/commit/2377d0b7c0483946046f8fcd3c90df594c99bb07))
* add additional tender filters ([47ad019](https://gitlab.com/team-enigma/api/commit/47ad0194108a70daf5b18fbe7faa6cacb617b99c))
* add create trucker endpoint ([da98b76](https://gitlab.com/team-enigma/api/commit/da98b76d76bb4b24569f748d3d98d56512d40dba)), closes [#7](https://gitlab.com/team-enigma/api/issues/7)
* add exception handling ([fd462bb](https://gitlab.com/team-enigma/api/commit/fd462bbb83d6aaac6705655eb2d95b7bd5dcab23)), closes [#30](https://gitlab.com/team-enigma/api/issues/30)
* authenticate requests based on client scopes ([ee427b2](https://gitlab.com/team-enigma/api/commit/ee427b249a6904ee1e555de1c3c3ec7932848433)), closes [#1](https://gitlab.com/team-enigma/api/issues/1)
* configure push notifications for messages ([d7896a5](https://gitlab.com/team-enigma/api/commit/d7896a50fc412aaf06355b29f2dc5dda336f58b0)), closes [#74](https://gitlab.com/team-enigma/api/issues/74)
* create basic trucker endpoints ([0fefea6](https://gitlab.com/team-enigma/api/commit/0fefea6f05eef5dca407a445e6bf46a3cf0cf004)), closes [#7](https://gitlab.com/team-enigma/api/issues/7)
* create bid ([bd22fb8](https://gitlab.com/team-enigma/api/commit/bd22fb8296f5c04e7b25320f3573a8cb33ac6287))
* create dev environment for keycloak and postgres ([805d714](https://gitlab.com/team-enigma/api/commit/805d714671755e9ba4bff7527167b5bf80768880)), closes [#9](https://gitlab.com/team-enigma/api/issues/9) [#14](https://gitlab.com/team-enigma/api/issues/14)
* create entity models ([6f438d2](https://gitlab.com/team-enigma/api/commit/6f438d293f0e64bf0a1511816e95974963922835)), closes [#2](https://gitlab.com/team-enigma/api/issues/2)
* integrate with jenetics optimizer ([14370e4](https://gitlab.com/team-enigma/api/commit/14370e498cb60200af3b13c455aa0c14bc20fee2)), closes [#77](https://gitlab.com/team-enigma/api/issues/77)

# [1.0.0-alpha.58](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.57...v1.0.0-alpha.58) (2020-09-18)


### Bug Fixes

* remove the relationship with a review on the bid entity ([6d935a2](https://gitlab.com/team-enigma/api/commit/6d935a22efcfb46bee99a2b74dbdc5e3075149fc))
* validations for updating a job ([8e4362b](https://gitlab.com/team-enigma/api/commit/8e4362bcbec03f80331c11b80d46b57f225f09c5))

# [1.0.0-alpha.57](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.56...v1.0.0-alpha.57) (2020-09-16)


### Features

* integrate with jenetics optimizer ([14370e4](https://gitlab.com/team-enigma/api/commit/14370e498cb60200af3b13c455aa0c14bc20fee2)), closes [#77](https://gitlab.com/team-enigma/api/issues/77)

# [1.0.0-alpha.56](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.55...v1.0.0-alpha.56) (2020-09-16)


### Bug Fixes

* resolve minor bugs and issues ([adf2375](https://gitlab.com/team-enigma/api/commit/adf23753d07159992f75dbcb6f6da0da37dd28f3))

# [1.0.0-alpha.55](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.54...v1.0.0-alpha.55) (2020-09-16)


### Bug Fixes

* update incorrect bid filter mappings in controller ([6bbb0b4](https://gitlab.com/team-enigma/api/commit/6bbb0b440feeca3739d8f1277708e329bd1c084c)), closes [#85](https://gitlab.com/team-enigma/api/issues/85)
* update incorrect job filter mappings in controller ([2dd4f1a](https://gitlab.com/team-enigma/api/commit/2dd4f1a7436fe98f345dd376b33f8b3e394f70b1)), closes [#86](https://gitlab.com/team-enigma/api/issues/86)
* update incorrect tender filter mappings in controller ([4647602](https://gitlab.com/team-enigma/api/commit/46476029f7e1baa365686166d3be51e69dd1c84c)), closes [#84](https://gitlab.com/team-enigma/api/issues/84)

# [1.0.0-alpha.54](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.53...v1.0.0-alpha.54) (2020-09-16)


### Features

* add ability for truckers to start and complete errands ([689d042](https://gitlab.com/team-enigma/api/commit/689d0423035c328354d8726b2555d62c57cd0064)), closes [#83](https://gitlab.com/team-enigma/api/issues/83)

# [1.0.0-alpha.53](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.52...v1.0.0-alpha.53) (2020-09-14)


### Features

* add ability to retrieve a review for a bid ([901a548](https://gitlab.com/team-enigma/api/commit/901a54872f96ada3d26ea343d745c3b85d6f1038)), closes [#81](https://gitlab.com/team-enigma/api/issues/81)

# [1.0.0-alpha.52](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.51...v1.0.0-alpha.52) (2020-09-13)


### Features

* add additional bid filters ([dafa82f](https://gitlab.com/team-enigma/api/commit/dafa82fad4631ef3e4dd7841b255645ce7252f9a)), closes [#80](https://gitlab.com/team-enigma/api/issues/80)

# [1.0.0-alpha.51](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.50...v1.0.0-alpha.51) (2020-09-13)


### Features

* add additional job filters ([2377d0b](https://gitlab.com/team-enigma/api/commit/2377d0b7c0483946046f8fcd3c90df594c99bb07))

# [1.0.0-alpha.50](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.49...v1.0.0-alpha.50) (2020-09-13)


### Features

* add additional tender filters ([47ad019](https://gitlab.com/team-enigma/api/commit/47ad0194108a70daf5b18fbe7faa6cacb617b99c))

# [1.0.0-alpha.49](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.48...v1.0.0-alpha.49) (2020-09-13)


### Features

* add ability to filter employees based on job and errand availability ([1230619](https://gitlab.com/team-enigma/api/commit/12306194074f710ccfc42293cd7345b5f28e2858)), closes [#76](https://gitlab.com/team-enigma/api/issues/76)

# [1.0.0-alpha.48](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.47...v1.0.0-alpha.48) (2020-09-06)


### Features

* configure push notifications for messages ([d7896a5](https://gitlab.com/team-enigma/api/commit/d7896a50fc412aaf06355b29f2dc5dda336f58b0)), closes [#74](https://gitlab.com/team-enigma/api/issues/74)

# [1.0.0-alpha.47](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.46...v1.0.0-alpha.47) (2020-09-06)


### Features

* add ability to update a job status ([a676ce5](https://gitlab.com/team-enigma/api/commit/a676ce505c599bd7b42c3dba6cfbac489900d62e)), closes [#75](https://gitlab.com/team-enigma/api/issues/75)

# [1.0.0-alpha.46](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.45...v1.0.0-alpha.46) (2020-09-01)


### Features

* add ability to retrieve messages ([6552fcd](https://gitlab.com/team-enigma/api/commit/6552fcd7228ab9cdad5d0c406b2ab140388badda)), closes [#26](https://gitlab.com/team-enigma/api/issues/26)

# [1.0.0-alpha.45](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.44...v1.0.0-alpha.45) (2020-08-31)


### Features

* add ability to post messages ([b215642](https://gitlab.com/team-enigma/api/commit/b215642cf80eafa9face24b1a48b6b8650c7c9d3)), closes [#25](https://gitlab.com/team-enigma/api/issues/25)

# [1.0.0-alpha.44](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.43...v1.0.0-alpha.44) (2020-08-31)


### Features

* add ability to update errands ([5b31618](https://gitlab.com/team-enigma/api/commit/5b31618a3524b4108b7a1be01e35424169d0f6fa)), closes [#71](https://gitlab.com/team-enigma/api/issues/71)

# [1.0.0-alpha.43](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.42...v1.0.0-alpha.43) (2020-08-29)


### Features

* add ability to delete errands ([e8eb759](https://gitlab.com/team-enigma/api/commit/e8eb75915ef453b60154c2674fc3cd555dbe0c62)), closes [#72](https://gitlab.com/team-enigma/api/issues/72)

# [1.0.0-alpha.42](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.41...v1.0.0-alpha.42) (2020-08-29)


### Features

* add ability for fleet managers and truckers to get errands ([35fabc9](https://gitlab.com/team-enigma/api/commit/35fabc9241330c15f0a6b58815d310cdf7615a9e)), closes [#73](https://gitlab.com/team-enigma/api/issues/73)

# [1.0.0-alpha.41](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.40...v1.0.0-alpha.41) (2020-08-28)


### Features

* add ability to create errands ([451f683](https://gitlab.com/team-enigma/api/commit/451f6831302c120ddf38f17be374b47fe643fcb0)), closes [#70](https://gitlab.com/team-enigma/api/issues/70)

# [1.0.0-alpha.40](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.39...v1.0.0-alpha.40) (2020-08-27)


### Features

* add ability for users to reset their avatar ([56b017b](https://gitlab.com/team-enigma/api/commit/56b017b53e352c6d265dac6bc20e3f16cd965512)), closes [#69](https://gitlab.com/team-enigma/api/issues/69)

# [1.0.0-alpha.39](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.38...v1.0.0-alpha.39) (2020-08-26)


### Features

* add ability for users to upload profile image ([b741506](https://gitlab.com/team-enigma/api/commit/b7415067ce122eb0d9af2044ddd2f7dd2bc079ef)), closes [#68](https://gitlab.com/team-enigma/api/issues/68)

# [1.0.0-alpha.38](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.37...v1.0.0-alpha.38) (2020-08-26)


### Features

* add ability for users to view customer and company reviews ([44a84cf](https://gitlab.com/team-enigma/api/commit/44a84cf62e0a530eae3754dfac8e3ead88983ccc)), closes [#22](https://gitlab.com/team-enigma/api/issues/22)

# [1.0.0-alpha.37](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.36...v1.0.0-alpha.37) (2020-08-26)


### Features

* add ability to view customer and company ratings ([379a35e](https://gitlab.com/team-enigma/api/commit/379a35eb508060353a0e5396166889aee9675582)), closes [#21](https://gitlab.com/team-enigma/api/issues/21)

# [1.0.0-alpha.36](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.35...v1.0.0-alpha.36) (2020-08-26)


### Features

* add ability for customers and fleet managers to review bids ([7722b1d](https://gitlab.com/team-enigma/api/commit/7722b1d2e0b59cd939a8bda079b95aff9ec3f81f)), closes [#20](https://gitlab.com/team-enigma/api/issues/20)

# [1.0.0-alpha.35](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.34...v1.0.0-alpha.35) (2020-08-25)


### Features

* add ability to delete bid ([b9ddfaf](https://gitlab.com/team-enigma/api/commit/b9ddfaf807cf2f39ecfe9ee1e76bd56cfddba945)), closes [#63](https://gitlab.com/team-enigma/api/issues/63)
* add ability to delete tender ([d100275](https://gitlab.com/team-enigma/api/commit/d100275e8ea9a692183621a30e0c200559fba998)), closes [#38](https://gitlab.com/team-enigma/api/issues/38)

# [1.0.0-alpha.34](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.33...v1.0.0-alpha.34) (2020-08-25)


### Bug Fixes

* prevent bid total weight exceeding tender remaining weight ([a1cdf28](https://gitlab.com/team-enigma/api/commit/a1cdf2850dd2979ab069ad07d3fc8269aee0a3aa))

# [1.0.0-alpha.33](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.32...v1.0.0-alpha.33) (2020-08-21)


### Features

* add ability for a user to view another users' profile information ([de0bae4](https://gitlab.com/team-enigma/api/commit/de0bae4c30de82a44c2aa877ea808070fc65744e)), closes [#66](https://gitlab.com/team-enigma/api/issues/66)

# [1.0.0-alpha.32](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.31...v1.0.0-alpha.32) (2020-08-20)


### Features

* add ability to automatically create jobs ([6591a5d](https://gitlab.com/team-enigma/api/commit/6591a5d55732cbc148a6568bfaabc46689f0067d))

# [1.0.0-alpha.31](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.30...v1.0.0-alpha.31) (2020-08-19)


### Bug Fixes

* allow trucker to view tender ([3182f00](https://gitlab.com/team-enigma/api/commit/3182f009c2ad09290feefe9cdae6126e835c499c))

# [1.0.0-alpha.30](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.29...v1.0.0-alpha.30) (2020-08-19)


### Features

* add ability to delete a job ([a0286e0](https://gitlab.com/team-enigma/api/commit/a0286e0b9b135c15c289beda20d75f053598be86)), closes [#47](https://gitlab.com/team-enigma/api/issues/47)

# [1.0.0-alpha.29](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.28...v1.0.0-alpha.29) (2020-08-17)


### Features

* add ability to update job ([6420b96](https://gitlab.com/team-enigma/api/commit/6420b9687fb9fb6d74b12f34a58128e6f7c3c1be)), closes [#48](https://gitlab.com/team-enigma/api/issues/48)

# [1.0.0-alpha.28](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.27...v1.0.0-alpha.28) (2020-08-17)


### Features

* add ability to view job(s) ([7a71238](https://gitlab.com/team-enigma/api/commit/7a7123845a9c2e40e9e976e58146c3b3242d8629))

# [1.0.0-alpha.27](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.26...v1.0.0-alpha.27) (2020-08-15)


### Features

* add ability to create jobs ([20d6239](https://gitlab.com/team-enigma/api/commit/20d6239d6f8ce94606d28bee28347240182624d3))

# [1.0.0-alpha.26](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.25...v1.0.0-alpha.26) (2020-08-15)


### Bug Fixes

* prevent deleting tender when bid is accepted ([a47d156](https://gitlab.com/team-enigma/api/commit/a47d1562a082d1911343809e5e173708b615e3f2))

# [1.0.0-alpha.25](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.24...v1.0.0-alpha.25) (2020-08-13)


### Features

* add ability to update bid (negotiate) ([9fe25aa](https://gitlab.com/team-enigma/api/commit/9fe25aa321e080038064f3425ec4aeb498731b11))
* add ability to update company trucks ([0524c2b](https://gitlab.com/team-enigma/api/commit/0524c2bf3bcb058f1bbaa969f6862d01a3b14b30)), closes [#41](https://gitlab.com/team-enigma/api/issues/41)
* add ability to view bid(s) ([4b8177c](https://gitlab.com/team-enigma/api/commit/4b8177cf2cb7d755d69c59526cb86df0fb6795bf)), closes [#61](https://gitlab.com/team-enigma/api/issues/61)
* create bid ([bd22fb8](https://gitlab.com/team-enigma/api/commit/bd22fb8296f5c04e7b25320f3573a8cb33ac6287))

# [1.0.0-alpha.25](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.24...v1.0.0-alpha.25) (2020-08-13)


### Features

* add ability to update bid (negotiate) ([9fe25aa](https://gitlab.com/team-enigma/api/commit/9fe25aa321e080038064f3425ec4aeb498731b11))
* add ability to view bid(s) ([4b8177c](https://gitlab.com/team-enigma/api/commit/4b8177cf2cb7d755d69c59526cb86df0fb6795bf)), closes [#61](https://gitlab.com/team-enigma/api/issues/61)
* create bid ([bd22fb8](https://gitlab.com/team-enigma/api/commit/bd22fb8296f5c04e7b25320f3573a8cb33ac6287))

# [1.0.0-alpha.25](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.24...v1.0.0-alpha.25) (2020-08-10)


### Features

* add ability to view bid(s) ([4b8177c](https://gitlab.com/team-enigma/api/commit/4b8177cf2cb7d755d69c59526cb86df0fb6795bf)), closes [#61](https://gitlab.com/team-enigma/api/issues/61)
* create bid ([bd22fb8](https://gitlab.com/team-enigma/api/commit/bd22fb8296f5c04e7b25320f3573a8cb33ac6287))

# [1.0.0-alpha.25](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.24...v1.0.0-alpha.25) (2020-08-09)


### Features

* add ability to create a bid ([bd22fb8](https://gitlab.com/team-enigma/api/commit/bd22fb8296f5c04e7b25320f3573a8cb33ac6287)), closes [#60](https://gitlab.com/team-enigma/api/issues/60)

# [1.0.0-alpha.24](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.23...v1.0.0-alpha.24) (2020-08-08)


### Features

* add ability to update a company ([570d7ff](https://gitlab.com/team-enigma/api/commit/570d7ff61bdd9b61e79ba87fa8444f14e941d90b)), closes [#53](https://gitlab.com/team-enigma/api/issues/53)

# [1.0.0-alpha.23](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.22...v1.0.0-alpha.23) (2020-08-08)


### Features

* add ability to update employees ([42a968b](https://gitlab.com/team-enigma/api/commit/42a968b7e5127097a0e4fc2d46544973f95e65dd)), closes [#50](https://gitlab.com/team-enigma/api/issues/50)

# [1.0.0-alpha.22](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.21...v1.0.0-alpha.22) (2020-08-07)


### Bug Fixes

* update trucker status ([3ab4548](https://gitlab.com/team-enigma/api/commit/3ab4548de25f1efebb1b3c38215c442e0c44e72c)), closes [#58](https://gitlab.com/team-enigma/api/issues/58)

# [1.0.0-alpha.21](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.20...v1.0.0-alpha.21) (2020-07-23)


### Bug Fixes

* make user 'role' visible for json subtypes ([d882d8e](https://gitlab.com/team-enigma/api/commit/d882d8e1924db4548132de92097792e3233fa5fd))

# [1.0.0-alpha.20](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.19...v1.0.0-alpha.20) (2020-07-22)


### Bug Fixes

* remove incorrect prod configurations ([45d6078](https://gitlab.com/team-enigma/api/commit/45d60783597f8742723474b848117b7696b5c09e))


### Features

* add ability to view employees ([4c80e8b](https://gitlab.com/team-enigma/api/commit/4c80e8b4ec4a80a173ed70c0035901a9e2a00d42)), closes [#56](https://gitlab.com/team-enigma/api/issues/56)

# [1.0.0-alpha.19](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.18...v1.0.0-alpha.19) (2020-07-21)


### Features

* add ability to retrieve tender(s) ([22b1f9f](https://gitlab.com/team-enigma/api/commit/22b1f9f21b24558cb886824f28ba90128160b5e8)), closes [#39](https://gitlab.com/team-enigma/api/issues/39)

# [1.0.0-alpha.18](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.17...v1.0.0-alpha.18) (2020-07-21)


### Features

* add ability to create tender ([d01063d](https://gitlab.com/team-enigma/api/commit/d01063d4f32d6c597e4292b9c2edbcbac9051bad)), closes [#35](https://gitlab.com/team-enigma/api/issues/35)

# [1.0.0-alpha.17](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.16...v1.0.0-alpha.17) (2020-07-19)


### Features

* add ability to use refresh token ([2735d75](https://gitlab.com/team-enigma/api/commit/2735d752b69961b008d84e6cd5f7d358dc43509e)), closes [#55](https://gitlab.com/team-enigma/api/issues/55)

# [1.0.0-alpha.16](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.15...v1.0.0-alpha.16) (2020-07-17)


### Features

* add ability to view company trucks ([41c9a34](https://gitlab.com/team-enigma/api/commit/41c9a34da990220984cbf9e63583fcd9cd98b202)), closes [#43](https://gitlab.com/team-enigma/api/issues/43)

# [1.0.0-alpha.15](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.14...v1.0.0-alpha.15) (2020-07-17)


### Features

* add ability to create company truck ([ba27b6a](https://gitlab.com/team-enigma/api/commit/ba27b6a48b05e0bbc76d9a073246c5b70fab56c4)), closes [#40](https://gitlab.com/team-enigma/api/issues/40)

# [1.0.0-alpha.14](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.13...v1.0.0-alpha.14) (2020-07-17)


### Features

* add ability to create employees ([ac3d275](https://gitlab.com/team-enigma/api/commit/ac3d2752b7ced5a231826d09bdfe98f1e57a507d)), closes [#49](https://gitlab.com/team-enigma/api/issues/49)

# [1.0.0-alpha.13](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.12...v1.0.0-alpha.13) (2020-07-16)


### Features

* add ability to create a company ([ecd842b](https://gitlab.com/team-enigma/api/commit/ecd842b21196844d4e1f8db70c9914262152d288)), closes [#52](https://gitlab.com/team-enigma/api/issues/52)

# [1.0.0-alpha.12](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.11...v1.0.0-alpha.12) (2020-07-16)


### Features

* add ability for users to update profile information ([a02b7ba](https://gitlab.com/team-enigma/api/commit/a02b7baf99103eb0a102ff90c709848e937500c5)), closes [#19](https://gitlab.com/team-enigma/api/issues/19)

# [1.0.0-alpha.11](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.10...v1.0.0-alpha.11) (2020-07-13)


### Bug Fixes

* enable users by default on keycloak ([0fd4fe4](https://gitlab.com/team-enigma/api/commit/0fd4fe4665121c927ddaf391898644f3c95bd3f3))
* validate new companies ([719775e](https://gitlab.com/team-enigma/api/commit/719775e853147bd2951fc4f57aabb430488e67a3))
* validate new users ([4753ddb](https://gitlab.com/team-enigma/api/commit/4753ddb3030e741e384a87a8c1fc58a5b8b11f00))

# [1.0.0-alpha.10](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.9...v1.0.0-alpha.10) (2020-07-09)


### Features

* add ability for users to get profile information ([c37cf06](https://gitlab.com/team-enigma/api/commit/c37cf06ca5bc4b1ef730b04a41789b318e395e9e)), closes [#17](https://gitlab.com/team-enigma/api/issues/17)

# [1.0.0-alpha.9](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.8...v1.0.0-alpha.9) (2020-07-08)


### Features

* add ability to retrieve access token ([6ab963e](https://gitlab.com/team-enigma/api/commit/6ab963e41fe0a35f2ed7e28d9187f693f95b635d)), closes [#16](https://gitlab.com/team-enigma/api/issues/16)

# [1.0.0-alpha.8](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.7...v1.0.0-alpha.8) (2020-06-30)


### Features

* add ability to register users ([0405745](https://gitlab.com/team-enigma/api/commit/04057456c59a5d13af77f5fc5e403faf79a7ea1a)), closes [#15](https://gitlab.com/team-enigma/api/issues/15)

# [1.0.0-alpha.7](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.6...v1.0.0-alpha.7) (2020-06-15)


### Features

* add exception handling ([fd462bb](https://gitlab.com/team-enigma/api/commit/fd462bbb83d6aaac6705655eb2d95b7bd5dcab23)), closes [#30](https://gitlab.com/team-enigma/api/issues/30)

# [1.0.0-alpha.6](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.5...v1.0.0-alpha.6) (2020-06-15)


### Features

* create dev environment for keycloak and postgres ([805d714](https://gitlab.com/team-enigma/api/commit/805d714671755e9ba4bff7527167b5bf80768880)), closes [#9](https://gitlab.com/team-enigma/api/issues/9) [#14](https://gitlab.com/team-enigma/api/issues/14)

# [1.0.0-alpha.5](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.4...v1.0.0-alpha.5) (2020-06-15)


### Features

* add ability to version endpoints ([5632e28](https://gitlab.com/team-enigma/api/commit/5632e28bd63ee5702a544a6aea514d8cbd6f4a66)), closes [#10](https://gitlab.com/team-enigma/api/issues/10)

# [1.0.0-alpha.4](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.3...v1.0.0-alpha.4) (2020-06-15)


### Bug Fixes

* add user subscribers to communication-channel entity ([85a6c2e](https://gitlab.com/team-enigma/api/commit/85a6c2e9b211c29f52f6c6400048c53fb30d2e4c)), closes [#2](https://gitlab.com/team-enigma/api/issues/2)

# [1.0.0-alpha.3](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.2...v1.0.0-alpha.3) (2020-06-14)


### Bug Fixes

* absolute path error for h2 db ([e295fa4](https://gitlab.com/team-enigma/api/commit/e295fa45692b9eaab9d8e795e59c6111f395ff45)), closes [#13](https://gitlab.com/team-enigma/api/issues/13)

# [1.0.0-alpha.2](https://gitlab.com/team-enigma/api/compare/v1.0.0-alpha.1...v1.0.0-alpha.2) (2020-06-12)


### Features

* add create trucker endpoint ([da98b76](https://gitlab.com/team-enigma/api/commit/da98b76d76bb4b24569f748d3d98d56512d40dba)), closes [#7](https://gitlab.com/team-enigma/api/issues/7)

# 1.0.0-alpha.1 (2020-06-12)


### Bug Fixes

* change related entities of trucker to nullable ([0c62208](https://gitlab.com/team-enigma/api/commit/0c62208af6a5d4753869ea7b04fee3d874edf3f5))


### Features

* authenticate requests based on client scopes ([ee427b2](https://gitlab.com/team-enigma/api/commit/ee427b249a6904ee1e555de1c3c3ec7932848433)), closes [#1](https://gitlab.com/team-enigma/api/issues/1)
* create basic trucker endpoints ([0fefea6](https://gitlab.com/team-enigma/api/commit/0fefea6f05eef5dca407a445e6bf46a3cf0cf004)), closes [#7](https://gitlab.com/team-enigma/api/issues/7)
* create entity models ([6f438d2](https://gitlab.com/team-enigma/api/commit/6f438d293f0e64bf0a1511816e95974963922835)), closes [#2](https://gitlab.com/team-enigma/api/issues/2)
