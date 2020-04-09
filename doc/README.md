Cureoptedcoin Core
=============

Setup
---------------------
Cureoptedcoin Core is the original Cureoptedcoin client and it builds the backbone of the network. It downloads and, by default, stores the entire history of Cureoptedcoin transactions, which requires approximately 22 gigabytes of disk space. Depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Cureoptedcoin Core, visit [cureoptedcoin.org](https://cureoptedcoin.org/).

Running
---------------------
The following are some helpful notes on how to run Cureoptedcoin Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/cureoptedcoin-qt` (GUI) or
- `bin/cureoptedcoind` (headless)

### Windows

Unpack the files into a directory, and then run cureoptedcoin-qt.exe.

### macOS

Drag Cureoptedcoin Core to your applications folder, and then run Cureoptedcoin Core.

### Need Help?

* See the documentation at the [Cureoptedcoin Wiki](https://cureoptedcoin.info/)
for help and more information.
* Ask for help on [#cureoptedcoin](http://webchat.freenode.net?channels=cureoptedcoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=cureoptedcoin).
* Ask for help on the [CureoptedcoinTalk](https://cureoptedcointalk.io/) forums, in the [Technical Support section](https://cureoptedcointalk.io/c/technical-support).

Building
---------------------
The following are developer notes on how to build Cureoptedcoin Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [FreeBSD Build Notes](build-freebsd.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [NetBSD Build Notes](build-netbsd.md)
- [Gitian Building Guide (External Link)](https://github.com/bitcoin-core/docs/blob/master/gitian-building.md)

Development
---------------------
The Cureoptedcoin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Productivity Notes](productivity.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [JSON-RPC Interface](JSON-RPC-interface.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [CureoptedcoinTalk](https://cureoptedcointalk.io/) forums.
* Discuss general Cureoptedcoin development on #cureoptedcoin-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=cureoptedcoin-dev.

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [bitcoin.conf Configuration File](bitcoin-conf.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)
- [PSBT support](psbt.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
