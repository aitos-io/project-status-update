# BoAT Project Status Update
Date: December 24th, 2021

## Update Summary
More test cases for chainmaker were added in this version. Some prepared configuration were added for test scripts. Some issues were resolved and contract interfaces generation method was optimized for chainmaker. Some readme files and documents were updated as well.

## Releases
[BoAT-X-v2.1.5](https://github.com/aitos-io/BoAT-X-Framework/releases/tag/BoAT-X-v2.1.5) is released.

**Change Log**

- Add more test cases for chainmaker part
- Add some prepared configuration for test scripts
- Fix some bugs and issues about chainmaker part
- Fix some bugs about genertating contract interface
- Update some descriptions and fix some errors about documents
- Update some README files (Chinese and English version)

## Major Commits
* [docs: update description about deploy contracts](https://github.com/aitos-io/BoAT-X-Framework/commit/2a302fa6a2ab982f638c52c41ac81dac7c348be3)
* [docs: fix a grammar error](https://github.com/aitos-io/BoAT-X-Framework/commit/7b3aabe749709004546b04366939fe0eb5b459d5)
* [docs: update description of c interface generation](https://github.com/aitos-io/BoAT-X-Framework/commit/43a46984a4e118990f07a0e6aa7986cdd3990782)
* [docs: update some description](https://github.com/aitos-io/BoAT-X-Framework/commit/454e5d2edcda59de911f1e08e29556dff1eca210)
* [[chainamker\][#436]rename 01CreateWallet.c to 01Wallet.c && add delete…](https://github.com/aitos-io/BoAT-X-Framework/commit/1c65de6b78ea32f7ce40bc3df2cf225a0e3b5d6e)
* [[chainmaker\][#436]rename 02InitSetTxParam.c to 02Paramters.c && modif…](https://github.com/aitos-io/BoAT-X-Framework/commit/3cca49b5834f4f3368d64ba73b4ac5886f807141) 
* [[chainmaker\][#436]add 03Contract.c and realize first contract test](https://github.com/aitos-io/BoAT-X-Framework/commit/4efdedc4436ad43db6807e8c0047995ec736d9fa)
* [[chainmaker\][#436]add tests test_03Contract_0002InvokeFailureMethodNull](https://github.com/aitos-io/BoAT-X-Framework/commit/5f9cabbbc3da71f911f582f933eba2d209256815)
* [docs: add blockchain official websites](https://github.com/aitos-io/BoAT-X-Framework/commit/749258039782dafb762ed94f4a4f51c6db53d574)
* [docs: remove blockchain official websites](https://github.com/aitos-io/BoAT-X-Framework/commit/51a7cf009e5584b1d6e85e4a23d84bf4226f647a)
* [[chainmaker\][#436]add tests test_03Contract_0003InvokeFailureContract…](https://github.com/aitos-io/BoAT-X-Framework/commit/87e91e9586f0146f8b714a49a8dc37a75413a2d1)
* [[chainmaker\][#436]add tests test_03Contract_0004InvokeFailureContract…](https://github.com/aitos-io/BoAT-X-Framework/commit/ea03ae955149d886467f381dd8c0ccceb6e49ef8)
* [[chainmaker\][#436]add tests test_03Contract_0005InvokeFailureReponseNull](https://github.com/aitos-io/BoAT-X-Framework/commit/754cee791d6d496b60dd0d40f09d85bab897f4f6)
* [[chainmaker\][#436]add tests test_03Contract_0006InvokeSucessSyncOn](https://github.com/aitos-io/BoAT-X-Framework/commit/2d2a6794e7b5d3e7d6045b9ef72e87b39dc65d46)
* [[chainmaker\][#436]add tests test_03Contract_0007InvokeSucessSyncOff](https://github.com/aitos-io/BoAT-X-Framework/commit/3a10755c85fc67f4d5323647d1f15f3c52a83f4d)
* [[chainmaker\][#436]add tests test_03Contract_0008QueryFailureTxNull](https://github.com/aitos-io/BoAT-X-Framework/commit/c72cd12163cde3d03e936f8175e66db10f023d47)
* [[chainmaker\][#436]add tests test_03Contract_0009QueryFailureMethodNull](https://github.com/aitos-io/BoAT-X-Framework/commit/90c0e49aad333f7efe302888a43e9194f85c78e6)
* [[chainmaker\][#436]add tests test_03Contract_00010QueryFailureContract…](https://github.com/aitos-io/BoAT-X-Framework/commit/33bb9e4aee59a17f48dd0e27d60eed370ef3c265)
* [[chainmaker\][#436]add tests test_03Contract_00011QueryFailureContract…](https://github.com/aitos-io/BoAT-X-Framework/commit/652eece9537c9bbeee310d2a2e49c316be9b1163)
* [[chainmaker\][#436]add tests test_03Contract_00012InvokeFailureRespons…](https://github.com/aitos-io/BoAT-X-Framework/commit/3d0e95fbdcaca3aa399d625597e15c0dae22840a)
* [[chainmaker\][#436]add tests test_03Contract_00013InvokeSucess](https://github.com/aitos-io/BoAT-X-Framework/commit/d75e560b6bffb7f65138033f0ff97eca9290fcec)
* [docs: Fix spelling errors](https://github.com/aitos-io/BoAT-X-Framework/commit/279c1a1f83520ba440fc02ab3e2ae133f172c82b)
* [docs: Remove extra Spaces](https://github.com/aitos-io/BoAT-X-Framework/commit/c676b2ed590cf983545191641ffa227017fb0a33)
* [docs: Fix spelling errors in function names](https://github.com/aitos-io/BoAT-X-Framework/commit/f95c42ced5753cb73c68632bb954264887e69c3f)
* [[chainmaker\][#449][#452]add contract_name and invoke_response check](https://github.com/aitos-io/BoAT-X-Framework/commit/7bafe462ee34f7d9e5e76455cd2ca267467b8fa3)
* [[chainmaker\][#450][#453]add query_reponse and contract_name check](https://github.com/aitos-io/BoAT-X-Framework/commit/a4eb91ce764a45b98a9e1499a420b0a385132d69)
* [[chainmaker\][#451]add invoke_response gas_used init](https://github.com/aitos-io/BoAT-X-Framework/commit/6a9eaadae42cb2632a6596792346a4b1e5111021)
* [[chainmaker\][#457]modify reponse as response](https://github.com/aitos-io/BoAT-X-Framework/commit/a684e023d2e1b3b308f7d60f394c026b28d5907d)
* [[chainmaker\][#436]add python build modify makefile](https://github.com/aitos-io/BoAT-X-Framework/commit/332c45af629426a64bd1ba66f76a21cf3eeceb15)
* [[chainmaker\][#436]node_url pass through makefile](https://github.com/aitos-io/BoAT-X-Framework/commit/c236eb3a4aae3c7691e4b9b3fef919ddb074b363)
* [[chainmaker\][#436]modify function name](https://github.com/aitos-io/BoAT-X-Framework/commit/1ec7a031a5dfa33927589e16c89797a072f06fee)
* [docs: updata README_en.md](https://github.com/aitos-io/BoAT-X-Framework/commit/d2c3cb78f1eb6f91c72537d72dc005512156b75c)
* [[chainmaker\][#460]remove BoatHlchainmakerNode struct and rename struct](https://github.com/aitos-io/BoAT-X-Framework/commit/310ea126710b5e6282c1d2ffa3a26ee5104946aa)
* [[chainmaker\][436][tests]modify wallte used struct name](https://github.com/aitos-io/BoAT-X-Framework/commit/1650d858d996a75c8162a5d209d5082484f3659b)
* [[chainmaker\][#436]add wallet check](https://github.com/aitos-io/BoAT-X-Framework/commit/22fe9e2a9f2bd7f35e10db4af4df344c57435e3d)
* [refactor: Modify comments to add description](https://github.com/aitos-io/BoAT-X-Framework/commit/3ffdfbc89208e0ad17084dbb2dfb128a66831628)
* [[chainmaker\][#436]add init param result content check](https://github.com/aitos-io/BoAT-X-Framework/commit/9b936311bf7023e331a1e8a035fe9f82bee8f14a)
* [[chainmaker\][#436]add param result check](https://github.com/aitos-io/BoAT-X-Framework/commit/c12316c3f66224651b22009b7fbe5450328e53a7)
* [[chainmaker\][#464]modify BOAT_CFLAGS](https://github.com/aitos-io/BoAT-X-Framework/commit/4afd08afd68e8288b6c151823ec0d988686934a1)
* [[chainmaker\][#436]modify chain_id and org_id name](https://github.com/aitos-io/BoAT-X-Framework/commit/cef11e95f7ca9e98c01114cbc47097bbc1b79148)
* [fix(Ethereum): Can generate contract interface file correctly](https://github.com/aitos-io/BoAT-X-Framework/commit/c1e951bd8408910163cbc04449fe14add5108efc)
* [fix(Fiscobcos): Can generate contract interface file correctly](https://github.com/aitos-io/BoAT-X-Framework/commit/d5cb3932e6353f53e7f9d00998878ec75edd2bc8)
* [fix(PlatON): Can generate contract interface file correctly](https://github.com/aitos-io/BoAT-X-Framework/commit/b262e8b089d0ea6b01b6c05a768972fcefe32390)
* [fix(PlatONE): Can generate contract interface file correctly](https://github.com/aitos-io/BoAT-X-Framework/commit/b78e6fd3f0978caf5c5d482627c6d3197ed2c72c)
* [docs: Add chainmaker to supported blockchain list](https://github.com/aitos-io/BoAT-X-Framework/commit/c891a06ceae448ce50f68b886cb1704b5f20fdef)
* [docs: add fabric official website.](https://github.com/aitos-io/BoAT-X-Framework/commit/04772956f4bb160a7c823053b9a9cf21f1e8dded)
* [[chainmaker\][#436]modify test code relize](https://github.com/aitos-io/BoAT-X-Framework/commit/6c5f51ade8b87d3add057d264bfef5053ddb49e7)
* [[chainmaker\][#436]add read cert and key interface](https://github.com/aitos-io/BoAT-X-Framework/commit/4f8bcf770ad02e7624d9cd0371855baa710343cf)
* [[chainmaker\][#436]modify url chain_id and org_id pass by python](https://github.com/aitos-io/BoAT-X-Framework/commit/aad48c33654971d8f655a588708f71b17c2c7fce)
* [[chainmaker\][#436]add cert and key file](https://github.com/aitos-io/BoAT-X-Framework/commit/2a51ff06ea0cc9a45fafaea39656421f141b0944)
* [[chainmaker\]add cert and kry contents](https://github.com/aitos-io/BoAT-X-Framework/commit/82f386801014a910f3bbcaa09f16dcfdde20f6d3)
* [[chainmaker\]modify key and cert path](https://github.com/aitos-io/BoAT-X-Framework/commit/51f88f6b7a6662aebfac924da25bcf652c44df11)
* [[chainmaker\][#472]add NULL para](https://github.com/aitos-io/BoAT-X-Framework/commit/37ef209451a448c4e946b1b7eefbf6a62ff7149c)
* [[chainmaker\][#472]paramters tests add NULL para](https://github.com/aitos-io/BoAT-X-Framework/commit/50f0bd949938caf85560c0caf2fdd74db0c23dc8)
* [[chainmaker\][#436]modify ccheck log file name](https://github.com/aitos-io/BoAT-X-Framework/commit/b38daa7e398c193157c6bb237db7cc19aa0a0452)
* [[chainmaker\][#436]add read file result judge](https://github.com/aitos-io/BoAT-X-Framework/commit/cd2c20b0f5308d8c6dbd92e19b8ff1600945ff78)
* [[chainmaker\][#436]add Input parameter NULL check](https://github.com/aitos-io/BoAT-X-Framework/commit/26be76c10c67785e02acdf9828a843423a6f4ffd)
* [[chainmaker\][#436]remove useless header file](https://github.com/aitos-io/BoAT-X-Framework/commit/5e677233062e9855c984af2d53493a6542e81df2)
* [Docs: fix chapter links](https://github.com/aitos-io/BoAT-X-Framework/commit/c59a19c1a970aafad8d7c4aad62935e7555a53a6)

## Major Issues

**Open**

- [Need instructions on how to call C interface documentation generated by python tools](https://github.com/aitos-io/BoAT-X-Framework/issues/462)
- [Web3intf.c lacks functions for parsing and processing error messages](https://github.com/aitos-io/BoAT-X-Framework/issues/465)
- [Lack of chainmaker operation manual](https://github.com/aitos-io/BoAT-X-Framework/issues/466)

**Closed**

* [Interpretation error of Ethereum contract transaction results](https://github.com/aitos-io/BoAT-X-Framework/issues/458)
* [chainmaker useless struct should remove](https://github.com/aitos-io/BoAT-X-Framework/issues/460)
* [404 for document getting from https://github.com/aitos-io/BoAT-X-Framework/tree/master/docs#readme](https://github.com/aitos-io/BoAT-X-Framework/issues/461)
* [When use Make Demo, the contract file may not be regenerated](https://github.com/aitos-io/BoAT-X-Framework/issues/463)
* [Chainmaker should be added in supported blockchain list.](https://github.com/aitos-io/BoAT-X-Framework/issues/467)
* [Suggest to add Hyperledger Fabric official website to the list.](https://github.com/aitos-io/BoAT-X-Framework/issues/468)


## Highlights of Ecosystem Update
* [On Dec 9th, aitos.io was awarded the AIoT New Dimension Award for Innovative Company of the Year at China AIoT Industrial Annual Ceremony and partnered in launching this year's AIoT Industry Landscape2022.](https://www.linkedin.com/feed/update/urn:li:activity:6877887470894219264)


* [Dec 15th, Aviel Cohen &John Pan &Alex Zhang &Mia Tang &Cavalier Liu were named #BoAT Github Monthly Star Q4 2021](https://www.linkedin.com/feed/update/urn:li:activity:6879262044097531904)
* [Recently, aitos.io was selected as Industrial Ecology usecase in the "China Blockchain Industry Ecological Map Report 2021"](https://mp.weixin.qq.com/s?__biz=MzI2MDE5NDYzNA==&mid=2247487446&idx=1&sn=bdfc5bedc1970c21936b062bf1db7ffe&chksm=ea6c27f3dd1baee505ca5a6ae3d96b696acbc644d39d65566201850059477a17ee54d0be247e&token=403491896&lang=zh_CN#rd)
