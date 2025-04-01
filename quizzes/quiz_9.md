# Questions

## Question 1
***Quelle commande permet d’afficher les permissions d’un fichier ?***

### solution 

```
$ ls -l fichier.txt
```


## Question 2
***Quelle option chmod utilise-t-on pour ajouter une permission d’exécution ?***

### Solution 1
```
 $ chmod +x script.sh
```


## Question 3
***Quelle est la valeur numérique de rwxr--r-- ?***

### Solution 1

```
$ 744
```

## Question 4
***Comment changer le propriétaire et le groupe d’un fichier en une seule commande ?***

### Solution 1
```
$ sudo chown user:group fichier.txt
```

## Question 5
***Que fait le Sticky Bit (chmod +t) sur un dossier ?***

### Solution 1
> Il empêche les utilisateurs autres que le propriétaire de supprimer des fichiers dans ce dossier.


