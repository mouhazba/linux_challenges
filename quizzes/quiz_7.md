# Questions

## Question 1
***Quelle commande permet de voir tous les fichiers .txt d’un dossier ?***

### solution 

```
$ ls *.txt
```


## Question 2
***Quelle est la différence entre " " et ' ' dans une commande ?***

### Solution 1

- " " ineterprete les variables dans la cahine
- ' ' aucune interpretationbles de varia dans les chaines

## Question 3
***Que fait cette commande ?***
```
$ echo $(ls)
```

### Solution 1
> elle excute et affiche le contenu du repertoire courant 

## Question 4
***Comment générer une liste de chiffres de 1 à 10 avec une seule commande ?***

### Solution 1
```
$ echo {1..10}
```

## Question 5
***Quelle commande affiche : Il est actuellement HH:MM avec l'heure actuelle ?***

### Solution 1
```
$ echo "Il est actuellement $(date +%H:%M)"

```


