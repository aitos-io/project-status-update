# BoAT Project Status Update
Date: March 1st, 2023

## Update Summary
In the version of 3.0.2, the BoAT 3.0 architecture is improved and optimized for Ethereum, Chainmaker, FISCO-BCOS, Fabric, PlatON, PlatONE and HWBCS blockchains. Cellular chip/module MA510, ML302, MN316, Simcom A7670C are added into BoAT 3.0 architecture. 10  BoAT demo code issues are optimized for cellular modules. 5 UT and Network unit test case issues are optimized.


## Releases

[BoAT-X-v3.0.2](https://github.com/aitos-io/BoAT-X-Framework/releases/tag/BoAT-X-v3.0.2) is released.

**Change Log**

- Add modules MA510, ML302, MN316, Simcom A7670C into BoAT 3.0 architechiture
- Optimize Ethereum, Chainmaker, FISCO-BCOS, Fabric, PlatON, PlatONE and HWBCS in BoAT 3.0 architecture
- Optimize 10 BoAT demo issues for cellular modulues
- Optimize 5 UT and Network unit test case issues

## Major Commits
* [feat[MA510]:Add rpcintf](https://github.com/aitos-io/BoAT-X-Framework/commit/5d5ea84512a2859dd11f92ee7817eee549b26909)
* [feat[MA510]:Add http_client.c](https://github.com/aitos-io/BoAT-X-Framework/commit/d2b3a5259c8b71cfaa8c3502ebc59be65ee6bc76)
* [feat[MA510]:Add http_client.h](https://github.com/aitos-io/BoAT-X-Framework/commit/8b2558ed46416900eafec2c7407210513ace0e4e)
* [feat[MA510]:Add fibocomhttpport.c](https://github.com/aitos-io/BoAT-X-Framework/commit/6f63aef57903ac341b9ba5f1242d0c9c22652f1e)
* [feat[MA510]:Add fibocomhttpport.h](https://github.com/aitos-io/BoAT-X-Framework/commit/43f4c318c2eaf45db481396b313edc0501debc21)
* [feat[MA510]:Add rpc Makefile](https://github.com/aitos-io/BoAT-X-Framework/commit/804a927e63b01270a4ad43b37fd8bc672e9de16c)
* [feat[MA510]:Add gen.py](https://github.com/aitos-io/BoAT-X-Framework/commit/11ac7de88005fc4976bd334bff235e6b5b66751b)
* [feat[MA510]:Add boatlog.h](https://github.com/aitos-io/BoAT-X-Framework/commit/2e41048ff8ae6acde6639d6040fbfaa4da06e75d)
* [feat[MA510]:Add boatplatform_internal.c](https://github.com/aitos-io/BoAT-X-Framework/commit/5f92518c8e5082e9c89077fb8d84c2e2d0ea98b8)
* [feat[MA510]:Add boatplatform.c](https://github.com/aitos-io/BoAT-X-Framework/commit/70b1c5f55f4c533465eb0090a29565ada5fa54c1)
* [feat[MA510]:Add port_crypto_default Makefile](https://github.com/aitos-io/BoAT-X-Framework/commit/afed0efb27c46004c8f579d9a6f5c77d25721998)
* [feat[MA510]:Modify boatplatform_internal.c](https://github.com/aitos-io/BoAT-X-Framework/commit/4cb8ca35f4f46f13a979dd649878612175fa7d51)
* [feat[MA510]:Modify boatplatform.c](https://github.com/aitos-io/BoAT-X-Framework/commit/49fbb561d954dad338bcd282db092983a9680ef9)
* [feat[MA510]:Add external.env](https://github.com/aitos-io/BoAT-X-Framework/commit/0ffe5403fec6b25231ff67280cc16c295d94a95b)
* [doc[MA510][#1366]:Add README](https://github.com/aitos-io/BoAT-X-Framework/commit/3815ba521fffafbc2087cb62c7b29e6285017386)
* [doc[MA510][#1366]:Add README_en](https://github.com/aitos-io/BoAT-X-Framework/commit/d36b961ef4e974de81c060868a24b0873e5243bf)
* [feat[MA510]:Add Makefile](https://github.com/aitos-io/BoAT-X-Framework/commit/e064b6750f5223cebfdbbb046e10282076c87b8e)
* [demo[MA510]:Add demo contract h file](https://github.com/aitos-io/BoAT-X-Framework/commit/bed741e18d4b897bc9fc6935f59735e72e27235a)
* [demo[MA510]:Add demo contract c file](https://github.com/aitos-io/BoAT-X-Framework/commit/1f2d4ad160750e116c0466af5e8b332f08f48c79)
* [demo[MA510]:Modify platone demo](https://github.com/aitos-io/BoAT-X-Framework/commit/43c6ace38f2e53436d755e2e9309d54870501a28)
* [demo[MA510]:Add fabric demo](https://github.com/aitos-io/BoAT-X-Framework/commit/767dc023544d691ce90c3a95f79027b9fcd4c45c)
* [demo[MA510]:Modify fabric demo](https://github.com/aitos-io/BoAT-X-Framework/commit/3d13fe6404a4ed296c9816d9857193ee82761f94)
* [demo[eth][#1345]:modify function name](https://github.com/aitos-io/BoAT-X-Framework/commit/7ed3955c04cc4d29f960377c3d13454c167499fd)
* [feat[eth][#1345]:Modify function name](https://github.com/aitos-io/BoAT-X-Framework/commit/b523cfa44da7c6eac3777a168ceb903750184ba0)
* [test[eth][#1345]:Modify function name](https://github.com/aitos-io/BoAT-X-Framework/commit/96871814bf88a788a74902fd3c80ad1855f8bd48)
* [test[network][#1345]:Modify function name](https://github.com/aitos-io/BoAT-X-Framework/commit/6fb4f2b14e86ba446071d80b81e121f19df3b541)
* [demo[chainmaker][#1367]:Modify function name](https://github.com/aitos-io/BoAT-X-Framework/commit/efc742fa063ff3c3c0f6e278ce0e072d747a66d9)
* [feat[chainmaker][#1367]:Modify function name](https://github.com/aitos-io/BoAT-X-Framework/commit/dc7a5430e6830352e15cbd850ddaee291526444d)
* [test[chainmaker][#1367]:Modify function name](https://github.com/aitos-io/BoAT-X-Framework/commit/9cb155c5aefc227997d3564d0a85de0a19711634)
* [demo[ChainMaker][#1367]:Modify function name](https://github.com/aitos-io/BoAT-X-Framework/commit/1f5e8b2a780fa2d6a78626ea47bfa6e3f84fa496)
* [fix(chainmaker test):Fixed chainmaker testing issues on the L610 #1368 AOHH-54](https://github.com/aitos-io/BoAT-X-Framework/commit/90c214b4fdabbd20b90ee7e66a1ebf64ad6b1bb6)
* [fix(chainmaker test):Fixed chainmaker testing issues on the L610 #1369 AOHH-54](https://github.com/aitos-io/BoAT-X-Framework/commit/fb1fcb37b654e6a490cd988f09f0f26f214e3855)
* [fix(chainmaker test):Fixed chainmaker testing issues on the L610 #1370 AOHH-54](https://github.com/aitos-io/BoAT-X-Framework/commit/898bab9dc09f812d312d6d1e60a822f9b2f1f30e)
* [demo[fiscobcos\][#1372]:Modify function name](https://github.com/aitos-io/BoAT-X-Framework/commit/a3d369a956eb4e438a5c1742d0bc2db92ca96f3c)
* [feat[fiscobcos\][#1372]:Modify function name](https://github.com/aitos-io/BoAT-X-Framework/commit/0525e2d37828f3e355e7cc49276225e050e7d07a)
* [test[FiscobcosNetwork\][#1372]:Modify function name](https://github.com/aitos-io/BoAT-X-Framework/commit/06384c5fbb4553b945b98ec0f1cfc02358fc38c1)
* [test[UT\][#1372]:Modify function name](https://github.com/aitos-io/BoAT-X-Framework/commit/8f36c501c96eb909a0bac3648915101a44b80e67)
* [feat(fabric ):add fabric onto ML302v2 #1373 BoATE-1027](https://github.com/aitos-io/BoAT-X-Framework/commit/c44a2ad1ee5cf82a7fc3f824b12c17edd56a75c7)
* [feat(ml302):add fabric onto ML302v2 #1373 BoATE-1026](https://github.com/aitos-io/BoAT-X-Framework/commit/433b30e9719957da28691d559bb545df80f85f99)
* [modify README.md of ML302v2](https://github.com/aitos-io/BoAT-X-Framework/commit/4452dbb10dcdae84e3d73252511db49f5fa9b8ef)
* [feat(MN316):Port BoAT3.0 to MN316 #1374 BoATE-1024](https://github.com/aitos-io/BoAT-X-Framework/commit/67adb9016a726eb658f218a48167921cb21a1e9c) 
* [demo[hwbcs\][#1375]:Modify function name](https://github.com/aitos-io/BoAT-X-Framework/commit/72ccdd419964e2d5ee27f1c900c1c3b00ea3d19f)
* [feat[hwbcs\][#1375]:Modify function name](https://github.com/aitos-io/BoAT-X-Framework/commit/7143ac7ac6d191bd1451dd62813fa2e6b8203547)
* [test[HwbcsNetwork\][#1375]:Modify function name](https://github.com/aitos-io/BoAT-X-Framework/commit/ab9e8fcbdab51861f41fe44d8e39cf03e47056fd)
* [test[UT\][#1375]:Modify function name](https://github.com/aitos-io/BoAT-X-Framework/commit/622159486d10f36f66e92c82f92f0549bf96978c)
* [demo[platon\][#1376]:Modify function name](https://github.com/aitos-io/BoAT-X-Framework/commit/02a1cbf48ad46b42f5c8482c4f3413e4b507a8ba)
* [feat[platon\][#1376]:Modify function name](https://github.com/aitos-io/BoAT-X-Framework/commit/67ac45213d132925ffee18264ce9f9eade3857b6)
* [test[platon\][#1376]:Modify function name](https://github.com/aitos-io/BoAT-X-Framework/commit/a4aac4301c43dcfbf2420e67104352400d6bf5be)
* [test[UT\][#1376]:Modify function name](https://github.com/aitos-io/BoAT-X-Framework/commit/b0ceec55f3590a8ee30dca5e4c487085735ed7bd)
* [feat(Simcom-A7670C):Add platone to Simcom-A7670C #1377 BoATE-872](https://github.com/aitos-io/BoAT-X-Framework/commit/0fc70feb73cf3cecd1007bdb8ae0b927d3ad3d40)
* [feat(Simcom-A7670C):Add fabric to Simcom-A7670C #1378 BoATE-910](https://github.com/aitos-io/BoAT-X-Framework/commit/45bb655ede0cd99b25e452ee2a13da5f8c1fe0aa)
* [feat(Simcom-A7670C):Some AES interfaces are redefined on the Simcom-A7670C platform #1379 BoATE-910](https://github.com/aitos-io/BoAT-X-Framework/commit/0a73f123ca6fdbe65ff586340911133fc5deac6e) 
* [demo[platone\][#1380]:](https://github.com/aitos-io/BoAT-X-Framework/commit/fa524325da7cf3098742b8586a37a1d80c8178ad) 
* [feat[platone\][#1380]:](https://github.com/aitos-io/BoAT-X-Framework/commit/936212eac372bd25bc01f1337e053fa201ca8e91)
* [test[platone\][#1380]:](https://github.com/aitos-io/BoAT-X-Framework/commit/d5da141865afc525315f649effac83d2aac3252a)
* [test[platone_demo\][#1380]:](https://github.com/aitos-io/BoAT-X-Framework/commit/e8d8884b91f534f01a14e404a1e02b87ac656f35)
* [test[network\][#1380]:](https://github.com/aitos-io/BoAT-X-Framework/commit/0bfa6b6d629c601cad180de36265c80a9ebaa392) 
* [demo[ML302v2\][#1380]:](https://github.com/aitos-io/BoAT-X-Framework/commit/236df0ad27239930b42da3f2ab3f696ea92d103c)
* [demo[MN316\][#1380]:](https://github.com/aitos-io/BoAT-X-Framework/commit/fcdb803c9a60f27e6cc270bb7ed3c5ee266ad039)
* [demo[FG150\][#1380]:](https://github.com/aitos-io/BoAT-X-Framework/commit/5998b1db5fd8334c5deeb1ffd97c0f8679074e41)
* [demo[FM650\][#1380]:](https://github.com/aitos-io/BoAT-X-Framework/commit/66a813403603ade67d068116292251d63c7ca2fd)
* [demo[L610\][#1380]:](https://github.com/aitos-io/BoAT-X-Framework/commit/84ef04b7ec824aace934ac02ca028990425bc5b6)
* [demo[MA510\][#1380]:](https://github.com/aitos-io/BoAT-X-Framework/commit/2555bd0bbcfe22283803f6a9741fd30f69c1f3e4)
* [demo[L503C\][#1380]:](https://github.com/aitos-io/BoAT-X-Framework/commit/358d533a7f4e390f51a0abf0cfdc67b637bebc3b)
* [demo[A7670C\][#1380]:](https://github.com/aitos-io/BoAT-X-Framework/commit/f9f8a76d5d9e7731cbfe8cc9851515c825c271c9)
* [demo[XY1100\][#1380]:](https://github.com/aitos-io/BoAT-X-Framework/commit/132efe0e05815d65adee677d2a4835350db2c088)
* [demo[XY1100-R14\][#1380]:](https://github.com/aitos-io/BoAT-X-Framework/commit/76fe6210ed15a8bf4495d3886a309e7ae6edc791)

## Major Issues

**Open**

- [3.0 branch lacks readme of MA510](https://github.com/aitos-io/BoAT-X-Framework/issues/1366)
- [Network function naming of chainmaker](https://github.com/aitos-io/BoAT-X-Framework/issues/1367)
- [Network function naming of Fiscobcos](https://github.com/aitos-io/BoAT-X-Framework/issues/1372)
- [Network function naming of hwbcs](https://github.com/aitos-io/BoAT-X-Framework/issues/1375)
- [Network function naming of PlatON](https://github.com/aitos-io/BoAT-X-Framework/issues/1376)
- [Add platone to Simcom-A7670C](https://github.com/aitos-io/BoAT-X-Framework/issues/1377)
- [Add fabric to Simcom-A7670C](https://github.com/aitos-io/BoAT-X-Framework/issues/1378)
- [Some AES interfaces are redefined on the Simcom-A7670C platform](https://github.com/aitos-io/BoAT-X-Framework/issues/1379)
- [Network function naming of PlatONE](https://github.com/aitos-io/BoAT-X-Framework/issues/1380)
- [Network function naming of Venachain](https://github.com/aitos-io/BoAT-X-Framework/issues/1381)
- [Network function naming of quorum](https://github.com/aitos-io/BoAT-X-Framework/issues/1382)

**Closed**

* [Fixed chainmaker testing issues on the L610](https://github.com/aitos-io/BoAT-X-Framework/issues/1368)
* [Fixed fabric testing issues on the L610](https://github.com/aitos-io/BoAT-X-Framework/issues/1369)
* [Fixed platone testing issues on the L610](https://github.com/aitos-io/BoAT-X-Framework/issues/1370)
* [add fabric onto ML302v2](https://github.com/aitos-io/BoAT-X-Framework/issues/1373)
* [Port BoAT3.0 to MN316](https://github.com/aitos-io/BoAT-X-Framework/issues/1374)


## Highlights of Ecosystem Update
* [Mr. Leo Lin 林瑶, CEO of aitos.io, participates in Matrix Partners China Billions Institute Entrepreneurs Camp.](https://www.linkedin.com/posts/aitos-io_be-ambition-sensitive-and-endowment-sensitive-activity-7038439480738910208-gCF0?utm_source=share&utm_medium=member_desktop)
* [Shortlisted as 2022 “Maker in China” Shanghai SME Innovation and Entrepreneurship Competition TOP100, aitos.io captured 3rd place prize during Yangtze River Delta’s Digital Trunk Professional Competition and was also shortlisted as one of the “50 Best Investment Potential candidates”.](https://www.linkedin.com/posts/aitos-io_aitosio-was-shortlisted-as-2022-maker-in-activity-7035126354555670529-Agpp?utm_source=share&utm_medium=member_desktop)
* [aitos.io is now cooperating with the national enterprise Blockchain BIF-Core in China and successfully advanced to the Eastern Division national finals with a second-place award.](https://www.linkedin.com/posts/aitos-io_aitosio-has-successfully-attained-a-second-place-activity-7016287401492840448-W_In?utm_source=share&utm_medium=member_desktop)

