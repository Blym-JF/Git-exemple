#Configuration locale fondamentale de Git


git config --global user.name "PrenomNom" → tu dis à Git ton nom, celui qui apparaîtra sur chaque commit que tu fais.

git config --global user.email "prenom.nom@ici_ou_la.fr" → même chose mais avec ton email, aussi affiché sur chaque commit.

<img width="835" height="160" alt="image" src="https://github.com/user-attachments/assets/c3f8917a-7a86-4d96-afbc-bc0f7e98ea9d" />


git config --global init.defaultbranch main → tu dis à Git que quand tu fais git init, la branche principale s'appellera main (au lieu de master par défaut)

git config --show-scope --list → tu affiches toute la config actuelle de Git, en précisant d'où vient chaque réglage (global, local, système).


Eventuelle installation de compléments graphiques :

<img width="932" height="1024" alt="image" src="https://github.com/user-attachments/assets/c4be594b-1b91-4fd7-ad12-839be12af61e" />



Liste des clients "git" graphiques: https://git-scm.com/downloads/guis


 TortoiseGit (gratuit , sous windows)
https://tortoisegit.org/download/
https://download.tortoisegit.org/tgit/2.14.0.0/TortoiseGit-2.14.0.1-64bit.msi

GitKraken
https://www.gitkraken.com/download/windows64 (produit payant , version gratuite limitée à 
7jours à priori)


SmartGit
----------
+ plugins "git" des principaux IDE (eclipse, intelliJ , Visual studio code , ...

