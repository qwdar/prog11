Micoin Core
=============

Setup
---------------------
Micoin Core is the original Micoin client and it builds the backbone of the network. It downloads and, by default, stores the entire history of Micoin transactions, which requires approximately 22 gigabytes of disk space. Depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Micoin Core, visit [micoin.org](https://micoin.org/).

Running
---------------------
The following are some helpful notes on how to run Micoin Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/micoin-qt` (GUI) or
- `bin/micoind` (headless)

### Windows

Unpack the files into a directory, and then run micoin-qt.exe.

### macOS

Drag Micoin Core to your applications folder, and then run Micoin Core.

### Need Help?

* See the documentation at the [Micoin Wiki](https://micoin.info/)
for help and more information.
* Ask for help on [#micoin](http://webchat.freenode.net?channels=micoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=micoin).
* Ask for help on the [MicoinTalk](https://micointalk.io/) forums, in the [Technical Support section](https://micointalk.io/c/technical-support).

Building
---------------------
The following are developer notes on how to build Micoin Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

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
The Micoin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Productivity Notes](productivity.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [JSON-RPC Interface](JSON-RPC-interface.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [MicoinTalk](https://micointalk.io/) forums.
* Discuss general Micoin development on #micoin-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=micoin-dev.

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
