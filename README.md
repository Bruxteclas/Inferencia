# Exercício de Inferência Estatística com Dados de Pinguins

Este repositório contém um exercício prático de inferência estatística utilizando um conjunto de dados sobre pinguins. O objetivo é analisar as diferenças de peso entre machos e fêmeas e investigar se essas diferenças são estatisticamente significativas para toda a população de pinguins.

## Descrição do Exercício

Utilizando o conjunto de dados de pinguins disponível no seaborn, realizaremos análises estatísticas para verificar se existe uma diferença significativa no peso corporal entre machos e fêmeas, tanto de forma geral quanto para cada espécie de pinguim.

### Objetivos

1. **Diferença de Peso entre Machos e Fêmeas:**
   - Calcular estatísticas descritivas dos pesos corporais de machos e fêmeas.
   - Visualizar a distribuição dos pesos por sexo.
   - Realizar um teste t de Student para verificar se a diferença observada é estatisticamente significativa.

2. **Representação Gráfica do Teste:**
   - Plotar a distribuição t com a estatística do teste e a região crítica.

3. **Análise por Espécies:**
   - Repetir o teste t de Student para cada espécie de pinguim e analisar os p-valores associados.

### Insights Obtidos

1. **Diferença de Peso entre Machos e Fêmeas:**
   - Diferença de média: 683.41 gramas
   - Desvio padrão combinado: 729.43
   - Erro padrão: 79.95
   - Estatística do teste t: 8.55
   - Região crítica (RC): 1.65
   - p-valor: 0.00000
   - Conclusão: Rejeitamos a hipótese nula, indicando que há uma diferença significativa entre as médias de peso de machos e fêmeas.

2. **Representação Gráfica:**
   - A distribuição t foi plotada com a estatística do teste e a região crítica marcada, mostrando visualmente a significância do teste.

3. **Análise por Espécies:**
   - Espécie Adelie: Diferença de média: 674.66, Estatística t: 13.13, p-valor: 2.22e-26
   - Espécie Chinstrap: Diferença de média: 411.76, Estatística t: 5.21, p-valor: 2.04e-06
   - Espécie Gentoo: Diferença de média: 805.09, Estatística t: 14.74, p-valor: 1.92e-28
   - Conclusão: Em todas as três espécies, há uma diferença significativa entre os pesos de machos e fêmeas, sugerindo uma tendência geral nas espécies de pinguins estudadas.

