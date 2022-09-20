# Classificação de Músicas em Gêneros Musicais

Esse repositório contém os códigos utilizados para o treinamento dos algoritmos SVM, K-NN, Árvores de Decisão e Redes Neurais Artificias para a classificação automática de gêneros musicais a partir de características sonoras.

Foram realizados 5 experimentos distintos cada um considerando 10-fold cross-validation no conjunto de treino do dataset. Internamente, para cada iteração do CV utilizamos uma estratégia nested CV com Grid Search para escolha dos melhores hiper-parâmetros para cada um dos algoritmos.