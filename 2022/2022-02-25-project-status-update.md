# BoAT Project Status Update
Date: February 25th, 2022

## Update Summary
BoAT-X is now re-organized to be 3 sub-components: BoAT-Engine, BoAT-Anchor and BoAT-Mast. The README is updated to follow this re-organization. Incorrect error handling for some fields in the transaction RPC response is fixed. One test case is newly added for Chainmaker. Both Chinese and English versions of user guide are updated for Chainmaker.

## Releases
[BoAT-X-v2.1.8](https://github.com/aitos-io/BoAT-X-Framework/releases/tag/BoAT-X-v2.1.8) is released.

**Change Log**

- Update BoAT-X README file
- Fix some issues of JSON fields
- Add and modify test cases for Chainmaker
- Fix some bugs for Chainmaker
- Fix some return errors
- Uniform some code format
- Update BoAT user guide and add descriptions of Chainmaker (Chinese and English versions)
- Add Chainmaker official websites
- Update some documents (Chinese and English versions)

## Major Commits
* [BoAT-X README update](https://github.com/aitos-io/BoAT-X-Framework/commit/32a5b572ba5923725c0390030d3fcaa511c1b781)
* [refactor(platone): Split the web3_parse_json_result function](https://github.com/aitos-io/BoAT-X-Framework/commit/37ca2ce231bf5c316b9fe1d7a329bbff5e647101)
* [refactor: Uniform code format](https://github.com/aitos-io/BoAT-X-Framework/commit/7a5ad66b9d731355abacfc8d28cf9fc732db2dd9)
* [fix: Modify the comparison of error types](https://github.com/aitos-io/BoAT-X-Framework/commit/5497433bfbd5229503ffc64c73b45232f05de997)
* [docs: format string type description.](https://github.com/aitos-io/BoAT-X-Framework/commit/49966f0609f574f969907ab100c1308f807f7905)
* [docs: add chainmaker official website](https://github.com/aitos-io/BoAT-X-Framework/commit/ed85342f1d38dd700d2ce39c29a63e8a490c094b)
* [docs: add chainmaker docs official website](https://github.com/aitos-io/BoAT-X-Framework/commit/e28bc249ff30c82e62c1c993bd8c8d58c1a4d35a)
* [docs: add Huawei BCS official website](https://github.com/aitos-io/BoAT-X-Framework/commit/d25b39330997046850d0d78a653e1a514a329216)
* [style: Supplementary notes](https://github.com/aitos-io/BoAT-X-Framework/commit/2a1de46995518a883c01e3ddefdbf7f2f24950ae)
* [fix: Fix incorrect return type and affected code](https://github.com/aitos-io/BoAT-X-Framework/commit/865a1cb0781e3861416a652ecd4b4406d8ce5ed0) 
* [fix: Modify the comparison of error types](https://github.com/aitos-io/BoAT-X-Framework/commit/c6199744f19134328383626e836a9cd3d187d1fd)
* [docs: Fix the wrong picture position](https://github.com/aitos-io/BoAT-X-Framework/commit/ddffc20597d56a48f05e81735444d439fb933c4a)
* [refactor(platon): Split the web3_parse_json_result function](https://github.com/aitos-io/BoAT-X-Framework/commit/ff565541c0db407b1d5aa6c877407e919fd06248)
* [\[chainmaker\][#575]add lost EXCEED_STR_MAX_LEN macro](https://github.com/aitos-io/BoAT-X-Framework/commit/b05af4cb7fc1dca3cedf5eb945bfdfce60a6fa37)
* [\[chainmaker\][#436]add wallet name test case](https://github.com/aitos-io/BoAT-X-Framework/commit/592a06bc26e8b7e76eaf2cf267e518f507ba3808)
* [docs: Fix the wrong format](https://github.com/aitos-io/BoAT-X-Framework/commit/ccb65df194056e049357485a9100f015cb8cfcb4)
* [Update hyperlink for Blockchain IoT Module Whitepaper and Blockcha…](https://github.com/aitos-io/BoAT-X-Framework/commit/bb3bb867e0250fd4524d8d771ee93d3318dc1e65)
* [Update Indirect Approach's diagram to conform to the text in README](https://github.com/aitos-io/BoAT-X-Framework/commit/f7f3ce75eb6bf7cd3d864034ea232450b043e530)
* [Correct spelling error](https://github.com/aitos-io/BoAT-X-Framework/commit/85e9b2cbdcf76cd7bd3dc481b076f4a47defc4a3)
* [docs: Eight examples have been added](https://github.com/aitos-io/BoAT-X-Framework/commit/9df67f2955ca49daccd9dc3bd2b9e065281b7afc)
* [refactor(fiscobcos): Split the web3_parse_json_result function](https://github.com/aitos-io/BoAT-X-Framework/commit/62bb0ccec1bdbc6864e158bb748bc81eb2d6d16f)
* [refactor: Delete the web3_parse_json_result function](https://github.com/aitos-io/BoAT-X-Framework/commit/ab896c263ae36bfe43df14954dc6d32c0505d435)
* [style: Uniform code format](https://github.com/aitos-io/BoAT-X-Framework/commit/6ae52b3aec9fb7a77c00a7ff3fcb969d144faa85)
* [fix: Transaction error during not mined](https://github.com/aitos-io/BoAT-X-Framework/commit/3aa060ac6b3b370bf1d0f70c8f4936ebf1668e28)
* [fix(eth): Failed to handle JSON null field](https://github.com/aitos-io/BoAT-X-Framework/commit/29cc80a18aad74ea49ab812bdd3b47e4ee99c80e)
* [fix(platon): Failed to handle JSON null field](https://github.com/aitos-io/BoAT-X-Framework/commit/6353c6a096a8a1668a7303eab42efb0920d22af9)
* [fix(fiscobcos): Failed to handle JSON null field](https://github.com/aitos-io/BoAT-X-Framework/commit/6cd8b6aa8b10e9f7fc7d46036ceb7ec4ee26a344)
* [fix: Fix errors in judging conditions](https://github.com/aitos-io/BoAT-X-Framework/commit/f874a87326d3ec0d475d3d540500ed7ecbe7f879)
* [fix: Fix error handling of return values](https://github.com/aitos-io/BoAT-X-Framework/commit/b36f994cec841f8b8a8a5a1ffe9b5fc3c5792428)
* [fix: Fix bad judgment statements](https://github.com/aitos-io/BoAT-X-Framework/commit/f7b1a9d2f72ef4acad5429825ffb628ecf990e27)
* [fix: Replace the position of functions](https://github.com/aitos-io/BoAT-X-Framework/commit/824f14fabfe89518ae0e2d3525fbc121c871fd04)
* [docs: change a sentence](https://github.com/aitos-io/BoAT-X-Framework/commit/4496a5f91f3d7e30c3e4ab951527dc5976191490)

## Major Issues

**Open**

- ["Supported Module List" issue](https://github.com/aitos-io/BoAT-X-Framework/issues/576)

**Closed**

* [Please refine your error codes definition](https://github.com/aitos-io/BoAT-X-Framework/issues/520)
* [Error types should not be compared](https://github.com/aitos-io/BoAT-X-Framework/issues/568)
* [Suggest to add chainmaker official websites.](https://github.com/aitos-io/BoAT-X-Framework/issues/571)
* [Suggest to add Huawei-BCS official websites.](https://github.com/aitos-io/BoAT-X-Framework/issues/572)
* [The program reported an error when RLP encoding the gasprice field](https://github.com/aitos-io/BoAT-X-Framework/issues/573)
* [Picture 4-1 typesetting problem](https://github.com/aitos-io/BoAT-X-Framework/issues/569)
* [Type description formatting](https://github.com/aitos-io/BoAT-X-Framework/issues/570)
* [BoAT wallet char info set maximum length 127 bytes](https://github.com/aitos-io/BoAT-X-Framework/issues/530)
* [huawei protocol lack proto file](https://github.com/aitos-io/BoAT-X-Framework/issues/387)
* [fabric has many useless protos](https://github.com/aitos-io/BoAT-X-Framework/issues/386)
* [BoatEthGetTransactionReceipt function to deal with problems of return values](https://github.com/aitos-io/BoAT-X-Framework/issues/561)
* [The web3_parse_json_result function does not meet the requirements](https://github.com/aitos-io/BoAT-X-Framework/issues/313)
* [platON rum demo error](https://github.com/aitos-io/BoAT-X-Framework/issues/309)
* [The compile failed because the header file was not referenced](https://github.com/aitos-io/BoAT-X-Framework/issues/579)
* [Judgment statement error](https://github.com/aitos-io/BoAT-X-Framework/issues/578)
* [BoAT-X Framework for Fibocom L610 Integration Guideline- Broken sentence](https://github.com/aitos-io/BoAT-X-Framework/issues/580)


## Highlights of Ecosystem Update
* [Feb 25th, aitos.io provides BLockchain IoT Module data on Chain solution for Wanxiang Smart building carbon footprint monitoring system. ](https://mp.weixin.qq.com/s?__biz=MzI2MDE5NDYzNA==&mid=2247487560&idx=1&sn=7cb49af0a9382be985a2c525defd2b76&chksm=ea6c386ddd1bb17b68a87d6ffa7aa6cb31b2ac7c4623b624db8c4a04958ddc164d9ff85f9e2c&token=320009599&lang=zh_CN#rd)
* [FAQ Top 100 valuable questions- Q1-What is BoAT? ](https://mp.weixin.qq.com/s/U4JPpL_ZV57lW9kqa1Ct9g)

