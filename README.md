# MWE-embedded

Ce dépôt est le dépôt principal pour tous les Minimum Working Exampless (MWE) ayant trait au travail something_neat développé par les membres de l'équipe du [https://le-click.be/](CLICK) .
Ces MWE correspondent à la prise en main d'une technique, d'une librairie, d'un concept ou d'une carte électronique ou environnement matériel spécifique en rapport avec le monde de l'`embedded` qu'il s'agisse de microcontrolleur, d'IoT ou de Linux embarqué.

Ces MWE correspondent essentiellement au test de tutoriels trouver sur internet et à leur augmentation par le développement ou l'utilisation d'une feature particulière. En l'occurence, ces dépôts sont documentés et sourcés de manière à éviter les écueils de prise en main d'une nouvelle technologie.

<!-- TABLE DES MATIÈRES -->
<details open="open">
  <summary><h2 style="display: inline-block">Table des matières</h2></summary>
  <ol>
    <li><a href="#projets">Les projets</a></li>
    <li><a href="#utilisation">Utilisation du dépôt</a></li>
      <ul>
        <li><a href="#clone">Cloner le dépôt principal MWE-embedded</a></li>
        <li><a href="#add">Étapes pour ajouter un dépôt existant</a></li>
        <li><a href="#update">Pour mettre à jour un module</a></li>
      </ul>
    <li><a href="#contribution">Contribution</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#remerciements">Remerciements</a></li>
  </ol>
</details>



## Les projets

Les projets repris dans ce dépôt sont les suivants : 
* [MWE-ESP8266-APMod](https://github.com/loicreboursiere/MWE-ESP8266-APMod.git)
* [MWE-painlessMesh-ESP](https://github.com/loicreboursiere/MWE-painlessMesh-ESP-Ruisantos.git)
* [MWE-pymakr_MESH](https://github.com/loicreboursiere/MWE-pymakr_MESH.git)


## Utilisation du dépôt

### Cloner le dépôt principal MWE-embedded

Deux options : 
* Soit vous êtes intéressés par tous le dépôts :
```
git clone --recurse-submodules https://Your/repository
```
* Soit seulement quelques modules vous intéressent pour commencer : 
```
git clone
cd MWE-embedded/
git submodule update --init /path/to/submodule
```


### Étapes pour ajouter un dépôt existant

Deux options : 
* Soit cloner le dépôt, ajouter le submodule, commit et push
```
git clone https://github.com/loicreboursiere/MWE-embedded.git
git submodule add http://your.git.repo.adress
git commit -m "Addition of module git submodule add http://your.git.repo.adress"
git push -u origin main
```


* Une méthode moins orthodoxe, mais qui fonctionne : créer une nouvelle issue demandant à la personne qui maintient le dépôt général d'ajouter (ou de mettre à jour) un dépôt particulier. Cett issue devra contenir le texte et le lien à ajouter dans le README du dépôt global.

### Pour mettre à jour un module
* Soit vous avez une copie locale du dépôt et vous travaillez à partir de celle-ci, soit vous créez une nouvelle issue

```
cd existing/module
git fetch
git merge
cd ..
git add * (si rien d'autres n'attend d'être committé)
git commit -m "Update of existing/module"
git push -u origin main
```

## Contribution

## Licence

## Contact

## Remerciements
