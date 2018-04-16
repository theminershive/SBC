SBC development tree

SBC is a PoS-based cryptocurrency.

SBC is dependent upon libsecp256k1 by sipa, the sources for which can be found here:
https://github.com/bitcoin/secp256k1

Block Spacing: 60 Seconds
Diff Retarget: 4 Blocks
Maturity: 30 Blocks
Stake Minimum Age: 1 Hours

40 MegaByte Maximum Block Size (40X Bitcoin Core)
PoS Proof of stake begins: 1440 block
Port: 10000
RPC Port: 10001

Magic Bytes: 0x1a 0x26 0x01 0x3c

SBC includes an Address Index feature, based on the address index API (searchrawtransactions RPC command) implemented in Bitcoin Core but modified implementation to work with the SBC codebase (PoS coins maintain a txindex by default for instance).

Initialize the Address Index By Running with -reindexaddr Command Line Argument.  It may take 10-15 minutes to build the initial index.
