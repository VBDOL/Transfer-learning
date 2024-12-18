# Treinamento de Redes Neurais com Transfer Learning

Aplicar o método de Transfer Learning em uma rede de Deep Learning na linguagem Python no ambiente COLAB. 


### Descrição do Desafio ###
 
#### Projeto de Transfer Learning em Python #### 
O projeto consiste em aplicar o método de Transfer Learning em uma rede de Deep Learning na linguagem Python no ambiente COLAB.  

Para exemplo, utilizaremos o seguinte projeto que realiza Transfer Learning com o Dataset do MNIST: 
https://colab.research.google.com/github/kylemath/ml4a-guides/blob/master/notebooks/transfer-learning.ipynb 

> Como o dataset possui muitas imagens, foi utilizado a função tf.keras.utils.image_dataset_from_directory para preparar o dataset. Evitando que a imagens fossem carregadas na memoria, como do colab anterior. 

O dataset utilizado engloba duas classes: gatos e cachorros. Uma descrição da base de dados pode ser visualizada neste link: https://www.tensorflow.org/datasets/catalog/cats_vs_dogs. 

Já o dataset para download pode ser acessado por meio deste outro link:

https://www.microsoft.com/en-us/download/details.aspx?id=54765. 

> O dataset recomendado tinha algumas figuras corrompido, com isto utilizei o seguinte dataset https://storage.googleapis.com/mledu-datasets/cats_and_dogs_filtered.zip 

Observações: Neste projeto, você pode usar sua própria base de dados (exemplo: fotos suas, dos seus pais, dos seus amigos, dos seus animais domésticos, etc), o exemplo de gatos e cachorros, pode ser substituído por duas outras classes do seu interesse. O Dataset criado em nosso projeto anterior, pode ser utilizado agora.  

O projeto deve ser enviado para o GitHub da DIO: https://github.com/digitalinnovationone.



#### Conclusão #### 
Neste colab, pode-se perceber a facilidade de treinamento e ajuste na RNA utilizando o Transfer Learning. Através de poucas épocas obtém um resultado muito satisfatório.
