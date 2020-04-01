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

#### 后端以太坊APIs

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

#### Bootstrap/即用工具

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

### 基础设施

#### 以太坊客户端

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
* [Quorum](https://github.com/jpmorganchase/quorum) -  [JP Morgan](https://jpmorgan.com/quorum) 授权的以太坊实现，支持数据隐私
* [Mana](https://github.com/mana-ethereum/mana) - 以太坊全节点客户端的Elixir实现
* [Chainstack](https://chainstack.com/) - 提供共享和专用Geth节点的托管服务
* [QuikNode](https://quiknode.io/) - 具有API访问和节点即服务的区块链开发者云端

#### 存储

* [IPFS](https://ipfs.io/) - 去中心化存储和文件引用
  * [Mahuta](https://github.com/ConsenSys/Mahuta) - 具有附加搜索功能的IPFS存储服务（前身为IPFS-Store）
  * [OrbitDB](https://github.com/orbitdb/orbit-db) - 基于IPFS的去中心化数据库
  * [JS IPFS API](https://github.com/ipfs/js-ipfs-http-client) - JavaScript实现的IPFS HTTP API客户端库
  * [TEMPORAL](https://github.com/RTradeLtd/Temporal) - 将API集成到IPFS和其他分布式/去中心化存储协议中
* [Swarm](https://swarm-gateways.net/) - 分布式存储平台和内容分发服务，以太坊web3堆栈的本地基础层服务
* [Infura](https://infura.io/) - 托管IPFS API网关和固定服务
* [3Box Storage](https://docs.3box.io/api/storage) - 用户控制的分布式存储API，基于IPFS和Orbitdb

#### 消息

* [Whisper](https://github.com/ethereum/wiki/wiki/Whisper) - DApp通信协议，以太坊web3堆栈的本地基础层服务
* [DEVp2p Wire Protocol](https://github.com/ethereum/devp2p/blob/master/rlpx.md) - 以太坊点对点通信协议
* [Pydevp2p](https://github.com/ethereum/pydevp2p) - RLPx网络层的Python实现
* [3Box Threads](https://docs.3box.io/api/messaging) - 使开发者能够持久实现IPFS的API，或在内存中实现点对点消息传递

### 测试工具

* [Truffle Teams](https://trufflesuite.com/teams) - Truffle项目的零配置持续集成
* [Solidity code coverage](https://github.com/0xProject/0x-monorepo/tree/development/packages/sol-coverage) - Solidity代码覆盖工具
* [Solidity coverage](https://github.com/sc-forks/solidity-coverage) - Solidity智能合约备选覆盖工具
* [Solidity function profiler](https://github.com/EricR/sol-function-profiler) - 智能合约功能探查器
* [Sol-profiler](https://github.com/Aniket-Engg/sol-profiler) - 升级版智能合约探查器
* [Espresso](https://github.com/hillstreetlabs/espresso) - 快速、并行、热重载Solidity测试框架
* [Eth tester](https://github.com/ethereum/eth-tester) - 以太坊应用程序测试工具组件
* [Cliquebait](https://github.com/f-o-a-m/cliquebait) - 使用与真实区块链网络极为相似的Docker实例简化智能合约应用程序的集成和接受测试
* [Hevm](https://github.com/dapphub/dapptools/tree/master/src/hevm) - hevm项目是以太坊虚拟机的实现，专用于单元测试和调试智能合约
* [Ethereum graph debugger](https://github.com/fergarrui/ethereum-graph-debugger) - Solidity图形调试器
* [Tenderly CLI](https://github.com/Tenderly/tenderly-cli) - 通过人类可读的堆栈跟踪加速开发
* [Solhint](https://github.com/protofire/solhint) - 提供安全性、样式指南和最佳实践规则，用于智能合约验证
* [Ethlint](https://github.com/duaraghav8/Ethlint) - 可以识别并修复Solidity中样式和安全性问题（前身为Solium）
* [Decode](https://github.com/hacker-DOM/decode) - npm软件包，将事务提交到本地testrpc节点进行解析，使其更具可读性和易懂性
* [truffle-assertions](https://github.com/rkalis/truffle-assertions) - npm软件包，具备额外断言和实用程序，用于测试使用Truffle的Solidity智能合约
* [Psol](https://github.com/Lamarkaz/psol) - 具有mustache.js样式的语法、宏、条件编译和自动远程依赖关系包含的Solidity词法预处理器
* [solpp](https://github.com/merklejerk/solpp) - 具有全面指令、表达式语言、高精度运算和许多辅助功能的Solidity预处理器和展平器
* [Decode and Publish](https://flightwallet.github.io/decode-eth-tx/) – 解码并发布原始以太坊事务
* [Doppelgänger](https://getdoppelganger.io/) - 用于在单元测试期间模拟智能合约依赖关系的库
* [rocketh](https://github.com/wighawag/rocketh) - 用于以太坊智能合约测试的简单库，可以选择任意web3库和测试程序
* [pytest-cobra](https://github.com/cobraframework/pytest-cobra) - PyTest插件，用于测试以太坊智能合约

### 安全工具

* [MythX](https://mythx.io/) - 以太坊开发者的安全验证平台和工具生态系统
* [Mythril](https://github.com/ConsenSys/mythril) - EVM字节码安全性开源分析工具
* [Oyente](https://github.com/melonproject/oyente) - 静态智能合约安全性分析工具
* [Securify](https://securify.chainsecurity.com/) - 以太坊智能合约安全扫描器
* [SmartCheck](https://tool.smartdec.net/) - 静态智能合约安全分析器
* [Ethersplay](https://github.com/crytic/ethersplay) - EVM反汇编器
* [Evmdis](https://github.com/Arachnid/evmdis) - EVM反汇编器
* [Hydra](https://github.com/IC3Hydra/Hydra) - 加密经济合约安全性框架，去中心化安全性赏金
* [Solgraph](https://github.com/raineorshine/solgraph) - 智能合约安全性分析可视化Solidity控制流
* [Manticore](https://github.com/trailofbits/manticore) - 智能合约和二进制的符号执行工具
* [Slither](https://github.com/crytic/slither) - Solidity静态分析框架
* [Adelaide](https://github.com/sec-bit/adelaide) - Solidity编译器的SECBIT静态分析扩展程序
* [solc-verify](https://github.com/SRI-CSL/solidity/) - 用于Solidity智能合约的模块化验证程序
* [Solidity security blog](https://github.com/sigp/solidity-security-blog) - 已知攻击媒介和常见反模式的完整列表
* [Awesome Buggy ERC20 Tokens](https://github.com/sec-bit/awesome-buggy-erc20-tokens) - 带有通证实例的ERC20智能合约漏洞集合
* [Free Smart Contract Security Audit](https://callisto.network/smart-contract-audit/) - Callisto Network的免费智能合约安全审计
* [Piet](https://piet.slock.it/) - 可视化Solidity架构分析

### 监测

* [Alethio](https://aleth.io/) - 以太坊分析平台，可提供实时监控、预测和异常检测、通证指标、智能合约审计，图形可视化和区块链搜索。还可以观察以太坊去中心化交易所的实时市场信息和交易活动
* [amberdata.io](https://amberdata.io/) - 提供实时监控、预测和异常检测、通证指标、智能合约审计，图形可视化和区块链搜索
* [Neufund - Smart Contract Watch](https://github.com/Neufund/smart-contract-watch) - 用于监测大量智能合约和交易的工具
* [Scout](https://scout.cool/) - 以太坊上智能合约活动和事件日志的实时数据馈送
* [Tenderly](https://tenderly.dev/) - 该平台可通过网页面板为用户提供可靠的智能合约监测和警报，无需用户托管或维护基础架构
* [Chainlyt](https://www.chainlyt.io/main/dashboard/contract) - 探索具有解码交易数据的智能合约，查看合约的使用方式以及通过特定功能调用搜索交易
* [BlockScout](https://github.com/poanetwork/blockscout) - 用于检查和分析基于EVM的区块链，针对以太坊网络唯一功能齐备的区块链浏览器
* [Terminal](https://terminal.co/) - 用于监测DApp的控制面板。Terminal可用于监测用户、DApp、区块链基础设施和交易等
* [Ethereum-watcher](https://github.com/HydroProtocol/ethereum-watcher) - Go语言可扩展框架，用于收听链上事件并做出响应

### 其他工具

* [aragonPM](https://hack.aragon.org/docs/apm-intro.html) - 由aragonOS和以太坊提供支持的去中心化软件包管理器。aragonPM支持对软件包升级进行去中心化治理，从而消除中心故障点
* [Truffle boxes](https://www.trufflesuite.com/boxes) - 用于快速构建DApp的打包组件
  * [Cheshire](https://github.com/endless-nameless-inc/cheshire) - CryptoKitties API和智能合约的本地沙盒实现，可以作为Truffle Box使用
* [Solc](https://solidity.readthedocs.io/en/latest/using-the-compiler.html) - Solidity编译器
* [Sol-compiler](https://sol-compiler.com/) - 项目级Solidity编译器
* [Solidity cli](https://github.com/pubkey/solidity-cli) - 简捷可靠的Solidity编译器
* [Solidity flattener](https://github.com/poanetwork/solidity-flattener) - 将Solidity项目合并到平面文件实用程序，有助于可视化导入的合约或在Etherscan上验证合约
* [Sol-merger](https://github.com/RyuuGan/sol-merger) - 备选，将所有导入合并到单个Solidity合约文件
* [RLP](https://github.com/ethereumjs/rlp) - JavaScript递归长度前缀编码
* [eth-cli](https://github.com/protofire/eth-cli) - CLI工具集合，可辅助以太坊学习和开发
* [Ethereal](https://github.com/wealdtech/ethereal) - Ethereal是用于管理以太坊中常见任务的命令行工具
* [Eth crypto](https://github.com/pubkey/eth-crypto) - 以太坊的加密javascript函数以及将其与web3js和solidity结合使用的教程
* [Parity Signer](https://github.com/paritytech/parity-signer) - 允许签名交易的移动应用程序
* [py-eth](http://py-eth.com/) - 以太坊生态系统的Python工具集合
* [truffle-flattener](https://github.com/nomiclabs/truffle-flattener) - Concats使用Truffle开发的实体文件及其所有依赖项
* [Decode](https://github.com/hacker-DOM/decode) - npm软件包，对提交到本地testrpc节点的事务进行解析，使其更可读易懂
* [TypeChain](https://github.com/ethereum-ts/TypeChain) - 以太坊智能合约的Typescript绑定
* [EthSum](https://ethsum.netlify.com/) - 简单的以太坊地址校验和工具
* [PHP based Blockchain indexer](https://github.com/digitaldonkey/ethereum-php-eventlistener) - 允许索引区块或收听PHP中的事件
* [Purser](https://github.com/JoinColony/purser) - 基于以太坊的钱包的JavaScript通用钱包工具。支持软件、硬件和Metamask钱包
* [Node-Metamask](https://github.com/JoinColony/node-metamask) - 通过node.js连接Metamask
* [Solidity-docgen](https://github.com/OpenZeppelin/solidity-docgen) - Solidity项目的文档生成器
* [Ethereum ETL](https://github.com/blockchain-etl/ethereum-etl) - 将以太坊区块链数据导出为CSV或JSON文件
* [prettier-plugin-solidity](https://github.com/prettier-solidity/prettier-plugin-solidity) - 用于格式化Solidity代码
* [Unity3dSimpleSample](https://github.com/Nethereum/Unity3dSimpleSample) - 以太坊和Unity集成演示
* [Flappy](https://github.com/Nethereum/Nethereum.Flappy) -  以太坊和Unity集成演示/样本
* [Wonka](https://github.com/Nethereum/Wonka) - Nethereum业务规则引擎演示/样本
* [Resolver-Engine](https://github.com/Crypto-Punkers/resolver-engine) - 用于在框架中标准化Solidity导入和工件解析的工具
* [eth-reveal](https://github.com/justinjmoses/eth-reveal) - 节点和浏览器工具，用于检查事务，使用在线找到的ABI尽可能解码方法、事件日志和还原原因
* [Ethereum-tx-sender](https://github.com/HydroProtocol/ethereum-tx-sender) - 用Golang编写的库，能够可靠地发送交易，抽象出棘手的底层细节，例如gas优化、随机数计算、同步等

### 智能合约标准&库

#### [ERCs](https://eips.ethereum.org/erc) - The Ethereum Request for Comment repository 以太坊意见征求稿

* 通证
  * [ERC-20](https://eips.ethereum.org/EIPS/eip-20) - 可置换资产的原始通证合约
  * [ERC-721](https://eips.ethereum.org/EIPS/eip-721) - 不可置换资产的通证标准
  * [ERC-777](https://eips.ethereum.org/EIPS/eip-777) - 可置换资产的优化版通证标准
  * [ERC-918](https://eips.ethereum.org/EIPS/eip-918) - 可挖矿通证标准
* [ERC-165](https://eips.ethereum.org/EIPS/eip-165) - 创建一种标准方法，发布和检测智能合约实现的接口
* [ERC-725](https://eips.ethereum.org/EIPS/eip-725) - 用于密钥管理和执行的代理合约，以建立区块链身份
* [ERC-173](https://eips.ethereum.org/EIPS/eip-173) - 合约所有权的标准接口

#### 主流智能合约库

* [Zeppelin](https://github.com/OpenZeppelin/openzeppelin-contracts) - 包含经测试的可重用智能合约，例如SafeMath和OpenZeppelin SDK库，以实现智能合约的可升级性
* [cryptofin-solidity](https://github.com/cryptofinlabs/cryptofin-solidity) - Solidity库集合，用于在以太坊上构建安全且节省gas的智能合约
* [Modular Libraries](https://github.com/Modular-Network/ethereum-libraries) - 使用以太坊虚拟机构建用于区块链的软件包
* [DateTime Library](https://github.com/bokkypoobah/BokkyPooBahsDateTimeLibrary) - 节省gas的Solidity日期和时间库
* [Aragon](https://github.com/aragon/aragon) - DAO协议。包含[aragonOS智能合约框架](https://github.com/aragon/aragonOS)，重点关注可升级性和治理
* [ARC](https://github.com/daostack/arc) - DAO的操作系统和DAO堆栈基础层
* [0x](https://github.com/0xProject) - DEX（去中心化交易所）协议
* [Token Libraries with Proofs](https://github.com/sec-bit/tokenlibs-with-proofs) - 根据给定的规范和高级属性，包含通证合约wrt.的正确性证明
* [Provable API](https://github.com/provable-things/ethereum-api) - 提供使用Provable服务的合约，允许进行链下操作、数据获取和计算

### 开发者指南及第二层基础设施

#### 扩容性

#### 支付/状态通道

* [Ethereum Payment Channel](https://medium.com/@matthewdif/ethereum-payment-channel-in-50-lines-of-code-a94fad2704bc) - 以太坊支付通道的50行代码
* [µRaiden Documentation](https://microraiden.readthedocs.io/) - µRaiden发送器/接收器用例的指南和示例

#### 侧链

* [POA Network](https://www.poa.network/)
  * [POA Bridge](https://bridge.poa.net/)
  * [POA Bridge UI](https://github.com/poanetwork/bridge-ui)
  * [POA Bridge Contracts](https://github.com/poanetwork/poa-bridge-contracts)
* [Loom Network](https://github.com/loomnetwork)
* [Matic Network](https://docs.matic.network/)

#### 隐私

**zkSNARKs**

* [ZoKrates](https://github.com/Zokrates/ZoKrates) - 以太坊zkSNARKS工具箱
* [The AZTEC Protocol](https://github.com/AztecProtocol/AZTEC) - 以太坊网络上的私密交易，实现已上线以太坊主网
* [Nightfall](https://github.com/EYBlockchain/nightfall) - 将所有ERC-20 / ERC-721通证设为私有-开源工具和微服务
* [NuCypher Network](https://github.com/nucypher/nucypher) - 再加密代理网络，可在去中心化系统中增强数据隐私
* [pyUmbral](https://github.com/nucypher/pyumbral) - 门限代理再加密密码库
* [NuFHE](https://github.com/nucypher/nufhe) - GPU加速的FHE库

#### 预建UI组件

* [aragonUI](https://ui.aragon.org/) - 包含DApp组件的React库
* [components.bounties.network](https://components.bounties.network/) - 包含DApp组件的React库
* [ui.decentraland.org](https://github.com/decentraland/ui) - 包含DApp组件的React库
* [dapparatus](https://github.com/austintgriffith/dapparatus) - 可重用的React Dapp组件
* [Metamask ui](https://github.com/MetaMask/metamask-extension/tree/develop/ui/app/components) - Metamask React组件
* [DappHybrid](https://github.com/Nethereum/Nethereum.DappHybrid) - 基于Web的去中心化应用程序的跨平台混合托管机制
* [Nethereum.UI.Desktop](https://github.com/Nethereum/Nethereum.UI.Desktop) - 跨平台桌面钱包示例
* [eth-button](https://eth-button.github.io/eth-button/) - 极简捐赠按钮
* [Rimble Design System](https://rimble.consensys.design/) - 适用于去中心化应用程序的适应性组件和设计标准
* [3Box Plugins](https://docs.3box.io/build/plugins) - 加入用于社交功能的react组件。包括评论、个人资料和消息

