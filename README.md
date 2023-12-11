# Git-Rebase

# Git Rebase - Guide Rapide

Le rebasage consiste à déplacer vers un nouveau commit de base ou à combiner une séquence de commits. Le rebasage est plus utile et facilement visible dans le contexte d'un workflow de branche de fonctionnalité. Vous pouvez visualiser le processus général comme suit :

![](https://wac-cdn.atlassian.com/dam/jcr:4e576671-1b7f-43db-afb5-cf8db8df8e4a/01%20What%20is%20git%20rebase.svg?cdnVersion=1352)

Au niveau du contenu, le rebase consiste à changer la base de votre branche d'un commit vers un autre, donnant l'illusion que vous avez créé votre branche à partir d'un commit différent. En interne, Git réalise cette tâche en créant de nouveaux commits et en les appliquant à la base spécifiée. Il est important de comprendre que, même si la branche semble identique, elle est composée de commits tout nouveaux.


## Avantages du Rebasing

1. **Historique Linéaire :** Le rebasage crée un historique linéaire, ce qui le rend plus lisible que l'historique de fusion complexe.

2. **Évite les Commits de Fusion Redondants :** Les commits de fusion sont éliminés, ce qui rend l'historique plus propre.

3. **Facilite la Résolution des Conflits :** En résolvant les conflits au fur et à mesure des commits, il est plus facile de gérer les conflits.

## Comment Utiliser Git Rebase


