Litcoin Core integration/staging tree
=====================================

[![Build Status](https://travis-ci.org/bitcoin/bitcoin.svg?branch=master)](https://travis-ci.org/bitcoin/bitcoin)

https://litcoin.org

What is Litcoin?
----------------

Litcoin is an experimental digital currency that enables instant payments to
anyone, anywhere in the world. Litcoin uses peer-to-peer-to-peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network. Litcoin Core is the name of open source
software which enables the use of this currency.

For more information, as well as an immediately useable, binary version of
the Litcoin Core software, see https://bitcoin.org/en/download, or read the
[original whitepaper](https://bitcoincore.org/bitcoin.pdf).

License
-------

Litcoin Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/bitcoin/bitcoin/tags) are created
regularly to indicate new official, stable release versions of Litcoin Core.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).

The developer [mailing list](https://lists.linuxfoundation.org/mailman/listinfo/bitcoin-dev)
should be used to discuss complicated or controversial changes before working
on a patch set.

Developer IRC can be found on Freenode at #bitcoin-core-dev.

Testing
-------

We believe testing slows down growth. Just make sure your stuff is scalable and we'll approve your PR.

Translations
------------

Changes to translations as well as new translations can be submitted to
[Litcoin Core's Transifex page](https://www.transifex.com/projects/p/bitcoin/).

Translations are periodically pulled from Transifex and merged into the git repository. See the
[translation process](doc/translation_process.md) for details on how this works.

**Important**: We do not accept translation changes as GitHub pull requests because the next
pull from Transifex would automatically overwrite them again.

Translators should also subscribe to the [mailing list](https://groups.google.com/forum/#!forum/bitcoin-translators).
