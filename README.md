# Importações de Fertilizantes na Bahia 

![André Bueno](https://avatars.githubusercontent.com/u/152298881?v=4&s=64)  
**Responsável:** André Bueno  
**Contato:** [LinkedIn](https://www.linkedin.com/in/andre-coutinho-bueno/) | [GitHub](https://andrecoutinhobueno.github.io/AndreCoutinhoBueno/)

As previsões a seguir foram obtidas utilizando a linguagem [Python](https://www.python.org) e algumas de suas bibliotecas de ***machine learning***, especialmente [scikit-learn](https://scikit-learn.org/stable/).

![Python](https://www.python.org/static/img/python-logo@2x.png)  
![Scikit-Learn](https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png)  

A principal fonte de dados é o site governamental [Comexstat](https://comexstat.mdic.gov.br/pt/home), utilizado para extrair estatísticas do comércio exterior brasileiro de bens.

O programa criado está apto a aceitar novos dados relacionados às importações de fertilizantes, visando aumentar a precisão das previsões.

Técnicas de **classificação, regressão e clusterização**, amplamente aplicadas em precificação de estoque, foram utilizadas e estão documentadas. Os registros estão disponíveis para conferência aqui no GitHub. Solicite para mais detalhes!

![Em Obras](http://ryco.eng.br/wp-content/uploads/2017/08/obras-em-andamento2.png)  

**Em Obras:**  
A máquina virtual que gera as previsões ainda apresenta distorções que estão sendo corrigidas, como as ocorridas nos meses 5 e 6 para o produto MOP.

### Gráficos por Produto
![MAP](https://raw.githubusercontent.com/AndreCoutinhoBueno/Import-Fertilizer-Bahia/refs/heads/main/MAP.png)  
![MOP](https://raw.githubusercontent.com/AndreCoutinhoBueno/Import-Fertilizer-Bahia/refs/heads/main/MOP.png)  
![UREIA](https://raw.githubusercontent.com/AndreCoutinhoBueno/Import-Fertilizer-Bahia/refs/heads/main/UREIA.png)  

Para previsão de cada binômio "produto e mês", algumas informações adicionais já foram utilizadas no processamento, proporcionando maior precisão. A tabela a seguir apresenta quais informações adicionais foram consideradas:

![Tabela](https://raw.githubusercontent.com/AndreCoutinhoBueno/Import-Fertilizer-Bahia/refs/heads/main/tabela.png)
