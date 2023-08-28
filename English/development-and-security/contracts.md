# 📃 Contracts information

## Security deployment and contract administration

Algem contracts are deployed using GitHub CI and incorporate OpenZeppelin library modules, bolstering protocol dependability.

A majority of these contracts are designed for upgradability. When engaging with such contracts, remember to exclusively employ the Proxy address.

## Role-based smart-contact management

Algem employs a role-based system for managing smart contracts. This entails confining vital operations to the multisig wallet, while routine, non-critical actions are permissible via the ordinary wallet. This system encompasses two distinct roles:

* **DEFAULT\_ADMIN\_ROLE**

3/4 Gnosis Safe Multisig controlled by the two Algem team members and two Astar Network Core team members.&#x20;

Multisig address: [0xf1893e221227ff7B28D0dBe4dc367F54AAf9BEBD](https://blockscout.com/astar/address/0xf1893e221227ff7B28D0dBe4dc367F54AAf9BEBD) (Astar Network mainnet).&#x20;

All the contracts changes and grant/revoke role operations could be made only under the DEFAULT\_ADMIN\_ROLE (via the multi-signature transaction).

* **MANAGER**

Regular address with Algem development team access.&#x20;

Manager address: [0xf9B9068276163f47cd5599750496c48BeEba7B44](https://blockscout.com/astar/address/0xf9B9068276163f47cd5599750496c48BeEba7B44) (Astar Network mainnet).&#x20;

This role is used for the non-crucial operations which cannot affect the security level of the dApp such as setting the minimal staking amount, etc.

For a comprehensive rundown of operations allocated to each role, please refer to the [Miro board](https://miro.com/app/board/uXjVMPk0\_uk=/) provided.

## Deployed Smart Contract Addresses

View Algem's Smart Contracts on Github:&#x20;

{% embed url="https://github.com/AlgemDeFi/algem-contracts" %}

1. **Liquid Staking**

Contract name: Liquid Staking\
Contract address: [0x70d264472327B67898c919809A9dc4759B6c0f27\
](https://blockscout.com/astar/address/0x70d264472327B67898c919809A9dc4759B6c0f27)The contract is upgradeable.

2. **Liquid Staking Manager**

Contract name: LiquidStakingManager\
Contract address: [0x6edB3FdA40B8110fc0B820b48B7567E337915ffa\
](https://blockscout.com/astar/address/0x6edB3FdA40B8110fc0B820b48B7567E337915ffa)The contract is upgradeable.

3. **NDistributor**

Contract name: NDistributor\
Contract address: [0x460FB32070b77eB4Ff8d8f3EF717972F24433C83\
](https://blockscout.com/astar/address/0x460FB32070b77eB4Ff8d8f3EF717972F24433C83)The contract is upgradeable.

4. **NFT Distributor**

Contract name: NFTDistributor\
Contract address: [0x5167D19e76934D881FBdd77FB97ea36fb4FaE0cf\
](https://blockscout.com/astar/address/0x5167D19e76934D881FBdd77FB97ea36fb4FaE0cf)The contract is upgradeable.

5. **Adapters Distributor**

Contract name: AdaptersDistributor\
Contract address: [0x294Bb6b8e692543f373383A84A1f296D3C297aEf\
](https://blockscout.com/astar/address/0x294Bb6b8e692543f373383A84A1f296D3C297aEf)The contract is upgradeable.

6. **Algem Liquid Staking Discount**

Contract name: AlgemLiquidStakingDiscount\
Contract address: [0xF0F9238013af5982f97A347D190181F200Ad68CD\
](https://blockscout.com/astar/address/0xF0F9238013af5982f97A347D190181F200Ad68CD)The contract is upgradeable.

7. **Sirius Adapter**

Contract name: SiriusAdapter\
Contract address: [0x29774f72d921d1F5C591ab68dE532a528A4288B4](https://blockscout.com/astar/address/0x29774f72d921d1F5C591ab68dE532a528A4288B4)

The contract is upgradeable.

8. **Kagla Adapter**

Contract name: KaglaAdapter\
Contract address: [0x8d4F87A8f688Af04e9E3023C8846c3f6c64f410e\
](https://blockscout.com/astar/address/0x8d4F87A8f688Af04e9E3023C8846c3f6c64f410e)The contract is upgradeable.

9. **Arthswap Adapter**

Contract name: ArthswapAdapter\
Contract address: [0x09D5476c1c31eeE81E31dFD6923C314D33E57a4F\
](https://blockscout.com/astar/address/0x09D5476c1c31eeE81E31dFD6923C314D33E57a4F)The contract is upgradeable.

10. **​​Sio2 Adapter**

Contract name: Sio2Adapter\
Contract address: [0x7dE84319633850Bdabc557A1C61DA9E926cB4fF0\
](https://blockscout.com/astar/address/0x7dE84319633850Bdabc557A1C61DA9E926cB4fF0)The contract is upgradeable.

11. **nASTR**

Contract name: nASTR\
Contract address: [0xE511ED88575C57767BAfb72BfD10775413E3F2b0\
](https://blockscout.com/astar/address/0xE511ED88575C57767BAfb72BfD10775413E3F2b0)The contract is upgradeable.

12. &#x20;**Algemantis Nautilus Pass (NFT)**

Contract name: AlgemantisNautilusPass\
Contract address: [0x170a3768117A9Ae6939EA46c1b4265e94De44534\
](https://blockscout.com/astar/address/0x170a3768117A9Ae6939EA46c1b4265e94De44534)The contract is immutable.

13. **Algem Liquid Staking Discount (NFT)**

Contract name: AlgemLiquidStakingDiscount\
Contract address: [0xF0F9238013af5982f97A347D190181F200Ad68CD\
](https://blockscout.com/astar/address/0xF0F9238013af5982f97A347D190181F200Ad68CD)The contract is upgradeable.

14. **Algem Dojo (NFT)**

Contract name: AlgemDojo\
Contract address: [0xeBdA851087FF6A75961781987B9f1F7832D9DeB0\
](https://blockscout.com/astar/address/0xeBdA851087FF6A75961781987B9f1F7832D9DeB0)The contract is immutable.

## Pause Functionality

The pause feature serves to halt contracts temporarily during incident response.&#x20;

Presently, it's activated for the following contracts:

* Liquid Staking
* NASTR
* Sio2 Adapter

Pause functionality adheres to the Pausable module standard within the OpenZeppelin library for all these contracts.

**Contract.pause()**\
Pause a contract by setting the paused boolean flag to True.

**Contract.unpause()**\
Unpause a contract that was previously paused, re-enabling exchanges.

**Disabling functionality:**

1. Liquid Staking\
   All calls to contract functions are blocked.
2. NASTR

* transfer()
* transferFrom()
* mint()
* burn()

3. Sio2 Adapter

* supply()
* withdraw()
* borrow()
* addSTokens()
* claimRewards()

## Timelock

Our contracts operate without a time-lock function, as administrative actions are exclusively managed through the multi-signature wallet's address. This design guarantees swift execution of administrative decisions, eliminating the necessity for time-based delays, all the while upholding a secure and well-regulated environment.

## On-chain threats monitoring system

Presently, the Algem team is actively investigating on-chain monitoring systems, akin to the functionality offered by platforms such as [Forta](https://forta.org/).
