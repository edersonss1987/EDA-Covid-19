1. Introdução
1.1. TLDR
Dashboard:
Google Data Studio (link).
Processamento:
Kaggle Notebook (link).
Fontes:
Casos pela universidade John Hopkins (link);
Vacinação pela universidade de Oxford (link).
1.2. Pandemia Coronavírus 2019
A COVID-19 é uma infecção respiratória aguda causada pelo coronavírus SARS-CoV-2, potencialmente grave, de elevada transmissibilidade e de distribuição global. Fonte: Governo brasileiro (link).

A disponibilidade de dados sobre a evolução da pandemia no tempo em uma determinada região geográfica é fundamental para o seu combate! Este projeto busca construir um dashboard de dados para exploração e visualização interativa de dados sobre o avanço de casos e da vacinação do Brasil. O processamento de dados está neste link e o dashboard, neste link.

1.3. Dados
Os dados sobre casos da COVID-19 são compilados pelo centro de ciência de sistemas e engenharia da universidade americana John Hopkins (link). Os dados são atualizados diariamente deste janeiro de 2020 com uma granularidade temporal de dias e geográfica de regiões de países (estados, condados, etc.). O website do projeto pode ser acessado neste link enquanto os dados, neste link. Abaixo estão descritos os dados derivados do seu processamento.

date: data de referência;
state: estado;
country: país;
population: população estimada;
confirmed: número acumulado de infectados;
confirmed_1d: número diário de infectados;
confirmed_moving_avg_7d: média móvel de 7 dias do número diário de infectados;
confirmed_moving_avg_7d_rate_14d: média móvel de 7 dias dividido pela média móvel de 7 dias de 14 dias atrás;
deaths: número acumulado de mortos;
deaths_1d: número diário de mortos;
deaths_moving_avg_7d: média móvel de 7 dias do número diário de mortos;
deaths_moving_avg_7d: média móvel de 7 dias dividido pela média móvel de 7 dias de 14 dias atrás;
month: mês de referência;
year: ano de referência.
Os dados sobre vacinação da COVID-19 são compilados pelo projeto Nosso Mundo em Dados (Our World in Data ou OWID) da universidade britânica de Oxford (link). Os dados são atualizados diariamente deste janeiro de 2020 com uma granularidade temporal de dias e geográfica de países. O website do projeto pode ser acessado neste link enquanto os dados, neste link. Abaixo estão descritos os dados derivados do seu processamento.

date: data de referência;
country: país;
population: população estimada;
total: número acumulado de doses administradas;
one_shot: número acumulado de pessoas com uma dose;
one_shot_perc: número acumulado relativo de pessoas com uma dose;
two_shots: número acumulado de pessoas com duas doses;
two_shot_perc: número acumulado relativo de pessoas com duas doses;
three_shots: número acumulado de pessoas com três doses;
three_shot_perc: número acumulado relativo de pessoas com três doses;
month: mês de referência;
year: ano de referência.
