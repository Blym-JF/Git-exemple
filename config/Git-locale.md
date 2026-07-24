#Configuration locale fondamentale de Git


git config --global user.name "PrenomNom" → tu dis à Git ton nom, celui qui apparaîtra sur chaque commit que tu fais.

git config --global user.email "prenom.nom@ici_ou_la.fr" → même chose mais avec ton email, aussi affiché sur chaque commit.

<img width="835" height="160" alt="image" src="https://github.com/user-attachments/assets/c3f8917a-7a86-4d96-afbc-bc0f7e98ea9d" />


git config --global init.defaultbranch main → tu dis à Git que quand tu fais git init, la branche principale s'appellera main (au lieu de master par défaut sur les vieilles versions).

git config --show-scope --list → tu affiches toute la config actuelle de Git, en précisant d'où vient chaque réglage (global, local, système).
