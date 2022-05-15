# Projet developpement android
---

# Description du projet

Ce projet est un projet de deuxieme année d'école d'ingénieurie (Tek-Up). Il a pour but de avoir une note du **DevoirSurveillé**. J'ai utiliser une **RecyclerView** afin d'afficher les données d'une **API REST**.J'ai utiliser l'**API de SpaceX** *(disponible à cette adresse : https://api.spacexdata.com/v3/launches/).* 


# Taches accomplie
- **Récuparatuion des données d'une API REST** disponible sur internet
- **Stockage** des données dans un **modèle JAVA**
- Architecture **MVC**
- Affichage des données dans une **RecyclerView** avec un **Adapter**
- **Affichage d'images** récupérées via des liens dans l'API avec la bibliothèque **Picasso** *(disponible à cette adresse : http://square.github.io/picasso/)*
- Utilisation de **plusieurs activités** dont une affichant une **liste de données** et une autre affichant le **détail d'un objet de cette liste**.

# Foncitonnalités

L'application dispose de 3 activités distnctes : **la page d'accueil**, les **différentes missions de SpaceX** et **détails de mission**. 

## Icone

l'icone de l'applicaiton est customisée afin de coller le plus possible à la charte graphique de cette dernière

<img src="https://github.com/Fouedrk/ProjetAndroid1.0/blob/master/pictures_markdown/Icone.PNG" width="100"/>

<img src="https://github.com/Fouedrk/ProjetAndroid1.0/blob/master/pictures_markdown/Icone1.PNG" width="250"/>

## Écran d'accueil

Cet écran est celui par lequel l'utilisateur est accueilli lorsqu'il ouvre l'application, on peut y voir le nom de l'application. 


<img src="https://github.com/Fouedrk/ProjetAndroid1.0/blob/master/pictures_markdown/Acceuil.PNG" width="250"/>

En bas de cet écran se situent deux boutons :
- Le bouton avec le dessin d'enveloppe permet d'**envoyer un mail au créateur de l'application** afin d'envoyer d'éventuels retours

<img src="https://github.com/Fouedrk/ProjetAndroid1.0/blob/master/pictures_markdown/Mail1.PNG" width="250"/>

quand on clique dessus, un onglet s'ouvre en bas et l'**utilisateur est invité à choisir l'application à utiliser**. 

<img src="https://github.com/Fouedrk/ProjetAndroid1.0/blob/master/pictures_markdown/Mail2.PNG" width="250"/>

On peut prendre par exemple Gmail, l'**application se lance** et le champ d'adresse se retrouve alors **automatiquement rempli** et l'utilisateur n'a plus qu'à tapper son message. 

<img src="https://github.com/Fouedrk/ProjetAndroid1.0/blob/master/pictures_markdown/Mail3.PNG" width="250"/>

- Le bouton entrer permet de **lancer la seconde activité** initialisant la connexion avec l'API Rest

## Liste des missions

La secone activité a pour objectif de récupérer les données obtenues via un appel à une API Rest afin de les afficher sous la forme d'une liste en utilisant la RecyclerView et un Adapter.

<img src="https://github.com/Fouedrk/ProjetAndroid1.0/blob/master/pictures_markdown/Liste1.PNG"/> 

<img src="https://github.com/Fouedrk/ProjetAndroid1.0/blob/master/pictures_markdown/Liste2.PNG" width="250"/>

Chaque mission est symbolisée par son logo, récupéré via le lien disponible dans l'API et affiché par **Picasso**, ainsi que par son numéro de mission, son nom et son année de lancement. 

En cliquant sur une mission, on accède à son écran détail *(décrit ci-après)*

## Écran de détail

Cet écran a pour but d'afficher les détails relatifs à chaque mission.

<img src="https://github.com/Fouedrk/ProjetAndroid1.0/blob/master/pictures_markdown/Details.PNG" width="250"/>

On peut y voir le logo de la mission affiché en grand ainsi que les détails du vol. 

En bas de page, un bouton permet de lancer une activité navigateur internet pointant vers l'adresse de la vidéo youtube du vol de la fusée. 

<img src="https://github.com/Fouedrk/ProjetAndroid1.0/blob/master/pictures_markdown/Youtube.PNG" width="250"/>

## Conclusion

Ce projet m'a permi de découvrir la difficultés de travailler avec android studio sur windows, je dois me familiariser plus au outils de developpements, je ne peut pas developper dans un environnement aussi evolutif et dynamique comme l'android tant que je doit fair un effort enorme pour debugge chaque code de ligne que je copie de stackoverflow.


