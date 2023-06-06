# 🌽 Kagla Finance

[Kagla Finance](https://kagla.finance/) is a StableSwap protocol for Astar Network and it aims to be the biggest StableSwap in the ecosystem by offering two important benefits to its users: Low Slippage & High Earnings (user can boost up to 2.5x by voting escrow).&#x20;

Kagla already supports several stable pools including: USDT/USDC/DAI, aUSD, BAI, or BUSD. Recently, Kagla has also launched a new stable pool: nASTR & ASTR allowing nASTR holders to provide liquidity, and perform swaps or arbitrage trading.&#x20;

### How to farm nASTR/ASTR on Kagla Finance

Once you have staked ASTR tokens on algem.io and received nASTR tokens, select Kagla Finance in the nASTR farming and you can follow this guide.

{% content-ref url="./" %}
[.](./)
{% endcontent-ref %}

### Kagla Finance's particularity:

When a user wants to provide liquidity on Kagla Finance, they have the option of providing one or both assets. If a user provides one or both assets but with a different balance than the asset balances in the pool, Kagla will automatically balance the user's liquidity based on the balance of the assets in the pool.

_EX: The nASTR-ASTR ratio is 55-45 in the pool, so if someone adds 1000 nASTR to the pool, 450 of their nASTR will automatically be replaced by 450 ASTR. And the balance will be 550 nASTR and 450 ASTR. So the user will receive staking reward based on 550 nASTR._

### Be aware of risks!

Before using a StableSwap like Kagla Finance, be sure you are aware of the risks:&#x20;

* **Impermanent loss & loss of peg.** The nASTR/ASTR pair can fluctuate and lose its 1:1 peg on Kagla depending on market and user usage (swap, buy and sell). Before using the protocol, we highly recommend reading the code and understanding the risks involved with being a Liquidity Provider(LP)and/or using the AMM to trade pegged value crypto assets. See [Impermanent loss](https://finematics.com/impermanent-loss-explained/) for more.&#x20;
* **Smart-contract risks.** Kagla Finance has been already [audited ](https://docs.kagla.finance/development/audit)by Hacken but please keep in mind that security audits don’t completely eliminate risks. Do not supply assets that you cannot afford to lose to Kagla Finance as a liquidity provider.

### Smart Contracts:

<table><thead><tr><th width="242.17675373852768">Type</th><th width="504">Contract address</th></tr></thead><tbody><tr><td>Pool contract</td><td><a href="https://blockscout.com/astar/address/0x327d5322242B5558bebA1dfb9C02A9Da63551D67">0x327d5322242B5558bebA1dfb9C02A9Da63551D67</a></td></tr><tr><td>Lp token</td><td><a href="https://blockscout.com/astar/address/0x847f0Fd7e3A234E7321D01fF2347E4501eA89cF1">0x847f0Fd7e3A234E7321D01fF2347E4501eA89cF1</a></td></tr><tr><td>Gauge token</td><td><a href="https://blockscout.com/astar/address/0xEC1BD689f7576E912348D50aE3F10F4cA5489384">0xEC1BD689f7576E912348D50aE3F10F4cA5489384</a></td></tr><tr><td>Kagla adapter</td><td><a href="https://blockscout.com/astar/address/0x8d4F87A8f688Af04e9E3023C8846c3f6c64f410e">0x8d4F87A8f688Af04e9E3023C8846c3f6c64f410e</a></td></tr></tbody></table>
