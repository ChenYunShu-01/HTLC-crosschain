# HTLC-crosschain
Hash TimeLock Contract(HTLC) is a Layer2 cross-chain solution applied widely. The atomic swap happens between 2 EVM compatible blockchains without any custodian and oracle. 

The HTLC.sol has been deployed respectively on BSC testnet by Bob and Ropsten testnet by Alice. Each contract locks amount of tokens. Bob can withdraw token locked by Alice on BSC testnet with a secret, and Alice can withdraw token locked by Bob on Ropsten testnet with the same secret.

If the locked token is not withdrawn and the lock time is exceeded, the owner can refund the locked token.
