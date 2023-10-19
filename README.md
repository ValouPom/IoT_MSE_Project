# IoT_MSE_Project

##Resumé du projet

Nous souhaitons développer une solution dédiée à l’agriculture.. Des capteurs seront du type LoRa et
d’autres de type Wi-Fi. Dans la réalité il pourrait s’agir de capteurs à proximité de la ferme qui seraient
en Wi-Fi et de capteurs déportés à l’extérieur par LoRa :
*Un dashboard permettra de visualiser l’évolution des mesures à distance (humidité,
température, suivi de bétails, etc…) et également donner des indicateurs dans la ferme avec la
possibilité de contrôler la fermeture ou ouverture d’une grange
*La communication par WiFi avec un cloud devra être sécurisée avec des certificats.
*En cas d’absence de message pendant un certain de la part d’un capteur une alarme devra
être visualisée
Nous avons du choisir d'appronfondir une variante pour ce projet. Ce projet devra intégrer le __provisioning__ des capteurs Wi-Fi par script.

##Tâches à faire

*Lister les capteurs à disposition et imaginer des sénario pour la création de notre application
*Connecter le device à notre ordinateur et comprendre comment récupérer l'identifiant unique de la board
*Ajouter manuellement un device à AWS IoT Cloud et lister les différentes étapes et paramètres requis
*Créer des certificats pour communiquer en Wi-Fi de manière sécurisé
*Envoyer des messages/valeurs depuis notre device à AWS IoT Cloud
*Envoyer des messages/valeurs depuis AWS IoT Cloud à notre device
*Comment lier AWS et the Things network (afin d'utiliser LoRa)
*Envoyer des paquets LoRa depuis notre device à AWS IoT network
*Envoyer des paquets LoRa depuis AWS à notre device
*Réaliser un dashboard (celui-ci se trouvera sur notre cloud AWS)
*Provisionning avec un script Python
