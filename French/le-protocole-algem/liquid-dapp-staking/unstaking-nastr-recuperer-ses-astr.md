# Unstaking nASTR (récupérer ses ASTR)

Pour récupérer leur ASTR, les détenteurs de nASTR doivent retourner leurs jetons à Algem en utilisant l'une des deux options de désengagement disponibles :

### De facon classique

L'option de désengagement classique utilise la même fonction que le dApp Staking du réesau Astar. Une fois qu'un utilisateur a retiré ses jetons nASTR, Algem déclenche le retrait sur le dApp Staking d'Astar. Après la fin de la période de désengagement, Algem recevra les jetons ASTR et les distribuera directement dans le portefeuille de l'utilisateur.

### De facon immédiate

Avec l'option retrait immédiat, l'utilisateur peut décider de retirer ses nASTR et de recevoir directement ses jetons ASTR sans attendre dix ères, comme dans le cas du retrait classique. En retour, Algem facture une somme modique pour le service. [Plus d'informations sur nos frais.](../revenus-du-protocole.md)

Cette option dépend également de la capacité de la pool de désengagement. La pool contient un certain nombre de jetons ASTR. Le système refusera la transaction si la pool est vide ou n'a pas assez de jetons pour répondre à la demande de retrait de l'utilisateur.

Les revenus du protocole alimentent la pool, tout comme le retrait avec option immédiate. C'est-à-dire que si un utilisateur retire immédiatement ses jetons nASTR en utilisant la pool de retrait, il recevra ses jetons ASTR directement de la pool. Pourtant, Algem déclenchera également l'option classique de désengagement dans le dApp Staking. Après dix époques, les jetons ASTR du dApp Staking seront ajoutés et rempliront de nouveau la pool, permettant aux autres utilisateurs de se retirer immédiatement.

Le fonctionnement est le même dans les deux options, seuls le temps et les frais changent. Les ASTR reçus après le désengagement ne correspondent pas au montant total du dépôt initial mais au montant des nASTR désengagés.

C'est-à-dire que si un utilisateur a acheté ou vendu des jetons nASTR depuis son premier dépôt et a retiré tout son solde de nASTR, il recevra plus ou moins de jetons ASTR que son dépôt initial.

### Q : Quelle est la période de retrait (unstaking)?

La période de retrait varie de 10 à 13 ERES (environ 10 à 13 jours).

### Q : Et pourquoi? La période de retrait du dApp Staking sur le résau Astar est de 10 ERES

Le dApp Staking a une limite de 4 appels par utilisateur sur une durée de 10 jours. Étant donné que notre contrat de Liquid Staking est considéré comme un unique utilisateur, Algem regroupe tous les appels pour les envoyer au dApp Staking en 4 fois sur 10 jours. C'est pourquoi si vous retirer vos ASTR au début de ce cycle, votre période de retrait sera de 13 ERES.
