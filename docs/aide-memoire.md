# Aide-mémoire du terminal Linux

## Se déplacer

| Commande | Ce qu'ellefait | Exemple | ------------------------------------------------------------------ |
| `pwd` | Affiche le dossier où je suis | `pwd` |
| `cd` | Change de dossier | `cd ~/dev` |
| `cd ..` | Remonte au dossier parent | `cd ..` |
| `cd ~` | Retourne au dossier personnel | `cd ~` |
| `cd /` | Va à la racine du système | `cd /` |
| `ls` | Affiche les fichiers et dossiers | `ls` |
| `ls -la` | Affiche tous les fichiers, y compris les fichiers cachés | `ls -la` |

## Fichiers et dossiers

| Commande | Ce qu'elle fait                    | Exemple                     |
| -------- | ---------------------------------- | --------------------------- |
| `mkdir`  | Crée un dossier                    | `mkdir projets`             |
| `touch`  | Crée un fichier vide               | `touch index.html`          |
| `cp`     | Copie un fichier                   | `cp a.txt b.txt`            |
| `cp -r`  | Copie un dossier et son contenu    | `cp -r images sauvegarde`   |
| `mv`     | Déplace ou renomme un fichier      | `mv ancien.txt nouveau.txt` |
| `rm`     | Supprime un fichier                | `rm fichier.txt`            |
| `rmdir`  | Supprime un dossier vide           | `rmdir test`                |
| `rm -r`  | Supprime un dossier et son contenu | `rm -r test`                |

## Lire et chercher

| Commande | Ce qu'elle fait                           | Exemple                     |
| -------- | ----------------------------------------- | --------------------------- |
| `cat`    | Affiche le contenu d'un fichier           | `cat JOURNAL.md`            |
| `less`   | Affiche un fichier page par page          | `less JOURNAL.md`           |
| `head`   | Affiche les premières lignes d'un fichier | `head JOURNAL.md`           |
| `tail`   | Affiche les dernières lignes d'un fichier | `tail JOURNAL.md`           |
| `grep`   | Recherche un mot dans un fichier          | `grep "GitHub" JOURNAL.md`  |
| `find`   | Recherche un fichier ou un dossier        | `find . -name "index.html"` |
| `wc`     | Compte les lignes, mots et caractères     | `wc JOURNAL.md`             |

## Informations et aide

| Commande         | Ce qu'elle fait                      | Exemple     |
| ---------------- | ------------------------------------ | ----------- |
| `clear`          | Nettoie l'écran du terminal          | `clear`     |
| `history`        | Affiche les commandes déjà utilisées | `history`   |
| `whoami`         | Affiche le nom de l'utilisateur      | `whoami`    |
| `date`           | Affiche la date et l'heure           | `date`      |
| `man`            | Affiche le manuel d'une commande     | `man ls`    |
| `command --help` | Affiche l'aide d'une commande        | `ls --help` |

## Permissions

| Commande | Ce qu'elle fait                                         | Exemple               |
| -------- | ------------------------------------------------------- | --------------------- |
| `chmod`  | Modifie les permissions d'un fichier                    | `chmod 755 script.sh` |
| `sudo`   | Exécute une commande avec les privilèges administrateur | `sudo apt update`     |

## Réseau

| Commande  | Ce qu'elle fait                                  | Exemple                    |
| --------- | ------------------------------------------------ | -------------------------- |
| `ping`    | Vérifie la connexion avec un serveur             | `ping google.com`          |
| `curl`    | Récupère des données depuis une adresse Internet | `curl https://example.com` |
| `ip addr` | Affiche les adresses réseau                      | `ip addr`                  |

## Git et GitHub

| Commande        | Ce qu'elle fait                                | Exemple                          |
| --------------- | ---------------------------------------------- | -------------------------------- |
| `git init`      | Initialise un dépôt Git                        | `git init`                       |
| `git status`    | Affiche l'état des fichiers                    | `git status`                     |
| `git add .`     | Ajoute les modifications à préparer            | `git add .`                      |
| `git commit -m` | Enregistre les modifications                   | `git commit -m "Premier commit"` |
| `git log`       | Affiche l'historique des commits               | `git log`                        |
| `git branch`    | Affiche les branches                           | `git branch`                     |
| `git switch`    | Change de branche                              | `git switch main`                |
| `git remote -v` | Affiche les dépôts distants                    | `git remote -v`                  |
| `git push`      | Envoie les modifications vers le dépôt distant | `git push origin main`           |
| `git pull`      | Récupère les modifications du dépôt distant    | `git pull origin main`           |
| `git clone`     | Copie un dépôt distant sur son ordinateur      | `git clone URL`                  |

`git log          --oneline --graph` dessine l'historique avec les branches
