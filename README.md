deux fonctionalitées

(seulement pour que je comprenne l'exo 2 (j'crois))

EXERCICE 6::

J'ai choisie git revert car en projet, avec plusieurs personnes dans un groupe, il est préférable de prendre le "git revert" au "git reset". Pourquoi ?
Tout simplement car un "git revert" permet d'annuler un commit precis que l'on veut enlever et le supprimer par la meme occasion avec les changements que j'avais ajouté. Ce qui est ce que je veux.

Alors que le "git reset" aurait pu etre utile mais il est très dangereux pour le repo de l'utiliser si l'on veut modifier un commit déjà push. Car le "git reset", va juste intervertir les commit entre eux sauf si on utilise --hard avant HEAD-x.
Mais cela reste plus compliqué a utilisé il est donc préférable d'utiliser le "git revert".

Et il y a toujours un risque de tout casser avec le "git reset", car si une personne a pull le premier push, mais a fait des modification dessus et que l'on push le deuxieme commit qu'il pull. Il aura donc ses modifications différentes dde celle que l'on as car il a possiblement change un de nos fichier.

Et avec un reset cela re changerais possiblement le sens d'un commit ou l'on aurait pu se trouper donc dans ce cas autant ne pas casser le repo et juste suprimer le dernier commit pour ne pas tous casser.
J'espere que j'ai été assez clair pour que vous compreniez mon avis.