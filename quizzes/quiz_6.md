# Questions

## Question 6
**Quelle est la différence entre > et >> ?**

### solution 

```
* >  ecrase
* >> fajout au fichier
```


## Question 2
**Quelle commande permet d’ignorer complètement les erreurs d’une commande ?**

### Solution 1
```bash
$command 2> /dev/null
```

## Question 3
**Comment rediriger stdout et stderr vers le même fichier ?**

### Solution 1
```bash
commande > file_name 2>&1
```

### Solution 2
```bash
commande  & > file_name
```

## Question 4
**Quelle commande permet de filtrer uniquement les fichiers .log dans /var/log ?**

### Solution 1
```
ls /var/log | grep '.log'
```

## Question 5
**Comment compter le nombre de lignes dans un fichier texte ?**

### Solution 1
```bash
$cat file | wl -l

```


