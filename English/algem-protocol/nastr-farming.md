# 📔 nASTR Farming

The nASTR Farming – which we previously referred to as nASTR Liquidity Hub – is a group of **intermediate contracts** that improve the user experience by allowing nASTR holders to interact with other protocols to use their nASTR tokens directly on Algem.

<figure><img src="../../Indonesian/.gitbook/assets/Article.png" alt=""><figcaption></figcaption></figure>

nASTR farming contracts receive $nASTR tokens and then proxy the actions to the selected protocol. Once locked in the contract, the balance cannot be changed unless removing the liquidity.

Users can transfer tokens into the nASTR farming contract through a single transaction improving at the same time the user experience by avoiding to switch to different website to use various Defi protocols.

Using nASTR Farming and directly on Algem, nASTR holders can:&#x20;

* Provide nASTR liquidity and stake LP tokens on AMM Standard and Stable Protocols.&#x20;
* Lend nASTR tokens to lending and collateral platforms.&#x20;
* Claim and receive farming rewards

⚠️ **Warning:** It is extremely important to use the adapters developed by Algem when using nASTR tokens with other Defi protocols in order to continue receiving staking rewards. \
If you use nASTR tokens directly on partner applications such as Arthswap, Sirius Finance, Kagla Finance or Sio2 Finance, you will no longer receive staking rewards.

### What is the benefit of the nASTR Farming

* **Flashloan protection via the buffered implementation:** Several improbable scenarios exist when staking rewards can be boosted retroactively through the LP tokens. For example, a user can use a flash loan to claim the rewards and receive significantly more that way, returning the LP tokens at the end of the transaction. This risk will rise in the future when more Defi dApps propose flashloan services.&#x20;
* **Protection from LP manipulations:** Some bots could monitor the mempool and switch tokens between their accounts in an attempt to artificially increase their reward amount.
* **Improved user experience such as:**&#x20;
  * Users no longer need to visit multiple websites to add their tokens to an additional dApps;&#x20;
  * Users require fewer actions for the whole process of depositing and withdrawals of tokens;&#x20;
  * Users can read all of the balances in one place;&#x20;
  * In the future, users can choose the DEX they want to interact with and see the statistics through Algem directly. -&#x20;
* **Calculation:** More precise reward calculation and higher platform security for users.&#x20;
* **Security:** Protection from the possibility of draining funds from or bankrupting the LP-provider contract.&#x20;
* **Supporting more protocols:** Not all dApp can support $nASTR for technical reasons. Among these are dApps such as AstridDAO and Arthswap, important for the Astar ecosystem.

More information on how to use Algem's nASTR Liquidity Hub in the user [guide section.](../get-started/how-to-use-algems-nastr-farming/)
