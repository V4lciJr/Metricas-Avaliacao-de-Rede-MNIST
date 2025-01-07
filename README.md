# Implementação de Rede Neural para Classificação do Dataset MNIST

## Métricas de Avaliação
Este projeto apresenta uma implementação de uma rede neural para classificar imagens do dataset MNIST, utilizando métricas de avaliação avançadas.

### Dataset MNIST
----------------
 - Conjunto de dados de imagens de dígitos manuscritos (0-9)
 - 60.000 amostras de treinamento e 10.000 de teste
 - Imagens em tons de cinza, 28x28 pixels

### Características
-----------------
 - Arquitetura: Rede neural convolucional (CNN)
 - Camadas: Conv2D, MaxPooling2D, Flatten, Dense
 - Otimizador: Adam
 - Função de custo: Sparse Categorical Crossentropy
 - Métricas: Acurácia, Precisão, Recall, F1-Score

### Arquitetura da Rede Neural
-----------------------------
 - Modelo de classificação multiclasse
 - Camadas de convolução e pooling
 - Camadas densas com ativação ReLU e softmax
 - Otimizador Adam e função de custo categorical cross-entropy

### Métricas de Avaliação
-----------------------
 - Acurácia: Proporção de previsões corretas.
 - Precisão: Proporção de verdadeiros positivos entre todos os positivos previstos.
 - Recall (Sensibilidade): Proporção de verdadeiros positivos entre todos os verdadeiros positivos reais.
 - Especificidade: Proporção de verdadeiros negativos entre todos os negativos reais.
 - Curva ROC e AUC-ROC: Avaliam a capacidade do modelo em distinguir classes.

### Resultados
------------
 - Acurácia: 98.5%
 - Precisão: 98.4%
 - Recall: 98.5%
 - F1-Score: 98.4%
 - Matriz de confusão e curva ROC

### Dependências
------------
 - Python 3.x
 - TensorFlow 2.x
 - Scikit-learn
 - Pandas
 - NumPy
 - Matplotlib
 - Seaborn

### Contribuições
------------
Sinta-se à vontade para contribuir com melhorias e sugestões!

>**Este código foi desenvolvido no Desafio do Bootcamp da BairesDev na plataforma da (DIO)[https://www.dio.me/]**
