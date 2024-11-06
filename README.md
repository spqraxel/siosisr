# Comment utiliser Git ?

- L'installer : ```apt install git```
---

**Ensuite, dans le répertoire où nous allons utiliser Git :**
- Initialiser le git avec : ```git init```
- On change le nom de la branche avec : ```git branch -m <nom>``` On utilise le nom main.
- Ensuite, dans chaque dossier Git, on a un ```README``` généralement écrit en markdown.
- Créer un fichier `.gitignore`.

---
## Les commandes importantes :

| Commande                   | Pourquoi faire ?                                           |
| :-------------------------: | :--------------------------------------------------------- |
| `git init`                  | Initialiser le dépôt Git dans le répertoire.               |
| `git status`                | Afficher l'état du dépôt Git (fichiers modifiés, etc.).    |
| `git log`                   | Afficher l'historique des commits du dépôt.                |
| `git branch`                | Afficher les branches existantes.                          |
| `git checkout <nom>`        | Passer à la branche spécifiée.                             |
| `git branch <nom>`          | Créer une nouvelle branche.                                |
| `git merge <nom>`           | Fusionner la branche spécifiée avec la branche active.     |
| `git tag <tag>`             | Appliquer un tag à la branche active (marque un point dans l'historique). |
| `git add .`                 | Ajouter tous les fichiers modifiés à l'index pour les commits. |
| `git commit -m "message"`   | Créer un commit avec le message donné.                     |
| `git pull`                  | Télécharger les changements du dépôt distant (GitHub).     |
| `git push`                  | Envoyer les changements locaux vers le dépôt distant (GitHub). |

---
## Visualisation des branches :

![Image des branches](https://lutece.paris.fr/support/image?resource_type=wiki_image&id=10)

---
## Visualisation des espaces :

![Image des espaces](https://media.geeksforgeeks.org/wp-content/uploads/20220221134227/gitindex.png)
