# GIT & GITHUB : [https://github.com/Roma-ric](https://github.com/Roma-ric)

>Je fais mes débuts avec ***`Git`*** et ***`GitHub`***.\
Cela me permettra de bien gérer le versionning des mes projects et de pouvoir les stockers en ligne afin de les récuperer une fois le besoin senti.

## Procédure

* Installer Git sur son ordinateur

        sudo apt-get install git

* Créer le dossier du project

        cd Documents/
        mkdir nom_du_dossier

* Procéder à la configuration de Git   

    * Accéder au dossier du project

            cd nom_du_dossier/

    * Nom d'utilisateur

            git config --global user.name "userName

    * Adresse mail

            git config --global user.email userEmail

    * Couleur

            git config --global color.diff auto
            git config --global color.status auto
            git config --global color.branch auto

    * Editeur 

            git config --global core.editor code
            git config --global merge.tool vimdiff

* Initialiser git
    
        git init

* Ajouter les fichiers a l'index

    * Tous les fichiers

            git add .

    * Certaines fichiers

            git add nom_du_fichier.html

* Créer une version du fichier

        git commit -m "Intitule du fichier"

* Lier le dépôt locale au dépôt distant

        git remote add origin https://github.com/..

* Envoyer la version créer dans le dépôt distant

        git push -u origin master

## Autres

* Voir les branches du repository

        git branch

* Créer une nouvelle branche

        git branch nom_de_la_branche

* Changer de branche active 

        git checkout nom_de_la_branche

* Fusionner une branche avec la branche principale

        git merge nom_de_la_branche

---

* Créer un nom de raccourci pour le nom du repository s'il est trop long

        git remote add nom_raccourci nom_repository

---

* Mettre à jour le dépôt en locale

        git pull origin main

---

* Changer le nom de la branche principal

        git branch -M nouveau_nom

---

* Voir les fichiers modifiés et pas encore versionner 

        git status 

## Gérer les erreurs

* Supprimer une branche

        git branch -d nom_de_la_branche

---

* Faire une remise 
        
        git stash 

* Voir la liste des remises

        git stash list

* Appliquer une remise

        git stash apply stash@{n}

---

* Analyser les derniers commit

        git log commit

* Supprimer le dernier commit

        git reset --hard HEAD^

* Appliquer le commit sur une nouvelle branche 

        git reset --hard 8_premiers_caractères_de_l_ID

---

* Changer le message du dernier commit deja fait

        git commit --amend -m "nouveau message"

* Ajouter un fichier oublié après un commit

        git add fichier.text
        git commit --amend --no-edit

## Créer une paire de cle SSH

    ssh-keygen -t rsa -b 4096 -C "adresseMailUser@gmail.com"

**Mon adresse mail: <romaricakodjenou54@gmail.com>**