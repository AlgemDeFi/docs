# 🌽 カグラファイナンス

ステーブルコインのスワップが行えます。低いスリッページと高い報酬（voting escrowで報酬最大2.5倍）を実現することでユーザーの利益を高めエコシステム最大のステーブルスワッププロジェクトを目指しています。

{% embed url="https://kagla.finance/" %}

"取扱いコインはUSDT/USDC/DAI/aUSD/BAI/BUSD。 $nASTR:$ASTRプールもローンチされ流動性供給やスワップ、アービトラージが可能になりました。"

### $nASTR:$ASTRファーミングのやり方

[アルジェム](https://www.algem.io/)で$ASTRをステーキングし$nASTRを入手後、カグラスファイナンスを選択し以下のガイドに従ってください。

{% content-ref url="./" %}
[.](./)
{% endcontent-ref %}

### カグラファイナンスにおいて

流動性供給は片側・両側の選択が可能です。流動性を供給するトークンの割合とプール内のトークンの割合が異なる場合、シリウスにおいて自動的にリバランスが行われます。報酬はリバランス後の$nASTRの数量に対して支払われます。

_例）プール内の$nASTR:$ASTR = 55:45 利用者が1000nASTRを入金すると自動的に550nASTRと450ASTRへリバランスされます。このためユーザーは550nASTR分の報酬を受け取ることになります。_

### リスクについて

カグラスファイナンスのようなDEXを利用する際は以下のようなリスクにご注意ください。

* インパーマネントロス & ペグ喪失. $nASTR:$ASTRの比率はマーケット状況やユーザーの利用状況（スワップ、売買等）に応じて変動しペグを喪失することがあります。プロジェクトを利用する前にコードを確認し、ペグ制資産を用いた流動性供給やAMM利用におけるリスクを確認することをお勧めします。詳細は[インパーマネントロス](https://finematics.com/impermanent-loss-explained/)をご参照ください。
* ・スマートコントラクトリスク. カグラファイナンスは[Hacken](https://docs.kagla.finance/development/audit)の監査を受けていますが、監査で全てのリスクを取り除くことはできません。限度を超えた資産運用は行わないでください。

### スマートコントラクト

<table><thead><tr><th width="242.17675373852768">タイプ </th><th width="504">コントラクトアドレス</th></tr></thead><tbody><tr><td>プール　コントラクト</td><td><a href="https://blockscout.com/astar/address/0x327d5322242B5558bebA1dfb9C02A9Da63551D67">0x327d5322242B5558bebA1dfb9C02A9Da63551D67</a></td></tr><tr><td>LP　トークン</td><td><a href="https://blockscout.com/astar/address/0x847f0Fd7e3A234E7321D01fF2347E4501eA89cF1">0x847f0Fd7e3A234E7321D01fF2347E4501eA89cF1</a></td></tr><tr><td>ゴージ　トークン</td><td><a href="https://blockscout.com/astar/address/0xEC1BD689f7576E912348D50aE3F10F4cA5489384">0xEC1BD689f7576E912348D50aE3F10F4cA5489384</a></td></tr><tr><td>カグラ　アダプター</td><td><a href="https://blockscout.com/astar/address/0x8d4F87A8f688Af04e9E3023C8846c3f6c64f410e">0x8d4F87A8f688Af04e9E3023C8846c3f6c64f410e</a></td></tr></tbody></table>
