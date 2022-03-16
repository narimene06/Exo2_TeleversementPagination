
L'idée de cette partie de l'éxercice étant de mettre en place deux mini scripts permettant de televerser des images dans un dossier dans un premier temps ensuite dans un second temps les charger et stocker au niveau d'une base de données ainsi qu'au final les appeler via une requete sql afin d les afficher sur un server Web en utilisant le principe de pagination.

Pour ce faire le fichier Formulaire.php a pour but de mettre en oeuvre un formulaire de choix de fichier image et les televerser dans un autre dossier figurant dans wamp WWW. 
le fichier Teleechargement.php a pour fonction, telecharger les images et les stocker dans une base de données en prenant en compte les differents attributs soient, Id, Nom, Format et l'URL
et finalement, le fichier PaginationImages a pour but, select les images stockées précédemment dans la base de données et les afficher dans une page web en mettant en place le système de pagination.
