### Importações de Fertilizantes na Bahia  

Edição: Janeiro de 2025

>![André Bueno](https://avatars.githubusercontent.com/u/152298881?v=4&s=64)  
>**Responsável:** André Bueno  
>**Contato:** [LinkedIn](https://www.linkedin.com/in/andre-coutinho-bueno/) | [GitHub](https://andrecoutinhobueno.github.io/AndreCoutinhoBueno/)

O objetivo deste estudo é apoiar decisões de importação e a precificação do estoque local. 

A programação dos cálculos foram feitas com a linguagem [Python](https://www.python.org) e suas bibliotecas de ***machine learning***, especialmente [scikit-learn](https://scikit-learn.org/stable/). 

A principal fonte de dados utilizada é o site governamental [Comexstat](https://comexstat.mdic.gov.br/pt/home), especializado em estatísticas do comércio exterior brasileiro de bens.

Em relação a última edição deste relatório, uma nova fonte de dados também foi utilizada, disponibilizando à "máquina" os volumes de chuva na região do Oeste da Bahia (Fonte:[INMET](https://portal.inmet.gov.br/)).

O programa está apto a receber novos e mais dados, que estejam relacionados ao consumo e as importações de fertilizantes.

Técnicas de **classificação, regressão** foram aplicadas. Toda a documentação e registros dessas técnicas estão disponíveis porém protegidos por senha, aqui mesmo, no GitHub. Solicite acesso para maiores detalhes.

Para cada previsão de importação, foram disponibilizadas à "máquina" informações adicionais sobre outros produtos e fenômenos correlacionados, que podem estar correlacionados com a previsão em questão. 

Por exemplo, a seguir podemos ver na tabela que, para o produto MOP no mês 10, a "máquina" obteve mais precisão considerando também os dados sobre importação de MAP e UREIA, as exportações de soja da Bahia (Soy Group), e ainda, os volumes de chuva no oeste da Bahia(c_o_ba):  

![Tabela](https://raw.githubusercontent.com/AndreCoutinhoBueno/Import-Fertilizer-Bahia/refs/heads/main/tabela.png)

### Gráficos por Produto  

> ![MAP](https://raw.githubusercontent.com/AndreCoutinhoBueno/Import-Fertilizer-Bahia/refs/heads/main/MAP.png)  

> ![MOP](https://raw.githubusercontent.com/AndreCoutinhoBueno/Import-Fertilizer-Bahia/refs/heads/main/MOP.png)  

> ![UREIA](https://raw.githubusercontent.com/AndreCoutinhoBueno/Import-Fertilizer-Bahia/refs/heads/main/UREIA.png)  

Analisando os volumes acumulados de importação de MOP no gráfico a seguir, que certamente esta correlacionado com o consumo de UREIA e MAP, o autor considera que o ano de 2025 será um ano de retração do mercado, e por isso, nos gráfico de previsão acima, se deve considerar maior acertividade nas previsões inferiores de cada produto e mês.

![têndência]()
