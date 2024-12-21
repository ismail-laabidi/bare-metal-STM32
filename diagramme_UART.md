# Diagramme des flux de données

Une représentation visuelle des interactions entre les différents composants du projet permet de mieux comprendre la structure et le fonctionnement du système. Dans ce cas, le diagramme des flux de données mettrait en évidence :

- **Capteur ultrason** : envoie des données sur la durée de l’écho au microcontrôleur.
- **Microcontrôleur** : traite les données reçues pour calculer la distance et déclenche des actions en conséquence.
- **UART** : utilisé pour transmettre les résultats calculés (comme la distance mesurée) à un terminal ou une interface utilisateur externe.
- **LED** : activée ou désactivée par le microcontrôleur en fonction des conditions définies (par exemple, lorsque la distance détectée dépasse un seuil).

Ce type de diagramme clarifie la manière dont les composants communiquent et coopèrent pour atteindre les objectifs du projet, tout en identifiant les éventuels points de défaillance ou d’amélioration.

