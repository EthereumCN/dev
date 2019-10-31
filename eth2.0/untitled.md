# 开发者手册和常见问题

## 搞D乜？ETH2也疯狂！

* 通过综合以太坊最新的ETH2.0开发进程，旨在提供一个开发者培训指南，迅速入手ETH2.0开发。
* 这个文档是精华中的精华，可能其它地方也出现过类似的文档，我们尝试把最有用的东西收集到这里。It’s a collection of collections; the same resource may overlap in different links. Although we would try to sort by difficulty levels.
* 请注意，ETH2.0在以太坊基金会的主导下正如火如荼的建设中，有些内容可能迅速修改和抛弃，请多留意我们的最新文档更新。

## 总舵

* 2019年10月29日：[规范v0.9.0发布](https://eth2.ethereum.cn/eth2-specs/v0.9.0)，精华解读也准备在路上了。



###  <a id="Learning-Ethereum-20"></a>

### Learning Ethereum 2.0 <a id="Learning-Ethereum-20"></a>

#### 👶🏻 Level 1: Introduction for newbies <a id="&#x1F476;&#x1F3FB;-Level-1-Introduction-for-newbies"></a>

* **\[2018 Nov @Devcon4\]** 🎞️ [@vbuterin: Ethereum 2.0 - the road to scaling Ethereum](https://slideslive.com/38911602/latest-of-ethereum)
  * An overview of the history and future roadmap.
* **\[2019 Oct @Devcon5\]** 🎞️ [@djrtwo - eth2.0; tldr video](https://slideslive.com/38919931/eth-20-tldr) and [slides](https://docs.google.com/presentation/d/1_C_79ilyX0BsyMnSY84M3DoItPU9hBNxnvUEWOOLN7k/edit#slide=id.p1)
  * The latest high-level introduction of Ethereum 2.0 phases.
* **`Update irregularly`** [ethereum.org collection](https://ethereum.org/learn/#eth-2-0)
  * Useful links to more learning resources.
* **`Update irregularly`** [Two Point Oh](https://our.status.im/tag/two-point-oh/) - organized on [status-im/the-explainers](https://github.com/status-im/the-explainers/)

#### 🤓 Level 2: If you want to fully understand the core protocols <a id="&#x1F913;-Level-2-If-you-want-to-fully-understand-the-core-protocols"></a>

* 🌟 **`Update irregularly`** [Ethereum 2.0 Specifications](https://github.com/ethereum/eth2.0-specs)
* Core spec comprehensive reading
  * **`Update irregularly`** [Serenity Rationale](https://notes.ethereum.org/@vbuterin/rkhCgQteN) - \(20190808 version\)
  * **`Update irregularly`** [@protolambda: Phase 0 Specs Diagrams](https://github.com/protolambda/eth2-docs)
  * **\[2019 Oct @Devcon5, spec v8\]** Phase 0 deepdive [slides](https://docs.google.com/presentation/d/1MZ-E6TVwomt4rqz-P2Bd_X3DFUW9fWDQkxUP_QJhkyw/edit?pli=1#slide=id.g621e1673fb_21_195) and [video @3h58m40s](https://slideslive.com/38919736/devcon5-convention-room-day2)

#### 🧐 Level 3: Deeper reading materials <a id="&#x1F9D0;-Level-3-Deeper-reading-materials"></a>

**Forums**

* 💡Ethereum Research discourse [ethresear.ch](http://ethresear.ch/) - [sharding](https://ethresear.ch/c/sharding) and [Casper](https://ethresear.ch/c/casper) topics.

**Sharding, scalalibility**

* **`Update irregularly`** [Sharding FAQ](https://github.com/ethereum/wiki/wiki/Sharding-FAQ)
  * What is blockchain sharding? The different tradeoffs of different cross-shard communication approaches?
* **`Update irregularly`** [Ethereum Sharding Research Compendium](https://notes.ethereum.org/@serenity/H1PGqDhpm?type=view)
  * Vitalik’s collection notes. Also including some proof-of-stake related resources.
* **`Update irregularly`** [@vbuterin: Eth2 sharding mindmap](https://www.mindomo.com/zh/mindmap/eth2-sharding-4408ec348bee4501aa125c3e3cd251d3)
* **\[2018 July @IC3-Ethereum Crypto Boot Camp\]** 🎞️ @vbuterin: Sharding: Making blockchains scalable, decentralized and secure - [video](https://vod.video.cornell.edu/media/Sharding+-+Vitalik+Buterin/1_1xezsfb4/97851101) and [slides](https://vitalik.ca/files/Ithaca201807_Sharding.pdf)

**Proof-of-Stake, Casper**

* **`Update irregularly`** [Proof of Stake FAQ ](https://github.com/ethereum/wiki/wiki/Proof-of-Stake-FAQ)
* **`Paper`** [Casper the Friendly Finality Gadget](https://arxiv.org/abs/1710.09437)

### What’s happening? <a id="What&#x2019;s-happening"></a>

* 🎙 [ETH2.0 Implementers Bi-weekly Calls](https://github.com/ethereum/eth2.0-pm/)
* 🗂 [eth2.info](https://eth2.info/) - by Ben Edgington \(PegaSys, ConsenSys\)
* Regular publications
  * 🦄 [Ethereum Foundation blog - eth2 quick update](https://blog.ethereum.org/2019/10/23/eth2-quick-update/)
  * 📣 [Week in Ethereum News](http://www.weekinethereum.com/) - by Evan Van Ness
  * 🆕 [What’s New in Eth2?](http://eth2.news/) - by Ben Edgington \(PegaSys, ConsenSys\)
* Client teams updates
  * 💠 [Prysmatic Labs Biweekly Development Update](https://medium.com/prysmatic-labs)
  * ☁️ [Nimbus Update](https://our.status.im/tag/nimbus/)
  * 🔆 [Lighthouse Update](https://lighthouse.sigmaprime.io/)

### Research topics <a id="Research-topics"></a>

#### Randomness <a id="Randomness"></a>

* 🎞️ [@justindrake: Ethereum 2.0 randomness - using a VDF- 2018 Nov @Devcon4](https://slideslive.com/38911623/ethereum-20-randomness)
* [Verifiable Delay Functions \(VDF\) Research Effort](http://vdfresearch.org/)

#### Phase 2: state execution <a id="Phase-2-state-execution"></a>

* **`Update irregularly`** [ETH 2 Phase 2 WIKI](https://hackmd.io/@villanuevawill/H1hgfATkB)
  * Execution Environments \(EEs\), Fee markets
* **\[2019 Oct, Devcon 5\]** [@villanuevawill: Phase 2 Dev Experience ](https://docs.google.com/presentation/d/1Oj96cudOsR1ZvlWneZPk4mo7YWo0wRVX-R-bsNvJStQ/edit#slide=id.g5d36bcd2da_0_0)

#### Economics <a id="Economics"></a>

* [EIP-1559: Fee market](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1559.md)
  * [@econoar: Fixing the Ethereum Fee Market \(EIP-1559\)](https://medium.com/@eric.conner/fixing-the-ethereum-fee-market-eip-1559-9109f1c1814b)

### Events outputs <a id="Events-outputs"></a>

* [Sharding/Eth2.0/Serenity workshops collection](https://github.com/ethereum/eth2.0-pm/blob/master/meetups/collection.md)

## ![handbook](https://storage.googleapis.com/ethereum-hackmd/upload_5757ff71b998715ddb4e1f82f4037f26.png) FAQs <a id="-FAQs"></a>

> Part of the previous [EF Research AMAs](https://docs.ethhub.io/other/ethereum-2.0-ama/) may be outdated.

### Roadmaps, plans <a id="Roadmaps-plans"></a>

#### What’s the Ethereum 2.0 roadmap? <a id="What&#x2019;s-the-Ethereum-20-roadmap"></a>

> Latest update: 2019, Oct 24th

See [@djrtwo - eth2.0; tldr video](https://slideslive.com/38919931/eth-20-tldr) and [slides](https://docs.google.com/presentation/d/1_C_79ilyX0BsyMnSY84M3DoItPU9hBNxnvUEWOOLN7k/edit#slide=id.p1).

#### How and when to merge eth1 chain into eth2? <a id="How-and-when-to-merge-eth1-chain-into-eth2"></a>

> Latest update: 2019, Oct 24th

Regarding migrating the PoW chain to PoS chain, the most promising proposal is to convert eth1 EVM and history as one of the eth2 Phase 2 Execution Environments \(EEs\). It will minimize the migration requirements for DApps.

Before Phase 2 system is ready, the current PoW eth1 chain and PoS eth2 chain will both exist for a while.

**Reference**

* [Posssible eth1 -&gt; eth2 transition technical proposal on ethresear.ch](https://ethresear.ch/t/the-eth1-eth2-transition/6265)

### Phase 0 beacon chain <a id="Phase-0-beacon-chain"></a>

#### What I need to do to be a beacon chain validator? <a id="What-I-need-to-do-to-be-a-beacon-chain-validator"></a>

> Latest update: 2019, Oct 24th, need to update the numbers of bandwidth requirements from the spec v0.9 patch.

1. In the current proposal, the minimum deposit is 32 ethers.
2. A normal computer.
3. Stable network environment.

#### When will Phase 0 beacon chain be launched? <a id="When-will-Phase-0-beacon-chain-be-launched"></a>

> Latest update: 2019, Oct 24th

Before launching beacon chain, we have serveral tasks in parrallel:

1. The BLS standardization: see [Deposit Contract section from the quick updates](https://blog.ethereum.org/2019/10/23/eth2-quick-update/)
2. The audit:
   1. Beacon chain protocol
   2. Deposit contract \(almost done by Runtime Verification team\)
   3. Client software
3. Fuzzing tests
4. The stable multi-client beacon chain testnet: it’s expected that the long-term testnet will be launch in November.

The launching progress is depending on how does the stable multi-client beacon chain testnet works. The testnet will provide valueable data for us to optimize both the efficiency and user experience.

#### How’s the liquidity in phase 0 and phase 1? <a id="How&#x2019;s-the-liquidity-in-phase-0-and-phase-1"></a>

> Latest update: 2019, Oct 24th

Phase 0 \(beacon chain\) is launching without transfer functionality. The transfer functionality is planned be added in phase 1 or 2.

### Phase 1 data chain <a id="Phase-1-data-chain"></a>

#### What is data availability? Why is it important? <a id="What-is-data-availability-Why-is-it-important"></a>

See [data availability notes](https://github.com/ethereum/research/wiki/A-note-on-data-availability-and-erasure-coding#what-is-the-data-availability-problem).

#### What is proof of custody? <a id="What-is-proof-of-custody"></a>

See [Serenity Design Rationale - The proof of custody game](https://notes.ethereum.org/@vbuterin/rkhCgQteN?type=view#The-proof-of-custody-game)

### Phase 2 state execution <a id="Phase-2-state-execution1"></a>

#### What are all the cross-shard transations mechanisms? <a id="What-are-all-the-cross-shard-transations-mechanisms"></a>

See [Phase 2 WIKI - Cross Shard Transactions](https://hackmd.io/UzysWse1Th240HELswKqVA#Cross-Shard-Transactions).

### Misc <a id="Misc"></a>

#### Why not EIP-1011 \(Casper FFG Contract\)? <a id="Why-not-EIP-1011-Casper-FFG-Contract"></a>

* [@djrtwo - signatures, competing games, and tx parallelization](https://notes.ethereum.org/s/rJDrKoBOQ)
* [@djrtwo - Casper ♥ Sharding \(June 2018\)](https://medium.com/@djrtwo/casper-%EF%B8%8F-sharding-28a90077f121)

#### How to become an Ethereum 2.0 developer? <a id="How-to-become-an-Ethereum-20-developer"></a>

1. Look around the [client teams repositories](https://docs.ethhub.io/ethereum-roadmap/ethereum-2.0/eth2.0-teams/teams-building-eth2.0/), find an issue, and solve it!
   * Even finding typos would be appreciated! :\)
   * If you have your language preference, there are Go, Java, JavaScript, Nim, Python, Rust… languages!
   * Some of the teams are still hiring, don’t be afraid to ask.
2. Get familar with [specs](https://github.com/ethereum/eth2.0-specs). See if you can [find a bug and get 5 ETH](https://github.com/ethereum/eth2.0-specs/issues/1345).

### Still have question? <a id="Still-have-question"></a>

* Welcome to the [discord](https://discord.gg/hpFs23p) or [bridged gitter channel](https://gitter.im/ethereum/sharding)! 👋

