# Questions

## Question 1
*Quelle commande permet de savoir si une commande est un exécutable, un alias ou un builtin ?*

### solution 1
```
- type commande
```

## Question 2
*Comment afficher une aide rapide sur grep ?*

### Solution 1
```
- grep --help
```

## Question 3
*Quelle commande permet d’afficher le manuel détaillé d’une commande ?*

### Solution 1
```
- man commande
```

## Question 4
*Quelle commande liste tous les alias définis sur le système*

### Solution 1
```
- alias
```

## Question 5
*Comment rendre un alias permanent ?*

### Solution 1
> creer un alias
```
- alias ll='ls -lah'
```

> rendre un alias permanent
```
- echo "alias gohome='cd -'" >> ~/.bashrc
- source ~/.bashrc
```


