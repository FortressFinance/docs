# Managed Vaults

The Managed Vaults architecture provides permissionless primitives for flexible investment strategy management on-chain. Anyone can deploy and manage investment strategies on-chain via the Fortress Managed Vaults interface. Below we clarify architectural concepts to better understand the Managed Vaults design.

### Vault Manager

Vault Managers are independent operators running on-chain investment strategies for profit. Vault Managers are required to deposit a certain amount of collateral and are incentivized to act honestly, since unreliable or dishonest behaviour may be subject to collateral liquidation. Collateral must be denominated in the meta vault's primary asset. This is the asset users deposit and therefore creates alignment between depositors and vault managers.

### Meta Vault

A Meta Vault contract is owned and operated by a Vault Manager and contains specific Asset Vaults and Strategy Vaults. Meta Vaults have primary assets which act as deposit assets and unit of account so that the Meta Vault PnL is measured in the Meta Vault's primary asset.&#x20;

### Asset Vault

Asset Vaults contain specific tokens that are allowed to be used by Strategy Vaults. The Vault Manager adds Asset Vaults to their Meta Vault depending on the desired investment strategy they want to manage on-chain.

### Strategy Vault

Strategy Vaults define the on-chain investment strategy operated by the Vault Manager. Strategy Vaults receive the tokens provided by the attached Asset Vaults. Said tokens fund the underlying investment strategy within the Strategy Vaults until they eventually flow back as PnL into their respective Meta Vaults.
