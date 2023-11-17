# Classifiez_automatiquement_des_biens_de_consommation

Réaliser, dans une première itération, une étude de faisabilité d'un moteur de classification d'articles, basé sur une image et une description, pour l'automatisation de l'attribution de la catégorie de l'article.

Analyser les descriptions textuelles et les images des produits, au travers:
- d'un prétraitement des données texte ou image suivant le cas 
- d'une extraction de features 
- d'une réduction en 2 dimensions, afin de projeter les produits sur un graphique 2D, sous la forme de points dont la couleur correspondra à la catégorie réelle + analyse du graphique afin d’en déduire ou pas, à l’aide des descriptions ou des images, la faisabilité de regrouper automatiquement des produits de même catégorie

Réalisation d’une mesure pour confirmer l' analyse visuelle, en calculant la similarité entre les catégories réelles et les catégories issues d’une segmentation en clusters.
Sera mis en œuvre : 
-deux approches de type “bag-of-words”, comptage simple de mots et Tf-idf 
-une approche de type word/sentence embedding classique avec Word2Vec
-une approche de type word/sentence embedding avec BERT
-une approche de type word/sentence embedding avec USE (Universal Sentence Encoder). 

Afin d’extraire les features image, il sera nécessaire de mettre en œuvre :
- un algorithme de type SIFT / ORB / SURF ;
- un algorithme de type CNN Transfer Learning.
