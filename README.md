# Geração de Imagens Sintéticas com DCGANs no Keras
## DCGAN - Deep Convolutional Generative Adversarial Network

![image](https://user-images.githubusercontent.com/91763957/186495329-d31a1bf8-6162-45f9-a31f-cd66b2c02fb6.png)


## Objetivo
O objetivo principal do projeto é treinar um gerador de imagens sintéticas que consiga gerar novas imagens para cada uma das classes do dataset Fashion-MNIST. Além disso, pretende-se realizar modificações no script utilizado no dataset Fashion-MNIST para ser utilizado no dataset CIFAR10 que contém imagens coloridas. A Parte 1 deste trabalho está focada no dataset Fashion-MNIST, enquanto a Parte 2 está direcionada para o dataset CIFAR10.

## Datasets
O dataset utilizado na Parte 1 deste projeto foi o Fashion-MNIST que possui 70.000 imagens de moda. O Fashion-MNIST é um conjunto de dados das imagens do artigo de Zalando — que consiste em um conjunto de treinamento de 60.000 exemplos e um conjunto de testes de 10.000 exemplos. Cada exemplo é uma imagem em escala de tons de cinza, possuindo dimensão de 28×28, associada a um rótulo de 10 classes.
Cada exemplo de treinamento e teste é atribuído a um dos seguintes rótulos:

* 0 - Camiseta
* 1 - Calça
* 2 - Pullover
* 3 - Vestido
* 4 - Casaco
* 5 - Sandália
* 6 - Camisa
* 7 - Tênis
* 8 - Bolsa
* 9 - Bota

Para mais informações sobre o Fashion-MINIST acesse: https://github.com/zalandoresearch/fashion-mnist
<br>
O dataset utilizado na Parte 2 foi o CIFAR10 que possui 60.000 imagens coloridas, sendo o conjunto de treinamento composto por 50.000 exemplos e o conjunto de testes composto por 10.000 exemplos. Cada exemplo é uma imagem RGB, possuindo dimensão de 32x32, associada a um rótulo de 10 classes.
Cada exemplo de treinamento e teste é atribuído a um dos seguintes rótulos:

* 0 - avião
* 1 - automóvel
* 2 - pássaro
* 3 - gato
* 4 - veado
* 5 - cão
* 6 - rã
* 7 - cavalo
* 8 - navio
* 9 - caminhão
<br>
Para mais informações sobre o Fashion-MINIST acesse: https://www.cs.toronto.edu/~kriz/cifar.html

## Pipeline do Projeto
Pipeline adotado neste projeto para a geração de imagens sintéticas utilizando uma DCGAN:
<br>
1. Importa Bibliotecas;
2. Carrega o dataset e pré-processa os dados;
3. Cria os batches dos dados de treinamento;
4. Implementa o Gerador;
5. Implementa o discriminador;
6. Compila o DCGAN;
7. Define o procedimento de treinamento;
8. Implementa função para exibir e salvar as imagens geradas em cada época;
9. Treino do DCGAN;
10. Gera imagens sintéticas.

![image](https://user-images.githubusercontent.com/91763957/186495163-3906a8b0-3d6f-4539-9dba-49cea4241808.png)
