# biblioteca_pandas

O dataset que temos em mãos é composto por informações de vendas de uma loja virtual que atua em todo o território nacional, vendendo produtos de diferentes departamentos. Além disso, a loja atua em diferentes canais de vendas, como marketplace, loja própria, entre outros.

Premissas do negócio:
Devemos considerar algumas premissas existentes que dizem respeito ao funcionamento do negócio e que irão interferir em nossa análise. A primeira premissa é que, devido a um erro no sistema, algumas compras não possuem informações de UF (Unidade Federativa). Foi definido que essas compras teriam como endereço de origem o estado do Mato Grosso do Sul (MS). A segunda premissa é que o preço final de um produto não pode ser maior do que o preço com frete.

Métricas:
Com base nesse contexto e nas premissas de negócio estabelecidas, podemos avaliar as seguintes métricas:

1. Departamentos mais vendidos: Anallisando os dados de vendas, podemos identificar quais são os departamentos mais populares entre os clientes. Essa informação é útil para entender quais são as prefêrencias dos clientes e ajustar a estratégia de venda da loja.
2. Média de preço com frete por Nome de Departamento: Para entender a dinâmica de vendas de cada departamento, calculamos a média de preço com frete por departamento. Essa métrica nos ajuda a identificar quais são os setores mais rentáveis e ajustar a precificação de produtos de acordo com a margem desejada.
3. Quantidade de vendas por mês: Através da quantidade de vendas por mês, podemos identificar sazonalidades no comportamento dos consumidores e planejar campanhas de marketing, distribuição, níveis de estoque, entre outros para cada período.
4. Média de renda para cada tipo de canal de venda: A análise dessa métrica permite o planejamento de campanhas de marketing e vendas para público alvo.
5. Média de idade de clientes por bandeira: Saber a faixa etária dos clientes por bandeira nos ajuda a identificar perfis de consumidores e tomar medidas de acordo com esse perfil.
