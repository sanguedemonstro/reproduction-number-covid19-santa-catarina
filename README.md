# reproduction-number-covid19-santa-catarina

## Motivação
Acredido que o **índice de contágio do COVID-19** regionalizado, por estados, municípios e até bairros, **em tempo real**, pode apoiar a tomada de decisões do poder público sobre como conter o contágio e como conduzir a retomada da atividade econômica de forma segura.

Esse índice também é conhecido por **Rt** ou número de reprodução eficaz.

## O que é o Rt

> O Rt, ou número de reprodução eficaz, é o número médio de contágios causados por cada pessoa infectada em um determinado ponto no tempo, levando em consideração mudanças no nosso comportamento (quarentena, uso de máscaras, home office, etc). Um Rt de 3–4 infectará virtualmente toda a população, enquanto um Rt de 1.5 pode ainda alcançar 60% da população. Somente se o Rt for menor do que 1, a epidemia irá diminuir de tamanho até ser eliminada. [Fonte](https://loft.science/).

## Do que trata esse repositório

Aqui estou exercitando o **índice de contágio do COVID-19 por municípios de Santa Catarina**.

Gostaria de tornar este índice facilmente acessível à qualquer gestor, de qualquer esfera, bastando inputar os dados do seu município em um [formato pré-determinado](input-data-format.md), em uma interface amigável.

**Disclaimer:** Trata-se de um trabalho experimental, não científico e ainda em fase de construção.

## Próximos passos, para uma versão beta:
* Plotar também o Rt do Brasil
* Plotar também o Rt de Santa Catarina
* Considerar todos os municípios de Santa Catarina (atualmente está gerando erro).
* Melhorar a qualidade dos gráficos
* Gerar uma visão Web para os gráficos

**Voluntários são bem vindos! [Entre em contato](https://www.linkedin.com/in/sanguedemonstro/).**

## Próximas versões:
* Permitir a geração de gráficos Rt e de comparação de Rt, de forma simplificada, a partir de uma interface amigável.

## Créditos

Esse trabalho é inspirado [neste material da Loft](https://loft.science/).

Que por sua vez é inspirado [neste material do Kevin Systrom](https://github.com/k-sys/covid-19/blob/master/Realtime%20R0.ipynb).


## Gráficos gerados para Santa Catarina com dados disponíveis em 28/04/2020:

![SC - 28/04/2020](https://github.com/sanguedemonstro/reproduction-number-covid19-santa-catarina/blob/master/images/rt-sc-2020-04-28.PNG)
![Compare SC - 28/04/2020](https://github.com/sanguedemonstro/reproduction-number-covid19-santa-catarina/blob/master/images/compare-rt-sc-2020-04-28.PNG)
