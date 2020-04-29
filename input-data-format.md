Olá, estamos juntos e queremos ajudar.

Com dados abertos, toda a comunidade poderá atuar em modelos estatísticos, previsões e insights, de forma comunitária e voluntária.

Percebemos que as prefeituras já estão zelando pela transparência, gerando e compartilhando comunicados periódicos para a comunidade, o que é ótimo! Obrigado!

Mas... Para tratarmos de modelos estatísticos, é fundamental utilizarmos:
* Dados estruturados
* Dados atualizados diariamente


Para [este projeto](.\readme.md), são necessários os seguintes dados:
* `date` Data da medição, no formato AAAA-MM-DD
* `location` O nome do bairro
* `totalCases` Número total de casos, naquela data, naquele bairro
* `newCases` Número de novos casos aferidos, naquela data, naquele bairro
* `deaths` Número total de mortes, naquela data, naquele bairro
* `newDeaths` Número de novas mortes, naquela data, naquele bairro

Além disso é importante que estes dados estejam estruturados em formato csv. Exemplo abaixo

E finalmente, é importante que estes dados estejam atualizados diariamente e acessíveis em uma url pública.

## Estou aqui para ajudar!
Se precisar de qualquer apoio para extrair estes dados, por favor entre em contato.

## Exemplo de dados históricos de 2 bairros em formato csv:

```
date,location,totalCases,newCases,deaths,newDeaths
2020-04-28,Bairro ABC,10,0,2,0
2020-04-27,Bairro ABC,10,1,2,0
2020-04-26,Bairro ABC,9,0,2,1
2020-04-25,Bairro ABC,9,4,1,0
2020-04-24,Bairro ABC,5,2,1,0
2020-04-23,Bairro ABC,3,0,1,0
2020-04-22,Bairro ABC,3,2,1,1
2020-04-21,Bairro ABC,1,0,0,0
2020-04-20,Bairro ABC,1,0,0,0
2020-04-19,Bairro ABC,1,1,0,0
2020-04-28,Bairro XPTO,20,1,2,0
2020-04-27,Bairro XPTO,19,2,2,0
2020-04-26,Bairro XPTO,17,0,2,1
2020-04-25,Bairro XPTO,17,3,1,0
2020-04-24,Bairro XPTO,14,5,1,0
2020-04-23,Bairro XPTO,9,4,1,0
2020-04-22,Bairro XPTO,5,0,1,1
2020-04-21,Bairro XPTO,5,2,0,0
2020-04-20,Bairro XPTO,3,0,0,0
2020-04-19,Bairro XPTO,3,3,0,0
```