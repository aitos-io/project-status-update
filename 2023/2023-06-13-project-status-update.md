# BoAT Project Status Update
Date: June 13th, 2023

## Update Summary
Version 3.1.0 is the first version that BoAT adopts an new architecture called BIA (BoAT Infra Arch). 

BIA is a cross-platform application framework that provides a unified application abstraction interface for BoAT applications. It abstracts a lot of application APIs for various platforms. Starting with this release, the BoAT code repository is divided into BoAT-SupportLayger, BoAT-Engine, BoAT-ProjectTemplate repositories.

BoAT-SupportLayer is the core layer of the BIA architecture which provides a unified cross-platform application abstraction interface to the upper layer. The OSAL interfaces are defined and implemented to abstract the operating system APIs. The cellular chips/modules L610, ML307A, Unisoc 8850, FG150 and FM650 are adapted.

BoAT-Engine is a blockchain application component implemented in the Composable BoAT Core layer of the BIA architecture. In this release version, Ethereum, Hyperledger Fabric, Chainmaker, Venachain, PlatON, PlatONE and FISCO-BCOS blockchains are adapted and supported.

BoAT-ProjectTemplate is a universal development template for developing applications based on the BIA infrastructure.


## Releases

[BoAT-SupportLayer-v3.1.0](https://github.com/aitos-io/BoAT-SupportLayer/releases/tag/BoAT-SupportLayer-v3.1.0) is released.
[BoAT-Engine-v3.1.0](https://github.com/aitos-io/BoAT-Engine/releases/tag/BoAT-Engine-v3.1.0) is released.
[BoAT-ProjectTemplate-v3.1.0](https://github.com/aitos-io/BoAT-ProjectTemplate/releases/tag/BoAT-ProjectTemplate-v3.1.0) is released.

**Features**

+ BoAT-SupportLayer
  - Adjust code structure
  - Define and implement OSAL interfaces
  - Adapt cellular chips/modules L610, ML307A, Unisoc 8850, FG150 and FM650
  - Update integrated manuals and readme files

+ BoAT-Engine
  - Adjust code structure
  - Adapt Ethereum, Hyperledger Fabric, Chainmaker, Venachain, PlatON, PlatONE and FISCO-BCOS blockchains
  - Update documents and readme files

+ BoAT-ProjectTemplate
  - Initial the project
  - Add the scripts and readme files



## Highlights of Ecosystem Update
* [Leo Lin, founder and CEO of aitos.io, showcased the #BoAT Trusted Carbon Data Management System at the recent Punggol Digital District (PDD) connecting smartness 2023 in Singapore.](https://www.linkedin.com/feed/update/urn:li:activity:7070206126289547266)
* [Macao, China — #BEYOND Expo 2023 was hosted from May 10 to 12 at the Venetian Macao Convention. Leo Lin, founder and CEO of aitos.io, has been invited to speak at the SUSTAINABILITY SUMMIT](https://www.linkedin.com/feed/update/urn:li:activity:7061547411978010624)
* [Discover the must-watch video on how IoT, Blockchain, and aitos.io's BoAT Trusted Carbon Data Management Solution with Microsoft Azure Sphere create a dependable digital infrastructure for green carbon, promoting sustainable development](https://www.linkedin.com/feed/update/urn:li:activity:7056910366357803008)

