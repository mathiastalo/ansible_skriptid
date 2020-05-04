# RSHA-ANSIBLE AUTOMATISEERITUD SKRIPTID. 
 Skriptid on automatiseeritud, mis teevad instaleerimis&seadistamise lihtsamaks ning kiiremaks.
Kõik skriptid on kättesaadaval github.com/mathiastalo.

## Paigaldamine
#### Antud READme's on erinevad automatiseeritud skripte, mis on kontrollitud ja töökorras. Kõik skriptid on kirjutatud Debian 9.12 versiooniga masina peal.

## Skriptid tuleb käivitada järgmises järjekorras:
1. apache2.yml
2. mysql_server5.7.yml
3. mysql_user
4. php7.yml
5. phpmyadmin.yml
6. wordpress.yml

## GIT'i paigaldamine
```
apt install git
```
## GIT'i seadistamine
```
git config --global user.name "*** ****"
git confug --global user.email email@domeen.com
git config --global core.editor nano
```
## NB!

### Selleks, et Te saaksite oma Wordpressile või PHPMYADMIN'ile ligi peate sisestama url vastava serveri ip, koos selle tähisega.
#### Näide:
- SERVERIIP/wordpress
- 192.168.1.10/wordpress
##
- SERVERIIP/phpmyadmin
- 192.168.1.10/phpmyadmin

## Paroolid:
NB! SKRIPTID PAIGALDAVAD AUTOMAATSELT ISE PAROOLID!
### MYSQL
- kasutaja: user
- parool: qwerty

### PHPmyadmin
- kasutaja: phpmyadmin
- parool: qwerty

### Wordpress'i andmebaas
- database: wpdatabase
- kasutaja: wpuser
- parool: qwerty
