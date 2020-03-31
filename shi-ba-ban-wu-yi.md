---
description: 本页为读者提供以太坊应用程序开发的工具、组件、模式以及平台列表。
---

# 链就码林高手

本列表译自[ConsenSys](https://github.com/ConsenSys/ethereum-developer-tools-list#ethereum-developer-tools-list)，促进开发者之间工具、开发模式和组件的共享十分有必要。

感谢ConsenSys的整理！

## 极速上手工具

* [Solidity](https://solidity.readthedocs.io/en/latest/)  _主流智能合约编程语言_
* [Truffle](https://trufflesuite.com/) _主流智能合约开发、测试和部署框架。通过npm安装cli，然后就可以开始编写您的第一个智能合约_
* [Metamask](https://metamask.io/) _可与Dapps进行交互的Chrome插件钱包_
* [Truffle boxes](https://trufflesuite.com/boxes) _以太坊生态系统的打包组件_
* [OpenZeppelin Starter Kits](https://openzeppelin.com/starter-kits/) _多合一入门工具箱，供开发人员快速上手基于智能合约的应用程序。包括Truffle、OpenZeppelin SDK、OpenZeppelin/contracts-ethereum-package EVM软件包、react-app和rimble_
* [EthHub.io](https://docs.ethhub.io/) _针对以太坊历史、治理、发展计划和开发资源的全面介绍_
* [Cobra](https://github.com/cobraframework/cobra) _快速，灵活、简单的以太坊智能合约开发环境框架，在以太坊虚拟机 \(EVM\) 上进行测试和部署_
* [Fortmatic](https://fortmatic.com/) _易于使用的SDK，无需扩展或下载即可构建web3 DApp_
* [Portis](https://portis.io/) _配备SDK的非托管钱包，可轻松与DApp进行交互而无需其他安装_
* [Kauri.io](https://kauri.io/) _基于社区的Web3和新兴技术知识平台_
* [dfuse](https://dfuse.io/) _易用的区块链API，构建一流的DApp_

## 开发工具

### 智能合约开发

#### 智能合约语言

* [Solidity](https://solidity.readthedocs.io/en/latest/) - 以太坊智能合约编程语言
* [Vyper](https://vyper.readthedocs.io/en/latest/) - 实验性python式编程语言
* [Flint](https://github.com/flintlang/flint) - 具有安全功能的新智能合约编程语言，包含资产类型、状态转换和安全整数，仍处于开发阶段

#### 框架

* [Truffle](https://trufflesuite.com/) - 主流智能合约开发、测试和部署框架。Truffle套件包括Truffle、[Ganache](https://github.com/trufflesuite/ganache), and [Drizzle](https://github.com/truffle-box/drizzle-box). （[教程](https://media.consensys.net/truffle-deep-dive-what-you-need-to-know-when-developing-on-ethereum-e548d4df6e9)）
* [Embark](https://github.com/embark-framework/embark) - DApp开发框架
* [Waffle](https://getwaffle.io/) - 小型、灵活、快速的高级智能合约开发和测试框架（基于ethers.js）
* [Dapp](https://dapp.tools/dapp/) - DApp开发框架
* [Etherlime](https://github.com/LimeChain/etherlime) - 基于ethers.js的DApp部署框架
* [Parasol](https://github.com/Lamarkaz/parasol) - 具备测试、Infura部署、自动合约文档等功能的智能合约开发环境
* [0xcert](https://github.com/0xcert/framework/) - 编写DApp的JavaScript框架
* [OpenZeppelin SDK](https://openzeppelin.com/sdk/) - 一套协助开发、编译、升级、部署智能合约并与之交互的工具
* [sbt-ethereum](https://sbt-ethereum.io/) - 制表符完整的、基于文本的控制台，用于智能合约交互和开发，包括钱包和ABI管理、ENS支持以及高级Scala集成
* [Brownie](https://github.com/iamdefinitelyahuman/brownie) - Python框架，用于以太坊智能合约部署、测试、交互
* [Cobra](https://github.com/cobraframework/cobra) - 灵活简易的以太坊智能合约开发环境框架，在EVM上进行测试和部署

#### IDEs

* [Remix](https://remix.ethereum.org/) - 具有内置静态分析功能的Web IDE，可测试区块链虚拟机
* [Ethereum Studio](https://studio.ethereum.org/) - 网页IDE。内置浏览器区块链虚拟机，Metamask集成（一键测试网/主网部署），包括事务记录器和实时编码WebApp等众多其他功能。
* [Atom](https://atom.io/) - 原子编辑器
* [Vim solidity](https://github.com/tomlion/vim-solidity) - Solidity Vim语法文件
* [Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=JuanBlanco.solidity) - Visual Studio Code扩展，增加对Solidity的支持
* [Ethcode](https://marketplace.visualstudio.com/items?itemName=quantanetwork.ethcode) - Visual Studio Code扩展，用于编译、执行和调试Solidity＆Vyper程序
* [Intellij Solidity Plugin](https://github.com/intellij-solidity/intellij-solidity) - JetBrains IntelliJ Idea IDE（免费/商业）的开源插件，具有语法高亮、格式设置、代码完成等功能
* [YAKINDU Solidity Tools](https://github.com/Yakindu/solidity-ide) - 基于Eclipse的IDE。具有代码完成和帮助、代码导航、语法着色、内置编译器、快速修复和模板功能。
* [Eth Fiddle](https://ethfiddle.com/) - [Loom Network](https://loomx.io/)开发的IDE，可编写、编译和调试智能合约。易于共享和查找代码片段。

### 其他工具

* [Atra Blockchain Services](https://console.atra.io/) - Atra提供Web服务在以太坊区块链上构建、部署和维护去中心化应用程序。
* [Buidler](https://buidler.dev/) - 可扩展的开发人员工具，通过整合工具提高智能合约开发者效率
* [Azure Blockchain Dev Kit for Ethereum for VSCode](https://marketplace.visualstudio.com/items?itemName=AzBlockchain.azure-blockchain) - VSCode扩展允许创建智能合约并将其部署到Visual Studio Code中

### 网络测试工具

* [ethnode](https://github.com/vrde/ethnode) - 运行以太坊节点（Geth或Parity）进行开发和测试
* [Ganache](https://github.com/trufflesuite/ganache) - 具有可视化UI和日志的以太坊区块链的测试类应用程序
* [Kaleido](https://kaleido.io/) - 使用Kaleido扩展联盟区块链网络，非常适合PoC和测试
* [Besu Private Network](https://besu.hyperledger.org/en/stable/Tutorials/Quickstarts/Azure-Private-Network-Quickstart/) - 在Docker容器中运行Besu节点的专用网络
* [Orion](https://github.com/PegaSysEng/orion) - PegaSys开发的执行私有交易的组件
* [Artemis](https://github.com/PegaSysEng/artemis) - PegaSys的以太坊2.0信标链Java实现
* [Cliquebait](https://github.com/f-o-a-m/cliquebait) - 使用与真实区块链网络极为相似的Docker实例简化智能合约应用程序的集成和验收测试
* [Local Raiden](https://github.com/ConsenSys/Local-Raiden) - 在Docker容器中运行本地Raiden网络以进行演示和测试
* [Private networks deployment scripts](https://github.com/ConsenSys/private-networks-deployment-scripts) - 私有PoA网络的现成部署脚本
* [Local Ethereum Network](https://github.com/ConsenSys/local_ethereum_network) - 私有PoW网络的现成部署脚本
* [Ethereum on Azure](https://docs.microsoft.com/en-us/azure/blockchain/templates/ethereum-poa-deployment) - 联盟以太坊PoA网络的部署和治理
* [Ethereum on Google Cloud](https://console.cloud.google.com/marketplace/details/click-to-deploy-images/ethereum?filter=category:developer-tools) - 基于PoW构建以太坊网络
* [Infura](https://infura.io/) - 访问以太坊网络的API（主网/Ropsten/Rinkeby/Goerli/Kovan）
* [CloudFlare Distributed Web Gateway](https://cloudflare.com/distributed-web-gateway/) - 通过Cloudflare对以太坊网络进行访问，而无需运行的节点
* [Chainstack](https://chainstack.com/) - 共享和专用的以太坊节点即服务（主网/Ropsten）

#### Ether水龙头 \(Faucets\)

* [Rinkeby faucet](https://faucet.rinkeby.io/)
* [Kovan faucet](https://github.com/kovan-testnet/faucet)
* [Ropsten faucet](https://faucet.metamask.io/)
* [Goerli faucet](https://goerli-faucet.slock.it/)
* [Universal faucet](https://faucets.blockxlabs.com/)
* [Nethereum.Faucet](https://github.com/Nethereum/Nethereum.Faucet) - A C\#/.NET faucet

### 以太坊通信

#### 前端以太坊APIs

* [Web3.js](https://github.com/ethereum/web3.js/) - Javascript Web3
  * [Eth.js](https://github.com/ethjs) - Javascript Web3替代
  * [Ethers.js](https://github.com/ethers-io/ethers.js/) - Javascript Web3替代，实用程序和钱包功能
  * [light.js](https://github.com/paritytech/js-libs/tree/master/packages/light.js) - 轻客户端优化的高级反应式JS库
  * [Web3Wrapper](https://github.com/0xProject/0x-monorepo/tree/development/packages/web3-wrapper) - TypeScript语言Web3替代
  * [Ethereumjs](https://github.com/ethereumjs/) - 以太坊实用程序功能集合，例如 [ethereumjs-util](https://github.com/ethereumjs/ethereumjs-util) 和 [ethereumjs-tx](https://github.com/ethereumjs/ethereumjs-tx)
  * [flex-contract](https://github.com/merklejerk/flex-contract)及[flex-ether](https://github.com/merklejerk/flex-ether) - 现代化的零配置高级库，用于与智能合约进行交互并进行交易
  * [ez-ens](https://github.com/merklejerk/ez-ens) - 简单的零配置以太坊域名服务（ENS）地址解析器
  * [web3x](https://github.com/xf00f/web3x) - web3.js的TypeScript端口。结构小巧和全类型安全性，包括合约交互安全性
* [Nethereum](https://github.com/Nethereum/) - 跨平台以太坊开发框架
* [dfuse](https://github.com/dfuse-io/client-js) - 以使用[dfuse Ethereum API](https://dfuse.io/)的TypeScript库
* [Drizzle](https://github.com/truffle-box/drizzle-box) - 将前端连接到区块链的Redux库
* [Tasit SDK](https://github.com/tasitlabs/tasitsdk) - JavaScript SDK，使用React Native制作本地以太坊移动DApp
* [Subproviders](https://0x.org/docs/tools/subproviders) - 几个有用的子提供程序，可与Web3-provider-engine结合使用（包括一个LedgerSubprovider，用于为DApp添加Ledger硬件钱包支持）
* [web3-react](https://github.com/NoahZinsmeister/web3-react) - 用于构建单页以太坊DApp的React框架
* [ethvtx](https://github.com/ticket721/ethvtx) - 支持以太坊且框架不可知的Redux存储配置（[文档](https://ticket721.github.io/ethvtx/)）
* 严格类型 - Javascript替代
  * [elm-ethereum](https://github.com/cmditch/elm-ethereum)
  * [purescript-web3](https://github.com/f-o-a-m/purescript-web3)
* [ChainAbstractionLayer](https://github.com/liquality/chainabstractionlayer) - 通过单个界面与不同的区块链（包括以太坊）进行通信。
* [Delphereum](https://github.com/svanas/delphereum) - 以太坊区块链的Delphi接口，可以开发适用于Windows/macOS/iOS和Android的本地DApp

#### Backend Ethereum APIs

* [Web3.py](https://github.com/ethereum/web3.py) - Python Web3
* [Web3.php](https://github.com/sc0Vu/web3.php) - PHP Web3
* [Ethereum-php](https://github.com/digitaldonkey/ethereum-php) - PHP Web3
* [Web3j](https://github.com/web3j/web3j) - Java Web3
* [Nethereum](https://nethereum.com/) - .Net Web3
* [Ethereum.rb](https://github.com/EthWorks/ethereum.rb) - Ruby Web3
* [Web3.hs](https://hackage.haskell.org/package/web3) - Haskell Web3
* [KEthereum](https://github.com/komputing/KEthereum) - Kotlin Web3
* [Eventeum](https://github.com/ConsenSys/eventeum) -Kauri用Java编写的以太坊智能合约事件和后端微服务之间的桥接
* [Ethereumex](https://github.com/mana-ethereum/ethereumex) - 以太坊区块链的Elixir JSON-RPC客户端
* [Ethereum-jsonrpc-gateway](https://github.com/HydroProtocol/ethereum-jsonrpc-gateway) - 允许运行多个以太坊节点以实现冗余和负载平衡的网管。可作为Infura替代（或在其之上）运行，以Go语言编写。
* [EthContract](https://github.com/AgileAlpha/eth_contract) - 在Elixir中查询ETH智能合约的辅助方法
* [Ethereum Contract Service](https://github.com/mesg-foundation/service-ethereum-contract) - MESG服务，可根据其地址和ABI与任何以太坊合约进行交互
* [Ethereum Service](https://github.com/mesg-foundation/service-ethereum) - MESG服务，用于与以太坊中的事件进行交互
* [Marmo](https://marmo.io/) - Python，JS和Java SDK，用于简化与以太坊的交互，将交易成本转移给中继器

#### Bootstrap/out of box tools

* [Truffle boxes](https://trufflesuite.com/boxes) - 以太坊生态系统的打包组件
* [Besu Private Network](https://besu.hyperledger.org/en/stable/Tutorials/Quickstarts/Azure-Private-Network-Quickstart/) - 在Docker容器中运行Besu节点的专用网络
* [Testchains](https://github.com/Nethereum/TestChains) - 预先配置的.NET开发链以实现快速响应（PoA）
* [Local Raiden](https://github.com/ConsenSys/Local-Raiden) - 在Docker容器中运行本地Raiden网络以进行演示和测试
* [Private networks deployment scripts](https://github.com/ConsenSys/private-networks-deployment-scripts) - 专用PoA网络的现成部署脚本
* [Parity Demo-PoA Tutorial](https://wiki.parity.io/Demo-PoA-tutorial.html) -使用两个节点搭建PoA测试链的教程
* [Local Ethereum Network](https://github.com/ConsenSys/local_ethereum_network) - 专用PoW网络的现成部署脚本
* [Kaleido](https://kaleido.io/) - 使用Kaleido扩展联盟区块链网络，非常适合PoC和测试
* [Cheshire](https://github.com/endless-nameless-inc/cheshire) - CryptoKitties API和智能合约的本地沙盒实现，可以作为Truffle Box使用
* [aragonCLI](https://github.com/aragon/aragon-cli) - aragonCLI用于创建和开发Aragon应用程序和组织。
* [ColonyJS](https://github.com/JoinColony/colonyJS) - 用于与Colony Network智能合约交互API的JavaScript客户端
* [ArcJS](https://github.com/daostack/arc.js) - 便于javascript应用程序访问DAOstack Arc以太坊智能合约的库
* [Arkane Connect](https://docs.arkane.network/pages/connect-js.html) - 用于与Arkane Network进行交互的API的JavaScript客户端
* [Blocknative](https://blocknative.com/) - Assist.js是可嵌入的小部件，可提高DApp可用性。该工具以编程形式识别并给出了清晰的操作，便于终端用户与MetaMask交互，以克服（甚至防止）常见的陷阱和障碍

### 以太坊ABI工具

Application Binary Interface 应用程序二进制接口

* [ABI decoder](https://github.com/ConsenSys/abi-decoder) - 用于解码以太坊交易中数据参数和事件的库
* [ABI-gen](https://github.com/0xProject/0x-monorepo/tree/development/packages/abi-gen) - 从合约ABI生成Typescript合约包装程序
* [Ethereum ABI UI](https://github.com/hiddentao/ethereum-abi-ui) - 从以太坊合约ABI自动生成UI表单字段定义和关联的验证器
* [headlong](https://github.com/esaulpaugh/headlong/) - 类型安全的合约ABI和递归长度前缀Java库
* [One Click dApp](https://oneclickdapp.com/) - 使用ABI在唯一的URL上立即生成DApp
* [Truffle Pig](https://npmjs.com/package/trufflepig) - 开发工具，提供简单的HTTP API来查找和读取Truffle生成的合约文件，以便在本地开发时使用，通过http提供新的合约ABI
* [Ethereum Contract Service](https://github.com/mesg-foundation/service-ethereum-contract) - MESG服务，可根据其地址和ABI与任何以太坊合约进行交互
* [Nethereum-CodeGenerator](https://github.com/StefH/Nethereum-CodeGenerator) - 基于Web的生成器，可基于Solidity智能合约创建基于Nethereum的C\#接口和服务

#### 模式&最佳实践

**智能合约开发模式**

* [Dappsys: ](https://github.com/dapphub/dappsys)安全、简单、灵活的以太坊合约基础模块
  * 为以太坊/Solidity中的常见问题提供解决方案
    * [白名单](https://steemit.com/ethereum/@nexusdev/dapp-a-day-11-whitelist-boring)
    * [可升级的ERC20通证](https://steemit.com/ethereum/@nikolai/dapp-a-day-6-upgradeable-tokens)
    * [ERC20通证保险箱](https://steemit.com/ethereum/@nexusdev/dapp-a-day-18-erc20-token-vault)
    * [验证（RBAC, 角色访问控制）](https://steemit.com/ethereum/@nikolai/dapp-a-day-4-access-control-via-auth)
    * [以及其他](https://github.com/dapphub/dappsys)
  * 为 [MakerDAO](https://github.com/makerdao/maker-otc) 或 [The TAO](https://github.com/ryepdx/the-tao) 提供基础模块
  * 在创建未经测试的解决方案之前应先进行咨询
  * 其使用在 [Dapp-a-day 1-10](https://steemit.com/@nikolai) 和 [Dapp-a-day 11-25](https://steemit.com/@nexusdev) 中皆有描述
* [OpenZeppelin Contracts: ](https://github.com/OpenZeppelin/openzeppelin-contracts)使用Solidity语言的可重用和安全的智能合约开放框架
  * 最广泛使用的库和智能合约
  * 与Dappsys相似，与Truffle框架有更多集成
  * [有关安全审计最佳实践的博客](https://blog.openzeppelin.com/)
* [Simpler Ethereum Multisig](https://medium.com/@ChrisLundkvist/exploring-simpler-ethereum-multisig-contracts-b71020c19037)
* [CryptoFin Solidity Auditing Checklist](https://github.com/cryptofinlabs/audit-checklist) - 常见审计结果清单，以及在主网启动时审计合约时需要注意的问题
* [aragonOS: ](https://hack.aragon.org/docs/aragonos-intro.html)用于构建DAO、Dapp和协议的智能合约框架
  * 可升级性：智能合约可以升级到新版本
  * 权限控制：通过使用`auth`和`authP`修饰符，只有其他应用程序或实体才能访问，保护功能性
  * 转发器：aragonOS应用程序可以将其执行操作的意向发送给其他应用程序，以便在满足要求的情况下转发意向

**可升级性**

* [Blog von Elena Dimitrova, Dev at colony.io](https://blog.colony.io/author/elena/)
  * [https://blog.colony.io/writing-more-robust-smart-contracts-99ad0a11e948](https://blog.colony.io/writing-more-robust-smart-contracts-99ad0a11e948)
  * [https://blog.colony.io/writing-upgradeable-contracts-in-solidity-6743f0eecc88](https://blog.colony.io/writing-upgradeable-contracts-in-solidity-6743f0eecc88)
* [Aragon research blog](https://blog.aragon.org/tag/research/)
  * [Library driven development](https://blog.aragon.org/library-driven-development-in-solidity-2bebcaf88736)
  * [Advanced Solidity code deployment techniques](https://blog.aragon.org/advanced-solidity-code-deployment-techniques-dc032665f434/)
* [OpenZeppelin on Proxy Libraries](https://blog.openzeppelin.com/proxy-libraries-in-solidity-79fbe4b970fd/)

### Infrastructure

#### Ethereum Clients

* [Besu](https://besu.hyperledger.org/en/latest/) - 基于Apache 2.0许可开发并用Java编写的开源以太坊客户端。该项目由Hyperledger托管。
* [Geth](https://geth.ethereum.org/docs/) - Go客户端
* [Parity](https://www.parity.io/ethereum/) - Rust客户端
* [Aleth](https://github.com/ethereum/aleth) - C++客户端
* [Nethermind](https://github.com/NethermindEth/nethermind) - .NET Core客户端
* [Infura](https://infura.io/) - 提供以太坊客户端标准兼容API的托管服务
* [Trinity](https://trinity.ethereum.org/) - 使用 [py-evm](https://github.com/ethereum/py-evm) 的Python客户端
* [Ethereumjs](https://github.com/ethereumjs/ethereumjs-client) - 使用 [ethereumjs-vm](https://github.com/ethereumjs/ethereumjs-vm) 的JS客户端
* [Seth](https://github.com/dapphub/dapptools/tree/master/src/seth) - 以太坊客户端工具，如同“命令行的MetaMask”一样
* [Mustekala](https://github.com/musteka-la/mustekala) - Metamask的以太坊轻客户端项目
* [Exthereum](https://github.com/exthereum/blockchain) - Elixir客户端
* [EWF Parity](https://github.com/energywebfoundation/energyweb-ui) - 用于Tobalaba测试网络的Energy Web Foundation客户端
* [Quorum](https://github.com/jpmorganchase/quorum) - A permissioned implementation of Ethereum supporting data privacy by [JP Morgan](https://jpmorgan.com/quorum)
* [Mana](https://github.com/mana-ethereum/mana) - Ethereum full node implementation written in Elixir.
* [Chainstack](https://chainstack.com/) - A managed service providing shared and dedicated Geth nodes
* [QuikNode](https://quiknode.io/) - Blockchain developer cloud with API access and node-as-a-service.

#### Storage

* [IPFS](https://ipfs.io/) - Decentralised storage and file referencing
  * [Mahuta](https://github.com/ConsenSys/Mahuta) - IPFS Storage service with added search capability, formerly IPFS-Store
  * [OrbitDB](https://github.com/orbitdb/orbit-db) - Decentralised database on top of IPFS
  * [JS IPFS API](https://github.com/ipfs/js-ipfs-http-client) - A client library for the IPFS HTTP API, implemented in JavaScript
  * [TEMPORAL](https://github.com/RTradeLtd/Temporal) - Easy to use API into IPFS and other distributed/decentralised storage protocols
* [Swarm](https://swarm-gateways.net/) - Distributed storage platform and content distribution service, a native base layer service of the Ethereum web3 stack
* [Infura](https://infura.io/) - A managed IPFS API Gateway and pinning service
* [3Box Storage](https://docs.3box.io/api/storage) - An api for user controlled, distrubuted storage. Built on top of IPFS and Orbitdb.

#### Messaging

* [Whisper](https://github.com/ethereum/wiki/wiki/Whisper) - Communication protocol for DApps to communicate with each other, a native base layer service of the Ethereum web3 stack
* [DEVp2p Wire Protocol](https://github.com/ethereum/devp2p/blob/master/rlpx.md) - Peer-to-peer communications between nodes running Ethereum/Whisper
* [Pydevp2p](https://github.com/ethereum/pydevp2p) - Python implementation of the RLPx network layer
* [3Box Threads](https://docs.3box.io/api/messaging) - API to allow developers to implement IPFS persisted, or in memory peer to peer messaging.

### Testing Tools

* [Truffle Teams](https://trufflesuite.com/teams) - Zero-Config continuous integration for truffle projects
* [Solidity code coverage](https://github.com/0xProject/0x-monorepo/tree/development/packages/sol-coverage) - Solidity code coverage tool
* [Solidity coverage](https://github.com/sc-forks/solidity-coverage) - Alternative code coverage for Solidity smart-contracts
* [Solidity function profiler](https://github.com/EricR/sol-function-profiler) - Solidity contract function profiler
* [Sol-profiler](https://github.com/Aniket-Engg/sol-profiler) - Alternative and updated Solidity smart contract profiler
* [Espresso](https://github.com/hillstreetlabs/espresso) - Speedy, parallelised, hot-reloading solidity test framework
* [Eth tester](https://github.com/ethereum/eth-tester) - Tool suite for testing Ethereum applications
* [Cliquebait](https://github.com/f-o-a-m/cliquebait) - Simplifies integration and accepting testing of smart contract applications with docker instances that closely resembles a real blockchain network
* [Hevm](https://github.com/dapphub/dapptools/tree/master/src/hevm) - The hevm project is an implementation of the Ethereum virtual machine \(EVM\) made specifically for unit testing and debugging smart contracts
* [Ethereum graph debugger](https://github.com/fergarrui/ethereum-graph-debugger) - Solidity graphical debugger
* [Tenderly CLI](https://github.com/Tenderly/tenderly-cli) - Speed up your development with human readable stack traces
* [Solhint](https://github.com/protofire/solhint) - Solidity linter that provides security, style guide and best practice rules for smart contract validation
* [Ethlint](https://github.com/duaraghav8/Ethlint) - Linter to identify and fix style & security issues in Solidity, formerly Solium
* [Decode](https://github.com/hacker-DOM/decode) - npm package which parses tx's submitted to a local testrpc node to make them more readable and easier to understand
* [truffle-assertions](https://github.com/rkalis/truffle-assertions) - An npm package with additional assertions and utilities used in testing Solidity smart contracts with truffle. Most importantly, it adds the ability to assert whether specific events have \(not\) been emitted.
* [Psol](https://github.com/Lamarkaz/psol) - Solidity lexical preprocessor with mustache.js-style syntax, macros, conditional compilation and automatic remote dependency inclusion.
* [solpp](https://github.com/merklejerk/solpp) - Solidity preprocessor and flattener with a comprehensive directive and expression language, high precision math, and many useful helper functions.
* [Decode and Publish](https://flightwallet.github.io/decode-eth-tx/) – Decode and publish raw ethereum tx. Similar to [https://live.blockcypher.com/btc-testnet/decodetx/](https://live.blockcypher.com/btc-testnet/decodetx/)
* [Doppelgänger](https://getdoppelganger.io/) - a library for mocking smart contract dependencies during unit testing.
* [rocketh](https://github.com/wighawag/rocketh) - A simple lib to test ethereum smart contract that allow to use whatever web3 lib and test runner you choose.
* [pytest-cobra](https://github.com/cobraframework/pytest-cobra) - PyTest plugin for testing smart contracts for Ethereum blockchain.

### Security Tools

* [MythX](https://mythx.io/) - Security verification platform and tools ecosystem for Ethereum developers
* [Mythril](https://github.com/ConsenSys/mythril) - Open-source EVM bytecode security analysis tool
* [Oyente](https://github.com/melonproject/oyente) - Alternative static smart contract security analysis
* [Securify](https://securify.chainsecurity.com/) - Security scanner for Ethereum smart contracts
* [SmartCheck](https://tool.smartdec.net/) - Static smart contract security analyzer
* [Ethersplay](https://github.com/crytic/ethersplay) - EVM disassembler
* [Evmdis](https://github.com/Arachnid/evmdis) - Alternative EVM disassembler
* [Hydra](https://github.com/IC3Hydra/Hydra) - Framework for cryptoeconomic contract security, decentralised security bounties
* [Solgraph](https://github.com/raineorshine/solgraph) - Visualise Solidity control flow for smart contract security analysis
* [Manticore](https://github.com/trailofbits/manticore) - Symbolic execution tool on Smart Contracts and Binaries
* [Slither](https://github.com/crytic/slither) - A Solidity static analysis framework
* [Adelaide](https://github.com/sec-bit/adelaide) - The SECBIT static analysis extension to Solidity compiler
* [solc-verify](https://github.com/SRI-CSL/solidity/) - A modular verifier for Solidity smart contracts
* [Solidity security blog](https://github.com/sigp/solidity-security-blog) - Comprehensive list of known attack vectors and common anti-patterns
* [Awesome Buggy ERC20 Tokens](https://github.com/sec-bit/awesome-buggy-erc20-tokens) - A Collection of Vulnerabilities in ERC20 Smart Contracts With Tokens Affected
* [Free Smart Contract Security Audit](https://callisto.network/smart-contract-audit/) - Free smart contract security audits from Callisto Network
* [Piet](https://piet.slock.it/) - A visual Solidity architecture analyzer

### Monitoring

* [Alethio](https://aleth.io/) - An advanced Ethereum analytics platform that provides live monitoring, insights and anomaly detection, token metrics, smart contract audits, graph visualization and blockchain search. Real-time market information and trading activities across Ethereum's decentralized exchanges can also be explored.
* [amberdata.io](https://amberdata.io/) - Provides live monitoring, insights and anomaly detection, token metrics, smart contract audits, graph visualization and blockchain search.
* [Neufund - Smart Contract Watch](https://github.com/Neufund/smart-contract-watch) - A tool to monitor a number of smart contracts and transactions
* [Scout](https://scout.cool/) - A live data feed of the activities and event logs of your smart contracts on Ethereum
* [Tenderly](https://tenderly.dev/) - A platform that gives users reliable smart contract monitoring and alerting in the form of a web dashboard without requiring users to host or maintain infrastructure
* [Chainlyt](https://www.chainlyt.io/main/dashboard/contract) - Explore smart contracts with decoded transaction data, see how the contract is used and search transactions with specific function calls
* [BlockScout](https://github.com/poanetwork/blockscout) - A tool for inspecting and analyzing EVM based blockchains. The only full featured blockchain explorer for Ethereum networks.
* [Terminal](https://terminal.co/) - A control panel for monitoring dapps. Terminal can be used to monitor your users, dapp, blockchain infrastructure, transactions and more.
* [Ethereum-watcher](https://github.com/HydroProtocol/ethereum-watcher) - An extensible framework written in Golang for listening to on-chain events and doing something in response.

### Other Miscellaneous Tools

* [aragonPM](https://hack.aragon.org/docs/apm-intro.html) - a decentralized package manager powered by aragonOS and Ethereum. aragonPM enables decentralized governance over package upgrades, removing centralized points of failure.
* [Truffle boxes](https://www.trufflesuite.com/boxes) - Packaged components for building DApps fast.
  * [Cheshire](https://github.com/endless-nameless-inc/cheshire) - A local sandbox implementation of the CryptoKitties API and smart contracts, available as a Truffle Box
* [Solc](https://solidity.readthedocs.io/en/latest/using-the-compiler.html) - Solidity compiler
* [Sol-compiler](https://sol-compiler.com/) - Project-level Solidity compiler
* [Solidity cli](https://github.com/pubkey/solidity-cli) - Compile solidity-code faster, easier and more reliable
* [Solidity flattener](https://github.com/poanetwork/solidity-flattener) - Combine solidity project to flat file utility. Useful for visualizing imported contracts or for verifying your contract on Etherscan
* [Sol-merger](https://github.com/RyuuGan/sol-merger) - Alternative, merges all imports into single file for solidity contracts
* [RLP](https://github.com/ethereumjs/rlp) - Recursive Length Prefix Encoding in JavaScript
* [eth-cli](https://github.com/protofire/eth-cli) - A collection of CLI tools to help with ethereum learning and development
* [Ethereal](https://github.com/wealdtech/ethereal) - Ethereal is a command line tool for managing common tasks in Ethereum
* [Eth crypto](https://github.com/pubkey/eth-crypto) - Cryptographic javascript-functions for Ethereum and tutorials to use them with web3js and solidity
* [Parity Signer](https://github.com/paritytech/parity-signer) - mobile app allows signing transactions
* [py-eth](http://py-eth.com/) - Collection of Python tools for the Ethereum ecosystem
* [truffle-flattener](https://github.com/nomiclabs/truffle-flattener) - Concats solidity files developed under Truffle with all of their dependencies
* [Decode](https://github.com/hacker-DOM/decode) - npm package which parses tx's submitted to a local testrpc node to make them more readable and easier to understand
* [TypeChain](https://github.com/ethereum-ts/TypeChain) - Typescript bindings for Ethereum smartcontracts
* [EthSum](https://ethsum.netlify.com/) - A Simple Ethereum Address Checksum Tool
* [PHP based Blockchain indexer](https://github.com/digitaldonkey/ethereum-php-eventlistener) - allows indexing blocks or listening to Events in PHP
* [Purser](https://github.com/JoinColony/purser) - JavaScript universal wallet tool for Ethereum-based wallets. Supports software, hardware, and Metamask -- brings all wallets into a consistent and predictable interface for dApp development.
* [Node-Metamask](https://github.com/JoinColony/node-metamask) - Connect to MetaMask from node.js
* [Solidity-docgen](https://github.com/OpenZeppelin/solidity-docgen) - Documentation generator for Solidity projects
* [Ethereum ETL](https://github.com/blockchain-etl/ethereum-etl) - Export Ethereum blockchain data to CSV or JSON files
* [prettier-plugin-solidity](https://github.com/prettier-solidity/prettier-plugin-solidity) - Prettier plugin for formatting Solidity code
* [Unity3dSimpleSample](https://github.com/Nethereum/Unity3dSimpleSample) - Ethereum and Unity integration demo
* [Flappy](https://github.com/Nethereum/Nethereum.Flappy) - Ethereum and Unity integration demo/sample
* [Wonka](https://github.com/Nethereum/Wonka) - Nethereum business rules engine demo/sample
* [Resolver-Engine](https://github.com/Crypto-Punkers/resolver-engine) - A set of tools to standarize Solidity import and artifact resolution in frameworks.
* [eth-reveal](https://github.com/justinjmoses/eth-reveal) - A node and browser tool to inspect transactions - decoding where possible the method, event logs and any revert reasons using ABIs found online.
* [Ethereum-tx-sender](https://github.com/HydroProtocol/ethereum-tx-sender) - A useful library written in Golang to reliably send a transaction — abstracting away some of the tricky low level details such as gas optimization, nonce calculations, synchronization, and retries.

### Smart Contract Standards & Libraries

#### [ERCs](https://eips.ethereum.org/erc) - The Ethereum Request for Comment repository

* Tokens
  * [ERC-20](https://eips.ethereum.org/EIPS/eip-20) - Original token contract for fungible assets
  * [ERC-721](https://eips.ethereum.org/EIPS/eip-721) - Token standard for non-fungible assets
  * [ERC-777](https://eips.ethereum.org/EIPS/eip-777) - An improved token standard for fungible assets
  * [ERC-918](https://eips.ethereum.org/EIPS/eip-918) - Mineable Token Standard
* [ERC-165](https://eips.ethereum.org/EIPS/eip-165) - Creates a standard method to publish and detect what interfaces a smart contract implements.
* [ERC-725](https://eips.ethereum.org/EIPS/eip-725) - Proxy contract for key management and execution, to establish a Blockchain identity.
* [ERC-173](https://eips.ethereum.org/EIPS/eip-173) - A standard interface for ownership of contracts

#### Popular Smart Contract Libraries

* [Zeppelin](https://github.com/OpenZeppelin/openzeppelin-contracts) - Contains tested reusable smart contracts like SafeMath and OpenZeppelin SDK [library](https://github.com/OpenZeppelin/openzeppelin-sdk) for smart contract upgradeability
* [cryptofin-solidity](https://github.com/cryptofinlabs/cryptofin-solidity) - A collection of Solidity libraries for building secure and gas-efficient smart contracts on Ethereum.
* [Modular Libraries](https://github.com/Modular-Network/ethereum-libraries) - A group of packages built for use on blockchains utilising the Ethereum Virtual Machine
* [DateTime Library](https://github.com/bokkypoobah/BokkyPooBahsDateTimeLibrary) - A gas-efficient Solidity date and time library
* [Aragon](https://github.com/aragon/aragon) - DAO protocol. Contains [aragonOS smart contract framework](https://github.com/aragon/aragonOS) with focus on upgradeability and governance
* [ARC](https://github.com/daostack/arc) - an operating system for DAOs and the base layer of the DAO stack.
* [0x](https://github.com/0xProject) - DEX protocol
* [Token Libraries with Proofs](https://github.com/sec-bit/tokenlibs-with-proofs) - Contains correctness proofs of token contracts wrt. given specifications and high-level properties
* [Provable API](https://github.com/provable-things/ethereum-api) - Provides contracts for using the Provable service, allowing for off-chain actions, data-fetching, and computation

### Developer Guides for 2nd Layer Infrastructure

#### Scalability

#### Payment/State Channels

* [Ethereum Payment Channel](https://medium.com/@matthewdif/ethereum-payment-channel-in-50-lines-of-code-a94fad2704bc) - Ethereum Payment Channel in 50 lines of code
* [µRaiden Documentation](https://microraiden.readthedocs.io/) - Guides and Samples for µRaiden Sender/Receiver Use Cases

#### Plasma

* [Learn Plasma](https://github.com/ethsociety/learn-plasma) - Website as Node application that was started at the 2018 IC3-Ethereum Crypto Boot Camp at Cornell University, covering all Plasma variants \(MVP/Cash/Debit\)
* [Plasma MVP](https://github.com/omisego/plasma-contracts) - OmiseGO's research implementation of Minimal Viable Plasma
* [Plasma MVP Golang](https://github.com/kyokan/plasma) - Golang implementation and extension of the Minimum Viable Plasma specification
* [Plasma Guard](https://github.com/mesg-foundation/plasma-guard) - Automatically watch and challenge or exit from Omisego Plasma Network when needed.
* [Plasma OmiseGo Watcher](https://github.com/mesg-foundation/service-plasma-omisego-watcher) - Interact with Plasma OmiseGo network and notifies for any byzantine events.

#### Side-Chains

* [POA Network](https://www.poa.network/)
  * [POA Bridge](https://bridge.poa.net/)
  * [POA Bridge UI](https://github.com/poanetwork/bridge-ui)
  * [POA Bridge Contracts](https://github.com/poanetwork/poa-bridge-contracts)
* [Loom Network](https://github.com/loomnetwork)
* [Matic Network](https://docs.matic.network/)

#### Privacy / Confidentiality

**zkSNARKs**

* [ZoKrates](https://github.com/Zokrates/ZoKrates) - A toolbox for zkSNARKS on Ethereum
* [The AZTEC Protocol](https://github.com/AztecProtocol/AZTEC) - Confidential transactions on the Ethereum network, implementation is live on the Ethereum main-net
* [Nightfall](https://github.com/EYBlockchain/nightfall) - Make any ERC-20 / ERC-721 token private - open source tools & microservices
* Proxy Re-encryption \(PRE\) \*\* [NuCypher Network](https://github.com/nucypher/nucypher) - A proxy re-encryption network to empower data privacy in decentralized systems \*\* [pyUmbral](https://github.com/nucypher/pyumbral) - Threshold proxy re-encryption cryptographic library
* Fully Homomorphic Encryption \(FHE\) \*\* [NuFHE](https://github.com/nucypher/nufhe) - GPU accelerated FHE library

#### Prebuilt UI Components

* [aragonUI](https://ui.aragon.org/) - A React library including Dapp components
* [components.bounties.network](https://components.bounties.network/) - A React library including Dapp components
* [ui.decentraland.org](https://github.com/decentraland/ui) - A React library including Dapp components
* [dapparatus](https://github.com/austintgriffith/dapparatus) - Reusable React Dapp components
* [Metamask ui](https://github.com/MetaMask/metamask-extension/tree/develop/ui/app/components) - Metamask React Components
* [DappHybrid](https://github.com/Nethereum/Nethereum.DappHybrid) - A cross-platform hybrid hosting mechanism for web based decentralised applications
* [Nethereum.UI.Desktop](https://github.com/Nethereum/Nethereum.UI.Desktop) - Cross-platform desktop wallet sample
* [eth-button](https://eth-button.github.io/eth-button/) - Minimalist donation button
* [Rimble Design System](https://rimble.consensys.design/) - Adaptable components and design standards for decentralized applications.
* [3Box Plugins](https://docs.3box.io/build/plugins) - Drop in react components for social functionality. Including comments, profiles and messaging.

