un script qui affiche hello world, on journalise l'exécution du fichier puis on test avec tail -f pour voir en temps réel les logs;
voici la commande qui a permis de faire la journalisation de l'execution du fichier est le suivant:
* * * * * /home/ec2-user/exercice.sh >> journal.log. ec2-user est le nom de mon instance EC2;
exercice.sh est le nom de mon fichier où j'ai mis le script qui affiche Hello World, journal.log est le fichier où se trouve le résultat de mon log
