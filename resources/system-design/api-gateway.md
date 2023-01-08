# API Gateway

<figure><img src="../../.gitbook/assets/Vaults (2).png" alt=""><figcaption></figcaption></figure>

The API Gateway is arguably the most centralized component in the Fortress stack because it is run by independent contributors in order to enhance the user experience. The user experience is enhanced using the API Gateway because it is supposed to act as transparent Caching Layer. Static information like Vault TVLs and Vault APYs are periodically refreshed and cached in order to deliver Vault specific information to the Web Client. All information provided by this transparent Caching Layer is essentially available on-chain, with the difference that querying all of the relevant data on-chain takes considerably more time that retrieving said data from the transparent Caching Layer. The goal of the Fortress protocol is to still be operational even without this centralized API Gateway.&#x20;
