# Analise-Descritiva-Excel
Analise descritiva utilizando o Excel

## O Problema de Negócio:

A Store X é uma rede de supermercado com várias unidades físicas
espalhadas por todo o Brasil, com o objetivo de fornecer alimentos e comercializar os mais diversos produtos para consumo.

A time de gerentes da Store X decidiu construir um time de dados para facilitar as decisões da empresa com relação ao abastecimento de produtos das lojas e também das vendas. 
Hoje, os gerentes tem acessos a algumas planilhas de dados com informações pontuais que ajudam nas decisões, mas eles gostariam de que todos os dados da empresa fossem integrados de modo com que cada área acompanhasse os mesmos indicadores.

O time de dados vai desempenhar um papel importante na criação desse indicadores da empresa, pois terão acesso aos dados transacionais para analisar o comportamento dos clientes, descrevendo os produtos que mais compram, a quantidade comprada, o tamanho da cesta de compra, o valor médio de gasto em cada compra, os produtos devolvidos, os números de pedidos feitos dentro de um determinado tempo e assim por diante.

Essas análises de dados geram insights que abrem espaço para entender como o negócio da empresa funciona do ponto de vista analítico, as razões de aumento ou diminuições dos números de pedidos, entre outras perguntas cuja resposta ajudam na tomada de decisão.

**Em outras palavras, como estão indo os pedidos da Store X?**

### Premissas:

* 1 Definição do Fato:
  
  Coluna "Order Id"
  

* 2 Definição das Dimensões
  
  | Coluna        |  Dimensão     |
  | ------------- |:-------------:|
  | Order Date    | Tempo         |
  | Ship Date     | Tempo         |
  | Ship Mode     | Entrega       |
  | Sales         | Produto       |
  | Quantity      | Produto       |
  | Discount      | Produto       |
  | Product       | Produto       |



* 3 Combinação Fato-Dimensão:

  3.1 Quantidade de Pedidos por Data (Dia, Mês, Ano)
  
  3.2 Quantidade de Pedidos por Quantidade de Itens
  
  3.3 Quantidade de Pedidos por Clientes

  ## Analise Descritiva:

* **Analise 1: Quantidade de Pedidos por Mês**

  <div align="center">
  <img src="https://github.com/user-attachments/assets/b355fbf3-9c68-47f2-a25b-f9c0e95d70f2" />
  </div>

  A linha de tendencia mostra um crescimento positivo no período analisado.
  Havendo um aumento nos pedidos nos meses de **Setembro**, **Novembro** e **Dezembro**.

---

* **Analise 2: Quantidade de Clientes Únicos por Mês**
 
  <div align="center">
  <img src="https://github.com/user-attachments/assets/f535b845-8e77-4ee8-899f-d7d5cb780c4b" />
  </div>

  A analise 1 e 2 tem correlação positiva, mostrando que o número de Pedidos aumenta quando o número de Clientes também aumenta. ( Os gráficos são quase iguais )
  
---

* **Analise 3: Quantidade de Pedidos por Item**

  <div align="center">
  <img src="https://github.com/user-attachments/assets/ab57c455-a14f-4a00-9368-ce844df6a719" />
  </div>

  O gráfico mostra a concentração no número de itens por pedido de cada cliente.
  A maior parte dos pedidos fica concentrado em 2 (**2.402 Pedidos**) e 3 (**2.409 Pedidos**) itens por pedidos respectivamente.
  
---

* **Analise 4: Média de Pedidos por Clientes Únicos**

  <div align="center">
  <img src="https://github.com/user-attachments/assets/ffd6400f-970d-496b-a83f-048ad89809a4" />
  </div>

  A média de pedidos por cliente fica em torno de 2. 
  Os meses de **Setembro**, **Novembro** e **Dezembro** puxam essa média pra cima chegando a 3.
  
---

* **Analise 5: Percentual da Modalidade de Entrega**

  <div align="center">
  <img src="https://github.com/user-attachments/assets/1de968b4-9405-433b-b3b1-80483c2b1903" />
  </div>

A maior porcentagem de clientes, **60%**, preferem a entrega normal. 
Aceitam esperar o prazo padrão de 5 dias uteis.
E apenas **5%** querem receber o produto no mesmo dia.




    









  

  
        
