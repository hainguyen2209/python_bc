# python_bc
A blockchain is a growing list of records, called blocks, that are linked using cryptography.Each block contains a cryptographic hash of the previous block, a timestamp, and transaction data (generally represented as a Merkle tree). By design, a blockchain is resistant to modification of its data. This is because once recorded, the data in any given block cannot be altered retroactively without alteration of all subsequent blocks.

For use as a distributed ledger, a blockchain is typically managed by a peer-to-peer network collectively adhering to a protocol for inter-node communication and validating new blocks. Although blockchain records are not unalterable, blockchains may be considered secure by design and exemplify a distributed computing system with high Byzantine fault tolerance. The blockchain has been described as "an open, distributed ledger that can record transactions between two parties efficiently and in a verifiable and permanent way".

The blockchain was invented by a person (or group of people) using the name Satoshi Nakamoto in 2008 to serve as the public transaction ledger of the cryptocurrency bitcoin. The identity of Satoshi Nakamoto remains unknown to date. The invention of the blockchain for bitcoin made it the first digital currency to solve the double-spending problem without the need of a trusted authority or central server. The bitcoin design has inspired other applications and blockchains that are readable by the public and are widely used by cryptocurrencies. The blockchain is considered a type of payment rail. Private blockchains have been proposed for business use but Computerworld called the marketing of such privatized blockchains without a proper security model "snake oil".However, others have argued that permissioned blockchains, if carefully designed, may be more decentralized and therefore secure in practice than permissionless ones.

Dependencies:

    Python 3.x
    Flask & Flask_cors: https://flask.palletsprojects.com/en/1.1.x/installation/#install-install-virtualenv
    Pycrypto: pip install pycrypto
    Binascii: https://flask.palletsprojects.com/en/1.1.x/
