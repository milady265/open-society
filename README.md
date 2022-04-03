# open-society
Smart contracts for governments
# open-society

Where I try to figure out how nation states can use crypto productively, since it seems they aren't going to figure it out on their own. 

## Design Space


- Countries vs rollups?


## Assumptions

- Ethereum wins out and becomes the dominant global blockchain
- There are not multiple winners. Naturally, a single security domain is selected for. EIP-1559-like mechanisms cause everyone to consense around a single smart contract platform. 
- The modular blockchain thesis is roughly true. We _at least_ distinguish between 3 layers: data availability, consensus, and execution. Maybe there are more by then. I'm not sure what the data layer looks like yet. 
- Ethereum sits in the middle of the stack as the consensus layer. It exists in PoS form and does not contain sharding in-protocol. 
- Only rollups settle on Ethereum at this point. There are rollups for specialized usecases (e.g high-frequency-trading) as well as for particular countries. Each country runs their own rollup. 
- Fiat dies out simply because it gets outcompeted

## Vision

- There is no such thing as being a citizen of a particular country. Everyone is a citizen (of the world) by default. This becomes a widespread belief people take for granted, akin to how we think of the right to free speech and bodily autonomy today. 
- All citizens have the ability to run a light client from their phones that validates the state transitions of both Ethereum as well as their local country's rollup. 
- A country that chooses to arrange its society along these lines is considered *open*. 
- Access to Ethereum serves as a schelling fence that allows individuals to easily know when the reigns have shifted into authoritarianism. 
- I'm not sure what happens if a country goes authoritarian and tries to lock citizens in using force. 
- You can think of the role of the country as projecting the state of its rollup into physical space

## Economics

- ETH staking sets the new risk-free rate. The risk-free rate is no longer tied to any particular country
- Without fiat, countries are forced to be net value-producing
- ...

## Mechanisms

### Real Estate Harberger-NFTs (HNFT)

The government issues Harberger-NFTs for each property they recognize within their jurisdiction. The holder of the HNFT is entitled to live at the property. An HNFT is always on sale. 
- Holder has sole right to set `valuation` at any time
- Anyone can purchase the HNFT at anytime at `valuation + (1 + dislocationPreventionFactor)`
- Anyone can place an offer for the HNFT between `valuation` and `valuation + (1 + dislocationPreventionFactor)`, but the holder does not have to choose to accept
- Sales of the HNFT incur a tax of `saleTaxRate` 
- Holder accrues a tax obligation per unit time based on `valuation * propertyTaxRate`


Gov params
- `dislocationPreventionFactor`: (10%) a % set by each government that determines how much to add onto sales in order to compensate the holder for dislocation 
- `saleTaxRate`: (1%) a % set by each government that determines the government's share of each sale  
- `propertyTaxRate`: (5%) a % set by each government that determines the government's rent extraction annually

## 
