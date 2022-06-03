# Trabalho_Deep_Learning

Neste trabalho exploramos a classificação de imagens através da utilização de dois algoritmos e também fizemos um comparativo no intuito de identificar qual deles apresentou para esse processo a melhor performance em termos de acurácia.

Como ponto de partida adotamos um conjuto de dados composto por frutas e vegetais, o qual foi obtido via plataforma Kaggle e que inicialmente possuia 90483 imagens divididas em 131 classes, entretanto diminuímos esse escopo e optamos por trabalhar apenas com a identificação de maçãs, a qual apresentava 13 espécies (classes) e um total de 8538 imagens.

Para o processo de classificação e para a posterior comparação de eficácia, foram escolhidos os algoritmos de Redes Neurais Convolucionais (CNN) e o de aprendizagem de máquina K-Nearest Neighbors (KNN).

Após o treinamento destes dois algoritmos utilizando-se configurações variadas de parâmetros e hiperparâmetros, da execução dos testes e das predições, e da identificação da melhor performance obtida de cada um deles podemos atestar que ambos apresentaram resultados bastante satisfatórios e muito parecidos para o problema proposto e o conjunto de dados submetido à análise.

Sendo que a Rede Neural Convolucional (CNN) na sua melhor configuração apresentou 99,47% de acurácia, enquanto o K-Nearest Neighbors (KNN) atingiu 100% quando configurado com K até o valor 9, o que em um primeiro momento nos fez suspeitar de overfiting, entrentando ao continuarmos aumentando o valor de K percebemos uma queda lenta e gradual na acurácia, a qual se mostrou um pouco mais acentuada a apartir de K igual a 42, atingindo o valor de 99,30%, ainda assim um excelente percentual.
