# WebServices REST
## Service WEB ?
	Service offert via des accès de type WEB
		- Appel à distance de code
		- Mécanisme d'encodage de données
		- Mécanisme d'exécution
	Extension de l'appel d'une fonction
		- à travers un réseau
		- exploitant des requêtes et réponses
		
## Solutions aux problèmes
	Protocoles d'échanges standard
		- HTTP, SMTP...
	Représentation normalisée des données
		- XML, JSON...
	Sémantique standardisée
		- RPC, persistance ou non des états
	Découverte des services
		- systèmes d'annuaires à grande échelle
	API standardisée pour les langages
		- marshalling et unmarshalling
			UTF8, texte par exemple
		- appel et transport des données / résultat
		
## Solution proposées
	XML-RPC
	Services WEB
		- SOAP
			- UDDI
			- WSDL
		- REST
		
## REST
	Representational State Transfert
	Définit par Roy Fielding (2000)
	Style d'architecture (Bonnes pratiques) basé sur le web
		- Pas d'état
		- Exploitation des verbes HTTP
		- Centré sur les ressources
		- Exploitation étendue des URL
	Rest est :
		- Une approche méthodologique pour les app
		- Un style d'architecture
		- Un ensemble de bonnes pratiques
	Rest n'est pas :
		- Format
		- Protocole
		- Standard
		- API
		
## Services REST
	Exploitation des ressources
	Conception d'applications RESTful
	Elements de gestion de l'hétérogénéité à large spectre
		- Serveurs
		- Langages
		- Formats de données...
	Exploités par tous les acteurs du WEB
	De part sa légèreté à remplacer la plupart des services SOAP
	
## Gestion des états
	Services WEB Rest sans état (stateless)
	Comme le protocole HTTP
	Requêtes self-contain
		- Les requêtes contiennent l'ensemble des informations nécessaires à leur traitement
	Efficacité des services WEB REST
		- Peu de ressources systèmes
		- Pas de session
		- Pas d'état
		
## Interfaces d'accès
	Définition des opérations CRUD sur les ressources
		- Create
		- Read / Retrieve
		- Update
		- Delete
	Exploitation des verbes HTTP
		- POST
		- GET
		- PUT
		- DELETE
	Extension possible aux autres verbes
	
## Gestion des accès
	Gestion centrée sur les ressources
	Ressources identifiées par les URI
	Définition du chemin d'accès
		- Sur le serveur
		- Dans la logique des ressources
		- Définition du contexte d'exécution
		- Réécriture d'URL sur le serveur
	Association ressource <-> données
	Association URL, verbe <-> opération sur des données
	
## Gestion orientée client
	Communication centrée sur l'état de la donnée
		- Etat de la données =! État du protocole
	Etat de la donnée == état de la ressource
	Client responsable de la gestion de l'état de la ressource
		- Emission des opérations et des éléments de traitement
		- Service : accès externe et application d'opérations
		
## Structure d'une requête REST
	Ressource
		- Identifiant de la requête
		- URI
		- http://localhost:8000/RT0704/etudiants
	Verbes HTTP
		- Manipulation de la ressource
		- GET, POST, PUT, DELETE
	Représentation
		- Vue de l'état
		- Données transférées
		- Format spécifique : XML, JSON...
		
## Association ressource / URI
	Ressource : élément accessible et identifiable
	URI : identification unique d'une ressource sur le système
	Exemple d'URI -> Diapo ?
	
## Create <-> POST
	Création d'une ressource
	Mode sans état : création multiple d'une même ressource
	Attention à la perte / écrasement d'une ressource
	Requête HTTP : exploitation des données !
	
## Retrieve / Read <-> GET
	Récupération de l'état d'une ressource
	Ne modifie pas l'état de la ressource
	Réponse HTTP : exploitation des données
	
## Update <-> PUT
	MAJ d'une ressource
	Modification de l'état de la ressource
		- Complète ou partielle
	Exploitation d'une ressource
	
## Exploitation de l'en-tête HTTP
	Eléments classiques du HTTP
		- Taille
		- Type MIME...
	Ajout d'éléments	d'identification / sécurité
		- Clé
		- Session
		- Identification développeur
		- Identification application...
		
## Exemple
	cf. diapo
	
## Développement

	Développement à la main
		- Définition dans un serveur WEB minimal des différents
		
## Exemple d'application : une vidéothèque
	format vidéothèque -> cf. Diapo
	Développement d'un service pour sauvegarder sa vidéothèque
	Développement full stack
		- Accès aux données : stockage en JSON sur le disque
			- Définition du format des données
	...
	
## API de manipulation
	Définition de l'ensemble des foncions
		- Paramètres
		- Actions réalisées
	Gestion des erreurs
		- Choix des tests
			- Vérifi de la validité des par
			- Vérif système
			
## Liste des fontions
	cf. diapo
