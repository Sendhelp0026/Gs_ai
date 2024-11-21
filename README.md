# Gs_ai
1. Descrição do Problema
Com o aumento da adoção de veículos elétricos (VEs), surge a necessidade de uma gestão eficiente das estações de carregamento.
Este projeto tem como objetivo utilizar técnicas de Machine Learning para prever a demanda de carregamento em diferentes regiões.
2. Metodologia Utilizada
Para alcançar o objetivo, o projeto foi estruturado nas seguintes etapas principais:
- Coleta e limpeza de dados: O dataset fornecido contém informações sobre estações de carregamento, incluindo tipos de carregadores, disponibilidade e localização geográfica.
- Pré-processamento de dado: Valores ausentes ou inconsistentes foram tratados. As coordenadas geográficas foram extraídas e convertidas em formato numérico.
- Modelagem com Random Forest: O modelo foi utilizado para prever a quantidade de carregadores de carga rápida disponíveis (EV DC Fast Count), com base em atributos como localização e tipos de carregadores existentes.
- Divisão de dados: Os dados foram divididos em conjuntos de treino e teste (80/20) para avaliar o desempenho do modelo.
3. Resultados Obtidos
Após treinar o modelo de Random Forest com 100 árvores, os seguintes resultados foram obtidos:
- Mean Absolute Error (MAE): Avalia o erro médio absoluto entre as previsões e os valores reais.
- Mean Squared Error (MSE): Mede o erro médio quadrático, destacando grandes discrepâncias.
4. Conclusões
O modelo Random Forest mostrou-se eficaz para prever a disponibilidade de carregadores DC rápidos com base nos dados fornecidos.
No entanto, o modelo ainda não atendeu a nossas espectativas, posivelmente o modelo nececita de mais dados para conceguir distinguir com mais facilidade cada possição.
