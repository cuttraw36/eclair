![Eclair Logo](.readme/logo.png)

[![Build Status](https://travis-ci.org/ACINQ/eclair.svg?branch=master)](https://travis-ci.org/ACINQ/eclair)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)
[![Gitter chat](https://img.shields.io/badge/chat-on%20gitter-rose.svg)](https://gitter.im/ACINQ/eclair)

**Eclair** (french for Lightning) is a scala implementation of the Lightning Network. This software follows the [Lightning Network Specifications (BOLTs)](https://github.com/lightningnetwork/lightning-rfc). Other implementations include [c-lightning], [lit], and [lnd].

### Status

- [X] Compliant with the Lightning Network specifications (BOLTS)
- [X] Works with Bitcoin Core 0.14+
- [X] Docker builds on [Docker Hub](https://hub.docker.com/r/acinq/eclair/builds/)
- [X] Optional GUI (see [screenshot](https://raw.githubusercontent.com/ACINQ/eclair/clean-readme/.readme/screen-1.png))
- [X] JSON-RPC API
- [X] Available on [Android](https://play.google.com/store/apps/details?id=fr.acinq.eclair.wallet)
- [ ] Mainnet
 
 ---
 
 :construction: Both the BOLTs and Eclair itself are a work in progress. Expect things to break/change!
  
 :rotating_light: We had reports of Eclair being tested on various segwit-enabled blockchains. Keep in mind that Eclair is still alpha quality software, by using it with actual coins you are putting your funds at risk!

---

### Get Started

1. [Installation instructions](https://github.com/ACINQ/eclair/wiki/Install)
2. [Run eclair](https://github.com/ACINQ/eclair/wiki/Run)
3. [Configuration options](https://github.com/ACINQ/eclair/wiki/Configure)
4. [API reference](https://github.com/ACINQ/eclair/wiki/API)

### FAQ

* How do I run multiple instances of eclair on my machine?

Check [these instructions](https://github.com/ACINQ/eclair/wiki/Run#run-several-instances-of-eclair-on-the-same-host).

* Is there a docker build?

Yes, please check [BUILD.md](https://github.com/ACINQ/eclair/blob/master/BUILD.md#docker) for instructions.

### Tools

* Testnet Demonstration coffee shop at [https://starblocks.acinq.co](https://starblocks.acinq.co)
* Testnet Lightning Network explorer at [https://explorer.acinq.co](https://explorer.acinq.co)

### Resources

- [1] [The Bitcoin Lightning Network: Scalable Off-Chain Instant Payments](https://lightning.network/lightning-network-paper.pdf) by Joseph Poon and Thaddeus Dryja
- [2] [Reaching The Ground With Lightning](https://github.com/ElementsProject/lightning/raw/master/doc/deployable-lightning.pdf) by Rusty Russell
