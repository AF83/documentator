# Grunt

[The JavaScript Task Runner](http://gruntjs.com/)

## Installation

Version recommandée : 0.4
Il est supposé que nodejs est installé dans une version supérieure à 0.8

``` shell
npm install -g grunt-cli
```

## Modules projet

Pour installer les modules nécessaires au build d'un projet

``` shell
npm install .
```

## Utilisation

Pour connaitre la liste des taches disponibles

``` shell
grunt --help
```

Dans la plupart des cas, la tache par défaut permet de construire le projet

``` shell
grunt
```

## Auto-complétion

L'auto-complétion est possible pour bash en ajoutant la ligne suivante au
fichier `$HOME/.bashrc` :

``` bash
eval "$(grunt --completion=bash)"
```
