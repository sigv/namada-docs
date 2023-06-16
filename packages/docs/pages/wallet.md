# Namada Wallet Guide

This document describes the different wallet concepts and options that are available to users of Namada who want to be able to [send, receive and interact](../users/send-and-receive-nam-tokens.md) with NAM tokens on the Namada blockchain.

## A brief introduction to the Namada wallet
The purpose of the Namada wallet is to provide a user-interface to store and manage both keys and addresses. [Technically speaking](https://vitalik.ca/general/2017/01/14/exploring_ecp.html), keys are just(potentially) very large integers that have some meaning on an eliptic curve. The wallet simply "remembers" these very large numbers on your behalf. Keys are the fundamental building blocks for accounts on Namada. Keys come in the form of *pairs* (secret and public), and can be used to derive the **account address** (first 40 chars of the SHA256 hash of the public key).

To read more about addresses see [An introduction to Namada addresses](../users/an-introduction-to-namada-addresses.md).

## The wallet options on Namada

Check out the different options to generate a wallet:

- [File System Wallet](./file-system-wallet.md)
- [Web Wallet](./web-wallet.md)
- [Hardware Wallet](./hardware-wallet.md)