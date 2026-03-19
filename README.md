# classificacao-iris-svm

# Classificação de Espécies de Flores Iris com SVM 🌸

Este projeto explora o uso do algoritmo **Support Vector Machine (SVM)** para a tarefa de classificação multiclasse, utilizando o clássico dataset *Iris*. O objetivo é identificar a espécie da flor com base em suas características morfológicas (comprimento e largura de sépalas e pétalas).

## 🚀 Resumo do Projeto

O desenvolvimento seguiu as etapas fundamentais de um fluxo de Ciência de Dados:
1.  **Análise Exploratória (EDA):** Verificação de integridade dos dados e estatísticas descritivas.
2.  **Pré-processamento:** Organização e tradução das variáveis para facilitar a interpretação.
3.  **Modelagem:** Treinamento de um classificador SVM utilizando a biblioteca Scikit-Learn.
4.  **Otimização:** Ajuste de hiperparâmetros para melhorar a robustez do modelo.
5.  **Avaliação:** Análise detalhada de performance através de Matriz de Confusão e Classification Report (Precision, Recall e F1-Score).

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python
* **Manipulação de Dados:** Pandas, NumPy
* **Visualização:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (SVM, train_test_split, metrics)

## 📊 Principais Resultados

* **Acurácia:** O modelo alcançou um desempenho elevado (cerca de 98%), demonstrando a eficácia do SVM para margens de separação bem definidas.
* **Estabilidade:** Através da comparação entre o modelo padrão e o otimizado, foi possível reduzir a variância dos resultados, garantindo predições mais confiáveis.
* **Insight de Negócio:** A análise mostrou que as dimensões das pétalas são os atributos com maior poder preditivo para diferenciar as espécies *Versicolor* e *Virginica*.

## 📈 Melhorias Futuras

Como parte da evolução contínua deste projeto, os próximos passos planejados são:
* Implementação de **Pipelines** para automação do fluxo de dados.
* Aplicação de **Feature Scaling (StandardScaler)** para testar o impacto na velocidade de convergência do SVM.
* Uso de **K-Fold Cross-Validation** para uma validação estatística ainda mais rigorosa.

---
**Autor:** Frederico Matheus
**Formação:** Cientista de Dados | Analista de Dados
