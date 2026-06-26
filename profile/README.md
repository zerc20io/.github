<p align="center">
  <img src="https://framerusercontent.com/images/IxSVugRu0p9cwJZEDq0j5uDoMk.svg?width=1277&height=220" width="96" alt="zERC20 logo">
</p>

<h1 align="center">zERC20</h1>

<p align="center">
  <strong>Private ERC-20 transfers with the wallets people already use.</strong>
</p>

<p align="center">
  <a href="https://zerc20.io">Website</a>
  ·
  <a href="https://zerc20.gitbook.io/zerc20">Docs</a>
  ·
  <a href="https://app.zerc20.io">App</a>
  ·
  <a href="https://ethereum-magicians.org/t/zerc20-cross-chain-private-erc-20-based-on-zk-proof-of-burn/26452">Technical paper</a>
</p>

---

zERC20 is building a fully ERC-20 compatible private transfer protocol. Users can send tokens privately from standard Ethereum wallets like MetaMask, without requiring a dedicated privacy wallet or a separate deposit-only UX.

The protocol uses zero-knowledge proof-of-burn mechanics inspired by EIP-7503 / zk-Wormhole. A sender transfers tokens to a cryptographically generated burn address, and the recipient later withdraws the equivalent amount with a zero-knowledge proof, without revealing the link between the send and receive addresses on-chain.

## What we are building

| Area | Focus |
| --- | --- |
| Wallet-native privacy | Private transfers through familiar ERC-20 operations |
| Cross-chain support | Private movement across supported EVM networks |
| Developer integration | SDKs, contracts, circuits, and frontend tooling |
| Practical UX | No special wallet required for everyday private transfers |

## Start here

- Try the app: [app.zerc20.io](https://app.zerc20.io)
- Read the docs: [zerc20.gitbook.io/zerc20](https://zerc20.gitbook.io/zerc20)
- Learn the design: [Cross-Chain Private ERC-20 Based on ZK Proof-of-Burn](https://ethereum-magicians.org/t/zerc20-cross-chain-private-erc-20-based-on-zk-proof-of-burn/26452)
- Visit the website: [zerc20.io](https://zerc20.io)

## For developers

zERC20 is designed to preserve the ERC-20 developer experience while adding private transfer capability. Integration work focuses on standard wallet flows, proof generation, cross-chain transfer support, and application-level tooling for products that need privacy without forcing users into a separate wallet stack.

---

<p align="center">
  <strong>Make your everyday tokens private.</strong>
</p>
