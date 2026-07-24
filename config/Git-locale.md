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


Elémentaire en mode local :

Se créer un répertoire de Test --> Créer des sous répertoires --> checker --> 

<img width="654" height="37" alt="image" src="https://github.com/user-attachments/assets/03a6efe6-e6b6-4f5f-8b47-4f00b33cac36" />

vérification -->

<img width="624" height="33" alt="image" src="https://github.com/user-attachments/assets/e230e729-8f21-440f-b267-7f63ef15192e" />


Création des fichiers & vérification -->

<img width="928" height="271" alt="image" src="https://github.com/user-attachments/assets/85b53510-f474-400c-9971-43fb886be3df" />


Initialiser Git


<img width="834" height="206" alt="image" src="https://github.com/user-attachments/assets/7675d416-bc1a-4ab7-b1f3-f3d494a3d3b8" />

 Vérifier l'état du projet --> Ajouter les fichiers texte
<img width="768" height="432" alt="image" src="https://github.com/user-attachments/assets/ddd3af32-7759-4737-99f1-ca3f3cd2acd3" />
<img width="861" height="344" alt="image" src="https://github.com/user-attachments/assets/67392a25-dd85-4103-a84b-9d74a7508c89" />
Commit initial --> git status --> git log

<img width="818" height="328" alt="image" src="https://github.com/user-attachments/assets/57f513d0-2bb2-43c6-ae79-86d21ce4066e" />



<img width="731" height="130" alt="image" src="https://github.com/user-attachments/assets/8f8ae1aa-1a88-4fa2-87e3-5d5a1cac2434" />


<img width="704" height="74" alt="image" src="https://github.com/user-attachments/assets/b6edb3a3-1d9a-4b6f-87af-681e48c131ab" />


Modification de f1.txt et ajout de f3.txt  -->
<img width="839" height="59" alt="image" src="https://github.com/user-attachments/assets/7df7a1cd-4a2b-4c10-baee-a2d831180771" />

<img width="747" height="168" alt="image" src="https://github.com/user-attachments/assets/5c2f15ed-1d48-4b7f-ae49-cebe0a9a3bfa" />

 git status --> git diff -->
 
<img width="791" height="260" alt="image" src="https://github.com/user-attachments/assets/05e5c08b-acaa-4f52-bba5-b1a7df6f6007" />


<img width="760" height="239" alt="image" src="https://github.com/user-attachments/assets/e0a34ed8-e965-40b3-9e35-7720a3c90a67" />

git add -->> git status pour verifier -->> git commit avec le commentaires -->> git log 

<img width="888" height="499" alt="image" src="https://github.com/user-attachments/assets/9453e2ce-817f-4b52-844b-a218c7a9fb25" />


Retour en arrière avec la commande "git checkout < hash > 

<img width="937" height="207" alt="image" src="https://github.com/user-attachments/assets/1b5c99d8-6ac0-4969-9d16-fcf92b98bd4c" />

<img width="653" height="86" alt="image" src="https://github.com/user-attachments/assets/6dcb7f72-c85b-4843-8136-ceccf5ca3153" />

Ajout du Tag  v1 --> 


<img width="935" height="83" alt="image" src="https://github.com/user-attachments/assets/03b377ae-690b-4535-a0e2-c1b976c4d1ac" />

<img width="942" height="305" alt="image" src="https://github.com/user-attachments/assets/ac67659b-2b9f-4c37-96bf-df253fac8f8d" />

