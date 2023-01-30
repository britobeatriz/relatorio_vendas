# Relatório de Vendas
Dashboard criado a partir de dados de vendas de produtos

# ETL - Extração, Transformação e Carregamento dos dados
Após carregar os dados para o Power BI eu realizei a modelagem e transformação dos mesmos conforme a necessidade dos requisitos que eu teria que informar no Dashboard.

![Relacionamento](/imagens/readme_img/TAB_DIM.png) 

Por fim o modelo ficou assim:

![Medidas](/imagens/readme_img/TAB_DIM_MEDIDAS.png) 

# Criação de calculos com linguagem M

Calculo do faturamento:

&nbsp;
```faturamento = SUM(vendas[ValorVenda])```

Quantidade de pedidos:

&nbsp;
```qtde_pedidos = COUNTROWS(vendas)```

Ticket médio:

&nbsp;
```ticket_medio = DIVIDE([faturamento],[qtde_pedidos])```

![texto](/imagens/readme_img/DASHBOARD.jpg) 

Link para visualizar o Dashboard: <a href="https://app.powerbi.com/view?r=eyJrIjoiZGZjODA4OGQtNzQ5Yi00NTYyLWIxZWQtN2Y0YjFiZmZhNDcyIiwidCI6ImFmZjhlZWE0LTNkM2MtNGE0OC1hZGIwLTAxNzMwNDBjNDQyMSJ9">AQUI</a>
