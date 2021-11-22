Une demande qui revient de temps en temps avec Azure Purview, est la possibilité de mettre à jour les propriétés des assets à partir d'un existant comme un fichier Excel.

Dans cet article, je vais illustrer une manière possible pour répondre à ce besoin en utilisant les API Azure Purview. Au passage, Merci à Will Jonhson pour son aide !

## Description du scenario

Ici, nous avons un fichier excel qui contient les descriptions des colonnes de nos tables SQL. Vous noterez que la valeur de la colonne **"qualifiedName"** est le résultat d'une formule. Cela peut avoir de l'omportance, plus tard, dans le code python.

![Excel](Pictures/001.png)

