# 🌊 Liquid Lending

{% embed url="https://www.youtube.com/watch?v=CJHTTbDvFwg&t=14s" %}

Le Liquid Lending est la deuxième fonctionalité et la plus importante d'Algem, offrant un nouveau concept et un nouveau service à l'ensemble de l'industrie de la defi.

La solution de Liquid Lending d'Algem permet aux utilisateurs de continuer à recevoir des récompenses de prêt ou de farming et d'augmenter leurs revenus grâce aux incitations en ALGM tout en utilisant des jetons nASTR liquides et échangeables.

Le Liquid Lending utilise les mêmes mécanismes que le Liquid Staking, mais au lieu d'interagir uniquement avec le dApp Staking d'Astar, il est directement connecté aux protocoles des autres dApp du réseau Astar. Les utilisateurs peuvent fournir et prêter leurs jetons aux différents protocoles décentralisés via Algem et en échange recevoir des jetons nASTR liquides représentant leur position de prêt.

Grâce à Algem, les détenteurs d'ASTR peuvent fournir ou prêter leurs jetons à des plateformes de prêt ou de staking, à des projets de stablecoin, à des échanges décentralisés ou à d'autres protocoles defi.

![](<../.gitbook/assets/Liquid Lending1.PNG>)

Le Liquid Lending d'Algem est développé autour de 3 coffres-forts avec des durées différentes (100/200/300 jours) et des incitations en jeton ALGM

La durée correspond à l'intention de l'utilisateur de conserver ses jetons et donc de soutenir le protocole. Contrairement au Liquid Staking, où les utilisateurs recoivent immédiatement 100% des jetons nASTR, dans les coffres-forts, une partie des jetons nASTR a une période d'acquisition progressive.

Les coffres-forts avec une durée plus longue reçoivent plus d'incitations en ALGM mais en échange ont une plus grande quantité de jetons nASTR vérouillés et une période d'acquisition plus longue. Il ne s'agit pas d'un blocage ferme mais simplement d'une représentation du nombre de jours où les utilisateurs recevront des incitations en ALGM et leurs jetons nASTR. Dans les régles du protocole, les utilisateurs peuvent déverrouiller les jetons à tout moment.

_Par exemple, si un utilisateur dépose 1000 ASTR dans le coffre-fort de 100 jours, il recevra immédiatement 930 nASTR (le coefficient de déverrouillage pour le coffre-fort de 100 jours est de 0,93. 0,93 × 1000 = 930), et 70 nASTR sont déverrouillés de manière linéaire. Les jetons non acquis doivent être réclamés manuellement._

Jusqu'à ce que la solution du Liquid Lending soit lancée, les coefficients d'acquisition des nASTR peuvent être adaptés, par coffre-fort, dans l'utilité du protocole.

Pour la première itération du Liquid Lending prenant en charge les jetons ASTR, Algem a alloué 15 % de l'offre ALGM (15 000 000 ALGM) comme incitations pour les 3 coffres.

Après avoir déposé des jetons ASTR dans l'un des coffres, les utilisateurs choisiront la dApp qui recevra le jeton ASTR et gagneront des récompenses en ALGM.

Algem déléguera le jeton déposé à la dApp souhaitée via les contrats intélligents (smart contracts). Ensuite, après un certain temps, Algem, pour avoir apporté de la liquidité, récoltera les récompenses auprès de la dApp. Nous les appelons : Récompenses partenaires.

Les récompenses des partenaires sont distribuées aux fournisseurs de jetons ASTR en fonction de leurs parts dans les coffres et de leur pouvoir de vote ALGM. Le pouvoir de vote correspond à la quantité de jetons ALGM qui a été staké sur la pool de la dApp dédiée.

Au fil du temps, l'utilisateur recevra du coffre-fort des récompenses en ALGM et pourra les réinvestir dans la pool afin de gagner encore plus de récompenses partenaires.
