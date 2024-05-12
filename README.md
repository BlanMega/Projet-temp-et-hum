Ce projet est une solution complète de surveillance environnementale qui utilise la technologie de pointe pour recueillir, transmettre et visualiser les données en temps réel.

Le cœur du système est un microcontrôleur PICO qui est connecté à un capteur DHT11. Ce capteur est capable de mesurer la température et l’humidité de l’environnement. Les données recueillies par le DHT11 sont ensuite envoyées au PICO.

Le PICO est connecté à un réseau WiFi et a une adresse IP fixe. Il utilise cette connexion pour transmettre les données du capteur à un serveur MAMP. Le serveur MAMP est configuré pour recevoir ces données et les stocker dans une table de données.

Une fois que les données sont stockées dans la table de données, elles peuvent être récupérées et utilisées pour diverses analyses. Dans ce projet, les données sont utilisées pour créer un graphique avec Chart.js. Ce graphique permet de visualiser les variations de température et d’humidité au fil du temps, ce qui peut être très utile pour surveiller les conditions environnementales.

En résumé, ce projet offre une solution efficace et automatisée pour la surveillance environnementale, en utilisant des technologies modernes pour recueillir, transmettre et visualiser les données de température et d’humidité. Il est un excellent exemple de l’utilisation de la technologie pour résoudre des problèmes concrets et fournir des informations précieuses.
