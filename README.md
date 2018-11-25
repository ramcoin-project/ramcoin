Ramcoin integration/staging tree
================================

http://www.ramcoinmining.org

Copyright (c) 2009-2018 Bitcoin Developers

Copyright (c) 2017-2018 Ramcoin Developers

What is Ramcoin?
----------------

Ramcoin is an experimental digital currency that enables instant payments to anyone, anywhere in the world. 
Ramcoin uses peer-to-peer technology to operate with no central authority: managing transactions and issuing money are carried out collectively by the network. 
Ramcoin is the name of open source software which enables the use of this currency.

Ramcoin uses scrypt as a proof-of-work algorithm.
 - 2.5 minute block targets
 - subsidy halves in 840k blocks (~4 years)
 - ~84 million total coins

The rest is the same as Bitcoin.
 - 50 coins per block
 - 2016 blocks to retarget difficulty

For more information, as well as an immediately useable, binary version of
the Ramcoin client sofware, see http://www.ramcoinmining.org.

License
-------

Ramcoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the Ramcoin
development team members simply pulls it.

If it is a *more complicated or potentially controversial* change, then the patch
submitter will be asked to start a discussion with the devs and community.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/ramcoin-project/ramcoin/tags) are created
regularly to indicate new official, stable release versions of Ramcoin.

