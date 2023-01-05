# MultiSigs

Fortress uses 3 dedicated multi signature wallets to decentralize access and ownership of various aspects within the protocol. These multi signature wallets are bootstrapped via as [Gnosis Safes](https://app.safe.global) and signed by various independent contributors upon consensus making.

The setup of signer wallets required the use of fresh addresses on hard wallets to ensure separation of concerns and information security best practices. The list of current signers of every multi signature wallet can be read following the given Blockchain Explorer links. Under the tab `Read as Proxy` the method `getOwners` returns the current list of signers. Further, the method `getThreshold` returns the currently required quorum for signing transactions.
