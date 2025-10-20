# Renommeur-Python
Petit projet python - Créer un exécutable permettant d'appliquer des règles de renommage aux fichiers d'un dossier entier.

## Points d'attention : 

* Gestion des conflits (doublons)
* Ajouter un mode --dry-run (exécution à sec)
* Ajouter un loogger ainsi qu'un undo

## Liste des commandes

* `--prefix <texte>` : ajoute un préfixe.
* `--suffix <texte>` : ajoute un suffixe (avant l’extension).
* `--replace <avant>` <apres> : remplace un texte par un autre.
* `--lower/--upper/--title` : change la casse (une seule de ces options).
* `--numbering start=<N> width=<W> sep="-"` : numérotation.
* `--ext <liste>` : ne traiter que certaines extensions (ex: jpg,png,txt).
* `--recursive` : parcours des sous-dossiers.
* `--dry-run` : n’applique rien, affiche le plan.
* `--log <fichier>` : journal des opérations.
* `--undo-file <fichier>` : export des paires ancien↔nouveau.
* `--apply` : confirme l’application réelle (sécurité).
