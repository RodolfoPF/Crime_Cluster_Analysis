# Projeto de Análise de Clusters para Crimes em São Francisco

Neste projeto de ciência de dados, conduzimos uma análise detalhada dos crimes na cidade de São Francisco. Nosso objetivo era identificar padrões e agrupamentos nos dados de crimes usando técnicas de análise de clusters. Para isso, utilizamos a linguagem R e várias bibliotecas especializadas.

## Desafio:
O desafio deste projeto consistia em entender a distribuição dos crimes na cidade e identificar regiões com padrões semelhantes de comportamento criminal. Essa análise poderia ser fundamental para o planejamento de estratégias de policiamento e segurança pública.

## Métodos Utilizados:
- Pré-processamento de Dados: Iniciamos o projeto com a limpeza e transformação dos dados brutos de crimes, considerando variáveis como tipo de crime, localização (latitude e longitude), data e horário.
- Escalonamento: Aplicamos a técnica MinMaxScaler() para normalizar as variáveis numéricas e garantir que todas estivessem na mesma escala.
- Análise de Clusters: Utilizamos o algoritmo KMeans para agrupar os dados em clusters com base nas características dos crimes. Experimentamos diferentes números de clusters (K) para encontrar o melhor agrupamento.
- Determinação do Número de Clusters (Elbow Method): Utilizamos o método de Elbow para identificar o número ótimo de clusters. Traçamos um gráfico da variabilidade explicada em relação ao número de clusters e buscamos o "cotovelo" no gráfico.
- Visualização Interativa: Para visualizar os resultados de forma interativa, utilizamos a biblioteca Plotly para criar um mapa dinâmico. Plotamos os clusters no mapa de São Francisco, destacando as áreas onde os crimes tinham padrões semelhantes.

## Resultado:
O projeto culminou na identificação de clusters de crimes na cidade de São Francisco. Esses clusters representam regiões geográficas onde a incidência de crimes é semelhante. A análise possibilitou insights valiosos para as autoridades de segurança pública na alocação eficiente de recursos.

## Impacto e Conclusão:
Este projeto demonstra o poder da análise de clusters na compreensão de padrões criminais em áreas urbanas. A visualização interativa do mapa dinâmico facilita a comunicação dos resultados e permite uma tomada de decisão mais informada por parte das autoridades. Ao adotar abordagens como o escalonamento, método de Elbow e a visualização em mapa, conseguimos realizar uma análise robusta e bem embasada para abordar o problema proposto.
