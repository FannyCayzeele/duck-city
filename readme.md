Ce site est un site web d'ébauche d'e-commerce pour acheter des canards en plastique.

Le but est de pouvoir sélectionner une liste de canards, de gérer son panier en ligne et de les commander.

L'utilisateur va pouvoir :
- créer son compte utilisateur et le modifier
- supprimer ses données
- modifier son mot de passe et son avatar
- ajouter des canards à son panier
- commander son panier (avec un email de confirmation résumant la commande)

Une pagination a été ajoutée à l'affichage du contenu du shop.
L'utilisateur peut facilement chercher dans la liste des canards grâce à une pagination et au tri que j'ai mis en place.
Il peut trier par nom, prix et date de création du canard.

Concernant le javascript :
A noter que l'ajout du canard au panier de l'utilisateur se fait via de l'Ajax.
J'ai également utilisé du Javascript pour l'affichage temporaire des messages de confirmation ou d'erreur d'opérations, ceci via la librairie jQuery.
Aussi sur la page d'accueil il y a du Javascript pour un décompte de promotion pour le "duck" ou canard du mois.

Concernant l'accès à la DB: 
Pour l'accès à la DB, j'ai utilisé la class PDO Wrapper comme conseillé.
Aussi je me suis inspirée du système de classes modèles du framework CakePHP afin de créer un accès évolutif à la DB.
Je me suis également inspirée de ce framework pour la validation des données avant insertion en DB.

Concernant la DB:
j'ai utilisé le software MySQL Workbench afin de faire le design complet de la DB et ainsi générer automatiquement le script de création
de ma base de données.

Par manque de temps, je n'ai pas terminé plusieurs idées intéressantes que je voulais mettre en place:
- gestion des utilisateurs et de leurs droits (une table permissions déjà présente)
- création d'un canard personnalisé en choisissant son costume, sa couleur et son accessoire : des tables accessories, suits et colors sont présentes et liées à la table products.
- une interface web d'administration pour gérer directement tous les canards : création, édition, suppression, ...
- une page de recherche dans la liste des canards