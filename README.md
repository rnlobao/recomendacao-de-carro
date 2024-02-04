# Recomendação veicular baseada em KNN
O trabalho tinha como objetivo a recomendacão de veículos à um usuário tendo um carro base. Ou seja, o usuário informa um carro que gosta e o nosso sitema deve
recomendar outros 3 semelhantes a ele.

Nossos datasets utilizados foram o [dataset](https://www.kaggle.com/datasets/ankkur13/edmundsconsumer-car-ratings-and-reviews/data?select=Scraped_Car_Review_mazda.csv) de rating
e o [dataset](https://www.kaggle.com/datasets/robsonnovato/car-features) com os veículos criado especialmente com todos veículos únicos do primeiro dataset.

A métrica de distância KNN com melhor resultado foi a do cosseno. Ademais, utilizando uma biblioteca externa foi possível baixar imagens da internet para deixar mais lúdico
para o usuário do sistema quais os veículos em questão. Com base na avaliação dos usuários do primeiro dataset, **72,98%** das recomendações tem rating >= a 4 (de 1 a 5).

<img src="https://github.com/rnlobao/recomendacao-de-carro/assets/66230142/8b4e3be9-0bd5-4ea1-a935-8224f9b5018b" alt="Imagem 1" width="400">
<img src="https://github.com/rnlobao/recomendacao-de-carro/assets/66230142/1851bc8b-9249-4a9e-9310-7be365809e58" alt="Imagem 2" width="400">
<img src="https://github.com/rnlobao/recomendacao-de-carro/assets/66230142/06b45505-6f06-4d98-aff3-0b48969e8691" alt="Imagem 3" width="400">


A imagem superior esquerda é o carro base, o restante são os carros recomendados.

Também plotamos as caracterísiticas e preço médio dos veículos para o usuário:
![image](https://github.com/rnlobao/recomendacao-de-carro/assets/66230142/0c1a9076-532e-47c0-a94b-15af6e03b356)
![image](https://github.com/rnlobao/recomendacao-de-carro/assets/66230142/ac461065-3759-4d45-98e6-dc69c5221b5f)


