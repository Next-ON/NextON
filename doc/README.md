NextON Core
=====================

Setup
---------------------
[NextON Core](http://nexton.io) is the original NXTON client and it builds the backbone of the network. However, it downloads and stores the entire history of NXTON transactions; depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more. Thankfully you only have to do this once.

Running
---------------------
The following are some helpful notes on how to run NXTON on your native platform.

### Unix

Unpack the files into a directory and run:

- bin/32/nxton-qt (GUI, 32-bit) or bin/32/nxtond (headless, 32-bit)
- bin/64/nxton-qt (GUI, 64-bit) or bin/64/nxtond (headless, 64-bit)

### Windows

Unpack the files into a directory, and then run nxton-qt.exe.

### OSX

Drag NXTON-Qt to your applications folder, and then run NXTON-Qt.

### Need Help?

* See the documentation at the [NXTON Wiki](https://en.bitcoin.it/wiki/Main_Page) ***TODO***
for help and more information.
* Ask for help on [BitcoinTalk](https://bitcointalk.org/index.php?topic=4391865.0;topicseen) or on the [NXTON Discord group](https://discord.gg/wMWwPaq).
* Join one of our Discord groups [NXTON Discord Groups](https://discord.gg/wMWwPaq).

Building
---------------------
The following are developer notes on how to build NXTON on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OSX Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The NXTON repo's [root README](https://github.com/Next-ON/NextON/blob/master/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Translation Process](translation_process.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Resources

* Discuss on the [BitcoinTalk](https://bitcointalk.org/index.php?topic=4391865.0;topicseen) .
* Join the [NXTON-Dev] Discord groups [NXTON Discord Groups](https://discord.gg/wMWwPaq).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT/X11 software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
