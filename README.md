# 🧑‍💻 **Tri Distribué d'un Tableau avec Flask, Python et React** 

Ce projet implémente un algorithme de tri pour un tableau réparti sur **4 nœuds distribués** en utilisant **Flask (Python)** pour le backend et **React** pour le frontend. L'objectif est de comparer les performances entre l'exécution normale et l'exécution distribuée du tri sur un tableau généré automatiquement.

###  **Description**

- **Tri de tableau** : Le tableau est généré de manière aléatoire et l'utilisateur peut spécifier la taille du tableau.
- **Exécution normale** : Le tri est effectué sur un seul nœud.
- **Exécution distribuée** : Le tableau est divisé en 4 parties et chaque nœud trie sa portion de manière parallèle, puis les résultats sont fusionnés.
- **Objectif** : Comparer les temps d'exécution entre les deux approches (normale vs distribuée) pour voir les gains de performance dans le cas d'une grande taille de tableau.

### ⚙️ **Technologies utilisées**

- **Backend** : Python avec **Flask** pour gérer l'API REST.
- **Frontend** : **React** pour l'interface utilisateur.


🎬 **Démonstration vidéo**

Voici une vidéo de démonstration du projet. Vous y trouverez un aperçu de l'interface utilisateur et de la comparaison des temps d'exécution pour les différentes méthodes de tri.

[![Regarder la vidéo](/react-app/src/imagedemo.png)](https://drive.google.com/file/d/1gZcUQ2p00lsi4axwFufBaU6xW2qDipKl/view?usp=sharing)


