# Exports des informations d'appels (CSV)
Certains de vos clients souhaiteront disposer de leurs CDR (Call Record Data), c'est-à-dire des informations d'appels au format CSV, au jour le jour.

[**BlueRockTEL**](http://bluerocktel.com) dispose d'une fonctionnalité facile à mettre en oeuvre pour cela.

![](exportsCalls01.jpg)
Il vous suffira d'ajouter une ligne aux **Exports Appels Clients**, en précisant :
* le nom du client,
* son ou ses groupes de facturation,
* les coordonnées FTP (serveur, utilisateur, mot de passe),
* le chemin (le cas échéant).

![](exportsCalls02.jpg)
Une fois ces paramètres entrés, **les nouveaux fichiers CSV seront déposés chaque nuit** dans l'espace FTP indiqué.

À noter que vous pouvez utiliser :
* soit un espace FTP appartenant à votre client,
* soit mettre vous-même un serveur FTP à la disposition de vos clients.

Dans ce dernier cas, nous vous fournirons un script à installer sur votre serveur FTP, qui synchronisera automatiquement les comptes FTP avec les informations entrées dans BlueRockTEL, de telle sorte que vous n'ayiez pas à saisir les mêmes informations à deux reprises.

Bien entendu, nous pouvons également, si vous le souhaitez, nous charger de la fourniture et de la maintenance du serveur FTP.






