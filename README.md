# Saude-mental-das-pessoas-na-area-de-tecnologia
Este relatório tem como objetivo registrar os procedimentos realizados para análise da base de dados em torno do problema da qualidade de saúde mental de pessoas que trabalham na área de tecnologia.

Este trabalho seguiu as seguintes etapas:

1. **Entendimento do Problema e da Base de Dados:** Exploração do dataset para compreender sua construção, significado dos atributos e sua relação com o problema.

2. **Ajuste da Base de Dados:** Verificação e remoção de atributos irrelevantes para a análise, como "timestamp" e "comments". Ajuste do atributo "gender" através de filtragem e reagrupamento usando código em Python.

3. **Seleção de Features:** Análise das features mais relevantes usando quatro métodos de busca bioinspirados. Seleção final baseada nos atributos considerados relevantes por pelo menos 50% dos métodos.

4. **Teste dos Classificadores:** Utilização de diversos classificadores (Multilayer Perceptron, Random Forest, Random Tree, SVM, Naive Bayes, J48, Redes Bayesianas) com ajuste de hiperparâmetros para encontrar as melhores configurações. Dividido em três experimentos: aplicação de classificação com cross-validation (Experimento 1), aplicação do modelo encontrado no dataset original (Experimento 2) e treinamento de um modelo com divisão de ⅔ para treinamento e ⅓ para testes (Experimento 3).

5. **Comparação das Técnicas:** Análise e comparação dos resultados para entender a influência dos hiperparâmetros e dos métodos de busca na seleção de features, visando identificar o melhor método para o problema em questão.
