# BoAT Project Status Update
Date: March 25th, 2022

## Update Summary
In the version of 2.1.10,  4 ethereum unit test cases and 6 fabric unit test cases are added, as well as 19 test scripts are adjusted to make the logic more rigorous.

## Releases
[BoAT-X-v2.1.10](https://github.com/aitos-io/BoAT-X-Framework/releases/tag/BoAT-X-v2.1.10) is released.

**Change Log**

- Add 4 ethereum unit test cases
- Add 6 fabric unit test cases
- Update and fix 19 test case code
- Update 2 makefile files base on the new added unit test modules
- Uniform some newly added code format
- Update 12 description in BoAT-X integration README files

## Major Commits
* [test(ethereum): Add InitEthWalletWithWrongGenMode](https://github.com/aitos-io/BoAT-X-Framework/commit/1b4a79d1184066cbbf7eb99f63d89710e1367e81)
* [test(ethereum): Add InitEthWalletWithWrongKeyFormat](https://github.com/aitos-io/BoAT-X-Framework/commit/e35b5354281ca8a2259dc5d3d60a383fbac35dd9)
* [test(ethereum): Add InitEthWalletWithWrongType](https://github.com/aitos-io/BoAT-X-Framework/commit/123680051b25c3e05e98a3920495091ff3cb5a52)
* [style: Uniform code format](https://github.com/aitos-io/BoAT-X-Framework/commit/77c3cda562000c55a3adc9c1af70c8f80e84023b)
* [docs: Added a tip for the Little-endian](https://github.com/aitos-io/BoAT-X-Framework/commit/d65ff64ef060c47a6f0678ba657ff57d7e7a176f)
* [test: Unnecessary input parameters are removed](https://github.com/aitos-io/BoAT-X-Framework/commit/de95677016b4dae03411aed36a59f637cc02eb42)
* [test: Fixed a problem that caused compilation to fail](https://github.com/aitos-io/BoAT-X-Framework/commit/5b7cff9e440162e22f64482b6b02f59909162951)
* [test: Fixed a problem that caused links to fail](https://github.com/aitos-io/BoAT-X-Framework/commit/fb74aac21c1c35836eb5a1c5bb27200cec5b032d)
* [test: Fix test case InitEthWalletGenerationKey](https://github.com/aitos-io/BoAT-X-Framework/commit/8ec00b31e0f7982772590a326b4aa3a8b3aea5d8)
* [test: Fix test case false expectations](https://github.com/aitos-io/BoAT-X-Framework/commit/0cf8681b7cc7dc8c971188af47f729d7ba137dc1)
* [test(ethereum): Fix error test case](https://github.com/aitos-io/BoAT-X-Framework/commit/0d0e6ff653ae4f6f59fb629cba94dbd3a52d6611)
* [test(ethereum): remove fuction string_eq_check](https://github.com/aitos-io/BoAT-X-Framework/commit/e5db009b59d5c7cbb845dc6f7096ce520cc19fce)
* [test: Fix the error caused by wild pointer and replace incorrect input](https://github.com/aitos-io/BoAT-X-Framework/commit/7e1bbd80dc8b637edb1856f5860b2d9b244d3da4)
* [feat: Added a function to check whether input is in hexadecimal notation](https://github.com/aitos-io/BoAT-X-Framework/commit/6afd7d1b0a95c844ec6c606958ea994911c5f6cb)
* [fix: Fixed the use of variable type long](https://github.com/aitos-io/BoAT-X-Framework/commit/c29f16774855a1520aba64e113ef36900b7df736)
* [fix: Fix errors in determining hexadecimal representation](https://github.com/aitos-io/BoAT-X-Framework/commit/c53b1d196cbd12754ddb3ed1553425ccfb2880ee)
* [fix: Added validity checks on input variables](https://github.com/aitos-io/BoAT-X-Framework/commit/debb389cab0884113a21074a3615f6fd94183724)
* [test: Fixed incorrect expected values in test cases](https://github.com/aitos-io/BoAT-X-Framework/commit/99f68852ce205386566713541fa66825d7b9d412)
* [fix: Added judgment on input address format](https://github.com/aitos-io/BoAT-X-Framework/commit/9209ae94a9d71f11a091955dbf25d34d4f03794f)
* [fix: Fix incorrect judgment of input address](https://github.com/aitos-io/BoAT-X-Framework/commit/f4e3fae84c726385c47a56a793ff3f9d17e0a8f2)
* [feat: Add a common private key type for Ethereum testing](https://github.com/aitos-io/BoAT-X-Framework/commit/ab19d96a4320d92baf5f8e8978e1cb9a841220d4)
* [test: Reduced the number of warnings](https://github.com/aitos-io/BoAT-X-Framework/commit/65d5408173fa721519f56c147f201bfdbd38281e)
* [test: Delete meaningless judgments](https://github.com/aitos-io/BoAT-X-Framework/commit/f10ee162b3be4e0408ceac9c81220f128b401d33)
* [feat: update makefile](https://github.com/aitos-io/BoAT-X-Framework/commit/fe698a91ab5dd3fc23b1c8637228691717ff7570)
* [feat(fabric test):](https://github.com/aitos-io/BoAT-X-Framework/commit/da222027cc735cc121c8b0237e148bf40728d163)
* [test: Modify some general definition locations](https://github.com/aitos-io/BoAT-X-Framework/commit/eecd831a8e6a1cf6b27d6e9791c696ecc35352d7)
* [test: Unneeded input is deleted](https://github.com/aitos-io/BoAT-X-Framework/commit/5f2f5de57f4bf669d300fde7ab2502df99bcd067)
* [test: Distinguish local variables from global variables](https://github.com/aitos-io/BoAT-X-Framework/commit/feefaa04d76459f8db660e7b5a40e7744bee3c5f)
* [test: Fixed an issue where the private key type could not be switched](https://github.com/aitos-io/BoAT-X-Framework/commit/e90f2eb5b74942ecd5ede6b2716756eb0de77cf3)
* [refactor: Lower the level of some printed LOG](https://github.com/aitos-io/BoAT-X-Framework/commit/5bfd8a96d7a70a506bb7a87dbc28133500dc56a9)
* [refactor: Added error logs](https://github.com/aitos-io/BoAT-X-Framework/commit/efe19ac1515bbdd7b3cfbd51eb554eec1dbfb128)
* [test: Add test 007Transfer_0001TransferSuccess](https://github.com/aitos-io/BoAT-X-Framework/commit/14ea7ae3547ee3d03dfce9b7d5949532f3559106)
* [Update README.md](https://github.com/aitos-io/BoAT-X-Framework/commit/15db016715d12954eee6e83e0180f7de5053e07e)

## Major Issues

**Open**

- [The description of \<BoAT Solidity Tool User Guide\> is incomplete](https://github.com/aitos-io/BoAT-X-Framework/issues/593)
- [Incorrect indent length](https://github.com/aitos-io/BoAT-X-Framework/issues/594)
- [An error occurs when test case SetNodeUrlFailureErrorNodeUrlFormat is run.](https://github.com/aitos-io/BoAT-X-Framework/issues/597)
- [The macro definition in the makefile is not in effect for ethereum test](https://github.com/aitos-io/BoAT-X-Framework/issues/604)

**Closed**

* [The ethereum test code failed to compile](https://github.com/aitos-io/BoAT-X-Framework/issues/595)
* [An error occurs when test case InitEthWalletGenerationKey is run.](https://github.com/aitos-io/BoAT-X-Framework/issues/598)
* [There are calls to wild Pointers in the test case](https://github.com/aitos-io/BoAT-X-Framework/issues/600)
* [Unnecessary functions exist in 02Parameters.c](https://github.com/aitos-io/BoAT-X-Framework/issues/599)
* [Function UtilityBuint8Buf2Uint64 may have problems when used on other platforms.](https://github.com/aitos-io/BoAT-X-Framework/issues/602)
* [Program handling error when gasprice value is an invalid hexadecimal number.](https://github.com/aitos-io/BoAT-X-Framework/issues/601)
* [An incorrect test case exists](https://github.com/aitos-io/BoAT-X-Framework/issues/603)


## Highlights of Ecosystem Update
* [Mar 14th, aitos.io is compiling an ongoing series of articles, appropriately titled “#BoAT Frequently Asked Questions (FAQs)” with the goal of introducing BoAT blockchain application framework to the community.](https://www.linkedin.com/feed/update/urn:li:activity:6906472150182588417)
* [March 17th, Karl J. Weaver，Global Biz Dev Director,aitos.io sat on a panel session of distinguished experts in Singapore for #IoTasia+ to discuss various views on conquering the interoperability challenge for IoT things. ](https://www.linkedin.com/feed/update/urn:li:activity:6909857016177987584)

