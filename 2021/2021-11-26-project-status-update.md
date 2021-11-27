# BoAT Project Status Update
Date: November 26th, 2021

## Update Summary
Chainmaker was newly supported in this version in addition to some bugfix and code reformatting. This version also updates User Guide documents and some readme files as well.

## Releases
[BoAT-X-v2.1.3](https://github.com/aitos-io/BoAT-X-Framework/releases/tag/BoAT-X-v2.1.3) is released.

**Change Log**

- Newly supported blockchain: Chainmaker (长安链)
- Optimize some code
- Fix some bugs and issues
- Uniforme some code format
- Update BoAT 2.x User Guide documents (Chinese and English version)
- Update some README files (Chinese and English version)

## Major Commits
* [perf(http2):](https://github.com/aitos-io/BoAT-X-Framework/commit/bffe773ee843a3e979afc7255e01ddbd7f5b412f)
* [[chainmaker\]remove unused header file: time.h](https://github.com/aitos-io/BoAT-X-Framework/commit/55067a835802d820999411350b8f7d55ce44ae4d)
* [[chainmaker\]use goto deal with error](https://github.com/aitos-io/BoAT-X-Framework/commit/8ccfcfd17a039f831f16c6c8d33074e0b5e89d0c)
* [[chainamker\]modify error deal logic](https://github.com/aitos-io/BoAT-X-Framework/commit/fc6b63b9ec30cbd68fff777b5cea4eff338c25f9)
* [refactor: Delete useless variables](https://github.com/aitos-io/BoAT-X-Framework/commit/0fc693d1bf37847d5ce0d001f3e137f4b98e257f)
* [refactor: Uniform code format](https://github.com/aitos-io/BoAT-X-Framework/commit/25e658eb2055eba5dd28c9bce5e9feb8cf293ae2)
* [[chainmaker\]modfiy pointer quote](https://github.com/aitos-io/BoAT-X-Framework/commit/f639a9003e163f371340a9a0df0aad0c455dd0a9)
* [[chainmaker\]modify free pointer sequence](https://github.com/aitos-io/BoAT-X-Framework/commit/4b68bf98954a716d7fc0e8db29a790eea1c6f5b4)
* [[chainmaker\]add BOAT_TLS_SUPPORT](https://github.com/aitos-io/BoAT-X-Framework/commit/df4a1de243a7db1ae93360ed04574106f6eda6db)
* [[chainmaker\]compatible with different chains](https://github.com/aitos-io/BoAT-X-Framework/commit/8622d780b0f48be201b69f011ec84b32102f00ba)
* [[chainmaker\]modify http2response content](https://github.com/aitos-io/BoAT-X-Framework/commit/16cf26680035db4ea2d8252e149d37e93fbba143)
* [perf(boatplatform_internal.c):](https://github.com/aitos-io/BoAT-X-Framework/commit/82d91db8a06f2762329482245fce1e1858e1c746)
* [perf(BoatHlchainType):](https://github.com/aitos-io/BoAT-X-Framework/commit/e7035d6b86b6e5534a66156d88a0e69527358993)
* [perf(chainType):](https://github.com/aitos-io/BoAT-X-Framework/commit/e88a61f9957c7edd9f557042068ad36ada671c81)
* [[chainmaker\]modify tls macro](https://github.com/aitos-io/BoAT-X-Framework/commit/ff22aaafe885b84826ba382bb13d10cb75bf0eb7)
* [[chainmaker\]add chainmaker macro switch](https://github.com/aitos-io/BoAT-X-Framework/commit/fb695d3f7d13d3dcffe256046cd2a62ac313e9ce)
* [[chainmaker\]add chainmaker macro replace fabric macro](https://github.com/aitos-io/BoAT-X-Framework/commit/a9d33a0b9c2ec3bdbac3e38b9651d2e7ad77e1fe)
* [[chainmaker\] remove useless pointer](https://github.com/aitos-io/BoAT-X-Framework/commit/4182ea071dad88b6703d8332c0112e8be5735832)
* [[chainmaker\]remove useless macro](https://github.com/aitos-io/BoAT-X-Framework/commit/891d4315c1493ed5358952744c053d1382142798)
* [[chainamker\]remove response struct](https://github.com/aitos-io/BoAT-X-Framework/commit/f878e153ae56df6f8365d53fae447c6d5c7f5594)
* [[chainmaker\]add result value process](https://github.com/aitos-io/BoAT-X-Framework/commit/d99faf5eb3aa3f514cc7442ee043c030914d2fd3)
* [fix: Assign an initial value to variables](https://github.com/aitos-io/BoAT-X-Framework/commit/ee9585702552d848c388b267cd8e51f9b9bf8a60)
* [refactor: Uniform code format](https://github.com/aitos-io/BoAT-X-Framework/commit/42d63731d0ac27ad38e12ba86075ee781d997e42)
* [fix: delect "chainType"](https://github.com/aitos-io/BoAT-X-Framework/commit/b273cc46f184dac865d071133fb7e49900b2ba80)
* [[chainmaker\]add function length param](https://github.com/aitos-io/BoAT-X-Framework/commit/e6d0ae8a357ec4a35f108954109c61d7753670f1)
* [[chainmaker\]modfiy setparam function](https://github.com/aitos-io/BoAT-X-Framework/commit/278f40559d86d19148933be1d731f7aee3325faf)
* [[chainmaker\]change the header file function declaration](https://github.com/aitos-io/BoAT-X-Framework/commit/baa47ae7175af2742ba0f20add1a0a2f04ffd44f)
* [fix(fiscobcos): Split a function into two](https://github.com/aitos-io/BoAT-X-Framework/commit/7ce953b450aba395a96365990de9180d665e0601)
* [fix(platone): Split a function into two](https://github.com/aitos-io/BoAT-X-Framework/commit/72e7a48c9d81dc736a55f406578bd77891f07438)
* [fix(platon): Split a function into two](https://github.com/aitos-io/BoAT-X-Framework/commit/1b5b1ac28c42896865571531c866c7f16d5c5481)
* [docs:updata BoAT_User_Guide_cn.md](https://github.com/aitos-io/BoAT-X-Framework/commit/8cb0409d6762dacbb1436e2ba45ab00da697a75b)
* [docs: updata BoAT_User_Guide_en.md](https://github.com/aitos-io/BoAT-X-Framework/commit/fbacd4c45305742f4645ae18270e8282070b0966)
* [docs: Fix the wrong path](https://github.com/aitos-io/BoAT-X-Framework/commit/964e2ed842348c910be425bea0e72c560aa66352)
* [fix(http2):](https://github.com/aitos-io/BoAT-X-Framework/commit/4adcfb16e21a5ad8282b1275ca10e9e1828f7741)
* [update api_fiscobcos.h](https://github.com/aitos-io/BoAT-X-Framework/commit/1f3932ca58d7895005e8dd63a285c70c6af74ce3)
* [update api_platon.h](https://github.com/aitos-io/BoAT-X-Framework/commit/ccf911f8c00829ee8660461e318b8bcc2281d444)
* [update api_platone.h](https://github.com/aitos-io/BoAT-X-Framework/commit/0a8cc3b26de9824d8b3ec9ef66a219b1b0c871a9)
* [[chainmaker\]demo compatible dev2.0](https://github.com/aitos-io/BoAT-X-Framework/commit/681c2ad0deec63ae8fab29ea45003aab7eb7879b)
* [[chainmaker\]docs compatible dev2.0](https://github.com/aitos-io/BoAT-X-Framework/commit/95196d4c46d846f205ec6a448a7af18b13f44fab)
* [[chainmaker\]include compatible dev2.0](https://github.com/aitos-io/BoAT-X-Framework/commit/40da14bcee10102a861e7df08375276512613ac7)
* [[chainmaker\]sdk compatible dev2.0](https://github.com/aitos-io/BoAT-X-Framework/commit/b936e8be24547ed580f804fea0e15a506b0660a9)
* [[chainmaker\]tests compatible dev2.0](https://github.com/aitos-io/BoAT-X-Framework/commit/7c212a4bbc4fe9cf198ba19d48f3a1d067ae5ba1)
* [[chainamker\]tools compatible dev2.0](https://github.com/aitos-io/BoAT-X-Framework/commit/fe2d5c56d0b067e851ead036920dc68618f050a7)
* [[chainmaker\]vendor compatible dev2.0](https://github.com/aitos-io/BoAT-X-Framework/commit/b161447e9953940ee64d11a85442e8c6eeb7c19b)
* [[chainmaker\]chainmaker compatible dev2.0](https://github.com/aitos-io/BoAT-X-Framework/commit/601e504f375b645133d3fb0eff4fe1323625e7ec)
* [[chainmaker\]update dev 2.0](https://github.com/aitos-io/BoAT-X-Framework/commit/575ac25de1dbdaf10cb18c5e3243b35499eb068b)
* [[chainmaker\]update MTK-MT3620](https://github.com/aitos-io/BoAT-X-Framework/commit/74db444030e303c2b9e37b59fe381b663217d5db)
* [[chainmaker\]reslove conflict](https://github.com/aitos-io/BoAT-X-Framework/commit/9dd02857c386f47e4a903630c218d9e4ec1eaede)
* [[chainmaker\]add chaninamker macro](https://github.com/aitos-io/BoAT-X-Framework/commit/43d7c0f5345de4cf8a0b10981f62219b78420d44)
* [fix(fabric demo):](https://github.com/aitos-io/BoAT-X-Framework/commit/23e270dbb62dcf593b2c974acafcdec8d9fb54f4)
* [fix:](https://github.com/aitos-io/BoAT-X-Framework/commit/9c153281435deb7de0f9922bfee24daf937dc033)
* [fix(chainmaker): Duplicate variable names have been renamed](https://github.com/aitos-io/BoAT-X-Framework/commit/07059d3bbad3c70d775a7520af35a3601ab8b58d)
* [fix(chainmaker):fix the issue](https://github.com/aitos-io/BoAT-X-Framework/commit/11f2e644b0cd6db555076420961fcbfb360ef98f) [#416](https://github.com/aitos-io/BoAT-X-Framework/issues/416)
* [common tx_header_descriptor](https://github.com/aitos-io/BoAT-X-Framework/commit/6cc3f31079e32479b85c9a2d4a70cc69f3494ff1)
* [fix(chainmaker):fix the issue](https://github.com/aitos-io/BoAT-X-Framework/commit/5a38a0092e72ed4a9ff0573aa3f68e0033372f26) [#418](https://github.com/aitos-io/BoAT-X-Framework/issues/418)
* [fix(chainmaker):fix the issue](https://github.com/aitos-io/BoAT-X-Framework/commit/09b2df31a28c11d5811c78504bc4f702def7029f) [#419](https://github.com/aitos-io/BoAT-X-Framework/issues/419)
* [fix(chainmaker):fix the issue](https://github.com/aitos-io/BoAT-X-Framework/commit/0ad40d04e0598d79877bd6576f7deade69b18ad9) [#420](https://github.com/aitos-io/BoAT-X-Framework/issues/420)
* [fix(chainmaker):fix the issue](https://github.com/aitos-io/BoAT-X-Framework/commit/ac24857a326748daf85e55541bebba1fd34ff06d) [#422](https://github.com/aitos-io/BoAT-X-Framework/issues/422)
* [fix(MT3620):](https://github.com/aitos-io/BoAT-X-Framework/commit/2b977b8413dba613cd8065772126c10acf39f350)
* [revert:](https://github.com/aitos-io/BoAT-X-Framework/commit/b99a1def7febadecd2eec8b12e9fc6eb5d3fd5e3)
* [revert(MT3620):](https://github.com/aitos-io/BoAT-X-Framework/commit/ed7a5a99fa8fceaf66fa99f2cd560b59fd2630d8)
* [docs(MT3620):](https://github.com/aitos-io/BoAT-X-Framework/commit/e33671bfbeabf73230f51e6551cc11f1af255034)
* [perf(MT3620):](https://github.com/aitos-io/BoAT-X-Framework/commit/53ca536b6520ba7ab4587f3f1a9cba33367fb133)
* [[chainmaker\][#415]slove compile warnings](https://github.com/aitos-io/BoAT-X-Framework/commit/1e2e772d374dae8497ed0b38d45419a4564bd1f2)
* [[chainmaker\][#426]solve close can not find http2 path](https://github.com/aitos-io/BoAT-X-Framework/commit/add5839d1c527180bb7235c933e4f29ae84f8ff3)
* [[chainmaker\][#427]before memcpy check length](https://github.com/aitos-io/BoAT-X-Framework/commit/9bfb8c7d37ebbfd5d69523cfe471494ac99e2ead)
* [[chainmaker\][#428]check parammters Null pointer](https://github.com/aitos-io/BoAT-X-Framework/commit/4434b001b5ab4cb890a47777d208d103026b6dc7)
* [[chainmaker\][#429]check length before memcpy](https://github.com/aitos-io/BoAT-X-Framework/commit/c9e6ac50b5f9d1d4fb507597e59bbb383a873c64)
* [[chainmaker\][#430]check whether the variable parameter is empty](https://github.com/aitos-io/BoAT-X-Framework/commit/d9ffafc1c1b3aca066fc73075dd16c7ce0adae15)
* [[chainmaker\][#431]check http2submitrequest result and then parsing st…](https://github.com/aitos-io/BoAT-X-Framework/commit/a349fc8ff510cf15e6f6a64c55b2ebb1501df92a)

## Major Issues

**Open**

- [fabric has many useless protos](https://github.com/aitos-io/BoAT-X-Framework/issues/386)
- [huawei protocol lack proto file](https://github.com/aitos-io/BoAT-X-Framework/issues/387)
- [Some code can be refactored](https://github.com/aitos-io/BoAT-X-Framework/issues/388)
- [BoatWalletCreate can not return specific error code](https://github.com/aitos-io/BoAT-X-Framework/issues/390)
- [中文文档中的图最好换成中文版](https://github.com/aitos-io/BoAT-X-Framework/issues/392)
- [The Pain point](https://github.com/aitos-io/BoAT-X-Framework/issues/394)
- [图 2-2 BoAT IoT Framework SDK架构](https://github.com/aitos-io/BoAT-X-Framework/issues/395)
- [Wrong return value.](https://github.com/aitos-io/BoAT-X-Framework/issues/397)
- [boatiosdk-M5311-dev开发分支中的中文帮助文档链接返回404](https://github.com/aitos-io/BoAT-X-Framework/issues/400)
- [We got "404" when we click the hyperlink "English"](https://github.com/aitos-io/BoAT-X-Framework/issues/401)
- [chainmaker if contract non-existent repsonse can not deal with](https://github.com/aitos-io/BoAT-X-Framework/issues/412)
- [chainmaker need set url interface](https://github.com/aitos-io/BoAT-X-Framework/issues/413)
- [chainmaker need set chainid](https://github.com/aitos-io/BoAT-X-Framework/issues/414)
- [BoAT System Requirements/ grammar mistake](https://github.com/aitos-io/BoAT-X-Framework/issues/421)
- [BoAT-X Framework for XinYi-XY1100 Integration Guideline/File Modification- Inaccurate expression](https://github.com/aitos-io/BoAT-X-Framework/issues/423)
- [BoAT-X Framework for XinYi-XY1100 Integration Guideline/Compile BoAT-X Framework Static library-inaccurate descripton](https://github.com/aitos-io/BoAT-X-Framework/issues/424)
- [BoAT-X Framework for Fibocom L610 Integration Guideline/File Modification-Inconsistency between Chinese and English version](https://github.com/aitos-io/BoAT-X-Framework/issues/425)
- [chainmaker variable parameter check](https://github.com/aitos-io/BoAT-X-Framework/issues/430)
- [need to Judge the return value before parsing struct](https://github.com/aitos-io/BoAT-X-Framework/issues/431)

**Closed**

* [The format of arguments in functions generated by Python scripts needs to be changed](https://github.com/aitos-io/BoAT-X-Framework/issues/381)
* [http2intf optimization suggestion](https://github.com/aitos-io/BoAT-X-Framework/issues/383)
* [BoatWalletCreate 函数参数不需要传递](https://github.com/aitos-io/BoAT-X-Framework/issues/385)
* [warning during make rulecheck](https://github.com/aitos-io/BoAT-X-Framework/issues/389)
* [optimization suggestions of boatplatform_internal.c](https://github.com/aitos-io/BoAT-X-Framework/issues/391)
* [chainType in http2IntfContext not used](https://github.com/aitos-io/BoAT-X-Framework/issues/393)
* [函数参数指针的检查](https://github.com/aitos-io/BoAT-X-Framework/issues/396)
* [Some variables are not initialized.](https://github.com/aitos-io/BoAT-X-Framework/issues/398)
* [BoAT-X-Framework/BoAT User Guide/PlatONE demo contract and ABI JSON files are not match the table.](https://github.com/aitos-io/BoAT-X-Framework/issues/402)
* [BoAT-X-Framework/BoAT User Guide/Add Fabric and HW_BCS C code for demo contracts into the table](https://github.com/aitos-io/BoAT-X-Framework/issues/403)
* [Failed to compile the BoAT library](https://github.com/aitos-io/BoAT-X-Framework/issues/404)
* [Fail to compile platone](https://github.com/aitos-io/BoAT-X-Framework/issues/405)
* [Fail to build fiscobcos](https://github.com/aitos-io/BoAT-X-Framework/issues/406)
* [Failed to compile CHAINMAKER](https://github.com/aitos-io/BoAT-X-Framework/issues/411)
* [chainmaker has compile warnings](https://github.com/aitos-io/BoAT-X-Framework/issues/415)
* [clang: error: linker command failed with exit code](https://github.com/aitos-io/BoAT-X-Framework/issues/416)
* [compile error](https://github.com/aitos-io/BoAT-X-Framework/issues/419)
* [Compilation failed when using Makedemo](https://github.com/aitos-io/BoAT-X-Framework/issues/422)
* [chainmaker close tls can not find http2 path](https://github.com/aitos-io/BoAT-X-Framework/issues/426)
* [chainmaker before memcpy should check lenth](https://github.com/aitos-io/BoAT-X-Framework/issues/427)
* [chainmaker BoatHlChainmakerTxInit Null pointer check](https://github.com/aitos-io/BoAT-X-Framework/issues/428)
* [chainmaker BoatHlChainmakerTxInit memcpy need check length](https://github.com/aitos-io/BoAT-X-Framework/issues/429)


## Highlights of Ecosystem Update
* [Nov 19th, Leo Lin, CEO of autos.io, visited Singapore's Punggol Digital District (PDD) Smart City in person.aitos.io and Wanxiang Blockchain are jointly developing of their “PlatONE+BoAT IoT Data Empowerment Platform” at Singapore’s Punggol Digital District. ](https://www.linkedin.com/feed/update/urn:li:activity:6827965464845541376)
* [Nov 19th, aitos.io was invited to attend  #SEQUOIA2021 DIGITAL TECH offline activities. aitos.io BoAT came to the old Shanghai shipyard MIFA 1862 Art Center for upgrading.](https://www.yun-live.com/h5/sequoiacaptech/2410)


  