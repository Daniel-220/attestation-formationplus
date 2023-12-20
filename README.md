# attestation-formationplus
Ce projet permet de générer des attestations de formation pour les étudiants de FormationPlus. Il est écrit en Java et utilise la base de données MySQL.
Pour installer le projet, vous devez créer une base de données MySQL et une table Attestation avec les colonnes suivantes :

id (int, primary key)
etudiant (string)
convention (string)
message (string)
Vous devez ensuite modifier le fichier src/main/resources/application.properties pour spécifier les informations de connexion à la base de données.

Pour lancer le projet, exécutez la classe AttestationApp.
