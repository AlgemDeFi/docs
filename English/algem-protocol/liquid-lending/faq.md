# FAQ

#### What is Liquid Farming?

Liquid Farming is a new product that allows users to stay liquid while farming on automated market maker (AMM) pools. It expands the concept of liquid staking, but with a focus on farming, offering new opportunities and strategies for liquidity providers.

#### How is Liquid Farming different from Liquid Staking?

Liquid staking usually involves staking tokens (e.g., ETH) to secure the network and earn rewards, whereas Liquid Farming is about providing liquidity to AMM pools and earning farming rewards. Users receive liquid tokens (lfETH) that can be used or sold before the vault expiration date.

#### What is a vault in Liquid Farming?

A vault is a smart contract that distributes rewards and mints/burns liquid tokens (lfETH). Each vault has an expiration date, after which deposits become unavailable, and lfETH holders can redeem their ETH.

#### What is vault expiration?

Vault expirations last for 4-6 months and are a preset date when a vault stops operating. When this happens:

* Deposits are no longer accepted or modified.
* lfETH holders can withdraw their ETH at a 1:1 ratio (one lfETH = one ETH).
* Users can claim their assets, including ETH (if they have lfETH), accumulated rewards, and ERC20 tokens.
* Before expiration, users can freely use their lfETH—trade it, use it as collateral, or hold it to redeem ETH later.
* After expiration, lfETH is burned upon ETH withdrawal, and users receive their base assets.

#### What is lfETH and how does it work?

lfETH is a liquid ERC20 token, unique to each vault. It represents the right to claim ETH after the vault expires and can be used in various ways before that—trading, collateral, or holding for future ETH redemption.

#### What is an ERA?

An ERA is a time unit within the vault, currently set to one day. Rewards are distributed at the start of each ERA and must be manually claimed by the user.

#### How to participate in Liquid Farming?

To participate:

* Provide ETH and an ERC20 token in a pair via the Algem interface.
* Assets are sent to an AMM and farming rewards will start accumulating.
* Upon deposit, the vault mints lfETH equal to the amount of ETH provided.

#### What assets do I need to provide?

You need to provide ETH and an ERC20 token, which together form a supported pair on an AMM.

#### How do I choose a vault?

Vaults vary by expiration date and ALGM incentive rewards. Typically, longer-term vaults offer higher incentives.

#### Can I use my lfETH before expiration?

Yes, you can:

* Add it to the ETH/lfETH pool to earn trading fees.
* Use it as collateral in lending dApps.
* Hold it until expiration.
* Sell it without affecting farming rewards.

#### What happens if I sell some lfETH?

If you sell 20 out of 100 lfETH, you will receive 80 ETH after expiration. The 20 lfETH sold will go to the withdrawal pool, available for other holders.

#### What types of rewards will I earn?

You can earn three types of rewards:

1. ALGM incentives, distributed based on your liquidity share.
2. Farming rewards from trading fees in the AMM pair.
3. Income from using lfETH, such as trading or collateralization.

#### How are ALGM incentives calculated?

ALGM rewards are calculated based on your share of liquidity relative to the total liquidity in the vault.

#### How are farming rewards distributed?

Farming rewards depend on:

* Your ETH-ERC20 liquidity share in the vault.
* Your share of ALGM in the staking pool.
* Weight parameter "a", which increases over time, making ALGM staking more influential in reward distribution.

#### What role does the ALGM staking pool play?

The ALGM staking pool allows users to stake ALGM tokens to boost their share of farming rewards. Over time, as the "a" parameter increases, this pool becomes more important for maximizing rewards.

#### How does the "a" parameter affect my rewards?

The "a" parameter starts at 0 and increases linearly with each ERA, reaching 100% by vault expiration.

* Early rewards are primarily based on liquidity share.
* Over time, ALGM staking has a larger impact on rewards.

#### What is the liquidation mechanism?

The liquidation mechanism maintains a 1:1 ratio between ETH and lfETH. If the ETH balance in the vault drops below a threshold, liquidation occurs.

#### What happens to my assets during liquidation?

During liquidation:

* The vault withdraws ETH and ERC20 from the AMM pool.
* The ERC20 token is swapped for ETH to maintain the ETH balance.
* lfETH tokens are burned in proportion to the amount of ETH recovered.

#### Are there any fees or penalties for liquidation?

No, there are no fees or penalties for liquidation.

#### How can I maximize my farming rewards?

To maximize rewards:

* Stake ALGM rewards in the staking pool.
* Since the "a" parameter increases over time, ALGM staking becomes more important for higher rewards.

#### What happens if I don’t stake ALGM in the staking pool?

If you don’t stake ALGM, you will gradually lose a portion of farming rewards, as the "a" parameter increases each ERA.

#### What can I do with my lfETH?

You can:

* Add it to the ETH/lfETH pool for trading fees.
* Use it as collateral in lending dApps.
* Hold it until expiration to redeem ETH.
* Sell it on AMM markets.

#### How does selling lfETH help with hedging?

Selling lfETH allows you to hedge against a drop in ETH price. If ETH price falls before expiration, you can profit from selling lfETH earlier (see [whitepaper](https://github.com/AlgemDeFi/White-Paper) for details).

#### What benefits do external buyers of lfETH have?

External buyers can:

* Buy lfETH at a discount compared to ETH.
* Hold lfETH until expiration to redeem ETH.
* Trade lfETH on AMMs for potential profits.

#### Can I withdraw my assets before expiration?

Yes, you can close your deposit early, receiving:

* Remaining ERC20 tokens.
* Accumulated ALGM rewards.
* Farming rewards.

#### What fees does Algem charge?

Algem charges a 10% fee on farming rewards, which is distributed among ALGM stakers.

#### What risks are associated with Liquid Farming?

Risks include:

* Price fluctuations in AMM pools (impermanent loss).
* Potential liquidation if ETH balance falls below a set threshold.
