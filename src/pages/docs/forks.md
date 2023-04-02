---
title: "Fork Networks"
description: "How to use fork networks"
layout: "@layouts/DocsLayout.astro"
---

### Fork Networks

Tantheta provides a fork network to help you test your smart contracts. You can use  use these network RPCs to
 - Test your smart contracts
 - Build Preview dApps for your smart contracts
 - Beta test your smart contracts & dApps


### How to use fork networks

Once you have created a API key from your <a href="https://app.tantheta.dev/forks/" target="_blank">App</a>, you can use the RPCs provided connect to the fork network.

The RPCs are provided in the following format:

```bash
https://forks.tantheta.dev/<network>/<apiKey>
```


### Supported Networks

Tantheta currently only supports the Forking of **Ethereum Mainnet**. We are working on adding support for other networks.

### Limitations

- These Free Fork Networks are limited to 15 requests per second.
- Fork Resets every 1 hour. to keep the fork network up to date with the latest block.
  

### Understanding Forks

We use Hardhat to create fork networks, Hardhat is a popular Ethereum development environment that provides a suite of tools for building, testing, and deploying smart contracts on the Ethereum network. One of its key features is the ability to create forks of the Ethereum mainnet, which allows developers to work on their contracts in an isolated environment without having to worry about the effects of their work on the real Ethereum network.

Here are some common use cases for forks of the Ethereum mainnet:

1. Development and testing: Tantheta forks provide a safe and secure environment for developers to test their smart contracts and applications without affecting the real Ethereum network. This is especially important for complex contracts that could have unintended consequences if deployed on the mainnet.

2. Debugging: If a smart contract is failing in some way, developers can use a Tantheta fork to isolate the issue and debug it.

3. Contract upgrades: Upgrading a smart contract on the Ethereum mainnet can be a complex and risky process. By using a Tantheta fork, developers can test their upgrades and make sure they are working as expected before deploying them to the mainnet.

4. Contract experimentation: Tantheta forks allow developers to experiment with new contract designs and features without having to worry about the cost or risks associated with deploying them on the mainnet.