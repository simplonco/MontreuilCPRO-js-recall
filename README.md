# JS RECALL

## Premier temps : Faire passer les testes !!!

*Inside you will find a collection of exercises to improve your Javascript.*

Dans ce repos, vous trouverez 3 fichiers (avec la nomenclature suivante : [nom].js) et leurs specs respectives ([nom].spec.js).

Dans les 3 fichiers specs, vous trouverez des testes que vous devez faire passer.

Vous devez donc implementer les fonctions du fichier [nom].js pour faire passer les testes du fichier [nom].spec.js

Vous trouverez aussi 3 fichiers specrunner.html qui suivent la numerotation des couples fichier/spec. Ces fichiers permettent de lancer les testes et d'en voir le resultat.

Pour commencer, ouvrer le fichier SpecRunner1.html dans un navigateur.

Pour info, les testes sont écrit en jasmine. La documentation peut être utile ;).

https://jasmine.github.io/2.0/introduction.html

Par exemple, pour eviter d'avoir des méchantes croix rouges sur les testes des fonctions que vous n'avez pas encore implémentés, vous pouvez simplement remplacer "it" par "xit" (cf. https://jasmine.github.io/2.0/introduction.html#section-Pending_Specs).

## Second temps : Lancer les testes via une command NPM

Pour ce faire, vous devez :

- initialiser npm dans vous projet
- installer jasmine
- ecrire le script npm pour lancer jasmine
- A ce moment, vous découvrirez qu'il vous faut légérement modifier les fichiers de spec pour qu'il passe sans le spec-runner.html

## Troisième temps : Lancer les testes sur github (intégration continue)

Pour ce faire, vous devez :
