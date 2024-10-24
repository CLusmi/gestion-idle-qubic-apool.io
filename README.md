Permet la gestion de l'IDLE pendant le mining QUBIC sur la pool APOOL.IO

Le script "idle.sh" doit etre utiliser dans le dossier du mineur APOOL. (/hive/miners/custom/apoolminer_hiveos/)

Les scripts "ocdebut.sh" et "ocfin.sh" doivent etres dans le dossier user. (/home/user)

Pour utiliser, veuillez lancer le mining Qubic depuis HiveOS avec votre FL.

Positionnez vous dans le bon dossier (cd /hive/miners/custom/apoolminer_hiveos/), puis lancez le script dans un screen. (screen -dmS idle idle.sh)

Le script tourne en boucle pour check toutes les 5 secondes si nous sommes en periode IDLE.

Si pas de periode IDLE, rien ne ce passe.

Si periode IDLE, le script stop le miner Qubic, puis lance le miner IDLE.

Lorsque la pariode IDLE est passée, le script stop le miner IDLE et relance le miner Qubic.

Ce script a été développé par "sebit27" et modifié par mes soins. Vous pouvez le contacter pour d'autres idées.

Mon discord : CLusmi
