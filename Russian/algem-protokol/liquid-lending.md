# 🌊 Liquid Lending

{% embed url="https://www.youtube.com/watch?v=CJHTTbDvFwg&t=14s" %}

Ликвидное кредитование — вторая и самая важная функция Algem, предлагающая новую концепцию и услуги для всей индустрии дефи.

Решение Algem для ликвидного кредитования позволяет пользователям продолжать получать вознаграждение за кредитование или фермерство и увеличивать свой доход с помощью стимулов ALGM и с помощью торгуемых ликвидных токенов nASTR.

В ликвидном кредитовании используются те же механизмы, что и в ликвидном стекинге, но вместо взаимодействия только с стейкингом dApp Astar он напрямую подключается к другим протоколам dApp в сети Astar. Пользователи могут предоставлять и одалживать свои токены протоколам dApp через Algem и получать ликвидные токены nASTR, представляющие их кредитную позицию.

Через Algem держатели ASTR могут предоставлять или одалживать свои токены кредитным или стекинговым платформам, проектам стейблкоинов, децентрализованным биржам или другим протоколам defi.

![](<../.gitbook/assets/Liquid Lending1.PNG>)

Ликвидное кредитование Algem разработано вокруг 3 хранилищ с разной продолжительностью (100/200/300 дней) и стимулами ALGM.

Продолжительность соответствует намерению пользователя удерживать свои токены и поддерживать протокол. В отличие от ликвидного стейкинга, когда пользователи сразу получают 100% токенов nASTR, в хранилищах часть токенов nASTR имеет период наделения правами.

Хранилища с более длительным сроком действия получают больше стимулов от ALGM и имеют самое значительное количество токенов nASTR и самый продолжительный период наделения правами. Это не блокировка, а просто представление количества дней, в течение которых пользователи будут получать поощрения ALGM и токены nASTR. Пользователи могут разблокировать токены в любое время в соответствии с правилами.

_Например, если пользователь внесет 1000 ASTR в 100-дневное хранилище, он сразу же получит 930 nASTR (коэффициент разблокировки для 100-дневного хранилища равен 0,93. 0,93×1000 = 930), а 70 nASTR разблокируются линейно. Токены без права собственности должны быть востребованы вручную._

Перед запуском решения по ликвидному кредитованию коэффициент наделения хранилища nASTR может быть изменен для целей протокола.

Для первой итерации ликвидного кредитования, поддерживающего токены ASTR, Algem выделил 15% от предложения ALGM (15 000 000 ALGM) в качестве стимулов для 3 хранилищ.

После внесения токенов ASTR в одно из хранилищ пользователи выберут децентрализованное приложение для предоставления внесенных ими ASTR и получения вознаграждений ALGM.

Algem делегирует депонированный токен желаемому dApp, используя свои смарт-контракты. Затем, через некоторое время, Algem начнет собирать вознаграждения от dApp за предоставление активов. Мы называем их: партнерские вознаграждения .

Партнерские вознаграждения распределяются между поставщиками токенов ASTR в зависимости от их доли в хранилищах и их права голоса в ALGM. Право голоса соответствует количеству токенов ALGM, которые они разместили в выделенном пуле dApp.

Со временем пользователь продолжит получать вознаграждения ALGM из хранилища и сможет реинвестировать эти ALGM обратно в пул, чтобы заработать больше партнерских вознаграждений.