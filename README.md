# Classificador d'art japonés

*Aquest jupyter notebook va ser un projecte creat per @diana-fsa durant el tercer curs d'universitat l'any 2020.*

> Es poden classificar les obres d'art segons els artistes?

Al fitxer `code-catalan.ipnyb`[^1] s'explora la base de dades i es crea un classificador d'imatges per arribar a una resposta.

El [dataset](https://www.kaggle.com/kengoichiki/the-metropolitan-museum-of-art-ukiyoe-dataset) tracta d'imatges "Ukiyo-e" ( gènere de gravats xilogràfics i pintures produïts al Japó entre els segles XVII i XX ) procedents del Metropolitan Museum of Art sota la llicència CC0.
![Image1](https://github.com/diana-fsa/ukiyo-e/blob/main/img/exp.png)

Aquest dataset conté les imatges originals amb una alta resolució. Cada imatge és a la carpeta amb el nom del seu corresponent autor.
Hi ha un total de 4040 imatges de 50 autors diferents.

Aquest notebook es centrarà en els 5 autors amb més obres d'art: Utagawa Hiroshige, Katsushika Hokusai, Katsukawa Shunsho, Kubo Shunman i Kitagawa Utamaro.

![Image2](https://github.com/diana-fsa/ukiyo-e/blob/main/img/5authors.png)

El classificador d'imatges es tracta d'una xarxa neuronal senzilla creada amb `TensorFlow` (ja que va ser un dels primers projectes als que vaig utilitzar xarxes neuronals per primera vegada). I va obtenir bons resultats.

![Image3](https://github.com/diana-fsa/ukiyo-e/blob/main/img/resultat.png)

[^1]: Quan s'obre el fitxer, github retorna "The notebook took too long to render." i no ensenya el codi. Per visualitzar-lo podeu clicar l'enllaç següent [code-catalan.ipynb](https://nbviewer.org/github/diana-fsa/ukiyo-e/blob/main/code-catalan.ipynb)


# Classifier of Japanese art

*This jupyter notebook was a project created by @diana-fsa at third year of college in 2020.*

> Can we classify art pieces by their artists?

In the file `code-english.ipnyb`[^2] there is first a approximation of the data base and an image classifier is built to get to an answer.

The [dataset](https://www.kaggle.com/kengoichiki/the-metropolitan-museum-of-art-ukiyoe-dataset) has "Ukiyo-e" ( a genre of woodblock prints and paintings made in Japan from the 17th through 19th centuries ) images proceding from the Metropolitan Museum of Art under the CC0 licence.
![Image1](https://github.com/diana-fsa/ukiyo-e/blob/main/img/exp.png)

This dataset contains the original images in high resolution. Every image is in the folder with the name of its corresponding author. 
There is a total of 4040 images from 50 different painters. 

This notebook focuses on the 5 authors with more paintings: Utagawa Hiroshige, Katsushika Hokusai, Katsukawa Shunsho, Kubo Shunman and Kitagawa Utamaro.

![Image2](https://github.com/diana-fsa/ukiyo-e/blob/main/img/5authors.png)

The image classifier is a simple neural network created using `TensorFlow` (as it was one of the first projects in which I used neural networks for the first time). And the results were good.

![Image3](https://github.com/diana-fsa/ukiyo-e/blob/main/img/resultat.png)

[^2]: When the file is opened, github returns "The notebook took too long to render." and it doesn't show the code. To see it you can click on the following link  [code-english.ipynb](https://nbviewer.org/github/diana-fsa/ukiyo-e/blob/main/code-english.ipynb)
