# Fonctionnement de GIT #

### Etape 1 : Initialisation
* Créer un dépôt (repository, projet) sur GitHub en utilisant le boutton pret de la photo de profil
et sur New Repository
  * cocher la case qui demande de creer le fichier *README.md*
* pour avoir le meme projet sur GitHub dans son PC local, vous pouvez **cloner** votre dépôt 
  * **git clone https://github.com/djedou/nom-proje.git**
1. Créer une branche __"developpement"__
1. Aller dans cette nouvelle branche
1. Rédiger *3* lignes de textes pour débuter une histoire dans le *README.md* __(en utilisant un maximum le markdown)__
1. Faire un `add`
1. Faire un `commit`
1. Faire un `push` de la branche __"developpement"__
1. Inviter vos collègues en tant que __contributeurs__

### Etape 2 : Contributions
1. Aller sur un dépôt où vous avez été invité
1. Faire un `clone`
1. Faire `git branch -a` pour afficher la liste des branches sur le serveur
1. Faire un `pull` de la branche __"developpement"__
1. Faire un `checkout` sur la branche __"developpement"__
1. Créer une branche nommée __"ajouts-votre-prenom"__ à partir de __"developpement"__
1. Ajouter vos *3* lignes de texte dans le *README.md* à la suite du précédent utilisateur 
1. Faire un `add`
1. Faire un `commit` 
1. Faire un `push`de la branche  __"ajouts-votre-prenom"__
1. Faire un `merge` de votre branche __"ajouts-votre-prenom"__ avec __"developpement"__
1. Faire un `push`de la branche  __"developpement"__
1. Faire ceci pour tous vos autres collègues

### Etape 3 : Versioning
1. Quand tous vos collègues sont passés chez vous, retourner sur votre dépôt
1. Faire un `merge` de "developpement" sur "master"
1. Faire un `tag` de "master" nommé __"version-1"__

### Etape 4 : Correction
1. Créer une branche "corrections" à partir de __"master"__
1. Faire les corrections d'orthographe. S'il n'y en a pas, ajouter la mention ("Sans faute")
1. Faire un `add`
1. Faire un `commit` 
1. Faire un `push`
1. Faire un `merge` avec __"master"__
1. Aller sur la branche __"developpement"__
1. Mettre à jour __"developpement"__ en faisant un merge avec la branche __"corrections"__

