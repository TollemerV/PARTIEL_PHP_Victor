# PARTIEL_PHP_Victor

Quelles sont les 2 méthodes HTTP utilisables dans un formulaire en PHP ?

Les méthodes sont $_GET et $_POST.


Quelle est la différence entre include, include_once, require et require_once ?

include inclut et exécute le fichier spécifié en argument. C'est exactement pareil pour require à l'exception que require emet une erreur 
lorsqu'il y en a une alors que include n'en affiche pas.
Include_once agit comme include la diffèrence est que si le code est déja inclus il ne va pas le reinclure une seconde fois.
Require_once est identique a require ormis le fait que le code ne sera pas inclus une seconde fois si celui ci à déjà était inclus.

Quelle fonction devez-vous appeler pour utiliser les sessions dans votre application ?

La fonction est :session_start();

Qu'est-ce qu'un DSN et à quoi sert-il dans le cadre de PDO ?

DSN: DATA SOURCE NAME, il permet d'établir une connexion à une source de donnée. En PDO, il sert à se connecter à notre base de donnée.

Quelle est la différence entre une requête préparée et une requête non préparée ?

Une requete préparée est utilisée pour exécuter la même requête plusieurs fois alors que la requete non préparé s'éxecute une fois.

Quelle est la différence entre la méthode GET et la méthode POST ?

La méthode Get ajoute les données à l'URL alors que Post non. En plus de cele post n'a pas de limite de taille.
