# Commandes de base Bash

Ce document présente une sélection de commandes Bash couramment utilisées avec une brève explication de chacune.

## Navigation dans le système de fichiers

- `pwd` : Affiche le chemin complet du répertoire courant.
- `ls` : Liste les fichiers et répertoires dans le répertoire courant.
- `cd <répertoire>` : Change le répertoire courant pour `<répertoire>`.

## Gestion des fichiers et répertoires

- `touch <fichier>` : Crée un nouveau fichier ou met à jour la date de modification d'un fichier existant.
- `mkdir <répertoire>` : Crée un nouveau répertoire.
- `rm <fichier>` : Supprime un fichier.
- `rmdir <répertoire>` : Supprime un répertoire vide.
- `cp <source> <destination>` : Copie un fichier ou un répertoire.
- `mv <source> <destination>` : Déplace ou renomme un fichier ou un répertoire.

## Affichage et manipulation de contenu de fichier

- `cat <fichier>` : Affiche le contenu d'un fichier.
- `less <fichier>` : Affiche le contenu d'un fichier une page à la fois.
- `head <fichier>` : Affiche les premières lignes d'un fichier.
- `tail <fichier>` : Affiche les dernières lignes d'un fichier.
- `grep '<motif>' <fichier>` : Recherche `<motif>` dans `<fichier>`.

## Gestion des processus

- `ps` : Affiche les processus en cours d'exécution.
- `top` : Affiche les processus en utilisant le plus de ressources système.
- `kill <PID>` : Termine le processus avec l'ID de processus `<PID>`.

## Informations sur le système

- `df` : Affiche l'utilisation du disque par les systèmes de fichiers.
- `free` : Affiche la quantité de mémoire libre et utilisée.

## Réseau

- `ping <adresse>` : Teste la connectivité avec `<adresse>`.
- `ifconfig` : Affiche la configuration réseau (utilisez `ip a` sur les systèmes récents).

---

Note : Cette liste n'est pas exhaustive mais couvre certaines des commandes les plus fondamentales pour la gestion de base et la navigation dans un environnement Bash.
