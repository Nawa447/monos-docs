# MonOS 

## Alias utiles

Voici quelques alias pratiques à ajouter dans votre terminal pour faciliter la navigation et la gestion des fichiers :

```bash
alias ll='ls -alF --color=auto'
alias la='ls -A --color=auto'
alias l='ls -CF --color=auto'
alias ..='cd ..'
alias ...='cd ../..'
```

| Alias         | Commande réelle                          | Utilité                                         |
| ------------- | ---------------------------------------- | ----------------------------------------------- |
| `ll`          | `ls -alF --color=auto`                   | Voir tous les fichiers avec détails et couleurs |
| `la`          | `ls -A --color=auto`                     | Voir tous les fichiers sauf `.` et `..`         |
| `..`          | `cd ..`                                  | Remonter d’un dossier                           |
| `...`         | `cd ../..`                               | Remonter de deux dossiers                       |
| `update-system` | `sudo apt update && sudo apt upgrade -y` | Mettre à jour ton système facilement            |

--- 

L’ISO contient tous les éléments nécessaires pour démarrer et utiliser le système d’exploitation, incluant les outils, scripts et configurations de base. Cependant, il n’intègre pas les informations sensibles telles que les clés, mots de passe ou autres données personnelles.

Ces informations confidentielles doivent être générées et configurées par l’utilisateur après l’installation. Cette démarche garantit que ces secrets ne sont accessibles qu’à leur propriétaire.

Il s’agit d’une pratique recommandée en matière de sécurité, car inclure des secrets dans une image distribuée expose à des risques de compromission.

Ainsi, la politique adoptée distingue clairement les éléments publics et partagés (l’ISO) des éléments privés et personnels (clés, mots de passe, configurations sensibles). Cette séparation contribue à assurer la confidentialité et la sécurité de l’utilisateur final.

> **Note importante**  
> Aucun secret n'est distribué

### Lien pour création de l'ISO 

```bash
https://nawa447.github.io/monos-docs/index.html
```