### Importações de Fertilizantes na Bahia  

Edição: Março de 2025

>![André Bueno](https://avatars.githubusercontent.com/u/152298881?v=4&s=64)  
>**Responsável:** André Bueno  
>**Contato:** [LinkedIn](https://www.linkedin.com/in/andre-coutinho-bueno/) | [GitHub](https://andrecoutinhobueno.github.io/AndreCoutinhoBueno/)

O objetivo deste estudo é apoiar decisões de importação e a precificação do estoque local. 

Com caráter demonstrativo, apresento a seguir previsões de importação produzidas por modelo de ‘machine learning’ de minha autoria.


Importante notar:


‘date_base’: em português, data-base. É a data limite até onde o modelo teve acesso a dados ou, o último mês divulgado. 


1ª previsão de cada gráfico: é a previsão do mês imediatamente seguinte a data-base, no caso, o mês de março. Tem função auxiliar na precificação do estoque local. Por exemplo: Temos dados até fevereiro. A primeira previsão é para março. Se em março desembarcar volume de produto muito superior ao previsto, super-oferta, cria-se vetor de baixa nos preços do estoque local. E vice-versa.


Quadrados verdes: representam o limite da normalidade da previsão. Desembarques ocorridos fora do limite demarcados por eles têm elevado potencial de impacto no preço.


Previsões seguintes a 1ª previsão: Tem função de balizar as decisões de importação.


Regressão Multi-fatorial: Para todas as previsões feitas o modelo considera o histórico de múltiplos fatores, o que aumenta a precisão, sendo esse o maior benefício dos sistemas de ‘machine-learning’. No caso dessa demonstração foram considerados:


Fonte: [Comex Stat](https://comexstat.mdic.gov.br/pt/home) 

> Peso e valor das importações de MAP, MOP e UREIA
> Peso e valor das exportações de café, cacau, soja, algodão e milho

Fonte: [INMET](https://portal.inmet.gov.br/)

> Chuvas na região do oeste da Bahia


Probalidade de ocorrência: É proporcional ao tamanho dos marcadores no gráfico (vide legenda).



### Gráficos por Produto  

> ![MAP](https://raw.githubusercontent.com/AndreCoutinhoBueno/Import-Fertilizer-Bahia/refs/heads/main/MAP.png)  

> ![MOP](https://raw.githubusercontent.com/AndreCoutinhoBueno/Import-Fertilizer-Bahia/refs/heads/main/MOP.png)  

> ![UREIA](https://raw.githubusercontent.com/AndreCoutinhoBueno/Import-Fertilizer-Bahia/refs/heads/main/UREIA.png)  