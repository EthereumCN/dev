# 开发规范

## What are EIPs?

[Ethereum Improvement Proposals \(EIPs\)](https://eips.ethereum.org/) are standards specifying potential new features or processes for Ethereum. EIPs contain technical specifications for the proposed changes and act as the “source of truth” for the community. Network upgrades and application standards for Ethereum are discussed and developed through the EIP process.

Anyone within the Ethereum community has the ability to create an EIP. Guidelines for writing EIPs are included in [EIP 1](https://eips.ethereum.org/EIPS/eip-1). The EIP should provide a concise technical specification of the feature its rationale. The EIP author is responsible for building consensus within the community and documenting dissenting opinions. Given the high technical bar for submitting a well-formed EIP, historically, most EIP authors have been application or protocol developers.

## Why do EIPs matter?

EIPs play a central role in how changes happen and are documented on Ethereum. They are the way for people to propose, debate and adopt changes. There are [different types of EIPs](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1.md#eip-types) including core EIPs for low-level protocol changes that affect consensus and require a network upgrade as well as ERCs for application standards. For example, standards to create tokens, like [ERC20](https://eips.ethereum.org/EIPS/eip-20) or [ERC721](https://eips.ethereum.org/EIPS/eip-721) allow applications interacting with these tokens to all treat tokens using the same rules, which makes it easier to create interoperable applications.

Every network upgrade consists of a set of EIPs that need to be implemented by each [Ethereum client](https://ethereum.org/learn/#clients-and-nodes) on the network. This implies that to stay in consensus with other clients on the Ethereum mainnet, client developers need to make sure they have all implemented the required EIPs.

Along with providing a technical specification for changes, EIPs are the unit around which governance happens in Ethereum: anyone is free to propose one, and then various stakeholders in the community will debate to determine if it should be adopted as a standard or included in a network upgrade. Because non-core EIPs don't have to be adopted by all applications \(for example, you can create a non-[ERC20 token](https://eips.ethereum.org/EIPS/eip-20)\), but core EIPs must be widely adopted \(because all nodes must upgrade to stay part of the same network\), core EIPs require broader consensus within the community than non-core EIPs.

## History of EIPs <a id="history-of-eips"></a>

The [Ethereum Improvement Proposals \(EIPs\) Github repository](https://github.com/ethereum/EIPs) was created in October 2015. The EIP process is based on the [Bitcoin Improvement Proposals \(BIPs\)](https://github.com/bitcoin/bips) process, which itself is based on the [Python Enhancement Proposals \(PEPs\)](https://www.python.org/dev/peps/) process.

EIP editors are tasked with reviewing EIPs for technical soundness, correct spelling/grammar, and code style. Martin Becze, Vitalik Buterin, Gavin Wood, and a few others were the original EIP editors from 2015 to late 2016. The current EIP editors are:

* Alex Beregszaszi \(EWASM/Ethereum Foundation\)
* Greg Colvin \(Community\)
* Casey Detrio \(EWASM/Ethereum Foundation\)
* Hudson James \(Ethereum Foundation\)
* Nick Johnson \(ENS\)
* Nick Savers \(Community\)

