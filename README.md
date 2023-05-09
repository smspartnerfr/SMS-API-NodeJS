# SMS-API-NodeJS


Assurez-vous d'installer le module "https" en exécutant "npm install https" avant d'exécuter ce code.


Ce code est un script Node.js qui envoie un SMS via l'API SMS Partner.

Le script commence par importer le module https. Ensuite, il définit les informations nécessaires pour envoyer le SMS : une clé d'API, le numéro de téléphone du destinataire, le nom de l'expéditeur, la gamme de SMS à envoyer et le contenu du message.

Ensuite, le script définit les options pour la requête HTTP POST vers l'API SMS Partner. Cela inclut l'URL de l'API, le port utilisé, le chemin de l'API pour envoyer un SMS, la méthode utilisée (POST), ainsi que les en-têtes de la requête, notamment le type de contenu et la longueur des données envoyées.

Le script effectue ensuite la requête HTTP POST avec les options et les données définies précédemment. Lorsque la réponse est reçue, le script affiche le code d'état de la réponse et affiche les données de la réponse sur la sortie standard.

Si une erreur se produit lors de l'exécution de la requête HTTP, le script affichera l'erreur sur la sortie d'erreur standard.

Avant de executer 
