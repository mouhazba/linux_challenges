# Questions

## Question 1
***Quelle est la différence entre .bashrc et .profile ?***

### solution 

- .bashrc 
	-- Chargé à chaque ouverture d’un terminal interactif.
	-- Contient les alias, variables locales, et configurations spécifiques à Bash.
- .profile 
	-- Chargé une seule fois lors de la connexion à une session.
	-- Définit des variables d’environnement permanentes et est utilisé par tous les shells (pas seulement Bash).


## Question 2
***Quelle commande permet d’appliquer immédiatement une modification dans .bashrc sans redémarrer la session ?***

### Solution 1
```
$ source ~/.bashrc

```

## Question 3
***Où faut-il ajouter une variable pour qu’elle soit globale à tous les utilisateurs ?***

### Solution 1

- Dans  /etc/profile

**OR**

- Dans /etc/bash.bashrc

## Question 4
***Quelle commande permet d’afficher uniquement les alias définis dans .bashrc ?***

### Solution 1
```
$ cat ~/.bashrc | grep alias
```

## Question 5
***Comment rendre permanent un alias la='ls -A' pour un utilisateur spécifique ?***

### Solution 1
```
$ echo "alias la='ls -A'" > ~/.bashrc
$ source ~/.bashrc
```


