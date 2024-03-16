<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <span>Formação Machine Learning Specialist</span>
</h1>


# :computer: Desafio de projeto: 

## Criando um Sistema de Recomendação por Imagens Digitais
Sistema de recomendação por imagens 
Depois de entender o funcionamento de Sistemas de Recomendação e suas aplicações, neste projeto vamos então desenvolver um modelo capaz de classificar imagens por sua similaridade e gerar resultados para o usuário de um site. Os resultados esperados são direcionados para, por meio de um produto buscado na internet, o Sistema de Recomendação deve indicar produtos relacionados, mas não por seus dados textuais (preço, modelo, marca, loja) e, sim, por sua aparência física (formato, cor, textura, etc).  

Para que este sistema seja desenvolvido, vamos treinar uma rede de Deep Learning com várias classes de objetos, como por exemplo: relógio, camiseta, bicicleta, sapato, etc.  Dentro de cada classe devemos ter objetos que são parecidos em sua aparência.


Para exemplo, podemos então utilizar o sistema de recomendação por imagens apresentado a seguir: https://colab.research.google.com/github/sparsh-ai/rec-tutorials/blob/master/_notebooks/2021-04-27-image-similarity-recommendations.ipynb 

 
# :bulb: Solução do desafio

A solução se encontra no jupyter notebook imageSimilarity.ipynb

Segui o exemplo dado mas ao invés do colab usei o [lightingAI](https://lightning.ai/). No Colab excedia o tempo de simulação e a GPU ficava indisponível.

Retirei do step 6 em diante do exemplo pois não se faz necessário para esse projeto. 