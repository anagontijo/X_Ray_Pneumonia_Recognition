# Reconhecimento de pneumonia em imagens de raio X
## Projeto de Ana Carolina Gontijo Graça para o curso de Aprendizado de Máquinas - UFMG 2019.1

# O banco de dados:
  O banco de dados utilizado foi obtido no kaggle, no link a seguir:
    https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

  A pasta "chest-xray-pneumonia/chest_xray/" deve estar na base onde você estiver rodando o notebook localmente.

# Tempo de execução:
  Como é um projeto de deep-learning, sua execução é muito lenta em um computador normal. Caso o programa esteja demorando para rodar localmente, descomentando as linhas 6, 7 e 8 da primeira célula de código e rodando o código no google colab com aceleração com GPU o tempo de execução é reduzido consideravelmente. Vale a pena notar que a parte de carregamento das imagens será mais lenta no google colab, mas os treinamentos serão mais rápidos. Descomentando as linhas especificadas será ativado o uso do Google Drive como fonte de dados, portanto será necessário que os arquivos estejam em um google drive.
