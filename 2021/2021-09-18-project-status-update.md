# BoAT Project Status Update
Date: September 18th, 2021


## Update Summary
This is the first version of V2.1.x. A new feature *Node Discovery* is introduced, which allows the device to find available nodes around so that the client could decide send transaction or query to which node(s). This version also support Huawei's blockchain which is named BCS as well as some bugfix and documents update.

## Releases
[BoAT-X-v2.1.0](https://github.com/aitos-io/BoAT-X-Framework/releases/tag/BoAT-X-v2.1.0) is released.

**Change Log**

- New feature: Node discovery (for PlatONE and HyperLedger Fabric)
- Newly supported blockchain: Huawei BCS (华为链)
- Update: Xinyi XY1100 (芯翼 XY1100 NB-IoT chipset) now supports BoAT 2.x
- A lot of enhancements on support for HyperLedger Fabric's endorsement strategy
- Fix some bugs and compile issues
- Uniform some code format
- Update BoAT 2.0 User Guide documents (Chinese version)
- Update BoAT 2.0 Overall Design documents (Chinese and English version)
- Update BoAT 2.0 System Requirements documents (Chinese and English version)


## Major Commits
* [Feat:Add support for XinYi1100 module](https://github.com/aitos-io/BoAT-X-Framework/commit/d4c4447a71dc7a49f41a2d9a01378e542c57df70)
* [Feat:Add demo for XinYi1100 module](https://github.com/aitos-io/BoAT-X-Framework/commit/2c99f387b542b63fc4664b78df1937c530ad41a9)
* [Feat:Add makefile,use XinYi1100's TLS](https://github.com/aitos-io/BoAT-X-Framework/commit/f38fafefc9afa1fdf9ec0a80655a0cf4161afb24)
* [Feat:modify storage functions,use XinYi's flash instead of FS](https://github.com/aitos-io/BoAT-X-Framework/commit/f95762e9f705b5e67a1cc9be324369c0669f03cb)
* [Docs：Add ReadME.md for XinYi1100](https://github.com/aitos-io/BoAT-X-Framework/commit/5fcbc49e67108ffb859774e40ad8edf2dd2ddc1f)
* [style(huawei chain): Modify code comments](https://github.com/aitos-io/BoAT-X-Framework/commit/c611be763aa71b44c227f3ae49ee4f53884637c9)
* [fix(boatplatone.c): add "cJSON.h"](https://github.com/aitos-io/BoAT-X-Framework/commit/1b9143f72246751f9902ebb735c053bb2988f85c)
* [docs: Corrected a complex sentence](https://github.com/aitos-io/BoAT-X-Framework/commit/20134e9571f269b8437222b9afbe4c603122164d)
* [refactor: Modified cJSON initial Settings to ensure that the program …](https://github.com/aitos-io/BoAT-X-Framework/commit/8cfc41ba2fa5df534de05786cee116a1e7871d31)
* [docs: Missing punctuation was added](https://github.com/aitos-io/BoAT-X-Framework/commit/bf1586c3a38e8d9704b77c07d1b15bf8d5bc0ae0)
* [Docs：update README.md](https://github.com/aitos-io/BoAT-X-Framework/commit/b8bbcdb3f6a3544c029f7806b5285c293d5ca9fe)
* [Docs:Add README_en.md](https://github.com/aitos-io/BoAT-X-Framework/commit/260369fc721e3be47d5916cc5c5017f7cd780854)
* [Docs:Modify the path of BoAT static lib in README.md](https://github.com/aitos-io/BoAT-X-Framework/commit/350bc8e1f3fccc3c3b4b291753074056b5cd518d)
* [style: Modified some comments to make them consistent with the code](https://github.com/aitos-io/BoAT-X-Framework/commit/09b1623707d0358a7f127673c5ecbe605e428b98)
* [docs: remove blank](https://github.com/aitos-io/BoAT-X-Framework/commit/1230fbd42f07257a9b1b1e557068f92ba759d84d)
* [docs: Add PlatON to the protocol list](https://github.com/aitos-io/BoAT-X-Framework/commit/bfc862f7bcbfc90ca0a723198f1ba7f654603546)
* [fix: Fixed a judgment statement error](https://github.com/aitos-io/BoAT-X-Framework/commit/576f6db7678404475251046f3bb156ed32aba342)
* [refactor: Modified a ‘condition != True’](https://github.com/aitos-io/BoAT-X-Framework/commit/fa6ab6d6f829cc4232f12593024f9ad31a25a02c)
* [fix:update boatplatform_internal.c,add support for BOAT_WALLET_PRIKEY…](https://github.com/aitos-io/BoAT-X-Framework/commit/e6aef3c2b1b0c7d0e84ac79c8f583ce8ea415b8b)
* [Docs:update readme,modify macro options of mbedtls](https://github.com/aitos-io/BoAT-X-Framework/commit/ad4aef6720561428296b3090ccdea31380d60acc)
* [fix:Delete useless code](https://github.com/aitos-io/BoAT-X-Framework/commit/e3fb5b16150de848ce6d1634163a2ba5139f2644)
* [fix: Reamove variable reuse](https://github.com/aitos-io/BoAT-X-Framework/commit/923eaffdc84559ff2750688f67a5ef79ab2038b4)
* [docs: update description](https://github.com/aitos-io/BoAT-X-Framework/commit/36ee98a8b9675aa4dfc550704dd8e6207efeaf2a)
* [ feat: add cmake](https://github.com/aitos-io/BoAT-X-Framework/commit/4ff7bee6e1fca760f68bdf9b3a95d485bc1e8e20)
* [fix: Fixed an error calculating the length of blocklimit (](https://github.com/aitos-io/BoAT-X-Framework/commit/f51ec45d2f20a9cc4f5706d4372f8db2c577c2dc)[#311](https://github.com/aitos-io/BoAT-X-Framework/pull/311)[)](https://github.com/aitos-io/BoAT-X-Framework/commit/f51ec45d2f20a9cc4f5706d4372f8db2c577c2dc)
* [refactor: Remove useless code](https://github.com/aitos-io/BoAT-X-Framework/commit/09208194e5c169dfc91411a43a16e2396d3245b6)
* [refactor: Reduced one call to api_ethereum.c function.](https://github.com/aitos-io/BoAT-X-Framework/commit/ddbb5ab0afcbab9ffa2ced0925dbddf032b9c1f0) 
* [feat(MTK-MT3620): add MTK-MT3620](https://github.com/aitos-io/BoAT-X-Framework/commit/ad0b9012437f8dd69976d4db93d8f25d3f02da62)
* [docs: Modified one punctuation mark](https://github.com/aitos-io/BoAT-X-Framework/commit/7d41c450cd5d6b2069ea18500d3838ae95e6428d)
* [fix: Fix some bugs](https://github.com/aitos-io/BoAT-X-Framework/commit/682db949b23d405767a7af705629cfdea65b7efc)
* [refactor: modify cmake](https://github.com/aitos-io/BoAT-X-Framework/commit/0a18bacf46858173350b01afaae5a378ef57dad3)
* [docs: update a description of overview](https://github.com/aitos-io/BoAT-X-Framework/commit/45b3f30f42bdba84dd913925cb986edd077081ea)
* [Feat:delete useless timeout value](https://github.com/aitos-io/BoAT-X-Framework/commit/c6a818618d79b0660f57b1893bd2f21a2fe0047c)
* [Feat: adapt calculate public key & boat sign function for XinYi1100](https://github.com/aitos-io/BoAT-X-Framework/commit/2d82abd46be05be19d4f65734b66fe77b47ff168)
* [Feat:update demo code for BoAT;delete useless code.](https://github.com/aitos-io/BoAT-X-Framework/commit/36c75eb45537438aed42d7e8f867b61b7632f53f)
* [Feat:delete the case of native key](https://github.com/aitos-io/BoAT-X-Framework/commit/e6acbe88cc71ec8c343f6ae3d51071615da68e64)
* [delect my_contract.cpp.abi.h](https://github.com/aitos-io/BoAT-X-Framework/commit/034b56ecf14352b3c38686266beebac4492c69db)
* [fix: The returned error can be handled correctly](https://github.com/aitos-io/BoAT-X-Framework/commit/7f3402897da08a0777c675c807e80eb049f99249)
* [refactor: Fixed an inappropriate call](https://github.com/aitos-io/BoAT-X-Framework/commit/b0518a11843f08c3e7680d5f356895d5a6095477)
* [refactor: Delete unused variables](https://github.com/aitos-io/BoAT-X-Framework/commit/0966bbeb470c708d3fde85cfbe44eaaa319310f1)
* [refactor: Simplify conditions for if](https://github.com/aitos-io/BoAT-X-Framework/commit/ef2de54ed34deda2b76162d86c3dbc5b187b15cb)
* [refactor: Uniform code format](https://github.com/aitos-io/BoAT-X-Framework/commit/de9bfe435f604d6109f3644f63b7e6723532f186)
* [Feat:Support PKCS key format.](https://github.com/aitos-io/BoAT-X-Framework/commit/433045c2ca522b8c0d966712be6d7bf1d5102b48)
* [Feat:update boatplatform_internal.c,support PKCS key](https://github.com/aitos-io/BoAT-X-Framework/commit/cbda898ae096cf179f901c5c4db7f10189a52541)
* [Docs:update readme,modify los_mbedtls_config](https://github.com/aitos-io/BoAT-X-Framework/commit/58c0000a199df9e997c5727099b08af21715af47)
* [Feat:delete useless function mbedtls_pk_setup](https://github.com/aitos-io/BoAT-X-Framework/commit/e558a482affdb205e8c4aa346aede0cee32997f5)
* [docs: add a hyphen in the titles.](https://github.com/aitos-io/BoAT-X-Framework/commit/17e4f651419c00bf7a4cd01cb0f431e9823cf5d3) 
* [docs: fix some grammar and spelling issues](https://github.com/aitos-io/BoAT-X-Framework/commit/02d639a8d474777bf3464261750a3c0a1b82967c)
* [docs: rephrase one sentence](https://github.com/aitos-io/BoAT-X-Framework/commit/44d6c639e53f10daaba0817d0c35a363f04ef710)
* [fix: Change an inline function to a generic function](https://github.com/aitos-io/BoAT-X-Framework/commit/2606da0e422f61dadd8020204b8eeba2a56d75a5)

## Major Pull Requests

* [fix: Fixed an error calculating the length of blocklimit](https://github.com/aitos-io/BoAT-X-Framework/pull/311)
* [Boatiosdk mtk mt3620 dev](https://github.com/aitos-io/BoAT-X-Framework/pull/319)
* [XinYi1100_dev分支合入2.0申请](https://github.com/aitos-io/BoAT-X-Framework/pull/320)

## Major Issues

**Open**

- ["full lifecycle" would be better than "full lifecycle flow"](https://github.com/aitos-io/BoAT-X-Framework/issues/288)
- [Does the name of the variable eip155_compatibility need to be changed](https://github.com/aitos-io/BoAT-X-Framework/issues/291)
- [A problem in a code static test.](https://github.com/aitos-io/BoAT-X-Framework/issues/297)
- [BoAT-X-Framework/Readme/Add more website to the list](https://github.com/aitos-io/BoAT-X-Framework/issues/300)
- [Optimize "Quick Start" in the README](https://github.com/aitos-io/BoAT-X-Framework/issues/301)
- [Part 3 Operating System and Communication Requirements](https://github.com/aitos-io/BoAT-X-Framework/issues/303)
- [BoAT_System_Requirements_cn/ Framework and SDK should not be used in the same sentence](https://github.com/aitos-io/BoAT-X-Framework/issues/304)
- [jsonrpc respone err](https://github.com/aitos-io/BoAT-X-Framework/issues/308)
- [platON rum demo error](https://github.com/aitos-io/BoAT-X-Framework/issues/309)
- [Some improper position of the function.](https://github.com/aitos-io/BoAT-X-Framework/issues/312)
- [The web3_parse_json_result function does not meet the requirements](https://github.com/aitos-io/BoAT-X-Framework/issues/313)
- [Not easy to find the Chinese Version documentation](https://github.com/aitos-io/BoAT-X-Framework/issues/318)

**Closed**

* [The query results cannot be obtained in the fabric demo](https://github.com/aitos-io/BoAT-X-Framework/issues/287)
* [It's hard to understand the describtion "such as initializing the use identifier as unused, and initializing the wallet as a null pointer"](https://github.com/aitos-io/BoAT-X-Framework/issues/289)
* [ChinaMobile-ML302 Chinese document has no punctuation at the end of the last sentence](https://github.com/aitos-io/BoAT-X-Framework/issues/292)
* [Fibocom-L610 Chinese document has no punctuation at the end of the last sentence](https://github.com/aitos-io/BoAT-X-Framework/issues/293)
* [YanFei-CUIot-MZ-6 Chinese document has no punctuation at the end of the last sentence](https://github.com/aitos-io/BoAT-X-Framework/issues/294)
* [Neoway-N58 Chinese document punctuation use error](https://github.com/aitos-io/BoAT-X-Framework/issues/295)
* [Fibocom-L610 Chinese document modification suggestions](https://github.com/aitos-io/BoAT-X-Framework/issues/296)
* [BoAT-X-Framework/Readme/Remove the space before commas](https://github.com/aitos-io/BoAT-X-Framework/issues/298)
* [BoAT-X-Framework/Readme/Add PlatON to the <protocol>](https://github.com/aitos-io/BoAT-X-Framework/issues/299)
* [Failed to call fiscobcos](https://github.com/aitos-io/BoAT-X-Framework/issues/302)
* [BoAT_System_Requirements_cn.md/ OpenCPU modules](https://github.com/aitos-io/BoAT-X-Framework/issues/305)
* [A parameter in FISCO-BCOS is incorrectly filled](https://github.com/aitos-io/BoAT-X-Framework/issues/306)
* [A variable reuse in FiscobcosSendRawtx()](https://github.com/aitos-io/BoAT-X-Framework/issues/307)
* [Fiscobcos transaction return value is not processed correctly](https://github.com/aitos-io/BoAT-X-Framework/issues/310)
* [Is it better to remove the comma in the sentence dscribed below?](https://github.com/aitos-io/BoAT-X-Framework/issues/314)
* [Figure 4-5,Figure 4-6 both can not be seen](https://github.com/aitos-io/BoAT-X-Framework/issues/315)
* [BoAT User Guide/BoAT System Requirements/English Documents](https://github.com/aitos-io/BoAT-X-Framework/issues/316)
* [BoAT User Guide/English Documents](https://github.com/aitos-io/BoAT-X-Framework/issues/317)


## Highlights of Ecosystem Update
* [On Sep 6, 2021, aitos.io was invited to Fibocom 5G AIoT annual innovation online conference and jointly promoted 5G AIoT Panoramic Commercial Product Manual.](https://mp.weixin.qq.com/s?__biz=MzI3NDYxOTc2NQ%3D%3D&mid=2247496108&idx=1&sn=9bfdbdc2cd715e71e16f0f03b6cf8140&scene=45#wechat_redirect)
* [On Sep 16, 2021, aitos.io CEO Leo Lin was invited to deliver a keynote speech for UP·2021 UNISOC Online Ecosystem Conference.](https://mp.weixin.qq.com/s?__biz=MzI2MDE5NDYzNA==&mid=2247487075&idx=1&sn=5f26aafbb91e1e7f7e481b4a5cbde6c5&chksm=ea6c2646dd1baf50062c1b44f9e66e02111c8c6f00e115f31f3807e7b40622177a45a085e5d2&token=1536262129&lang=zh_CN#rd)