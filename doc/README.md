Litecoin Core
Setup
Litecoin Core is the original Litecoin client and it builds the backbone of the network. It downloads and, by default, stores the entire history of Litecoin transactions, which requires approximately 22 gigabytes of disk space. Depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Litecoin Core, visit litecoin.org.

Running
The following are some helpful notes on how to run Litecoin Core on your native platform.

Unix
Unpack the files into a directory and run:

bin/litecoin-qt (GUI) or
bin/litecoind (headless)
Windows
Unpack the files into a directory, and then run litecoin-qt.exe.

macOS
Drag Litecoin Core to your applications folder, and then run Litecoin Core.

Need Help?
See the documentation at the Litecoin Wiki for help and more information.
Ask for help on #litecoin on Freenode. If you don't have an IRC client use webchat here.
Ask for help on the LitecoinTalk forums, in the Technical Support section.
Building
The following are developer notes on how to build Litecoin Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

Dependencies
macOS Build Notes
Unix Build Notes
Windows Build Notes
FreeBSD Build Notes
OpenBSD Build Notes
NetBSD Build Notes
Gitian Building Guide (External Link)
Development
The Litecoin repo's root README contains relevant information on the development process and automated testing.

Developer Notes
Productivity Notes
Release Notes
Release Process
Translation Process
Translation Strings Policy
JSON-RPC Interface
Unauthenticated REST Interface
Shared Libraries
BIPS
Dnsseed Policy
Benchmarking
Resources
Discuss on the LitecoinTalk forums.
Discuss general Litecoin development on #litecoin-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=litecoin-dev.
Miscellaneous
Assets Attribution
bitcoin.conf Configuration File
Files
Fuzz-testing
Reduce Traffic
Tor Support
Init Scripts (systemd/upstart/openrc)
ZMQ
PSBT support
License
Distributed under the MIT software license. This product includes software developed by the OpenSSL Project for use in the OpenSSL Toolkit. This product includes cryptographic software written by Eric Young (eay@cryptsoft.com), and UPnP software written by Thomas Bernard.
