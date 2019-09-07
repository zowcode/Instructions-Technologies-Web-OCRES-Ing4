# Instructions Technologies Web OCRES Ing4

### Comment cloner un repo
Rendez vous sur la page github du repo et cliquer sur le bouton **fork** en haut à droite de la page.
Ceci permettra de créer votre propre copie du repo sur votre compte github.
Ainsi vous serez proprietaire de ce repo et donc libre d'en faire ce que vous voulez.

Une fois le repo forké, clonez le. Pour ce faire cliquer sur le bouton vert *clone or download*.
Copier le lien (bien vérifier que c'est un lien se finissant par .git)
Puis cloner le dans un dossier sur votre ordinateur (*local*).

#### En ligne de commande
```bash 
git clone LIEN_DU_REPO_A_CLONE.git
```

Une fois une feature / une étape suffisante du TP/Projet finit. Pensez à commit régulièrement. Créer un commit n’engage pas à push immédiatement, vous pouvez travailler et faire plusieurs commits avant de les push sur votre remote. 
Le commit n’est qu’une sauvegarde à un instant T, il vous permet si vous le souhaitez de revenir à cet instant (rollback).

##### Step 1 - Ajouter les fichiers pour le prochain commit
#
```bash 
git add <nom du fichier>
```
##### Step 2 - Créer et ajouter un message pour ce commit
#
```bash 
git commit -m "Feature ajouter bouton finit"
Ou
git commit
```
Vous pouvez et devez user de ces deux étapes au maximum à chaque fois que vous avancez dans votre projet !

##### Step 3 - Envoi de votre travail sur le repo à distance
#
```bash 
git push
```
Lorsque vous souhaitez synchroniser votre repo local avec celui à distance effectuez un git push

## Syntax code

#### Espacement

**Indentez votre code !!!** cela permet de le lire plus facilement

Espacement de **2** ou **4** espaces !

Exemple: 
```javascript 
if(variable){
    if(variable2){
        for(let i =0; i<10;i++){
            console.log(i);
        }
    }
}
```

#### Camel Case
Chaque variable ou objet doit être écrit en camelCase!
C'est à dire que la première lettre du nom de la variable doit être en minuscule et les prochains mots commencent en majuscule.

Exemple: 
```javascript 
let nomDeLaVariable = "valeur de la variable";
```

#### Class
Chaque nom de classe commence en **majuscule**.

Exemple: 
```javascript 
class NomDeLaClasse{
    constructor(props){
        super(props);
    }
}
```

## Contact

Clément Aceituno: clement@luseed.io
Loïc Berthelot: meet@loicberthelot.com
