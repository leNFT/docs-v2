# Genesis Mint

## How does it work?

The Genesis Mint is an exclusive collection of non-fungible tokens (NFTs) that commemorates the launch of the Genesis NFT protocol. Limited to just 1337 tokens, each NFT can be minted for a price of 0.25 ETH.

When a user mints a Genesis NFT, they have the option to choose a locktime duration between 21 and 180 days. The protocol then pairs 0.1 ETH with 40000 LE tokens and deposits all the tokens  into a [LE/ETH trading pool](https://app.balancer.fi/#/ethereum/pool/0x8e6c196e201942246cef85718c5d3a5622518053000200000000000000000582). After the lockup period, the Genesis NFT can be burned and the liquidity position withdrawn. If the withdrawal amount is higher than 40000 LE the user will receive WITHDRAWAL\_AMOUNT - 40000 LE tokens, if the withdrawal amount is smaller than 40000 LE the burn won't yield any LE.\
The remaining 0.15 ETH is reserved for protocol development costs. \
The Genesis NFT itself is always transferable between different users.

Additionally, users who mint a Genesis NFT are also rewarded with LE tokens, which are given in the form of veLE tokens locked for the chosen locktime. These tokens represent a share of protocol revenue and can also be used to vote for gauges that distribute inflation within the ecosystem. LE tokens are distributed according to the following formula:

$$
reward= \frac{locktime * (1337 - \frac{minted}{2})}{400000}\hspace{2mm}LE
$$

The locktime is in seconds and 'minted' is the number of Genesis NFTs already minted.

## What can I do with my Genesis NFT?

* Pair it with ETH and provide liquidity in the Genesis NFT / ETH trading pool. Then stake the LP token you received in the pool's gauge for extra LE rewards.
* Use it to join the exclusive areas of our Discord.

## What can I do with my LE tokens?

* Lock them for up to 4 years to get a share of the protocol's earnings and LE rebates
* Direct the LE inflation to different gauges by voting
* Trade them on the balancer pool
