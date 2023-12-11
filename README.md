# Git-Rebase

# Git Rebase - Guide Rapide

## Introduction

Le rebasage (rebase) est une opération Git qui permet de fusionner une branche avec une autre en réappliquant les commits de la branche actuelle sur la branche cible. Cela diffère de la fusion traditionnelle qui crée un nouveau commit de fusion.

## Avantages du Rebasing

1. **Historique Linéaire :** Le rebasage crée un historique linéaire, ce qui le rend plus lisible que l'historique de fusion complexe.

2. **Évite les Commits de Fusion Redondants :** Les commits de fusion sont éliminés, ce qui rend l'historique plus propre.

3. **Facilite la Résolution des Conflits :** En résolvant les conflits au fur et à mesure des commits, il est plus facile de gérer les conflits.

## Comment Utiliser Git Rebase

### 1. Se Positionner sur la Branche à Rebaser

```bash
