Credit to WarningMalware 

Commande : ./script.sh -a setup
Fonction associée : setup
Description : Configure les règles de pare-feu, installe les dépendances si nécessaire, et configure le reniflage automatique des IDs.
stop

Commande : ./script.sh -a stop
Fonction associée : Gérée directement dans le bloc if correspondant
Description : Arrête la restriction de matchmaking en supprimant les règles de pare-feu configurées.
start

Commande : ./script.sh -a start
Fonction associée : Gérée directement dans le bloc if correspondant
Description : Démarre la restriction de matchmaking en ajoutant les règles de pare-feu configurées.
add

Commande : ./script.sh -a add
Fonction associée : Gérée directement dans le bloc if correspondant
Description : Ajoute un ID spécifique à la liste de blocage. L'utilisateur est invité à entrer l'ID.
reset

Commande : ./script.sh -a reset
