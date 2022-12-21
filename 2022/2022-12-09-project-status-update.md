# BoAT Project Status Update
Date: December 9th, 2022

## Update Summary
In the version of 3.0.0, the BoAT architecture was redesigned, the keystore and the blockchain network information is splitted, the code structure is also tweaked. The module mobiletek-L503C-6S is adapted as well. The mbedtls library is removed and use crypto-default library instead. Ethereum, Hyperledger Fabric, PlatON, PlatONE, Venachain unit test cases are update to fit the new architeture. 11 issues are fixed and optimized. 53 unit test cases are fixed. At least 3 descriptions in BoAT documents and README files are updated.


## Releases

[BoAT-X-v3.0.0](https://github.com/aitos-io/BoAT-X-Framework/releases/tag/BoAT-X-v3.0.0) is released.

**Change Log**

- Redesign the BoAT architecture
- Adapt to mobiletek-L503C-6S
- Remove mbedtls library and use crypto-default library
- Update Ethereum, Fabric, PlatON, PlatONE and Venachain unit test cases
- Fix and optimize 11 BoAT core code issues
- Fix 53 unit test case issues
- Update at least 3 descriptions in BoAT documents and README files

## Major Commits
* [docs: Fix a syntax error](https://github.com/aitos-io/BoAT-X-Framework/commit/a34fa837dafe144022e7e68cfcb2b53b1799506c)
* [Update to version 3.0.0 dev](https://github.com/aitos-io/BoAT-X-Framework/commit/41ab47cfc566e8b1c07eca7f43d24b33a14ff3a1)
* [feat: Add test_010CallContract_0001SetBytesSuccess](https://github.com/aitos-io/BoAT-X-Framework/commit/f0ea11ca44e32dbdcb8a79bd2c96a34c58b9a473)
* [feat: Add test_010CallContract_0002SetTwoBytesArraySuccess](https://github.com/aitos-io/BoAT-X-Framework/commit/4ad8e2348a50e1e625ea9a02228d36eddd0508c6)
* [feat: Add test_010CallContract_0003SetTwoBytesArraysAndTwoNonFixedSuc…](https://github.com/aitos-io/BoAT-X-Framework/commit/1e3866d34aeee867738a49d4cc0ed7eb0b2799a1)
* [feat: Added test contract file](https://github.com/aitos-io/BoAT-X-Framework/commit/92460906d3e14e70bce370aa69239eed2fc88d32)
* [feat: Add test functions declaration in header file](https://github.com/aitos-io/BoAT-X-Framework/commit/50a3c47953c1e58f5e9e67d11c4ff6b0435d8a45)
* [test[platon]:Add test keys](https://github.com/aitos-io/BoAT-X-Framework/commit/d3710cbb0eb073051c61480e275d7641c1d10b45)
* [test[platon]:Add test keys](https://github.com/aitos-io/BoAT-X-Framework/commit/5e6de0f005815dc50d5732ef2ac70591b597b68c)
* [test[platon]:Add platon test build makefile](https://github.com/aitos-io/BoAT-X-Framework/commit/263dfa4be096afd7ae807df08c062dd0630e7763)
* [test[platon]:Add tcase_entry](https://github.com/aitos-io/BoAT-X-Framework/commit/04d68e754dd15d667f2d43eba65145213c4950f2)
* [test[platon]:Add tcase_platon.h](https://github.com/aitos-io/BoAT-X-Framework/commit/b732f73988e3260a005e5ed8549ce4001d0818d4)
* [test[platon]:modify g_platon_network_config](https://github.com/aitos-io/BoAT-X-Framework/commit/7044eeeb4e2dea3cd1c7c667e8c2d3c0695e3b59)
* [test[platon]:Add 0102Keypair case](https://github.com/aitos-io/BoAT-X-Framework/commit/885408480c6dcf80c07f555cad85859c8b46715c)
* [test[platon]:Modify 0102Keypair case](https://github.com/aitos-io/BoAT-X-Framework/commit/e20f150b30b2f4164d56da46db3b47a374bbf8b4)
* [test[platon]:Add 0304Network case](https://github.com/aitos-io/BoAT-X-Framework/commit/23166006b178a1d4d037dc8d3c33ef2e0f00d50b)
* [[PlatoneTest][][#1296][]slove make clean err](https://github.com/aitos-io/BoAT-X-Framework/commit/55c31a65875dcee84ac77458c634ee5ca8e8e90a)
* [[chainmaker]slove compile warning](https://github.com/aitos-io/BoAT-X-Framework/commit/1dce7bba95cabe6d1abb06998aecd7e1b659cf16)
* [[chainmaker]add wallet type err check](https://github.com/aitos-io/BoAT-X-Framework/commit/e4addd9c162315e8c723330ab98a027a09437d5b)
* [test[platon]:Modify 0304Network cases](https://github.com/aitos-io/BoAT-X-Framework/commit/b29c20d11b2f1390fbb3a85840a3926054ca5dc4)
* [test[platon]:Add 0506Wallet cases](https://github.com/aitos-io/BoAT-X-Framework/commit/4cd9c13670f73062d402ae2a367a8931ee53daa9)
* [added void to BoatGetTimes funcation.](https://github.com/aitos-io/BoAT-X-Framework/commit/31068e3c49cf22bf1d88d316d5b238e3ab6c513d)
* [added platform/mobiletek-L503C-6S](https://github.com/aitos-io/BoAT-X-Framework/commit/0c29927a061cd3fe8c02a7b9581835e3236d58ba)
* [added L503 config to Makefile](https://github.com/aitos-io/BoAT-X-Framework/commit/2a06468c535e7ac65d3f315822b79825e9d54e38)
* [fix: Fix issues that cause test cases to fail](https://github.com/aitos-io/BoAT-X-Framework/commit/83eab9a32ad58530212d2be09f868c00fbe74bc2)
* [feat: Added balance and transfer test cases](https://github.com/aitos-io/BoAT-X-Framework/commit/984beb8a126dcc7cbfdf15b862f8432d65854dc3)
* [changed README.md and README_en.md](https://github.com/aitos-io/BoAT-X-Framework/commit/afe12a3ceb166ffaf9e3385a2ea02647bb0a5ea0)
* [perf: Adjusting the directory structure](https://github.com/aitos-io/BoAT-X-Framework/commit/8cf29de2023413fa4bcfc27f1026743775045fcc)
* [[chainmaker][tests]modify tests cases](https://github.com/aitos-io/BoAT-X-Framework/commit/ddd9cdf569fd3e9a8ac8fcc4058ceeb78b38bbf8)
* [feat[platon]:fix the issue](https://github.com/aitos-io/BoAT-X-Framework/commit/f063c335ee0cc6e9433ecc51dd8b719e5afc7aff) [#1301](https://github.com/aitos-io/BoAT-X-Framework/issues/1301)
* [feat[platon]:fix the issue](https://github.com/aitos-io/BoAT-X-Framework/commit/0ab8d3a33c8b5756ad25cff982302b9b80e43a6c) [#1302](https://github.com/aitos-io/BoAT-X-Framework/issues/1302)
* [added fabric demo to L503 and fix platone demo](https://github.com/aitos-io/BoAT-X-Framework/commit/d219fc236d86954694cc05d797f4eded50c75dfd)
* [[chainmaker][tests]modify node info for ptr](https://github.com/aitos-io/BoAT-X-Framework/commit/026e3cea50492e650e5bc07916ed4a4c71924417)
* [perf: Modify the file with reference to the test specification](https://github.com/aitos-io/BoAT-X-Framework/commit/1752e509d014a4baecfe56718adaf4d308bb6807)
* [fix: Added Ethereum test compilation options](https://github.com/aitos-io/BoAT-X-Framework/commit/6a32710ef364d8803cfb99fd98aa00fac79a2da9)
* [fix: Fixed the wrong variable being used in the test](https://github.com/aitos-io/BoAT-X-Framework/commit/cb04e55a5793140b94cce476ba5bd30b34073c25)
* [fix: Fixed the wrong expected value in the test](https://github.com/aitos-io/BoAT-X-Framework/commit/d9617864222feccb72ea65d7f145f502ffc7ed5a)
* [delete fabric demo for L503](https://github.com/aitos-io/BoAT-X-Framework/commit/2a2b91c205d6f36ca1a06b83ab08610766d81571)
* [fix(hwbcs):](https://github.com/aitos-io/BoAT-X-Framework/commit/e42151b151daa4423e440d8a02c06e49836e45a4) 
* [feat(mbedtls):](https://github.com/aitos-io/BoAT-X-Framework/commit/5194bf8eefe0424e8a86e03b114d6d68104d1a99)
* [feat:](https://github.com/aitos-io/BoAT-X-Framework/commit/e9c428e32fcdb02f728a61ac5449300d7ccb7ba2)
* [fix:](https://github.com/aitos-io/BoAT-X-Framework/commit/373e1a5c3e036039c6585699b148e10a4e054d02)
* [fix: Fixed incorrect return values](https://github.com/aitos-io/BoAT-X-Framework/commit/95f429d8edf0f0b98c317d19ddae51b55280e1c5)
* [feat(L503): added L503 fabric demo README_en.md](https://github.com/aitos-io/BoAT-X-Framework/commit/5c08b541752e20870a7e09fd61ec887ba4d8202e)
* [feat(L503): added L503 fabric demo README.md](https://github.com/aitos-io/BoAT-X-Framework/commit/8c1e14a70aaae82cab109d1267563adec31cb78e)
* [feat(L503): added makefile](https://github.com/aitos-io/BoAT-X-Framework/commit/538a5f635222b6e97ebdc4b200bb1d1a12a20f54)
* [feat(L503): added L503 fabric demo makefile](https://github.com/aitos-io/BoAT-X-Framework/commit/d2842bf0dca29683e2fd5ddbfc1f94226e8186d3)
* [feat(L503): delete mbedtls](https://github.com/aitos-io/BoAT-X-Framework/commit/6fd5e5d19d7f21d7b05c5ff9f42a53160598da13)
* [feat(L503): added L503 fabric demo main.c](https://github.com/aitos-io/BoAT-X-Framework/commit/fc5d96e51b4cb36bfb737ddc44aa0d2669935839)
* [feat(L503): added L503 fabric demo boat_fabric_demo.c](https://github.com/aitos-io/BoAT-X-Framework/commit/8cbd5393c0bd8627d3e14d496315f1f3968ba93b)
* [feat(L503): added L503 fabric demo boat_fabric_demo.h](https://github.com/aitos-io/BoAT-X-Framework/commit/946341230cd04ce5c42df06ff2b3faaba98fccab)
* [feat(L503): fix L503 platone demo REANDME_en.mf](https://github.com/aitos-io/BoAT-X-Framework/commit/4cbe07d9155eb23723a22a3bb67b07dd6fd3e813)
* [feat(L503): fix L503 platone demo boat_platone_demo.c](https://github.com/aitos-io/BoAT-X-Framework/commit/5a6663ab1456368d648831c8cd52086b4785fb46)
* [feat(L503): fix L503 platone demo boat_platone_demo.h](https://github.com/aitos-io/BoAT-X-Framework/commit/d59fd29723c20e200612ec60ea5dbca5b45a7ab9)
* [feat(L503): fix L503 boatplatform_internal.c](https://github.com/aitos-io/BoAT-X-Framework/commit/0cd6f864dd39b0fe9381655ea0d62154ba07af31)
* [feat(L503): fix L503 boatplatform.c](https://github.com/aitos-io/BoAT-X-Framework/commit/2fdf8a7a0b0a6917fb7ec8c099966d9aa40fbde7)
* [feat(L503): fix main Makefile](https://github.com/aitos-io/BoAT-X-Framework/commit/addf03dca4a0bc35b1ba9b7526584fa293dde8d0)

## Major Issues

**Open**

- [chainmaker TLS two way support](https://github.com/aitos-io/BoAT-X-Framework/issues/1165)

- [Boat code which is recommended for upper and lower case camel case and upper and lower case lines?](https://github.com/aitos-io/BoAT-X-Framework/issues/1166)

- [Does boat support multiple wallet storage?](https://github.com/aitos-io/BoAT-X-Framework/issues/1167)

- [Can boat provide node building tutorials for different chains?](https://github.com/aitos-io/BoAT-X-Framework/issues/1168)

- [chainmaker chainid orgid url and hostname not save in wallet](https://github.com/aitos-io/BoAT-X-Framework/issues/1169)

- [function describe the error](https://github.com/aitos-io/BoAT-X-Framework/issues/1170)

- [chainmaker gas what is it for](https://github.com/aitos-io/BoAT-X-Framework/issues/1171)

- [comments are missing in boatversion.h](https://github.com/aitos-io/BoAT-X-Framework/issues/1173)

- [comments error in boatutility.h](https://github.com/aitos-io/BoAT-X-Framework/issues/1174)

- [platon test test_002InitWallet_0007SetNodeUrlFailureErrorNodeUrlFormat failure](https://github.com/aitos-io/BoAT-X-Framework/issues/1181)

- [platon test test_002InitWallet_0015InitPlatONWalletWithWrongKeyFormat failure](https://github.com/aitos-io/BoAT-X-Framework/issues/1182)

- [platon test test_004ParametersInit_0004~test_004ParametersInit_0011 failure](https://github.com/aitos-io/BoAT-X-Framework/issues/1183)

- [platone wallet test cases failure](https://github.com/aitos-io/BoAT-X-Framework/issues/1185)

- [platone parameters test cases failure](https://github.com/aitos-io/BoAT-X-Framework/issues/1189)

- [quorum Inappropriate name of structure](https://github.com/aitos-io/BoAT-X-Framework/issues/1194)

- [quorum wrong comment](https://github.com/aitos-io/BoAT-X-Framework/issues/1195)

- [The "gasprice" initialization is not correct in api_quorum.c](https://github.com/aitos-io/BoAT-X-Framework/issues/1197)

- [comments correction in boatversion.h](https://github.com/aitos-io/BoAT-X-Framework/issues/1199)

- [sdk/protocol/Makefile mak clean error](https://github.com/aitos-io/BoAT-X-Framework/issues/1200)

- [There are warnings when compiling the demo of FISCOBCOS](https://github.com/aitos-io/BoAT-X-Framework/issues/1201)

- [There are warnings when compiling the HLFABRIC demo](https://github.com/aitos-io/BoAT-X-Framework/issues/1202)

- [Migrate BoAT-X-Framework ethereum to mobiletek-L503C-6S platform](https://github.com/aitos-io/BoAT-X-Framework/issues/1211)

- [compile warning in function BoatQuorumTxInit](https://github.com/aitos-io/BoAT-X-Framework/issues/1215)

- [compile warning in function test_004ParametersAdd_0006AddTxParamFailureTxNULLParam](https://github.com/aitos-io/BoAT-X-Framework/issues/1216)

- [compile warning in BoatHlchainmakerContractInvoke](https://github.com/aitos-io/BoAT-X-Framework/issues/1222)

- [Does BoAT support TEE or SE as Root of trust to protect key and algorithm](https://github.com/aitos-io/BoAT-X-Framework/issues/1224)

- [Compile warning in function test_006ContractQuery_0001QueryFailureTxNull](https://github.com/aitos-io/BoAT-X-Framework/issues/1225)

- [Compile warning in function check_chainmaker_wallet](https://github.com/aitos-io/BoAT-X-Framework/issues/1226)

- [Compile warning in function test_001CreateWallet_0012_CreatePersisWalletFailureIndexExceed](https://github.com/aitos-io/BoAT-X-Framework/issues/1227)

- [Compile warning in function test_001CreateWallet_0016_CreateOneTimeWalletFailurePrikeyError](https://github.com/aitos-io/BoAT-X-Framework/issues/1228)

- [Can I use the SDK for commercial applications?](https://github.com/aitos-io/BoAT-X-Framework/issues/1239)

- [add tests cases of chainmaker's network](https://github.com/aitos-io/BoAT-X-Framework/issues/1244)

- [Compile warning in function BoatCitaWalletInit.](https://github.com/aitos-io/BoAT-X-Framework/issues/1245)

- [Compile warning in function CitaSendRawtx.](https://github.com/aitos-io/BoAT-X-Framework/issues/1250)

- [Compile warning for the expects argument](https://github.com/aitos-io/BoAT-X-Framework/issues/1251)

- [Compile note in expansion of macro BoatLog_hexdump.](https://github.com/aitos-io/BoAT-X-Framework/issues/1252)

- [Compile warning for unused variable sig_parity](https://github.com/aitos-io/BoAT-X-Framework/issues/1253)

- [Migrate BoAT-X-Framework fabric to mobiletek-L503C-6S platform](https://github.com/aitos-io/BoAT-X-Framework/issues/1255)

- [在使能/禁能区块链协议中 的"使能/禁能"应该改为"使用/禁用"](https://github.com/aitos-io/BoAT-X-Framework/issues/1256)

- [In the scenario of crossing chain， How BoAT SDK work？](https://github.com/aitos-io/BoAT-X-Framework/issues/1258)

- [BoAT SDK在NFT或数字藏品上能有什么应用吗？](https://github.com/aitos-io/BoAT-X-Framework/issues/1259)

- [http2Init return value should check NULL](https://github.com/aitos-io/BoAT-X-Framework/issues/1262)

- [Compile warning in function BoatCitaWalletInit](https://github.com/aitos-io/BoAT-X-Framework/issues/1267)

- [Compile warning in function CitaSendRawtx](https://github.com/aitos-io/BoAT-X-Framework/issues/1268)

- [Compile note in expansion of macro 'BoatLog_hexdump'](https://github.com/aitos-io/BoAT-X-Framework/issues/1269)

- [Compile chainmaker warning in function test_004ParametersAdd_0006AddTxParamFailureTxNULLParam](https://github.com/aitos-io/BoAT-X-Framework/issues/1270)

- [Compile chainmaker warning in function check_chainmaker_wallet](https://github.com/aitos-io/BoAT-X-Framework/issues/1271)

- [BoAT User Guide-BoAT IoT Framework SDK Compilation](https://github.com/aitos-io/BoAT-X-Framework/issues/1276)

- [Migrate BoAT-X-Framework ethereum to Simcom-A7670C platform](https://github.com/aitos-io/BoAT-X-Framework/issues/1277)

- [In the scenario of V2X, how does it work?](https://github.com/aitos-io/BoAT-X-Framework/issues/1278)

- [How many major versions of the BoAT SDK will be upgraded each year probably?](https://github.com/aitos-io/BoAT-X-Framework/issues/1279)

- [For Bluetooth communication，is it applicable?](https://github.com/aitos-io/BoAT-X-Framework/issues/1280)

- [which cryptographic algorithms can be supported?](https://github.com/aitos-io/BoAT-X-Framework/issues/1281)

- [Add Comments to xxx.c in sdk/wallet](https://github.com/aitos-io/BoAT-X-Framework/issues/1287)

- [A problem with pointer processing after the wallet deinit](https://github.com/aitos-io/BoAT-X-Framework/issues/1288)

- [BoAT3.0 make clean error](https://github.com/aitos-io/BoAT-X-Framework/issues/1296)

- [“ML302” 中的“文件存储”和“随机数生成器” 没有对齐](https://github.com/aitos-io/BoAT-X-Framework/issues/1297)

- [Images in the "Brief Description of Fabric Protocol Layer" cannot be displayed](https://github.com/aitos-io/BoAT-X-Framework/issues/1298)

- [BoAT IoT Framework SDK编译-钱包数量前后表述不一致](https://github.com/aitos-io/BoAT-X-Framework/issues/1299)

- [BoAT User Guide-BoAT IoT Framework SDK Compilation-Better translation and correct number of wallets](https://github.com/aitos-io/BoAT-X-Framework/issues/1300)

- [Print error in BoatPlatONTxInit](https://github.com/aitos-io/BoAT-X-Framework/issues/1301)

- [There is a problem with the receiver address in BoatPlatONTxInit](https://github.com/aitos-io/BoAT-X-Framework/issues/1302)

**Closed**

* [platon WrongKeyFormat test error](https://github.com/aitos-io/BoAT-X-Framework/issues/1261) 
* [a warning in network_hlfabric.c](https://github.com/aitos-io/BoAT-X-Framework/issues/1266)
* [boatiotsdk_3_0-dev branch is lack of .gitignore file](https://github.com/aitos-io/BoAT-X-Framework/issues/1272)
* [Some compiled content has not been cleared](https://github.com/aitos-io/BoAT-X-Framework/issues/1273)
* [BoAT User Guide-Software Dependency](https://github.com/aitos-io/BoAT-X-Framework/issues/1275)
* [An expected return value of Ethereum test 004_0001 is incorrect.](https://github.com/aitos-io/BoAT-X-Framework/issues/1282)
* [An expected return value of Ethereum test 004_0002 is incorrect.](https://github.com/aitos-io/BoAT-X-Framework/issues/1283)
* [An expected return value of Ethereum test 004_0003 is incorrect.](https://github.com/aitos-io/BoAT-X-Framework/issues/1284) 
* [An expected return value of Ethereum test 004_0004 is incorrect.](https://github.com/aitos-io/BoAT-X-Framework/issues/1285)
* [The error code contains an unreadable error type.](https://github.com/aitos-io/BoAT-X-Framework/issues/1286)
* [UtilityPKCS2Native() returns error](https://github.com/aitos-io/BoAT-X-Framework/issues/1291)
* [An error was returned while compiling hwbcs](https://github.com/aitos-io/BoAT-X-Framework/issues/1295)
* [length returned by BoATxxxx_Get_NetworkData_Len() is wrong](https://github.com/aitos-io/BoAT-X-Framework/issues/1308)
* [delete mbedtls library, all the blockchains use crypto-default library](https://github.com/aitos-io/BoAT-X-Framework/issues/1307)
* [The UtilityNative2PKCS function returns incorrect values](https://github.com/aitos-io/BoAT-X-Framework/issues/1309)


## Highlights of Ecosystem Update
* [Leo Lin, CEO of aitos.io has been selected as a member of 5th phase of Billions Institute Entrepreneurs Camp by Matrix Partners China](https://mp.weixin.qq.com/s?__biz=MzU0NTk5NjE2OA==&mid=2247487098&idx=1&sn=e67c3616bbd60a87ac7e7f8c5d2ff6a7&chksm=fb65229dcc12ab8b2471eb4e00156b9cbe6ef14d941eae01c6308b2234fe291cffa9143615ad&token=275538993&lang=zh_CN#rd)
* [aitos.io was shortlisted as one of the "50 Best Investment Potential candidates during 2022 "Maker in China" Shanghai SME Competition](https://mp.weixin.qq.com/s?__biz=MzU0NTk5NjE2OA==&mid=2247487087&idx=1&sn=5db8c9caca515972facb90a56333e76b&chksm=fb652288cc12ab9e1a74d81964d7984f9e8aacfe128132f6e169907bf58715e165179f51e59e&token=275538993&lang=zh_CN#rd)
