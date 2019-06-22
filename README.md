# Sistemas autônomos
O presente trabalho foi desenvolvido durante a disciplina de sistemas autônomos e foi dividido em duas partes pricipais, que serão descritas abaixos juntamente com a indicação de quais códigos foram utilizados.

## Pré requisitos
Para que seja possível replicar esse trabalho, o usuário deverá ter instalado em seu computador o programa anaconda. Para a execução da primeira parte do projeto, deverá ser criado o ambiente que está disponível sobe o nome de environment.ylm, enquanto para a execução da segunda parte serão necessárias as ferramentas presentes no ambiente cururu.ylm. O usuário poderá obtar por instalar seperadamente todas as ferramentas do python de forma independente desde que no momento da execução todas as ferramentas listadas nos dois arquivos citados anteriormente estejam presente no computador.

## 1º parte - Navegação autônoma
A primeira parte do presente projeto foi a execução do projeto desenvolvido pela empresa Udacity, que desenvolveu um simulador para a aplicação de redes neurais arficiais capazes de deixar o veículo autônomo. O simulador está disponível para download com o nome de beta_simulator_windows para computadores que utilizem como sistema operacional o windows ou com o nome de beta_simulator_linux para computadores que utilizem o sistema operacional Ubuntu.

### Execução do simulador
Ao executar o simulador, serão apresentadas duas opções, uma de treinamento e uma de navegação autônoma. Inicialmente deverá ser clicada na opção de treinamento para a gravação das imagens e dos ângulos a serem utilizadados no treinamento da rede neural CNN. Ao entrar na opção de treinamento deve ser clicado na botão de gravação e selecionado um diretório para os arquivos que serão gerados. Após a realização dos procedimentos citados anteriormente, o usuário deverá jogar com o veículo, procurando se manter sempre dentro dos limites da pista. Ao final de pelo menos duas voltas, deverá ser clicado para a finalização da gravação.

### Depois eu continuo

## 2º parte - Generative adversarial networks
A rede neural GAN é uma promissora rede para a geração de imagens baseadas em imagens prévias

## Execução da rede
Para a execução da rede GAN será necessário que o usuário faça o download do arquivo de nome ganTeste.py, que conterá a implementação da mesma. Será necessário também que sejam modificados os diretórios para o qual estejam localizadas as imagens que serão utilizadas para a geração, assim como será necessário criar um diretório de destino para as imagens que serão geradas. 

## Trabalhos relacionados
O presente código foi baseado em projetos prévios que utilizam a rede GAN para a geração de imagens.

O primeiro trabalho utiliza como dataset de imagens um dataset disponibilizado pelo Keras chamado MNIST, com configurações para que sejam utilizadas imagens do respectivo formato. O trabalho pode ser visualizado no [link](https://github.com/eriklindernoren/Keras-GAN/blob/master/gan/gan.py). O dataset utilizado pode ser visualizado no [site do keras](https://keras.io/datasets/), juntamente com os demais que estão disponíveis. É possível também modificar as imagens utilizadas como fonte de entrada desde que mantida a formatação da imagem. O código xxxxxxxxxxx disponibilizado neste github é capaz converter imagem para o formato utilizado no MNIST.

O segundo trabalho utiliza como dataset imagens dos Simpsons, onde este é capaz de aceitar imagens com formatos diferentes do primeiro trabalho e mais próximos do formato utilizado pelo simulador. O trabalho pode ser visualizado no [link](https://github.com/gsurma/image_generator), onde haverá o arquivo para ser baixo no formato ".ipynb" e indicações de como realizar o download do dataset para que se possa replicar o trabalho.
