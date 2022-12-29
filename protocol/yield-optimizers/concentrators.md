# Concentrators

Fortress auto-concentrators (Concentrators) are ERC-4626 vaults that use certain
farming strategies to provide the user with minimum exposure to reward tokens. 

Concentrators claim their strategy rewards periodically and swap their reward
tokens into target assets, which are then invested into vaults that provide risk
profiles different from the originating vault. That is how Concentrators
minimize exposure to reward tokens, by not holding on to them, but repurposing
their economic value immediately.

Concentrators mint ERC20 vault shares (fortTokens) for users upon deposits. In
turn, Concentrators burn these vault shares again upon withdrawals. Vault shares
simply represent receipts to the auto-compounding vault assets that are managed
by the vaults. Vault shares increase in value at every compounding event, as
more of the vault assets accumulate, while the amount of vault shares remain
unchanged.

Users may chose to utilize fortTokens in different DeFi Protocols or Fortress
Strategies for additional capital efficiency.
