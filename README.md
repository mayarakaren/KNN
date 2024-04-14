## Título do Projeto: Classificação de Espécies de Iris com k-Nearest Neighbors

### Descrição:
Este repositório contém um código em Python para classificação de espécies de íris usando o algoritmo k-Nearest Neighbors (k-NN). O conjunto de dados Iris é um conjunto de dados clássico amplamente utilizado para fins de aprendizado de máquina e mineração de dados. O código realiza as seguintes tarefas:

- Carrega o conjunto de dados Iris a partir de um arquivo CSV.
- Pré-processa os dados, garantindo que não haja valores ausentes.
- Divide os dados em conjuntos de treinamento e teste.
- Utiliza o algoritmo k-NN com diferentes valores de k (vizinhos) para classificar as amostras de teste.
- Avalia o desempenho do modelo usando a métrica de acurácia.
- Identifica o melhor valor de k com base na acurácia do modelo.

Além disso, o código está configurado para ser executado periodicamente, utilizando a biblioteca `schedule`, para atualizar o desempenho do modelo ao longo do tempo.

### Tecnologias Utilizadas:
- Python
- scikit-learn (sklearn)
- pandas
- NumPy

### Como Usar:
1. Clone este repositório para o seu ambiente local.
2. Certifique-se de ter todas as dependências instaladas, conforme listado no arquivo `requirements.txt`.
3. Execute o arquivo `knn_iris.py`.
4. Visualize as saídas do modelo k-NN para diferentes valores de k e o melhor desempenho alcançado.

Este projeto é útil para iniciantes em aprendizado de máquina que desejam entender e praticar o uso do algoritmo k-NN para classificação de dados.

---
