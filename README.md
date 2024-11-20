
# Trabalho V2 - Ciência de Dados

## Contexto
Este projeto visa contribuir com ONGs de proteção animal por meio de uma solução que ajuda biólogos a classificar espécies de pinguins e fornecer insights úteis. Serão utilizados apenas dados numéricos para criar e avaliar modelos de classificação.

## Estrutura do Projeto
1. **Seleção de Algoritmos de Classificação**  
   - Árvore de Decisão  
   - Floresta Aleatória  


2. **Definição de Métrica de Avaliação**  
   Escolhi métricas (como F1, Recall, Precisão, ou AUC ROC)

3. **Criação e Avaliação de Modelos**  
   - Treinei e avaliei modelos usando validação cruzada.  
   - Apliquei Grid Search para otimização.  
   - Listei a importância dos atributos.  

4. **Verificação de Overfitting e Underfitting**  
   Avaliei e justifiquei a existência de problemas de ajuste nos modelos.

5. **Análise de Clusters**  
   - Utilizei K-Means para análise de clusters.  
   - Comparei o número de clusters e centróides com as espécies existentes.  
   - Normalize os dados antes da análise.

## Dados Utilizados
Os dados contêm as seguintes variáveis:  
- **Variável Alvo**: Espécie (Chinstrap, Adélie, Gentoo)  
- **Atributos Numéricos**:  
  - `culmen_length_mm`  
  - `culmen_depth_mm`  
  - `flipper_length_mm`  
  - `body_mass_g`  

Outras variáveis como `ilha` e `sexo` foram descartadas.

## Links Úteis

- [DecisionTreeClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html)  
- [RandomForestClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)  
- [KMeans](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)  
- [Confusion Matrix](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.confusion_matrix.html)  
