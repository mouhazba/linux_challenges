# Questions
## Question 1
***Quelle commande affiche la valeur actuelle du prompt Bash ?***
### Solution 1
```
$ echo $PS1
```

## Question 2
***Que signifie le code \w dans PS1 ?***
### Solution
> \w affiche le repertoire courant.

### Question 3
***Comment ajouter la couleur bleue au répertoire affiché dans PS1 ?***
## Solution
```
$ export PS1="\u@\[\e[32m\]w$" >> ~/.bashrc
```

## Question 4
***Comment rendre une modification du prompt permanente ?***
### Solution
```
$ source ~/.bashrc
```

## Question 5
***Quelle variable est utilisée pour les entrées multi-lignes (> par défaut) ?***
### Solution
> la variable $PS2 est utilisee pour les enetrees multi-lignes