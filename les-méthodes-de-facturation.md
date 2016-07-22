# Les méthodes de facturation

Différentes méthodes de facturation sont attachées aux articles ; leur diversité et leur spécificité vous permet de facturer vos services exactement comme vous l'entendez.

Voici les principales méthodes disponibles à ce jour.

## voiceIF

### Appels vers les numéros fixes :

Les appels vers les numéros fixes de la "zone OVH" \(France et 40 pays\) ne sont pas facturés, dans la limite des deux restrictions suivantes :

1. 99 numéros différents appelés dans le mois,
2. durée de l'appel ne dépassant pas une heure.

Les appels au-delà de 99 numéros par mois sont facturés à la seconde, au prix fixé dans le dossier du client.

Les appels d'une durée supérieure à une heure sont facturés à la seconde, au prix fixé dans le dossier du client et à partir d'une heure.

### Appels vers les autres numéros  :

Les appels vers les autres numéros  ont facturés à la seconde, au prix fixé dans le dossier du client.

## voiceIM

### Appels vers les numéros fixes :

Les appels vers les numéros fixes de la "zone OVH" \(France et 40 pays\) ne sont pas facturés, dans la limite des deux restrictions suivantes :

1. 99 numéros différents appelés dans le mois,
2. durée de l'appel ne dépassant pas une heure.

Les appels au-delà de 99 numéros par mois sont facturés à la seconde, au prix fixé dans le dossier du client.

Les appels d'une durée supérieure à une heure sont facturés à la seconde, au prix fixé dans le dossier du client et à partir d'une heure.

### Appels vers les numéros mobiles en France :

Les appels vers les numéros mobiles en France ne sont pas facturés, dans la limite des deux restrictions suivantes :

1. 99 numéros différents appelés dans le mois,
2. durée de l'appel ne dépassant pas une heure.

Les appels au-delà de 99 numéros par mois sont facturés à la seconde, au prix fixé dans le dossier du client.

Les appels d'une durée supérieure à une heure sont facturés à la seconde, au prix fixé dans le dossier du client et à partir d'une heure.

### Appels vers les autres numéros :

Les appels vers les autres numéros ont facturés à la seconde, au prix fixé dans le dossier du client.

## trunkSIP

La méthode trunkSIP se comporte exactement comme la méthode voiceIM, à cette exception près : les 99 numéros différents sont multipliés par un coefficient correspondant au nombre de canaux précisé dans le dossier du client.

Par exemple, s'il est précisé 10 canaux, les appels ne seront facturés qu'à partir du 1000ème numéro et non du 100ème.

## voiceCpt

Tous les appels sont chargés à la seconde, aux prix fixés dans le dossier du client.

## ecofax

Les communications sont facturées sur la base du nombre de pages, selon ce qui est précisé dans le dossier du cient.

## landPlus3h

Cette méthode se comporte comme la méthode voiceIF. On y ajoute 3 heures vers les mobiles en France, incluant les transferts et sans tenir compte du nombre de numéros appelés. Au delà de ces 3 heures, tous les appels vers les mobiles sont facturés à la seconde selon le prix indiqué dans le dossier du client.

## refact

Cette méthode vous permet de refacturer le client final en vous calquant sur ce qu'OVH vous facture, en appliquant en coefficient multiplicateur à préciser dans le dossier. À noter qu'il vous est possible de préciser un coefficient différent pour chaque type d'appels \(fixes, mobiles, spéciaux\).

Les appels vers les fixes compris dans la limite de 99 numéros appelés par mois.

voiceIF : free calls to landLines \(to 99 different numbers\) voiceIM : free calls to landLines and mobiles \(to 99 different numbers + 99 different numbers\) ecofax : pages trunkSIP : 99 different numbers x the number of channels for the line VoiceCpt : all calls are charged LandPlus3h : voiceIF + 3 hours to mobiles \(including transfers, the number of different called numbers DOESN'T matter\) refact : we multiply the priceWithoutVAT by a rate defined in the client file.

