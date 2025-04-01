# Questions

## Question 1
***Quelle commande permet d’afficher uniquement les variables d’environnement ?***

### solution 

```
$ printenv
```


## Question 2
***Comment créer une variable temporaire MY_VAR contenant "Hello" ?***

### Solution 1
```
 $ MY_VAR ="Hello"
```


## Question 3
***Quelle commande supprime une variable d’environnement existante ?***

### Solution 1

```
$ unset MY_VAR
```

## Question 4
***Où faut-il ajouter une variable pour qu’elle soit permanente ?***

### Solution 1
```
$ commande >> ~/.bashrc
$ source ~/./bashrc
```

## Question 5
***Comment modifier le prompt (PS1) pour qu’il affiche uniquement le répertoire courant (\W) suivi de $ ?***

### Solution 1
```
$ export $PS1="\w$"
```


