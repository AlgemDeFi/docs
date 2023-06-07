# ⚠ Gestion des risques

Avant d'utiliser Algem, veuillez lire nos [termes et conditions d'utilisation](https://www.algem.io/terms-of-use) et être conscient des risques.

* Risques liés aux contrats intelligents (smart contracts):\
  \
  Algem a fait [auditer son protocole et ses contrats intelligents](https://github.com/AlgemDeFi/audits/blob/main/AlgemQuantstampCertifacate.png) par [Quantstamp](https://quantstamp.com/), leader de la sécurité Web3.0. Sachez qu'un audit de sécurité ne garantit pas l'infaillibilité totale d'un protocole. Les risques peuvent toujours être présents. Ne misez pas sur Algem des actifs que vous ne pouvez pas vous permettre de perdre.\

* Perte du peg nASTR.\
  \
  Sur le protocole Algem, il y a toujours un ratio 1:1 pour créer (minter) les nASTR et les retourner. Peu importe le ratio de la paire nASTR/ASTR sur le marché. Les utilisateurs peuvent toujours échanger le même montant d'ASTR à partir de jetons nASTR. Cependant, si les détenteurs de nASTR utilisent leurs jetons dans les DEX pour fournir des liquidités, ils sont confrontés à la possibilité d'une perte impermanente et d'un dépeg comme tout farming dans les DEX. \
  \
  Pour atténuer ce risque, les utilisateurs peuvent effectuer des stratégies d'arbitrage entre les DEX et le protocole Algem en utilisant les fonctions d'échange (swap), stake et unstake. De cette manière, les utilisateurs ont des incitations financières à conserver le peg ASTR/nASTR et à stabiliser l'écosystème. Voir [la section sur le ratio nASTR:ASTR](dnts.md).\

*   Perte impermanente sur DEX\
    \
    En substance, la perte impermanente est une perte temporaire de fonds survenant lors de la fourniture de liquidités. Elle est très souvent expliquée comme une différence entre la détention d'un actif et la fourniture de liquidités dans cet actif. Une perte impermanente est généralement observée dans les pools de liquidités standard où le le fournisseur de liquidité (LP) doit fournir les deux actifs dans un ratio équivalent; et que l'un des deux actifs est plus volatil que l'autre. Par exemple, dans un pool de liquidité Arthswap ASTR/WETH 50/50.\


    Si la valeur de WETH augmente, le pool doit s'appuyer sur des arbitreurs qui s'assurent en permanence que le prix de la pool reflète bien le prix réel et ainsi maintenir la même valeur des deux jetons dans la pool. Cela conduit essentiellement à une situation où le profit du jeton qui s'est apprécié en valeur est retiré au fournisseur de liquidités. À ce stade, si le LP décide de retirer ses liquidités, la perte impermanente devient permanente." Voir "[Qu'est-ce qu'une perte impermanente ? DEFI](https://finematics.com/impermanent-loss-explained/) expliqué" de Finematics pour en savoir plus.

Pour les risques associés à l'utilisation de nASTR sur d'autres protocoles, consultez les sections connexes :

* [Risques Sirius Finance](../pour-commencer/comment-utiliser-le-nastr-farming-dalgem/sirius-finance.md);
* [Risques Kagla Finance](../pour-commencer/comment-utiliser-le-nastr-farming-dalgem/kagla-finance.md);
* [Risques Arthswap](../pour-commencer/comment-utiliser-le-nastr-farming-dalgem/arthswap.md);
