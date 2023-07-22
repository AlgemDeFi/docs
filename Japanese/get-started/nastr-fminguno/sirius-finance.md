# 👨🌾 Sirius Finance

[Sirius Finance](https://www.sirius.finance/) is a Polkadot-native stablecoin AMM on Astar Network. Its mission is to provide a stable, highly liquid trading platform for stablecoins, deep liquidity for connected protocols, and attract and lock tremendous value to facilitate more innovations and collaborations for Astar and Polkadot.

On Sirius Finance, nASTR holders can swap or deposit their tokens to provide liquidity in the nASTR:ASTR stable pair. In return, they will receive LP tokens and can stake them on Sirius to earn extra trading fees and rewards in Sirius's farming pool.

### How to farm nASTR/ASTR on Sirius Finance

Once you have staked ASTR tokens on algem.io and received nASTR tokens, select Sirius Finance in the nASTR farming and you can follow this guide.

{% content-ref url="./" %}
[.](./)
{% endcontent-ref %}

### Sirius Finance's particularity:

When a user wants to provide liquidity on Sirius Finance, they have the option of providing one or both assets. If a user provides one or both assets but with a different balance than the asset balances in the pool, Sirius will automatically balance the user's liquidity based on the balance of the assets in the pool.

_EX: The nASTR-ASTR ratio is 55-45 in the pool, so if someone adds 1000 nASTR to the pool, 450 of their nASTR will automatically be replaced by 450 ASTR. And the balance will be 550 nASTR and 450 ASTR. So the user will receive staking reward based on 550 nASTR._

### Be aware of risks!

Before using a DEX like Sirius Finance, be sure you are aware of the risks:&#x20;

* **Impermanent loss & loss of peg.** The nASTR/ASTR pair can fluctuate and lose its 1:1 peg on Sirius depending on market and user usage (swap, buy and sell). Before using the protocol, we highly recommend reading the code and understanding the risks involved with being a Liquidity Provider(LP)and/or using the AMM to trade pegged value crypto assets. See [Impermanent loss](https://finematics.com/impermanent-loss-explained/) for more.&#x20;
* **Smart-contract risks.** Sirius Finance has been already audited twice but please keep in mind that security audits don’t completely eliminate risks. Do not supply assets that you cannot afford to lose to Sirius Finance as a liquidity provider.

### Smart Contracts:

<table><thead><tr><th width="242.17675373852768">Type</th><th width="504">Contract address</th></tr></thead><tbody><tr><td>nASTR Stablepool farm</td><td><a href="https://blockscout.com/astar/address/0xEEa640c27620D7C448AD655B6e3FB94853AC01e3">0xEEa640c27620D7C448AD655B6e3FB94853AC01e3</a></td></tr><tr><td>nASTR Stablepool pool</td><td><a href="https://blockscout.com/astar/address/0xdCfFa5a92ef31DCc8979Ab44A0406859d7763c45/transactions#address-tabs">0xdCfFa5a92ef31DCc8979Ab44A0406859d7763c45</a></td></tr><tr><td>Gauge</td><td><a href="https://blockscout.com/astar/address/0xcB274236fBA7B873FC8F154bb0475a166C24B119">0xcB274236fBA7B873FC8F154bb0475a166C24B119</a></td></tr><tr><td>Sirius adapter</td><td><a href="https://blockscout.com/astar/address/0x29774f72d921d1F5C591ab68dE532a528A4288B4">0x29774f72d921d1F5C591ab68dE532a528A4288B4</a></td></tr></tbody></table>
