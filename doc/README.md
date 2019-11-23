GlobalMovementClub Core 0.7.7
=====================

This is the official reference wallet for GlobalMovementClub digital currency and comprises the backbone of the GlobalMovementClub peer-to-peer network. You can [download GlobalMovementClub Core](https://globalmovement.club/downloads/) or [build it yourself](#building) using the guides below.

Running
---------------------
The following are some helpful notes on how to run GlobalMovementClub on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/globalmovementclub-qt` (GUI) or
- `bin/gmcd` (headless)

### Windows

Unpack the files into a directory, and then run globalmovementclub-qt.exe.

### OS X

Drag GlobalMovementClub-Qt to your applications folder, and then run GlobalMovementClub-Qt.

Building
---------------------
The following are developer notes on how to build GlobalMovementClub Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The GlobalMovementClub Core repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- Source Code Documentation ***TODO***
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Resources
* Discuss on the [GlobalMovementClubTalk](https://globalmovementclubtalk.org/) forums, in the Development & Technical Discussion board.
* Discuss on [#globalmovementclub](http://webchat.freenode.net/?channels=globalmovementclub) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=globalmovementclub).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
