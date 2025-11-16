# Projet-Dana-Groupe-5
# Les footballeurs les plus chers de 2021  
### Par : Dabin Yanis , Mhabrech Ilef , Mhedhbi Khalil 


### 1. Description: 
Dans le cadre du projet Dana, nous avons choisi d’exploiter un dataset portant sur les joueurs de football les plus chers en 2021.
Ce dataset, disponible sur Kaggle, recense plus de 500 joueurs avec leurs caractéristiques personnelles, leur valeur marchande, 
ainsi que diverses statistiques de performance.

source :
```sh
https://www.kaggle.com/datasets/sanjeetsinghnaik/most-expensive-footballers-2021
```

### 2. Importation du Dataset
Nous avons téléchargé le fichier ```players.csv ``` depuis Kaggle, 
puis nous l’avons importé dans OpenRefine afin d'effectuer le nettoyage et la transformation des données.

### 3. Transformation en RDF
Nous avons utilisé l’extension RDF Transform d’OpenRefine pour convertir le CSV en RDF.
#### Étapes réalisées :
Installation de l’extension RDF Transform <br>
Création du modèle RDF <br>
Définition des préfixes (namespaces) <br>
Mappage des colonnes du CSV vers des propriétés RDF<br>
Nettoyage et uniformisation des données<br>
Export du résultat en format Turtle (.ttl)<br>
#### Fichier obtenu : ``` players.ttl ```

### 4 . Visualisation du graphe RDF
Voici le graphe RDF obtenu à partir du fichier Turtle :
![Projet-Dana-Groupe-5](rdf-grapher.png)

### 5 . Résumé : 
Nous avons réalisé l’ensemble du workflow de transformation :
```
CSV ➜ Nettoyage OpenRefine ➜ Modèle RDF ➜ Export Turtle ➜ Visualisation du graphe. 
```
