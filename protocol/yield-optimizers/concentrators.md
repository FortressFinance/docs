# Concentrators

Fortress auto-concentrators (Concentrators) are ERC-4626 vaults that use certain
farming strategies to provide the user with minimum exposure to vault assets. 

Concentrators claim their strategy rewards periodically and swap their reward
tokens into target assets, which are then invested into vaults that provide risk
profiles different from the originating vault. That is how Concentrators
leverage the investment attributes of the principal, while not leaving the
entire position exposed to the risks of the initial investment.

Concentrators mint ERC20 vault shares (fortTokens) for users upon deposits. In
turn, Concentrators burn these vault shares again upon withdrawals. Vault shares
represent pro-rata claims on vault assets deposited. The value of vault shares
is always equal to the value of vault assets, as reward tokens are invested into
other vaults, the vault assets to vault shares ratio remains unchanged. While
holding vault shares, holders accumulate rewards. All accrued rewards can be
claimed at any time, even if vault shares are not owned anymore. In other words,
users can claim rewards that already accrued, even if further rewards are not
accruing anymore.

Users may chose to utilize fortTokens in different DeFi Protocols or Fortress
Strategies for additional capital efficiency.
