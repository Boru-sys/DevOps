# TP Git – DevOps

## Présentation
Ce projet a pour objectif de découvrir les bases de Git et GitHub à travers
la création de branches, de commits et de fusions.

## Installation de Git
```bash

## Commandes réalisées

| Étape | Commande | Description |
|------:|----------|-------------|
| 1 | `git init` | Initialise un dépôt Git dans le dossier |
| 2 | `git checkout -b develop` | Crée la branche `develop` et se place dessus |
| 3 | `touch file1 file2 file3` | Crée les 3 fichiers demandés |
| 4 | `git add .` | Ajoute les modifications dans la zone de préparation (staging) |
| 5 | `git commit -m "..."` | Crée un commit (snapshot) des modifications |
| 6 | `git push -u origin develop` | Envoie la branche `develop` vers GitHub |
| 7 | `git checkout main` | Se place sur la branche `main` |
| 8 | `git merge develop` | Fusionne `develop` dans `main` |
| 9 | `git push origin main` | Envoie `main` vers GitHub |
| 10 | `mv file1 file1.txt` | Renomme `file1` en `file1.txt` |
| 11 | `rm file3` | Supprime `file3` |

## Diagramme du flow (branches & commits)

```text
(develop)                     (main)
   |                            |
   |-- C1: ajout file1 file2 file3
   |        |
   |        +--> merge --------> M1
   |
   |-- C2: ajout README / mv file1.txt / rm file3
            |
            +--> merge --------> M2



# Sous Windows
https://git-scm.com/downloads
