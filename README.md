# Commande_Git_Cheat_Sheet

# Utilisation des Commandes et des Concepts Git en Command Line

# git init (Création d'un nouveaux dépot Git)
# git status (Indique la position / Indique les commits / Les modifications)
# git add {PATH} (Ajout du dossier untrack)
# git add -A (Ajoute tous les dossiers untrack)
# git commit -m "message" (Donne un hash -> Défini un commit)
# git log (Donne l'historique des derniers commits)
# git push (Pousse les fichiers)
# git clone (Clone un projet (copie local de la remote))
# git fetch (Update la vérité de la remote de la vérité)
# git merge (Ajout des commits manquants + update le depot local)
# git pull (git fetch + git merge = git pull)
# git branch (Énumération des étiquettes)
# git branch {branche} (Création d'une étiquette)
# git checkout {branche} (Création d'une branche et la checkout)
# git branch -d {branche} (Supprime la branche)
# git push --delete origin {branche} (Supprime la branche)
# git tag (Ajouter un tag)
# git push --tag (Pousser le tag sur le repos remote)
# git tag -f "tag" + git push --tags -f (Changer le tag de place (de commit))

# Branch = Étiquette sur un commit
# Working tree clean = Toutes les modifications ont été faites
# Qu'est ce qu'un Fast-Foward merge?
Quand git est capable  de partir d'un état. On doit avoir la base du projet. Technique de merge : Marche lorsqu'il y a des liaisons. On doit avoir A, car il se base sur le A.
# Fast-Foward = NE CRÉE PAS DE COMMIT
# Qu'est ce que le HEAD
Pointeur vers l'étiquette
# Qu'est ce qu'un TREE WAY MERGE et quand ca arrive?
Quand on merge plusieurs branches ensemble
# Qu'est ce qu'une PULL REQUEST?
Va chercher un fichier

# Commande Utiles BASH non reliés à git
# cd {PATH}
Se déplacer dans l'arbre des répertoires
# pwd
Savoir où on se situe en ce moment
# touch
"Toucher" un fichier pour la première fois et le créer
# ls
Voir le contenu d'un  répertoire
# ls -al
Voir le contenu d'un répertoire, ainsi que les fichiers cachés
