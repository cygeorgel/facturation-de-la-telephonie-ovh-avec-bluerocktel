# Les fichiers de prélèvements SEPA

Une fois la facturation établie et vérifiée, vous allez pouvoir éditer les fichiers de prélèvements à la norme SEPA, à remettre à votre établissement bancaire.

BlueRockTEL regroupe les échéances à passer en banque par prélèvements en deux fichiers distincts :
* un fichier de prélèvements FIRST,
* un fichier de prélèvments RECUR.

## Séquencer et visualiser les prélèvements
Cette opération est à effectuer juste avant d'éditer les fichiers de prélèvement. Elle permet de "séquencer" chaque prélèvement, autrement dit de déterminer s'il doit être présenté à la banque en tant que FIRST ou RECUR. De même, la date de prélèvement de chacune des échéances est recalculée pour être conforme aux délais légaux. À l'issue de cette étape, BlueRockTEL génère un fichier récapitulatif au format Excel.
## Générer les fichiers de prélèvements
Cette opération est à faire une fois pour les prélèvements FIRST, une autre pour les prélèvements RECUR, en précisant les bornes de dates que vous souhaitez prendre en compte. Vous remettrez à votre banque les fichiers XML produits.
## Modification automatique du statut des échéances
Toute échéance par prélèvement intégrée à un fichier de prélèvements est automatiquement passée :
* en étape "Banque",
* en statut "Réglée".

L'échéance devra donc être modifiée manuellement si elle vous est retournée impayée.
## Voir le détail d'une remise
À tout moment, vous pouvez voir le détail d'une remise de prélèvements passée : le détail vous en est donné sous la forme d'un export Excel.