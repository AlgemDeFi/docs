# 🧵 nASTR Price Feeds by DIA

nASTR Price Feeds was developed by the leading Oracle of the Polkadot Ecosystem : [DIA Protocol](https://www.diadata.org/).

### **Methodology:**

nASTR price using collateral feed will be derived as follows:

* nASTR price = ASTR price \* (ASTR in staking contracts/ nASTR total supply)
* ASTR in staking contracts will be derived by calling function `getAstrInStakingContractFromAddress()` on [Astar DappsStaking contract](https://blockscout.com/astar/address/0x0000000000000000000000000000000000005001).
* nASTR total supply will be derived by calling function `totalSupply` on [nASTR token contract](https://blockscout.com/astar/address/0xE511ED88575C57767BAfb72BfD10775413E3F2b0/read-proxy#address-tabs)

### **DIA Oracle Contract:**

{% embed url="https://blockscout.com/astar/address/0x88463254469c37b9cECb71A34746707e008fb5A9" %}

To get the market price of ASTR/USD or nASTR/USD, query `getValue()` with argument “ASTR/USD” or “nASTR/USD”. \
Return values are the price (with 8 decimals, so divide by 10^8 to get the actual price) and unix timestamp of last update. Prices will update as soon as 1% change is detected.

### Algem adapter Contract:

{% embed url="https://blockscout.com/astar/address/0x8e066de9a3B0ac5965e4361fDE2752c11509f4F2" %}

The contract connects the ASTR/USD price to onchain collateral information.

Call `getNAstrPriceFromCollateralRatio()` to get the latest price from the collateral ratio and `getAstrInAllStakingContracts()` to retrieve the number of staked ASTR in all registered contracts.



More details can be found on DIA's forum:

{% embed url="https://forum.diadata.org/t/cdr-033-algem-price-feeds/543" %}

