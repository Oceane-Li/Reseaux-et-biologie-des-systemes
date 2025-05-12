# RESYS Project : Breast Cancer Gene Expression Profiles (METABRIC)

Auteurs : Océane LI, Adam BOUMESSAOUD, Thomas LOUVET



### Le dataset METABRIC

Le fichier `METABRIC_RNA_Mutation.csv` contient toutes les données brutes du dataset METABRIC sur 1904 patients atteints du cancer du sein.


### Le fichier `Metabric_gene_expression.Rmd`

Ce fichier contient tous les codes de prétraitement des données du dataset METABRIC, pour obtenir les fichiers CSV qui servent à reconstruire les réseaux de relations entre les différentes catégories de features et l'expression des gènes.

Pour reconstruire les graphes mentionnés dans notre rapport, il suffit de lancer ce code pour obtenir les fichiers CSV qui correspondent à chaque groupe de features (survie, traitement, variables cliniques, etc.), puis donner ces fichiers CSV générés en input à l'outil MIIC online. Vous obtiendrez les réseaux correspondants reconstruits par MIIC.


### Le fichier `Metabric_mutations.Rmd`

Ce fichier contient tous les codes de prétraitement des données du dataset METABRIC, pour obtenir les fichiers CSV qui servent à reconstruire les réseaux de relations entre les différentes catégories de features et les données de mutations.

Pour reconstruire les graphes mentionnés dans notre rapport, il suffit de lancer ce code pour obtenir les fichiers CSV qui correspondent à chaque groupe de features (survie, traitement, variables cliniques, etc.), puis donner ces fichiers CSV générés en input à l'outil MIIC online. Vous obtiendrez les réseaux correspondants reconstruits par MIIC.


### Le fichier `test_clustering_miic.Rmd`

Ce fichier contient du code qu'on a construit nous-même pour générer des réseaux, à l'aide d'outils vus en TP de RESYS.

Nous avons tenté de reconstuire un graph à partir de la matrice d'adjacence obtenue avec MIIC.