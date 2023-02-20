# Dev web

## Git 

Ceci est une commande :
``` bash
mkdir test
````


Ceci est du code : 

```javascript
const test = 'Hello wolrd' ;
````

La commande :
````
git init
````
permet d'initialiser, de créer un dépot Git local
elle aboutit a la création d'un repertoir .git
(se traduit par la présence d'un dossier cache `.git/`)

&nbsp;

l'édition ou l'ajout de ficher dans ce repertoire sera detecté par Git
Pour vérifier l'état de votre dépot et du nom de la branche dans le terminal, vous pouvez utiliser la commande : 
````
git status
````
&nbsp;

la commande
```
git branch -M name
```
permet de changer le nom de notre branche

&nbsp;

Avant de sauvegarder les modifications, il faut ajouter les modifications que l'on souhaite sauvegarder avec la commande : 

````
git add
````



&nbsp;

la commande 
````
git commit
````
fait une sauvegarde


&nbsp;


```
git config
```

&nbsp;

pour savoir qui touche a quoi et qu'est ce qui a été fait: 
````
git log
git dif
````

Si on a pas de vert ou de rouge c'est que tout est bon

&nbsp;

stagging area : la ou vont tous les fichiers à comitted, = zone intermédiaire de sauvegarde

&nbsp;

git add . : mettre à jour ce qui doit etre commit

&nbsp;

Le dépot Git ou repository est le dossier qui contient les données que l'on souhaite versionner

ssh : échange de clés publiques, protocole de chiffrement et de transport

pour configurer une clé ssh 


afficher le contenue d'un fichier 

````
cat filesname
````

copier la clé et la coller dans github