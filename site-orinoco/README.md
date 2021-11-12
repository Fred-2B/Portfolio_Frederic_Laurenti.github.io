Orinoco
Orinoco, une entreprise de commerce en ligne.

Son credo ? Se démarquer des grands site e-commerce comme Amazon en créant des applications thématiques ne vendant qu’un seul groupe de produits.

Prérequis :
Vous aurez besoin d'avoir Node et npm installés localement sur votre machine.

Installation :
Clonez ce dépôt. À partir du dossier du projet, exécutez "npm install". Vous pouvez ensuite exécuter le serveur avec "node server". Le serveur doit s'exécuter sur localhost avec le port par défaut 3000. Si le serveur s'exécute sur un autre port pour une raison quelconque, cela est imprimé sur la console lorsque le serveur démarre, par ex. "Listening on port 3001".

Architecture générale :
L’application web sera composée de 4 pages :

● Une page de vue sous forme de liste, montrant tous les articles disponibles à la vente.

● Une page “produit”, qui affiche de manière dynamique l'élément sélectionné par l'utilisateur et lui permet de personnaliser le produit et de l'ajouter à son panier.

● Une page “panier” contenant un résumé des produits dans le panier, le prix total et un formulaire permettant de passer une commande. Les données du formulaire doivent être correctes et bien formatées avant d'être renvoyées au back-end.

● Une page de confirmation de commande, remerciant l'utilisateur pour sa commande, et indiquant l'identifiant de commande envoyé par le serveur.

Produits présentés :
Dans un premier temps, une seule catégorie de produits sera présentée.

Choix à faire entre les 3 propositions suivantes :

● Ours en peluche faits à la main.

● Caméras vintage.

● Meubles en chêne.

Validation des données :
Pour les routes POST, l’objet contact envoyé au serveur doit contenir les champs firstName, lastName, address, city et email.

Le tableau des produits envoyé au backend doit être un array de strings products.

Les types de ces champs et leur présence doivent être validés avant l’envoi des données au serveur.

Technologies utilisées :
HTML, CSS, JavaScript

