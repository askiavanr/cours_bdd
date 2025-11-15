# Variables d’environnement en Bash

Les variables d’environnement sont des paires clé-valeur utilisées par le système pour stocker des informations accessibles à tous les processus. Elles influencent le comportement du shell et des programmes.

---

## Afficher une variable : `echo`

La commande `echo` permet d’afficher le contenu d’une variable.

### Syntaxe :
```bash
echo $NOM_VARIABLE
```

### Exemples :
Afficher le chemin vers le dossier personnel de l’utilisateur.
```bash
echo $HOME
```

Afficher la liste des dossiers où le système cherche les exécutables.
```bash
echo $PATH
```

## Créer ou modifier une variable : export
La commande export permet de définir une variable d’environnement ou de la rendre accessible aux processus enfants.

### Syntaxe :
```bash
export NOM_VARIABLE=valeur
```

### Exemples :
```bash
export API_KEY=123456789
```
Crée une variable API_KEY accessible par les scripts et programmes lancés depuis ce shell.

## Supprimer une variable
Pour supprimer une variable d’environnement :

```bash
unset NOM_VARIABLE
```

# Exercice rapide
1. Crée une variable MON_COURS avec la valeur bash

2. Affiche-la avec echo

3. Supprime-la avec unset

4. Vérifie qu’elle n’existe plus
