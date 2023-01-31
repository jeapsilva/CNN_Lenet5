<h1 align='center'> Rede Neural Convolucional com Pytorch </h1>


# Descrição do Projeto 

* **Introdução**
Nesse projeto vamos criar toda a arquitetura da rede neural convolucional (CNN), treinar e avaliarmos a convergência do modelo desenvolvido. 

* **Base de dados**
A base de dados utilizada para o treinamento e dev da nossa rede neural foi o *CIFAR10*, que é um conjunto de dados de visão computacional estabelecido usado para reconhecimento de objetos. É um subconjunto do conjunto de dados de 80 milhões de imagens minúsculas e consiste em 60.000 imagens coloridas de 32 x 32 contendo uma das 10 classes de objetos, com 6.000 imagens por classe. Foi coletado por Alex Krizhevsky, Vinod Nair e Geoffrey Hinton.

<img src='https://imgur.com/undefined' widht='700'>

A base de dados pode ser encontrada em: https://www.kaggle.com/c/cifar-10

# LeNet5

* **O que é o LeNet5?**

Lenet-5 é um dos primeiros modelos pré-treinados propostos por Yann LeCun e outros no ano de 1998, no artigo de pesquisa Gradient-Based Learning Applied to Document Recognition . Eles usaram essa arquitetura para reconhecer os caracteres manuscritos e impressos à máquina.

A principal razão por trás da popularidade deste modelo foi sua arquitetura simples e direta. É uma rede neural de convolução multicamadas para classificação de imagens.

* **Arquitetura da rede**

A rede tem 5 camadas com parâmetros que podem ser aprendidos e, portanto, denominada Lenet-5. Ele tem três conjuntos de camadas de convolução com uma combinação de agrupamento médio. Após as camadas de convolução e pooling médio, temos duas camadas totalmente conectadas. Por fim, um classificador Softmax que classifica as imagens em suas respectivas classes. Vale lembrar que a entrada para para o modelo é uma imagem em escala de cinza (1 só canal) nas dimensões de 32x32.

<img src="https://imgur.com/5IRp8aO.jpg" width="700">

<img src='https://imgur.com/j4fh28P.jpg' width='700'>

# Pessoas Desenvolvedoras do Projeto

<a href="https://github.com/jesapsilva">Jéssica Aparecida Silva - Cientista de dados</a>

# Licença

<img src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-nc.svg" />


Esta licença permite que outros remixem, adaptem e criem a partir do seu trabalho para fins não comerciais e, embora os novos trabalhos tenham de lhe atribuir o devido crédito e não possam ser usados para fins comerciais, os usuários não têm de licenciar esses trabalhos derivados sob os mesmos termos.

