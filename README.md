# Code créatif Module 03 3D

## version
v 0.0.2

## objectif

Réaliser à l'aide du langage Processing les exercices suivants.
Un exercice est soit raté, soit réussit.
Chaque exercice rapporte des points, pour valider un module il faut obternir au moins 60% des points de l'ensemble du modules.
Dés que la norme n'est pas respectée, l'exercice est considéré comme raté.

L'ensemble des exercices sont à renvoyer par mail au correcteur en respectant l'arborescence et le nommage des dossiers, sous-dossiers et nom de fichiers. Si l'arborescence n'est pas respectée l'exercice ou le module ne seront pas corrigés et considérés comme ratés.
Vous avez des listes de `primitive, globale, opérateur, méthode, condition` ou `itération` que vous pourrez utiliser. Il n'est pas obligatoire de toutes les utiliser, par contre vous ne pouvez pas en utiliser d'autres.

La taille de la fenêtre pourra être changée par le correcteur.

Toutes les consignes sont valables pour l'ensemble du module sauf indication contraire.

```
dossier : nom prénom
sous-dossier : m##
sous-dossier : m##_ex##_nom
fichier :  m##_ex##_nom.pde
```
* exemple `Maurice_Dupont/m00/m00_ex_00_truc/m00_ex_00_truc.pde`


contraintes : 
respecter la [norme](https://github.com/StanLepunK/La-Voie-du-Code/blob/master/norme_voie_du_code.md)


## m03_ex00_box
```
sketch : m03_ex00_box.pde
intitulé :
Dans une fenêtre de 640 par 480.
Créer une boite centrée dans la fenêtre et qui tourne toute seule sur elle même.
```
```
primitive : float
globale : P3D, width, height
opérateur : / = + +=
méthode primaire : setup(), draw()
méthode secondaire : size(), background(), push(), translate(), rotateX(), rotateY(), rotateZ(), box(), pop()
condition :
itération :
classe :
liste :
```
## m03_ex01_box_control
```
sketch : m03_ex01_box_control.pde
intitulé :
Dans une fenêtre de 640 par 480.
Créer une boite centrée dans la fenêtre et qui tourne sur elle même grâce aux informations horizontale et verticale de la souris, il faut que le mouvement parraisse intuitif...
```
```
primitive : float
globale : P3D, width, height, mouseX, mouseY
opérateur : /
méthode primaire : setup(), draw()
méthode secondaire : size(), background(), push(), translate(), rotateX(), rotateY(), rotateZ(), box(), pop(), map()
condition :
itération :
classe :
liste :
```
## m03_ex02_switch
```
sketch : m03_ex02_switch.pde
intitulé :
Dans une fenêtre de 640 par 480.
Reprendre l'intitulé de l'exercice m03_ex01_box_control et ajouter la possibilité de changer de forme en appuyant sur la touche "N", les formes doivent être les suivantes : box, sphere, ellipse et square. Une fois que l'utilisateur est arriver à la forme square cela doit recommencer à partir de la première forme.
```
```
primitive : float, int
globale : P3D, width, height, mouseX, mouseY
opérateur : / ++ > ==
méthode primaire : setup(), draw(), keyPressed()
méthode secondaire : size(), background(), push(), translate(), rotateX(), rotateY(), rotateZ(), box(), ellipse(), square(), rect(), pop(), map(), switch(),
condition : break, case, default, key, if
itération :
classe :
liste :
```
## m03_ex03_vertex
```
sketch : m03_ex03_vertex.pde
intitulé : 
Dans une fenêtre de 640 par 480.
créer un triangle quelconque à l'aide de vertex. À chaque fois que l'utilisateur appuira sur une touche du clavier un nouveau rectangle sera généré et remplacera le précédent. Le triangle doit posséder des coordonnées dans les trois dimensions et différentes de zéro.
Vous aurez sans doute besoin de créer vos methodes.
```
```
primitive : int, float
globale : P3D, CLOSE, width, height
opérateur : new < ++ /
méthode primaire : setup(), draw(), keyPressed()
méthode secondaire : votre_methode(), size(), background(), beginShape(), endShape(), vertex(), random()
condition :
itération : for
classe : PVector
liste : liste statique
```
## m03_ex04_list
```
sketch : m03_ex04_list.pde
intitulé : 
Dans une fenêtre de 640 par 480.
créer un triangle quelconque à l'aide de vertex. À chaque fois que l'utilisateur appuira sur une touche du clavier un nouveau rectangle sera ajouté. Les triangles doivent posséder des coordonnées dans les trois dimensions et seront différentes de zéro.
Le modulo pourrait être utile.
```
```
primitive : int, float, boolean
globale : P3D, CLOSE, width, height
opérateur : new < ++ / % ==
méthode primaire : setup(), draw(), keyPressed()
méthode secondaire : votre_methode(), size(), background(), beginShape(), endShape(), vertex(), random(), ma_liste.add(), ma_liste.get(), ma_liste.size()
condition :
itération : for
classe : PVector, ArrayList
liste : liste dynamique
```
## m03_ex05_light
```
sketch : m03_ex05_light.pde
intitulé : 
Dans une fenêtre de 640 par 480.
Reprendre l'exercice précédent et mettez le en lumière.
L'utilisateur devra utiliser la toucche "N" pour ajouter des triangles et le touche "L" pour modifier la couleur de la lumière et sa direction.
```
```
primitive : int, float, boolean
globale : P3D, CLOSE, width, height, key
opérateur : new < ++ / % ==
méthode primaire : setup(), draw(), keyPressed()
méthode secondaire : votre_methode(), size(), background(), beginShape(), endShape(), vertex(), random(), ma_liste.add(), ma_liste.get(), ma_liste.size(), directionalLight()
condition :
itération : for
classe : PVector, ArrayList
liste : liste dynamique
```
## m03_ex06_move
```
sketch : m03_ex06_move.pde
intitulé : 
Dans une fenêtre de 640 par 480.
Reprendre l'exercice précédent et donnez à l'utilisateur la possibilité de manipuler le résultat comme un globe qu'il aurait entre ses mains.
Attention de jouer la scène par rapport à son centre...
```
```
primitive : int, float, boolean
globale : P3D, CLOSE, width, height, key
opérateur : new < ++ / % ==
méthode primaire : setup(), draw(), keyPressed()
méthode secondaire : votre_methode(), size(), background(), beginShape(), endShape(), vertex(), random(), ma_liste.add(), ma_liste.get(), ma_liste.size(), directionalLight()
condition :
itération : for
classe : PVector, ArrayList
liste : liste dynamique
```


