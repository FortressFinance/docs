# Compounders

Fortress auto-compounders (Compounders) are ERC-4626 vaults that use certain
farming strategies to provide the user with maximum exposure to vault assets.
Maximum exposure has to be well understood by the user in order to assess risk
properties of the chosen investment strategy when depositing into a vault.

Compounders claim their strategy rewards periodically and swap their reward
tokens into more of their own vault assets, which are then re-invested back into
the vault itself. That is how Compounders maximize exposure, and thus yield, to
a vault's asset.

Compounders mint ERC20 vault shares (fortTokens) for users upon deposits. In
turn, Compounders burn these vault shares again upon withdrawals. Vault shares
simply represent receipts to the auto-compounding vault assets that are managed
by the vaults. Vault shares increase in value at every compounding event, as
more of the vault assets accumulate, while the amount of vault shares remain
unchanged.

Users may chose to utilize fortTokens in different DeFi Protocols or Fortress
Strategies for additional capital efficiency.
