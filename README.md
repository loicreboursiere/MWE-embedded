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