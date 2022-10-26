# NETTOYAGE DE DONNÉES WeRateDog

## by Ngan Desire
# Présentation du projet
L'ensemble des données que nous allons analyser et visualiser dans le cadre de ce projet est l’archive de tweets de l’utilisateur de Twitter @dog_rates, également connu sous le nom de WeRateDogs. WeRateDogs est un compte Twitter qui évalue les chiens des gens avec un commentaire humoristique sur le chien. Ces notes ont presque toujours un dénominateur de 10. Mais les numérateurs ? Presque toujours supérieur à 10. 11/10, 12/10, 13/10, etc. Pourquoi ? Parce que « ce sont des chiens Brent ». WeRateDogs compte plus de 4 millions d’abonnés et a reçu une couverture médiatique internationale.
# Structure des données
Les données ont été collecté de plusieurs sources qui sont les suivantes:
- Un fichier csv twitter-archive-enhanced.csv
- L'API de tweeter
# Nettoyage des données
Nous avons en résumé deceler des problemes de qualité et d'ordre consignés dans les documents suivants:
- Wrangle_act.pdf
- Wrangle_report.pdf
# Observation
- On remarque ici que 25% des notes sont comprises entre 0,8 et 1,2,75% des notes sont comprises entre 1,4 et 1,8 on remarque qu'il y'a des notes abérrantes de 2,8 et 3 et en dessous de 0,8
- En moyenne nous remarquons que les internautes like les photos des chiens trois fois.Pour certains chiens ces notes peuvent aller jusqu'a plus de 140000 fois
-  On remarque qu'il n'existe pas une corrélation linéaire entre le nombre de like et de retweet c'est pas forcément parcequ'ils aiment une photo qu'il le retweet.par contre elle devient constante à partir d'un certain nombre de retweet pres de 5000