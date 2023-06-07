# 📔 nASTR Farming

Le nASTR Farming - que nous appelions auparavant nASTR liquidiy hub - est un groupe de contrats intermédiaires qui améliorent l'expérience utilisateur en permettant aux détenteurs de nASTR d'interagir avec d'autres protocoles pour utiliser leurs jetons nASTR directement sur Algem.

<figure><img src="../.gitbook/assets/Article.png" alt=""><figcaption></figcaption></figure>

Les contrats de farming nASTR reçoient des jetons $nASTR, puis transmet les actions au protocole sélectionné. Une fois bloqué dans le contrat, le solde ne peut plus être modifié à moins de retirer la liquidité.

Les utilisateurs peuvent transférer des jetons nASTR dans le contrat de farming en une seule transaction, améliorant ainsi l'expérience utilisateur en restant sur le même site Web pour utiliser différents protocoles Defi.

En utilisant le nASTR farming directement sur Algem, les détenteurs de nASTR peuvent :

* Fournir de la liquidité en nASTR et déposer les jetons LP sur les protocoles AMM standard ou ceux spécialisés dans les stables.&#x20;
* Prêter des jetons nASTR aux plateformes de prêt et les déposer en collatéral.
* Réclamer et recevoir les récompenses de farming

### Quel est l'avantage du nASTR Farming?

* Protection contre les Flashloan en utilisant un tampon dans l'implémentation: plusieurs scénarios improbables existent lorsque les récompenses de staking peuvent être augmentées rétroactivement via les jetons LP. Par exemple, un utilisateur peut utiliser un prêt flash (flash loan) pour emprunter les jetons avant de réclamer les récompenses et ainsi en recevoir beaucoup plus, tout en retournant les jetons LP à la fin de la transaction. Ce risque augmentera à l'avenir lorsque davantage de dApps Defi proposeront des services de flash loan.
* Protection contre les manipulations de LP : certains bots pourraient surveiller le mempool et changer les jetons entre leurs comptes dans le but d'augmenter artificiellement le montant de leur récompense.
* Amélioration de l'expérience utilisateur telle que :
  * Les utilisateurs n'ont plus besoin de visiter plusieurs sites Web pour ajouter leurs jetons aux dApps supplémentaires ;&#x20;
  * L'ensemble du processus de dépôt et de retrait des jetons nécessite moins d'actions de la part de lutilisateur;&#x20;
  * Les utilisateurs peuvent lire tous les soldes en un seul endroit ;&#x20;
  * A l'avenir, les utilisateurs pourront choisir le DEX avec lequel ils souhaiteront interagir et consulter directement les statistiques via Algem.
* Au niveau du calcul : Les récompenses sont calculées plus précisémemnt et la sécurité est accrue pour les utilisateurs.
* Sécurité : Protection contre la possibilité de drainer des fonds ou de mettre en faillite le contrat de fournisseur LP.
* D'avantage de protocoles peuvent être pris en chages: Toutes les dApps ne peuvent pas prendre en charge le $nASTR pour des raisons techniques. Parmi celles-ci figurent des dApps telles que AstridDAO et Arthswap, importantes pour l'écosystème Astar.

Plus d'informations sur l'utilisation du nASTR Farming d'Algem dans la section guide de l'utilisateur.
