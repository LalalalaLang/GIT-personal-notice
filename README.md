
git fetchgit git Pour GIT BASH

- créer sur GitHub un dossier vide (sans licence sans readme etc.)
- copier le lien HTPPS ou SSH (plus rapide sans mot de passe fonctionne par système de clés)

Dans la fenêtre de Git Bash

$ git add .

$ git commit -m "blablabla"

$ git status (pour avoir l'état actuel le contenu actualisé)

$ git log (pour avoir les ID de commits)

$ git log --oneline --all

$ git remote add origin https(lien)

$ git push origin master (actualiser/envoyer un commit)

$ git checkout

pull
$ cd .. (retourner au dossier parent car 2 points)

$ git clone https(lien du dossier avec lequel je collabore)=> créer dossier entièrement configurer

$ git pull (=2 opérations fetch + merge)

$ git fetch (télécharger update)

$ git merge (intégration des modifications)

$ git branch (pour voir les branches d'un commit)

$ git branch -m(=master) main (regroupe la branche master et main= merge)



$ git remote (liste lien entre git Bash and git site)

$ git pull --allow-unrelated-histories (merge commits entre Bash et Github quand 2 dossiers différents)

$ git push -u(=setupstring)
