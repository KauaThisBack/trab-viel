Este código implementa um modelo de Rede Neural Convolucional (CNN) utilizando a biblioteca TensorFlow/Keras para classificação de imagens do conjunto 
de dados CIFAR-10. 
O conjunto de dados CIFAR-10 é composto por 60.000 imagens coloridas de 32x32 pixels, divididas em 10 classes.
O código carrega os dados de treinamento e teste da CIFAR-10 e realiza a normalização das imagens para facilitar o treinamento do modelo.
Em seguida, é definida uma lista com os nomes das classes presentes no conjunto de dados.
Uma amostra das imagens de treinamento é exibida, juntamente com seus respectivos rótulos, para visualização.
Em seguida, o modelo de CNN é construído, composto por camadas convolucionais, camadas de max pooling e camadas densas. A função de ativação 'relu'
é utilizada nas camadas convolucionais e densas.
O modelo é compilado com o otimizador 'adam', a função de perda 'SparseCategoricalCrossentropy' e a métrica de avaliação 'accuracy'. Em seguida,
o modelo é treinado por 10 épocas usando os dados de treinamento e é validado nos dados de teste a cada época. O histórico de treinamento é armazenado
para visualização posterior.
As curvas de precisão (accuracy) são plotadas para análise do desempenho do modelo durante o treinamento. Em seguida, o desempenho final do modelo é 
avaliado nos dados de teste, obtendo-se a perda e a precisão.
Por fim, uma imagem dos dados de teste é selecionada, exibida juntamente com seu rótulo verdadeiro e submetida ao modelo para previsão. As probabilidades
de pertencer a cada classe são impressas.
Em resumo, o código carrega, pré-processa, constrói, treina e avalia um modelo de CNN para classificação de imagens do conjunto de dados CIFAR-10, fornecendo 
visualizações e métricas de desempenho ao longo do processo.
