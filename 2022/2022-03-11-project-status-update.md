# BoAT Project Status Update
Date: March 11th, 2022

## Update Summary
Unit test modules for Ethereum and HyperLedger Fabric are added in Release 2.1.9. For XY1100, a wild pointer bug in the return value processing is fixed.

## Releases
[BoAT-X-v2.1.9](https://github.com/aitos-io/BoAT-X-Framework/releases/tag/BoAT-X-v2.1.9) is released.

**Change Log**

- Add ethereum unit test module
- Add fabric unit test module
- Modify the makefile files base on the new added unit test modules
- Change 3 variable definitions and 1 header file name of Chainmaker test cases
- Uniform some newly added codes format
- Update return variable definitions for XinYi XY1100 demos because of the wild pointers
- Update BoAT-X for Fibocom L610 Integration Guideline
- Update the document website link and link name for BoAT Blockchain IoT Module Product White Paper
- Update the document website link and link name for BoAT Blockchain IoT Module Technology and Application
- Add 12 types and descriptions in user guide of solidity contracts tools

## Major Commits
* [fix: Remove incorrect judgments of URL address](https://github.com/aitos-io/BoAT-X-Framework/commit/cc9856337763c33bef14636d7843df972ce6926d)
* [test: add initial ethereum test case](https://github.com/aitos-io/BoAT-X-Framework/commit/27311805a403669cc1abeabd9f60ea8c71c1e7c3)
* [test: add ethereum test case](https://github.com/aitos-io/BoAT-X-Framework/commit/500e24d35a4c94802ef96253d698a3f4a9018864)
* [docs: Fix some specifications and formatting](https://github.com/aitos-io/BoAT-X-Framework/commit/6f29d0b5b751c8487f9e588234ffe38299d6cfc7)
* [test: fix test_002InitWallet number](https://github.com/aitos-io/BoAT-X-Framework/commit/3bb4bce36b135a97988ca753c04920b931eab331)
* [docs: update link name](https://github.com/aitos-io/BoAT-X-Framework/commit/21b67d868bbc00343ead1b89326c31ce230043ae)
* [\[chainmaker\][#436]modify varible declare](https://github.com/aitos-io/BoAT-X-Framework/commit/1e0acd4590957672cac8cede3725dd61572c5555)
* [\[chainmaker\][#436]add macro define](https://github.com/aitos-io/BoAT-X-Framework/commit/bf2ad74dc2bb125938d7c8934ef6a1935ffbf2a5)
* [\[chainmaker\][#436]modify header file name](https://github.com/aitos-io/BoAT-X-Framework/commit/504f4bb96e999cf94807e4ff2839303c43f6dd6d)
* [style: Uniform code format](https://github.com/aitos-io/BoAT-X-Framework/commit/bc1e690d461d8844e9499edcd66cf93c7bc024b7)
* [fix: fix prikey file name](https://github.com/aitos-io/BoAT-X-Framework/commit/358d504499c3d2b66ee8038d6fea40eb3da0c06d)
* [feat: Added ethereum testing](https://github.com/aitos-io/BoAT-X-Framework/commit/459e5d84290ea0fe1d4e8bb508061e0a47526a30)
* [test: add parameters test file](https://github.com/aitos-io/BoAT-X-Framework/commit/79257c49313aca9097a5295b6a5db04d8a90ed8d)
* [test: change head file name](https://github.com/aitos-io/BoAT-X-Framework/commit/2b83478252f13d15caf030176bb3c4368e25726b)
* [fix: fix ethereum test case](https://github.com/aitos-io/BoAT-X-Framework/commit/4055b4cc20f922a2439e2e0ff6ca5279f0481312)
* [feat(add tests of fabric):](https://github.com/aitos-io/BoAT-X-Framework/commit/a2636eecfeedbdfbbc5121336d99ec116ca3f076)
* [fix(fabric header file):](https://github.com/aitos-io/BoAT-X-Framework/commit/eeda38f8adf7ec0b2699505949b08d2d12be314b)
* [test: add ethereum param_check function](https://github.com/aitos-io/BoAT-X-Framework/commit/879b7978a065b2781d649a465ea1333dc3d6ffdc)
* [Update boatplatform_internal.c](https://github.com/aitos-io/BoAT-X-Framework/commit/427f6163326dc4938afc2ccd0013b384cc497b6c)
* [Update boat_demo.c](https://github.com/aitos-io/BoAT-X-Framework/commit/968141b27681f7565cc7ba4d9bce9186aad4829b)
* [Update README_en.md](https://github.com/aitos-io/BoAT-X-Framework/commit/f8f465f9aa82638c71cd45dd643a307c2dd6d2e1)
* [fix: fix ethereum wallet test case](https://github.com/aitos-io/BoAT-X-Framework/commit/aa2ba10c014eef76ab0db33b60d4fd9261e3241d)
* [test: Add Ethereum InitEthWalletWithNullConfig](https://github.com/aitos-io/BoAT-X-Framework/commit/b6cb4cadb0a74279e04bae6ca06424a746417517)
* [test: Add Ethereum InitEthWalletWithSmallerSize](https://github.com/aitos-io/BoAT-X-Framework/commit/43c098bcf51fc0430ef63ed2dd7cb221a09a22ae)
* [test: Add Ethereum InitEthWalletWithBiggerSize](https://github.com/aitos-io/BoAT-X-Framework/commit/cbd7b0e471ddea4e87ab4ff1e5d8cc55fafcb08b)
* [test: InitEthWalletSuccess](https://github.com/aitos-io/BoAT-X-Framework/commit/998387ecab049e0cdfda93a1f26919b0961de6c2)
* [test: Add ethereum InitEthWalletGenerationKey](https://github.com/aitos-io/BoAT-X-Framework/commit/0c996aac8162224703a2276601a3ffa516563fc4)
* [docs: Twelve examples have been added](https://github.com/aitos-io/BoAT-X-Framework/commit/a799f03d448320e9d33f04fd09cdfc80e52c08a5)
* [feat(fabric tests):](https://github.com/aitos-io/BoAT-X-Framework/commit/86c3dfadb419f58a4b93fdf1d7f31a4243fb61e6)
* [Update boatplatform.c](https://github.com/aitos-io/BoAT-X-Framework/commit/0e7f430b518e7a14b789cb379e817a1397c90d7d)
* [Update boatplatform_internal.c](https://github.com/aitos-io/BoAT-X-Framework/commit/c55cf0f3b8a87696aa31f15008ae14827c5004cd)
* [perf(rlp compile):](https://github.com/aitos-io/BoAT-X-Framework/commit/ac995413f9bab6ded24005c0f6cbc78d2da02ffe)

## Major Issues

**Open**

- [Improper detection of URL while creating wallet](https://github.com/aitos-io/BoAT-X-Framework/issues/519)
- [add tests of fabric](https://github.com/aitos-io/BoAT-X-Framework/issues/584)
- [Ethereum test code compile error](https://github.com/aitos-io/BoAT-X-Framework/issues/587)
- [Get 2 Chainmaker test case errors](https://github.com/aitos-io/BoAT-X-Framework/issues/588)
- [rlp is not need compile when ETHEREUM is closed](https://github.com/aitos-io/BoAT-X-Framework/issues/592)

**Closed**

* [BoAT-X Framework for Fibocom L610 Integration Guideline-Inconsistency between Chinese and English](https://github.com/aitos-io/BoAT-X-Framework/issues/581)
* [Test case error](https://github.com/aitos-io/BoAT-X-Framework/issues/575)
* [Test case errors](https://github.com/aitos-io/BoAT-X-Framework/issues/574)
* [Compiling fabric tests returns error](https://github.com/aitos-io/BoAT-X-Framework/issues/585)
* [Wrong return value.](https://github.com/aitos-io/BoAT-X-Framework/issues/397) 
* [Assigns Pointers the memory requested by non-static functions in XY1100 demo](https://github.com/aitos-io/BoAT-X-Framework/issues/535)
* [Assigns Pointers the memory requested by non-static functions in MA510 demo](https://github.com/aitos-io/BoAT-X-Framework/issues/589)
* [A little problem in the English documentation of MA510](https://github.com/aitos-io/BoAT-X-Framework/issues/590)
* [Warning exists when cloning git](https://github.com/aitos-io/BoAT-X-Framework/issues/559)


## Highlights of Ecosystem Update
* [Mar 11th, aitos.io led and participated in the official release of the community standard for trusted blockchain access of IoT terminals.](https://mp.weixin.qq.com/s?__biz=MzU0NTk5NjE2OA==&mid=2247486362&idx=1&sn=0f6ece82664f3f33c1c57857ce5b0f26&chksm=fb65277dcc12ae6bc3dda51b97310f7aea1fde63eea6ec36a91c09949c71e3b8dc462b815b90&token=920161309&lang=zh_CN#rd)
* [Mar 2nd, aitos.io was invited to attend the launching ceremony of HyperLedger Manufacturing SIG preparatory group](https://mp.weixin.qq.com/s?__biz=MzU0NTk5NjE2OA==&mid=2247486285&idx=1&sn=c9e2c58fac97823eb1978f1a54270124&chksm=fb6527aacc12aebcffdf4b629f551fcbd63763095e1c1f0a4452c7fdc9a45137d41fe06fc11d&token=920161309&lang=zh_CN#rd)

