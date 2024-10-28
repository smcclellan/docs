## Introduction to sBTC

sBTC is a SIP-010 token on the Stacks blockchain that represents Bitcoin (BTC) in a 1:1 ratio. It enables Bitcoin holders to participate in DeFi applications and other smart contract functionalities while maintaining a peg to the underlying Bitcoin.

### Purpose

The primary purpose of sBTC is to bridge Bitcoin to DeFi via the Stacks blockchain, providing Bitcoin holders with access to the rich functionality of smart contracts without sacrificing the security and value of their BTC holdings.

### Key Benefits

1. **Bitcoin Compatibility**: Allows Bitcoin holders to participate in the Stacks ecosystem without selling their BTC.
2. **DeFi Access**: Enables BTC holders to participate in DeFi.
3. **Quick Conversions**: Facilitates rapid movement between BTC and sBTC.
4. **Decentralized Management**: Utilizes a set of signers for maintaining the peg wallet.
5. **Community Governance**: Involves the community in key decisions, such as selecting the initial signing set.

## Key Concepts

Understanding sBTC requires familiarity with several key concepts.

### sBTC

sBTC is a SIP-010 token on the Stacks Blockchain that can be converted back to BTC on the Bitcoin Blockchain. The key property of sBTC is its 1:1 peg to Bitcoin, meaning 1 sBTC is always equivalent to 1 BTC.

### sBTC UTXO

The sBTC UTXO is the single unspent transaction output (UTXO) on the Bitcoin blockchain that holds the entire BTC balance pegged into sBTC. This UTXO is managed and maintained by the sBTC Signers.

### sBTC Signer

In sBTC, the sBTC Signer is a signer entity separate from the Stacks Nakamoto signer. sBTC signer responsibilities include:

- Signing sBTC operations
- Communicating with contracts on the Stacks chain
- Managing the sBTC UTXO

### sBTC Signer Set

The sBTC Signer Set is the group of all sBTC signers. This set has full democratic access to the sBTC UTXO. Key properties include:

- Selected through a community vote weighted by STX holdings
- Responsible for maintaining the security of the peg wallet
- Ability to rotate their private keys for enhanced security

### Emily API

Emily is an API that helps facilitate and supervise the sBTC Bridge in addition to serving as a programmatic liaison between sBTC users and signers.

### SIP-010 Token

sBTC adheres to the SIP-010 standard for fungible tokens on the Stacks blockchain. This ensures compatibility with wallets and applications that support the SIP-010 standard.

Understanding these concepts is crucial for grasping the overall architecture and functionality of sBTC. In the following sections, we'll explore how these concepts come together to create sBTC.
