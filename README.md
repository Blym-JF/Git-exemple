
# Git-exemple

Repo  Git.

## Installation

```bash
sudo apt update
sudo apt install git
git --version
```

## Config

```bash
git config --global user.name "TonNom"       # identité
git config --global user.email "email"       # identité
git config --list                             # vérif config
```

## Local

```bash
git init                  # crée le repo
git status                # état des fichiers
git add fichier           # ajoute au suivi
git add .                 # ajoute tout
git commit -m "message"   # sauvegarde
git log                   # historique
git diff                  # différences
```

## Fichiers ignorés

```bash
.gitignore                # liste fichiers à ignorer
```

## Retour en arrière

```bash
git checkout -- fichier   # annule modif fichier
git reset                 # désindex fichier
git reset --hard          # annule tout
```

## Tags

```bash
git tag nom_tag           # marque une version
git tag                   # liste les tags
```

## Branches

```bash
git branch                # liste branches
git branch nom            # crée branche
git checkout nom          # change branche
git checkout -b nom       # crée + change
git merge nom             # fusionne branche
git branch -d nom         # supprime branche
```

## Remote

```bash
git remote add origin url   # lie repo distant
git push origin main        # envoie
git pull origin main        # récupère + fusionne
git fetch                   # récupère sans fusionner
git clone url                # copie un repo distant
```

## Stash

```bash
git stash        # met de côté modifs
git stash pop    # remet les modifs
```
