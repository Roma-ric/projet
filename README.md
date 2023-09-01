# GIT & GITHUB : [https://github.com/Roma-ric](https://github.com/Roma-ric)

>Je fais mes débuts avec ***`Git`*** et ***`GitHub`***.\
Cela me permettra de bien gérer le versionning des mes projects et de pouvoir les stockers en ligne afin de les récuperer une fois le besoin senti.

## Procédure

1. Installer Git sur son ordinateur

        sudo apt-get install git

2. Créer le dossier du project

        cd Documents/
        mkdir nom_du_dossier

2. Procéder a la configuration de Git   

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


3. Initialiser git
    
        git init

4. Ajouter les fichiers a l'index

    * Tous les fichiers

            git add .

    * Certaines fichiers

            git add nom_du_fichier.html

5. Créer une version du fichier

        git commit -m "Intitule du fichier"

6. Lier le dépôt locale au dépôt distant

        git remote add origin https://github.com/..

7. Envoyer la version créer dans le dépôt distant

        git push -u origin master

---
**Mon adresse mail: <romaricakodjenou54@gmail.com>**