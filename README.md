# Alban Sagot
### Procédure d'installation Jekyll, Git et Github Pages

---

Pour installer **Jekyll** il faut installer Ruby et ruby gem avec ces commandes à mettre dans le terminal :

```
sudo apt-get install ruby-full
```

```
sudo gem update –system
```

Puis il faut installer NodeJS (et donc Curl qui est obligatoire pour NodeJS) :

```
sudo apt-get install curl
```

```
curl --silent --location https://deb.nodesource.com/setup_0.12 | sudo bash -
```

```
sudo apt-get install --yes nodejs
```

Et pour terminer avec Jekyll (il faut au préalable créer un dossier pour héberger le site (sur le bureau par exemple et se placer dedans via le terminal à l'aide de cd .. :
```
jekyll new nomdusite
```
```
cd nomdusite
```
```
jekyll serve
```
Votre site est désormais accesible à l'adresse : **http://localhost:4000** le port 4000 est utilisé par défaut pour Jekyll<br />
<br />
Pour installer **Git** il faut :<br />
-Crée un compte GitHUB

-Ouvrir un nouveau terminal

```
sudo apt-get install libcurl4-gnutls-dev libexpat1-dev gettext \libz-dev libssl-dev
```

```
sudo apt-get install git 
```
se placer dans le dossier du site à cloner et remplacer les username dans la commande suivante
```
git clone https://github.com/username/username.github.io
```

**configuration du compte :**
```
git config --global user.email "you@example.com"
```
```
git config --global user.name "Your Name"
```
si les lignes précédentes ne fonctionne pas il faut enlever le “--global” →
```
git config user.email "you@example.com"
```
```
git config user.name "Your Name"
```
Après il faut suivre les insctructions situés ici : https://pages.github.com/ <br />
Qui sont résumé ci-dessous : <br />
- créer un répertoire sur github donc le nom est **username.github.io**
```cd username.github.io```
```echo "Hello World" > index.html```
```git add --all```
```git commit -m "Initial commit"```
```git push -u origin master```
Vous pouvez désormais accéder à votre site à cet adresse : http://username.github.io dans mon cas **http://alban0310.github.io**
---
Alban Sagot
# Alban Sagot
### Procédure d'installation Jekyll, Git et Github Pages

---

Pour installer **Jekyll** il faut installer Ruby et ruby gem avec ces commandes à mettre dans le terminal :

```
sudo apt-get install ruby-full
```

```
sudo gem update –system
```

Puis il faut installer NodeJS (et donc Curl qui est obligatoire pour NodeJS) :

```
sudo apt-get install curl
```

```
curl --silent --location https://deb.nodesource.com/setup_0.12 | sudo bash -
```

```
sudo apt-get install --yes nodejs
```

Et pour terminer avec Jekyll (il faut au préalable créer un dossier pour héberger le site (sur le bureau par exemple et se placer dedans via le terminal à l'aide de cd .. :
```
jekyll new nomdusite
```
```
cd nomdusite
```
```
jekyll serve
```
Votre site est désormais accesible à l'adresse : **http://localhost:4000** le port 4000 est utilisé par défaut pour Jekyll<br />
<br />
Pour installer **Git** il faut :<br />
-Crée un compte GitHUB

-Ouvrir un nouveau terminal

```
sudo apt-get install libcurl4-gnutls-dev libexpat1-dev gettext \libz-dev libssl-dev
```

```
sudo apt-get install git 
```
se placer dans le dossier du site à cloner et remplacer les username dans la commande suivante
```
git clone https://github.com/username/username.github.io
```

**configuration du compte :**
```
git config --global user.email "you@example.com"
```
```
git config --global user.name "Your Name"
```
si les lignes précédentes ne fonctionne pas il faut enlever le “--global” →
```
git config user.email "you@example.com"
```
```
git config user.name "Your Name"
```
Après il faut suivre les insctructions situés ici : https://pages.github.com/ <br />
Qui sont résumé ci-dessous : <br />
- créer un répertoire sur github donc le nom est **username.github.io**
```cd username.github.io```
```echo "Hello World" > index.html```
```git add --all```
```git commit -m "Initial commit"```
```git push -u origin master```
Vous pouvez désormais accéder à votre site à cet adresse : http://username.github.io dans mon cas **http://alban0310.github.io**
---
Alban Sagot
