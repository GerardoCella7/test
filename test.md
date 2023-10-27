[test](#commandes-de-base)
<br><br><br>
>10/2023

<hr style="border-color:#f3c12f;">
<center><h1> Commandes principales </h1></center>
<hr style="border-color:#f3c12f">

<br>

[<b>---> Lien : console de base Linux</b>](https://doc.ubuntu-fr.org/tutoriel/console_commandes_de_base)

## Mise à jour

|  <center><span style="color:#0278cb">Commande</span></center>  | <span style="color:#f3c12f">Option</span>  |  <span style="color:#aa48bb">Description</span>  |
|--------|:--------:|:--------:
|  `sudo apt-get update` | **-y** |  <span style="color:#4fc031">(listé les paquets pour les MAJ)</span>  |
|  `sudo apt-get upgrade` |   **-y** |  <span style="color:#4fc031">(fait les MAJ)</span>  |
|  `sudo apt autoremove` | |  <span style="color:#4fc031">(supprime les paquets inutiles)</span>

### Démarrage

|  <center><span style="color:#0278cb">Commande</span></center>  |  <span style="color:#aa48bb">Description</span>  |
|--------|:--------:
|  `sudo dpkg-reconfigure locales`  |  <span style="color:#4fc031">(changer la langue)</span>  |
|  `cat /etc/default/keyboard` |  <span style="color:#4fc031">(verifie la configuration du clavier)</span>
|  `sudo dpkg-reconfigure keyboard-configuration` | <span style="color:#4fc031">(passer le clavier kali en AZERTY permanente)</span>

### IP

|  <center><span style="color:#0278cb">Commande</span></center>  |  <span style="color:#aa48bb">Description</span>  |
|--------|:--------:
|  `nmcli -p device show` | <span style="color:#4fc031">(afficher Ip)</span>  |
|  `ifconfig`  |
|  `ip a`   |
|  `ip addr`   |
|  `hostname -I`  |
|  `curl ifconfig.co/json`|

### Pasword

|  <center><span style="color:#0278cb">Commande</span></center>  |  <span style="color:#aa48bb">Description</span>  |
|--------|:--------:
|  `sudo passwd root` | <span style="color:#4fc031">(changer MDP root)</span>  |
|  `sudo passwd -dl root`  |  <span style="color:#4fc031">(suppretion du changement)</span>

<br>

## Commandes de base

|  <center><span style="color:#0278cb">Commande</span></center>  |  <span style="color:#aa48bb">Description</span>  |
|--------|:--------:
|  `man` |  <span style="color:#f3c12f">(aide pour les commandes)</span>
|  `pwd`  |  <span style="color:#4fc031">(liste les fichiers du répertoir courant)</span>
|  `ls`  |  <span style="color:#4fc031">(change de dossier)</span>
|  `cd`  |  <span style="color:#4fc031">(change de dossier)</span>
|  `mkdir`  |  <span style="color:#4fc031">(nouveau dossier)</span>
|  `rmdir`  |  <span style="color:#4fc031">(supprimer dossier)</span>
|  `touch`  |  <span style="color:#4fc031">(nouveau fichier)</span>
|  `nano`   |  <span style="color:#4fc031">(éditeur de texte) {CTRL + O pour enregistrer}</span>
|  `rm`  |  <span style="color:#4fc031">(supprimer fichier)</span>
|  `rm -rf` |  <span style="color:#4fc031">(supprimer dossier et son fichier)</span>
|  `df`  |  <span style="color:#4fc031">(espace disque utilisé ou restant)</span>
|  `ping`   |  <span style="color:#4fc031">(test de connectivité)</span>
|  `mv`  |  <span style="color:#4fc031">(déplacer ou renomer)</span>
|  `cp`  |  <span style="color:#4fc031">(copier)</span>
|  `cat` |  <span style="color:#4fc031">(affiche le contenu d'un fichier) CTRL D pour terminer</span>
|  `chmod`  |  <span style="color:#4fc031">(les droits sur les fichier)</span>

***

<br><br><br><br><br><br><br>

|<span style="color:#0278cb">Ligne 1,1</span>|<span style="color:#aa48bb">Ligne 1,1</span>   
-|-

***

|  |   |   |   |
---|---|---|-:
|   

***

| | | | |
--|-|-|-
|
| 

***

```python
('You get syntax highlighting...')
print('You get syntax highlighting...')
print('...if you include the language name')
('You get syntax highlighting...')
```
***

```diff
- J'aime pas
+ J'aime
```

***

```javascript
// All the code you will ever need 
var hw = "Hello World!"
alert(hw);
```

***

$-b \pm \sqrt{b^2 - 4ac} \over 2a$

***

lol
