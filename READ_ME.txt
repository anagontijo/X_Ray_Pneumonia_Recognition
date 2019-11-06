O banco de dados está no google drive da conta:

proj.final.ml.2019@gmail.com

com a senha:

2016074242

A pasta "resized_xrays" deve estar na base onde você estiver rodando o notebook localmente.

Caso o programa esteja demorando para rodar localmente, descomentando as linhas 6, 7 e 8 da primeira célula de código e rodando o código no google colab com aceleração com GPU (foi como eu rodei) irá utilizar os dados a partir do google drive desta conta (é necessário autenticar no inicio do runtime, e as vezes será necessário reiniciar o runtime após a autenticação para que o google drive funcione direito). Vale a pena notar que a parte de carregamento das imagens será mais lenta no google colab, mas os treinamentos serão mais rápidos.
