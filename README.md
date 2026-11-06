# extracteur-meteo-grp2
## Version 2
- Ajout de la gestion d'une ville par défaut (`Toulouse`) si aucun argument n'est fourni au lancement du script.
## Automatisation (Version 2)
Pour planifier l'exécution automatique du script sur un environnement Linux, utilisez la commande suivante dans le terminal :
`crontab -e`

Puis ajoutez la ligne suivante pour exécuter le script automatiquement :
`0 * * * * /bin/bash /chemin/vers/votre/extracteur_meteo.sh`