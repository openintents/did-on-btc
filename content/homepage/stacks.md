---
title: "Stacks"
weight: 3
header_menu: true
---

The Stacks blockchain is a blockchain that recycles Proof-of-Work's security of the Bitcoin network. The consensus algorithm is Proof of Tranfer (PoX)

---

## PoX Mining

Blocks on the Stacks chain are minted by miners. Each miner transfers a certain amount of BTCs of a predefined BTC address. Their chance to win the next block reward (in Stacks tokens) is proportional to their commit.

Blocks on Stacks are built by all miners at the same time. The block hash is written to the BTC blockchain during the transfer transaction. Only the block of the winning miner is the next block under the assumption that the block is valid. If the miner created an invalid block the fork is discarded, the miner does not receive a reward.

---

## PoX Stacking

Owners of STX tokens can participate in PoX consensus by locking their Stacks token (stacking). During locking they signal support for the current longest chain. As a reward, the stackers' BTC addresses are selected as receiver addresses for the miners. Two addresses per block. The set of valid addresses is changed every 2100 Bitcoin blocks (around 2 weeks).

---

## Smart Contracts

The Stacks chain comes with a virtual machine to run smart contracts. These contracts are written in Clarity, a non-turing complete Lisp-like programming language made for more secure smart contracts.

---

Want to learn more about my Stacks?

Check out [documentation](https://docs.stacks.co) and join the [Stacks discord](https://discord.gg/YWa8BmKqvR).
