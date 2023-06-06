# Unstaking nASTR

To get their ASTR back, nASTR holders must return their tokens to Algem using one of the two unstaking options available:

### **Regular unstaking**

The regular unstake option uses the same function as the dApps staking of Astar Network. Once a user has unstaked his nASTR tokens, Algem triggers the unstaking on Astar dApps Staking. After the end of the unstaking period, Algem will receive the ASTR tokens and distribute them directly to the user's wallet.

### Immediate unstaking

In the Immediate unstaking option, the user can decide to unstake his nASTR and receive his ASTR tokens directly without waiting for ten eras, as in the case of regular unstaking. In return, Algem charges a small fee for the service. [More information about our fees](https://docs.algem.io/algem-protocol/protocol-revenues).

This option also depends on the capacity of the unstaking pool. The pool contains a certain amount of ASTR tokens. The system will deny the transaction if the pool is empty or does not have enough tokens to meet a user's unstaking request.

Protocol revenues supply the pool, and so does the regular unstaking of immediate users. I.e., if a user immediately unstakes his nASTR tokens using the unstaking pool, he will receive his ASTR tokens directly from the pool. Still, Algem will also trigger the regular unstaking option in dApps staking. After ten eras, ASTR tokens from dApp staking will be added and fill the pool allowing other users to immediately unstake.

The operation is the same in both options, only the time and fee change. The ASTR received after unstaking is not the initial deposit but the amount of unstaked nASTR.

I.e., If a user has bought or sold nASTR tokens since his first deposit and has unstaked his entire balance of nASTR, he will receive more or less ASTR tokens than his initial deposit.

### Q: What is the unstaking period?

Unstaking period varies from 10 ERAs to 13 ERAs (approximately 10-13 days).

### Q: Why so? In the Astar Network dApp staking unstaking period is 10 ERAs

DApp staking has a limit of 4 unbonding calls/user during the 10 days. Since our liquid staking contract is basically a user, Algem groups all unbonding calls into bunches and sends them to the dApp staking 4 times/10 days. That is why If you unstake ASTR at the beginning of this cycle, your unstaking period will be 13 ERAs.
