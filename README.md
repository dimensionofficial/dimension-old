
# Dimension - The Most Powerful Infrastructure for Decentralized Applications

[![Build status](https://badge.buildkite.com/370fe5c79410f7d695e4e34c500b4e86e3ac021c6b1f739e20.svg?branch=master)](https://buildkite.com/Dimension/dimension)

Welcome to the Dimension source code repository! This software enables businesses to rapidly build and deploy high-performance and high-security blockchain-based applications.

Some of the groundbreaking features of dimension include:

1. Free Rate Limited Transactions
1. Low Latency Block confirmation (0.5 seconds)
1. Low-overhead Byzantine Fault Tolerant Finality
1. Designed for optional high-overhead, low-latency BFT finality
1. Smart contract platform powered by WebAssembly
1. Designed for Sparse Header Light Client Validation
1. Scheduled Recurring Transactions
1. Time Delay Security
1. Hierarchical Role Based Permissions
1. Support for Biometric Hardware Secured Keys (e.g. Apple Secure Enclave)
1. Designed for Parallel Execution of Context Free Validation Logic
1. Designed for Inter Blockchain Communication

Dimension is released under the open source MIT license and is offered “AS IS” without warranty of any kind, express or implied. Any security provided by the Dimension software depends in part on how it is used, configured, and deployed. Dimension is built upon many third-party libraries such as WABT (Apache License) and WAVM (BSD 3-clause) which are also provided “AS IS” without warranty of any kind. Without limiting the generality of the foregoing, Block.one makes no representation or guarantee that Dimension or any third-party libraries will perform as intended or will be free of errors, bugs or faulty code. Both may fail in large or small ways that could completely or partially limit functionality or compromise computer systems. If you use or implement Dimension, you do so at your own risk. In no event will Block.one be liable to any party for any damages whatsoever, even if it had been advised of the possibility of damage.  

Block.one is neither launching nor operating any initial public blockchains based upon the Dimension software. This release refers only to version 1.0 of our open source software. We caution those who wish to use blockchains built on Dimension to carefully vet the companies and organizations launching blockchains based on Dimension before disclosing any private keys to their derivative software.

There is no public testnet running currently.

**If you have previously installed Dimension, please run the `

io_uninstall` script (it is in the directory where you cloned Dimension) before downloading and using the binary releases.**


#### Ubuntu 18.04 Debian Package Install
```sh
$ wget https://github.com/dimensionofficial/dimension/releases/download/v1.7.0/dimension_1.7.0-1-ubuntu-18.04_amd64.deb
$ sudo apt install ./dimension_1.7.0-1-ubuntu-18.04_amd64.deb
```
#### Ubuntu 16.04 Debian Package Install
```sh
$ wget https://github.com/dimensionofficial/dimension/releases/download/v1.7.0/dimension_1.7.0-1-ubuntu-16.04_amd64.deb
$ sudo apt install ./dimension_1.7.0-1-ubuntu-16.04_amd64.deb
```
#### Debian Package Uninstall
```sh
$ sudo apt remove dimension
```
#### Centos RPM Package Install
```sh
$ wget https://github.com/dimensionofficial/dimension/releases/download/v1.7.0/dimension-1.7.0-1.el7.x86_64.rpm
$ sudo yum install ./dimension-1.7.0-1.el7.x86_64.rpm
```
#### Centos RPM Package Uninstall
```sh
$ sudo yum remove dimension.cdt
```

#### Fedora RPM Package Uninstall
```sh
$ sudo yum remove dimension.cdt
```

## Supported Operating Systems
Dimension currently supports the following operating systems:  
1. Amazon 2017.09 and higher
2. Centos 7
3. Fedora 25 and higher (Fedora 27 recommended)
4. Mint 18
5. Ubuntu 16.04 (Ubuntu 16.10 recommended)
6. Ubuntu 18.04
7. MacOS Darwin 10.12 and higher (MacOS 10.13.x recommended)

## Resources
1. [Website](https://github.com/dimensionofficial/dimension)
1. [Blog](https://github.com/dimensionofficial/dimension)
1. [Developer Portal](https://github.com/dimensionofficial/dimension)
1. [StackExchange for Q&A](https://github.com/dimensionofficial/dimension)
1. [Community Telegram Group](https://github.com/dimensionofficial/dimension)
1. [Developer Telegram Group](https://github.com/dimensionofficial/dimension)
1. [White Paper](https://github.com/dimensionofficial/dimension)
1. [Roadmap](https://github.com/dimensionofficial/dimension)

<a name="gettingstarted"></a>
## Getting Started
Instructions detailing the process of getting the software, building it, running a simple test network that produces blocks, account creation and uploading a sample contract to the blockchain can be found in [Getting Started](https://dimensionofficial.dimension.io/dimension-home/docs) on the [Dimension Developer Portal](https://developers.dimension.io).
