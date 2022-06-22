# MWE-embedded

Dépôt principal pour tous les MWE (Minimum Working Exemples) ayant trait au développement embarqué qu'il s'agissent de microcontrolleur, d'IoT ou de Linux embarqué.

## Étapes pour ajouter un dépôt existant


Deux options : 
* Soit cloner le dépôt, ajouter le submodule, commit et push
`git clone https://github.com/loicreboursiere/MWE-embedded.git`
`git submodule add http://your.git.repo.adress`
`git commit -m "Addition of module git submodule add http://your.git.repo.adress"`
``git push -u origin main`
* Une méthode moins orthodoxe, mais qui fonctionne : créer une nouvelle issue demandant à la personne qui maintient le dépôt général d'ajouter (ou de mettre à jour) un dépôt particulier. Cett issue devra contenir le texte et le lien à ajouter dans le README du dépôt global.

## Pour mettre à jour un module
* Soit vous avez une copie locale du dépôt et vous travaillez à partir de celle-ci, soit vous créez une nouvelle issue

`cd existing/module`
`git fetch`
`git merge`
`cd ..`
`git add *` (si rien d'autres n'attend d'être committé)
`git commit -m "Update of existing/module"`
`git push -u origin main`