# BoAT Project Status Update
Date: January 7th, 2022

## Update Summary
In this version, some test cases were added and updated as well as some issues were resolved for chainmaker. Some memory leaks were resolved and the uniform error codes were defined. More official and github website links were added to the protocol list. The BoAT whitepaper and BoAT Blockchain IoT Module Technology and Application document were uploaded to the github. Some readme files and documents were updated as well.

## Releases
[BoAT-X-v2.1.6](https://github.com/aitos-io/BoAT-X-Framework/releases/tag/BoAT-X-v2.1.6) is released.

**Change Log**

- Add and modify test cases for chainmaker part
- Fix some bugs about chainmaker part
- Resolve memory leaks
- Define uniform error codes and adjust the codes
- Add official and github website links to the protocol list
- Upload BoAT whitepaper (Chinese and English version)
- Upload BoAT Blockchain IoT Module Technology and Application document
- Update some documents and README files (Chinese and English version)

## Major Commits
* [\[chainmaker\][#474]remove BoatChainmakerWalletSetNodeUrl func](https://github.com/aitos-io/BoAT-X-Framework/commit/aaeebf6d4ca4e6020b6f526b23e04c66f8e8e9fa)
* [\[chainmaker\][#475]remove not used function](https://github.com/aitos-io/BoAT-X-Framework/commit/a49b554d4084cb482d50a03a488f9ff70d3aecf5)
* [fix:MT3620](https://github.com/aitos-io/BoAT-X-Framework/commit/a1b4675cd0176689d2bbbea979cb7eb45e0a4201)
* [\[chainmaker\][#436]add param_add_check parameters number](https://github.com/aitos-io/BoAT-X-Framework/commit/f4fc9b3c459aa71dce549cc034fdffbf9b5e853a)
* [\[chainmaker\][#436]modify param_add_check function param check](https://github.com/aitos-io/BoAT-X-Framework/commit/2aaed5154bc1809fd4160bfe08b6598b68942bc2)
* [\[chainmaker\][#436]add test test_002Param_0009AddTxParamSucessTxLessMa…](https://github.com/aitos-io/BoAT-X-Framework/commit/20a8566db30207dfad3520f7ed4f247fa3ff67d3)
* [\[chainmaker\][#436]add test_002Param_0010AddTxParamFailureMoreMaxOddPa…](https://github.com/aitos-io/BoAT-X-Framework/commit/0af5041e0e505972ce35fbb7e32c37383d348724)
* [\[chainmaker\][#436]modify function name](https://github.com/aitos-io/BoAT-X-Framework/commit/8458951aad37d7da2dac1be3cd4af626dae0efff)
* [fix(memory leak):](https://github.com/aitos-io/BoAT-X-Framework/commit/8388cf91adcf0129dd5e1918c2c62b40af90e9b6)
* [\[chainmaker\][#436]remove BoatHlchainamkerClient struct](https://github.com/aitos-io/BoAT-X-Framework/commit/a0a362d37739b8012dde9739dab25ecbb6540cc0)
* [\[chainmaker\][#436]add BoatChainmakerNodeInfo struct](https://github.com/aitos-io/BoAT-X-Framework/commit/e0080afc876dd2345f3b6ad0c679a964c6d7b432)
* [\[chainmaker\][#483]BoatHlchainmakerWalletConfig add chain_id and org_i…](https://github.com/aitos-io/BoAT-X-Framework/commit/99d2df29843bc8635bcfd4c7107cf4700cc88095)
* [\[chainmaker\][#483]add chain_id and org_id len check](https://github.com/aitos-io/BoAT-X-Framework/commit/f25956ac9d7faf79eeed7c94e0ac2e88f3401f76)
* [\[chainmaker\][#483]copy chain_id and org_id to walletconfig](https://github.com/aitos-io/BoAT-X-Framework/commit/ec30050e0d8d37c763e4dbf6abd3c69e642b627f)
* [\[chainmaker\][#483]modify BoatHlChainmakerTxInit parameters](https://github.com/aitos-io/BoAT-X-Framework/commit/64ac861aa06d1a1ec315164a7402284b4ffec1e5)
* [\[chainmaker\][#483]modify chain_id and org_id str name](https://github.com/aitos-io/BoAT-X-Framework/commit/d5cbdfd90d9fcba870eca715c431e81b31a6ff02)
* [\[chainmaker\][#483]wallet init add chain_id and org_id](https://github.com/aitos-io/BoAT-X-Framework/commit/74471776a6262fe8e0dc80ecf8ed4071e9e44a2c)
* [\[chainmaker\][#483]add wallet Dinit chain_id and org_id](https://github.com/aitos-io/BoAT-X-Framework/commit/5935a417a0748a44a3cd00076d5a2f46ef4514e9)
* [docs: add FISCO BCOS official website to the list](https://github.com/aitos-io/BoAT-X-Framework/commit/203fcc94f795b5c3bbc4d99f6b92fcba4fa4ba6d)
* [docs: add FISCO BCOS github website to the list](https://github.com/aitos-io/BoAT-X-Framework/commit/24f4f0f51aea9c8c5f3402773ee1e02a1adc5ade)
* [fix(memory leak):](https://github.com/aitos-io/BoAT-X-Framework/commit/e462e3b33eb2b583128221a86a153e59dcdf10bf)
* [docs: add PlatON official websites to the list](https://github.com/aitos-io/BoAT-X-Framework/commit/85538786a4a988f0432aae7037b7b1ab472c4970)
* [docs: adjust the list](https://github.com/aitos-io/BoAT-X-Framework/commit/85f8702cad1577738b09521dac164fecf4e6c8e2)
* [\[chainmaker\][#436]modify test boatHlChainmakerTxInit parameters](https://github.com/aitos-io/BoAT-X-Framework/commit/79e65709fd07d22c49d613cba9049abc2329368c)
* [\[chainmaker\][#436]modify test chain_id and org_id](https://github.com/aitos-io/BoAT-X-Framework/commit/1968e89e79bdf881b8c17cf1d05cc70c7e6bd5d4)
* [\[chainmaker\][#436]modify url path](https://github.com/aitos-io/BoAT-X-Framework/commit/e81f5d1491bccb68f4291a77d484094e843ed5de)
* [\[chainmaker\][#436]modify contratc BoatHlChainmakerTxInit parameters](https://github.com/aitos-io/BoAT-X-Framework/commit/329eedb8b492d7a16c38c8d02b45722ce6b50810)
* [fix(fabric):](https://github.com/aitos-io/BoAT-X-Framework/commit/0212191e5b8ec9f4ad13d138c084148a335e79c8)
* [Update ReadMe](https://github.com/aitos-io/BoAT-X-Framework/commit/1b2219a43754363d1f73d4c253d19054073695c5)
* [fix: fix convert public key to Bech32 format](https://github.com/aitos-io/BoAT-X-Framework/commit/931312eac44a38aa1e33fe7313be9bb4c5033ae6)
* [fix(platon):](https://github.com/aitos-io/BoAT-X-Framework/commit/6ea1541a337350d56e33d8458f5735f6ff1e937f)
* [\[chainmaker\][#510]open TLS macro](https://github.com/aitos-io/BoAT-X-Framework/commit/ef2478318020d934a7b40a0bdbbfa7a74f5d9188)
* [\[chainmaker\][#510]slove compile err](https://github.com/aitos-io/BoAT-X-Framework/commit/63c26c2e8ce61b6f05aacc587d81103f67c46a71)
* [update README_en](https://github.com/aitos-io/BoAT-X-Framework/commit/02b9e2f505abf7b8efc0eda5a3f5609ceb2f2b73)
* [docs: Add chainmaker to the protocol list.](https://github.com/aitos-io/BoAT-X-Framework/commit/8a4b55d6432e5a4397c97d5af986992c6a1f17cc)
* [\[chainmaker\][#510]modify memcpy str len](https://github.com/aitos-io/BoAT-X-Framework/commit/3881e657c70fa5ca35fd8eecb7967aa06b171e99)
* [\[chainmaker\][#510]remove memset](https://github.com/aitos-io/BoAT-X-Framework/commit/07af5a2a5ccd7e61b9c2e63a28058e489b90af65)
* [\[chainmaker\][#436]modify py pass parameters](https://github.com/aitos-io/BoAT-X-Framework/commit/1bc62e9e0692e10ad7db7a9297e65d6950ceb9d2)
* [\[chainmaker\][#436]add chain_id host_name and org_id](https://github.com/aitos-io/BoAT-X-Framework/commit/f47238cfe2de47c92e8a5b230467d68bc71ab394)
* [\[chainmaker\][#436]modify cert len](https://github.com/aitos-io/BoAT-X-Framework/commit/4f4a906cc091d64962d1cac3e3e35e0a56b7d246)
* [\[chainmaker\][#436]add host name in Makefile](https://github.com/aitos-io/BoAT-X-Framework/commit/afff2cc8045ca4d41fa676bb71fa025a30c22b9a)
* [\[chainmaker\][#436]add open tls sign key and cert](https://github.com/aitos-io/BoAT-X-Framework/commit/25fd96d45f97bb265679515a7001b2bbf490ec27)
* [\[chainmaker\][#436]modify buf name](https://github.com/aitos-io/BoAT-X-Framework/commit/64150da0b37de0f7adc61017ed85f88b5a001afe)
* [\[chainmaker\][#436]add cert inteface](https://github.com/aitos-io/BoAT-X-Framework/commit/34a4fbad906df6f32d15132788e4f608260d5af9)
* [\[chainmaker\][#436]add cert file](https://github.com/aitos-io/BoAT-X-Framework/commit/7adb85d86d7ccb8951f12b33b63542089f867c54)
* [docs: upload BoAT whitepaper CN verison](https://github.com/aitos-io/BoAT-X-Framework/commit/3cc18746f2b4702a2810d307f64ba2ec493956fa)
* [docs: upload BoAT whitepaper EN version](https://github.com/aitos-io/BoAT-X-Framework/commit/8788c161a46d929936aafd2c1a8fa48386111576)
* [docs: add whitepaper link on the main page.](https://github.com/aitos-io/BoAT-X-Framework/commit/fefbb84e25f2c3da0a2ea30d008f9e53b2240e9a)
* [update English version white paper file name](https://github.com/aitos-io/BoAT-X-Framework/commit/ec78cd61d3c5b208ed01cc7d447d54da4cd0c174)
* [update Chinese version white paper file name.](https://github.com/aitos-io/BoAT-X-Framework/commit/e5a425d695f6d64d41618d98230eef771d34245a)
* [perf(errorCode):](https://github.com/aitos-io/BoAT-X-Framework/commit/de23f4c199dd9ee6e33650a95290daf5782d05bc)
* [\[chainmaker\][#436]modify Invalid error code name](https://github.com/aitos-io/BoAT-X-Framework/commit/f6e8b4efaba63954948366863a62fbbe315f89f3)
* [\[chainmaker\][#436]modify create wallet return value](https://github.com/aitos-io/BoAT-X-Framework/commit/40007feec32006ccd2a57eaa1080110ca1bfe6b1)
* [\[chainmaker\][#436]modify read file failed value](https://github.com/aitos-io/BoAT-X-Framework/commit/0351076347259b418e67811058d84be1d5478af7)
* [fix: Add the missing semicolon](https://github.com/aitos-io/BoAT-X-Framework/commit/318cc5dff06ae3409e65c06141f986ddb305faf8)
* [\[chainmaker\][#436]modify global variable value](https://github.com/aitos-io/BoAT-X-Framework/commit/4b26029cbb71f45c95b01c49eb11a376c34d4bcd)
* [docs: update docs](https://github.com/aitos-io/BoAT-X-Framework/commit/4b8eb89c90e85985ab59caff189e2d114f558b5e)
* [docs: update readme](https://github.com/aitos-io/BoAT-X-Framework/commit/8ef938d756e5ed2b920e5c0c7998aaefd5c6c70b)
* [fix(fabric discovery):](https://github.com/aitos-io/BoAT-X-Framework/commit/35b2cb05ba8a8f90909fc3969469db9b3e0830b2)
* [Add document BoAT Blockchain IoT Module Technology and Application](https://github.com/aitos-io/BoAT-X-Framework/commit/f3a45c53192bfc85e7e24870cff5454be88e822f)

## Major Issues

**Open**

- [Some chapter links in the user manual cannot be quickly redirected](https://github.com/aitos-io/BoAT-X-Framework/issues/473)
- [chainmaker should check url format](https://github.com/aitos-io/BoAT-X-Framework/issues/476)
- [chainmaker chain_id and org_id should save in wallet](https://github.com/aitos-io/BoAT-X-Framework/issues/483)
- [CHainmaker TLS function was not effective](https://github.com/aitos-io/BoAT-X-Framework/issues/510)
- [Improper detection of URL while creating wallet](https://github.com/aitos-io/BoAT-X-Framework/issues/519)
- [Please refine your error codes definition](https://github.com/aitos-io/BoAT-X-Framework/issues/520)
- [L610 Demo fails to run as expected](https://github.com/aitos-io/BoAT-X-Framework/issues/526)

**Closed**

* [chainmaker tests should pass cert and key](https://github.com/aitos-io/BoAT-X-Framework/issues/469)
* [chainmaker chain_id and org_id should save in wallet](https://github.com/aitos-io/BoAT-X-Framework/issues/470)
* [make tests error](https://github.com/aitos-io/BoAT-X-Framework/issues/471)
* [chainmaker BoatHlchainmakerAddTxParam last param should be NULL](https://github.com/aitos-io/BoAT-X-Framework/issues/472)
* [chainmaker BoatChainmakerWalletSetNodeUrl interface never used](https://github.com/aitos-io/BoAT-X-Framework/issues/474)
* [chainmaker api BoatChainmakerWalletSetHostName not used](https://github.com/aitos-io/BoAT-X-Framework/issues/475)
* [error in Random32() of MT3620](https://github.com/aitos-io/BoAT-X-Framework/issues/477)
* [BoAT-X-Framework for Fibocom-MA510 Integration Guideline/ First level title serial numbers are Chinese](https://github.com/aitos-io/BoAT-X-Framework/issues/478)
* [BoAT-X-Framework for Fibocom-MA510 Integration Guideline-Section 2 File Modification-Expression of accurate](https://github.com/aitos-io/BoAT-X-Framework/issues/479)
* [语句更通顺](https://github.com/aitos-io/BoAT-X-Framework/issues/480)
* [File Modification](https://github.com/aitos-io/BoAT-X-Framework/issues/481)
* [web3intf memory leak](https://github.com/aitos-io/BoAT-X-Framework/issues/482)
* [Suggest to add FISCO BCOS official website to the list.](https://github.com/aitos-io/BoAT-X-Framework/issues/484)
* [memory leak of platone](https://github.com/aitos-io/BoAT-X-Framework/issues/485)
* [Suggest to add PlatON official website to the list.](https://github.com/aitos-io/BoAT-X-Framework/issues/486)
* [memory leak of ethereum](https://github.com/aitos-io/BoAT-X-Framework/issues/487)
* [error of fabric if define BOAT_TLS_SUPPORT 0](https://github.com/aitos-io/BoAT-X-Framework/issues/488)
* [memory leak of fabric if return err](https://github.com/aitos-io/BoAT-X-Framework/issues/490)
* [memory leak of BoatHlfabricWalletConfig](https://github.com/aitos-io/BoAT-X-Framework/issues/491)
* [memory leak in hlfabricDiscoveryPayloadDataPacked](https://github.com/aitos-io/BoAT-X-Framework/issues/492)
* [memory leak in BoatHlfabricDiscoverySubmit()](https://github.com/aitos-io/BoAT-X-Framework/issues/493)
* [memory leak of discoverResult](https://github.com/aitos-io/BoAT-X-Framework/issues/495)
* ["tlsCAchain" in "http2Context" is not released](https://github.com/aitos-io/BoAT-X-Framework/issues/496)
* [XY1100的中文文档的最后缺少一个句号](https://github.com/aitos-io/BoAT-X-Framework/issues/497)
* [http2Res of fabricHttp2res in BoatHlfabricTxExec() is not freed](https://github.com/aitos-io/BoAT-X-Framework/issues/498)
* [The Chinese document of MA510 lacks punctuation at the end](https://github.com/aitos-io/BoAT-X-Framework/issues/499)
* ["wallet_ptr" in BoatHlfabricWalletDeInit() is not fully released](https://github.com/aitos-io/BoAT-X-Framework/issues/500)
* [There was a problem converting the public key to Bech32 format in PlatON](https://github.com/aitos-io/BoAT-X-Framework/issues/501)
* [err of platon when creat PersistWallet](https://github.com/aitos-io/BoAT-X-Framework/issues/502)
* ["wallet_ptr" in platonGetBalance() is not freed](https://github.com/aitos-io/BoAT-X-Framework/issues/503)
* ["data" in BoatPlatONBech32Decode() is not freed](https://github.com/aitos-io/BoAT-X-Framework/issues/504)
* ["ecPrikey" of BoatSignature() in linux-default/src/port_mbedtls/boatplatform_internal.c is not freed](https://github.com/aitos-io/BoAT-X-Framework/issues/505)
* [if ethereum demo return error,it will not execute BoatIotSdkDeInit()](https://github.com/aitos-io/BoAT-X-Framework/issues/506)
* [If creating a wallet returns an error in fiscobcos demo,it will not execute BoatIotSdkDeInit()](https://github.com/aitos-io/BoAT-X-Framework/issues/507)
* [if platon demo return error,it will not execute BoatIotSdkDeInit()](https://github.com/aitos-io/BoAT-X-Framework/issues/508)
* [If creating a wallet returns an error in platone demo,it will not execute BoatIotSdkDeInit()](https://github.com/aitos-io/BoAT-X-Framework/issues/509)
* [Open \<YanFei Root\>/cmake/toolchain-gcc.cmake Add the following two lines as below:](https://github.com/aitos-io/BoAT-X-Framework/issues/511) 
* [BoAT-X Framework for China Unicom YanFei-CUIot-MZ-6 Integration Guideline- inconsistent translation from Chinese version](https://github.com/aitos-io/BoAT-X-Framework/issues/512)
* [Suggest to add chainmaker to protocol list](https://github.com/aitos-io/BoAT-X-Framework/issues/513)
* [Suggest to publish the whitepaper on github](https://github.com/aitos-io/BoAT-X-Framework/issues/514)
* [make error](https://github.com/aitos-io/BoAT-X-Framework/issues/515)
* [make test error -- lcov: not found](https://github.com/aitos-io/BoAT-X-Framework/issues/516)
* [make test error -- cppcheck: not found](https://github.com/aitos-io/BoAT-X-Framework/issues/517)
* [Suggest to add whitepaper links on the main page](https://github.com/aitos-io/BoAT-X-Framework/issues/518)
* [标点符号不统一的问题](https://github.com/aitos-io/BoAT-X-Framework/issues/521)
* [BoAT-X Framework for XinYi-XY1100 Integration Guideline- missing space notation](https://github.com/aitos-io/BoAT-X-Framework/issues/522)
* [BoAT-X Framework for XinYi-XY1100 Integration Guideline- Inaccurate verb](https://github.com/aitos-io/BoAT-X-Framework/issues/524)
* [Failed to compile on L610 platform](https://github.com/aitos-io/BoAT-X-Framework/issues/525)
* [fabric discovery return error](https://github.com/aitos-io/BoAT-X-Framework/issues/527)


## Highlights of Ecosystem Update
* [Recently, 通商中国 Business China held the “Advanced Leaders Programme(ALP) Alumni Programme”, aitos.io CEO Leo Lin 林瑶 has been invited to be panel speaker themed “Tech Innovation and Critical Success Factors for Businesses under the #Endemic”. ](https://www.linkedin.com/posts/aitos-io_event-highlights-activity-6883295737493487616-GPy6)
* [Dec 10th, During a recent panel about Web 3.0 held by 通商中国 Business China, Our CTO  Gary Xu 许刚 discussed with Generation Z in Singapore and emphasized that the IoT+Blockchain will be key enablement for sustainable development of Web 3.0 ecology.](https://www.linkedin.com/feed/update/urn:li:activity:6881783082639331328)
* [On the 28th of December, aitos.io was admiringly honored as the best use-case award winner in 2021 for their BoAT IoT devices Trusted Data On-Chain Service.](https://www.linkedin.com/feed/update/urn:li:activity:6884453108483788800)
