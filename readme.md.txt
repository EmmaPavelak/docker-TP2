# Docker TP2
Une petite description du projet

## Question 2

### Une option de npm vous permet de n’installer que ce qui est nécessaire.
Quelle est cette option ? 

L'option de npm qui permet de n'installer que ce qui est nécessaire est "--production"

### Quelle bonne pratique Docker permet t-elle de respecter ?

Elle permet de réduire la taille de l'image Docker en ne copiant que les fichiers nécessaires pour l'exécution de l'application, et en ne téléchargeant que les dépendances nécessaires. Cela permet de respecter la bonne pratique Docker consistant à minimiser la taille des images Docker pour faciliter le stockage et la distribution des conteneurs.


## Question 3

### A l’aide de la commande docker build, créer l’image ma_super_app

Commande à lancer dans le dossier qui contient le Dockerfile :

```
docker build -t ma_super_app .

```

Résultat :

![](tp2_img1.png)


## Question 4 

### Compléter le fichier docker-compose.yml afin d’éxécuter ma_super_app avec sa
base de donnée

![](tp2_img2.png)


