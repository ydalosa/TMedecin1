# My Chat App
My Chat App est une application de chat qui regroupe une partie des outils essentiels de Firebase.

*Pour de plus amples informations sur la syntaxe des [README.md](https://www.christopheducamp.com/2014/09/18/love-markdown/)*

## Sommaire
1. [Charte graphique](#charte-graphique)
2. [Authentification](#authentification)
3. [Profil utilisateur](#profil-utilisateur)
4. [Splash screen](#splsh-screen)
5. [](#)
6. [](#)
***

## Charte graphique
La charte graphique, le document qui défini l'image que vous souhaitez renvoyer à vos clients/consommateurs. 
[Quelques conseils pour bien choisir sa charte graphique](https://majordesign.fr/comment-bien-choisir-sa-charte-graphique/)
### Les couleurs 
* Avec l'aide de l'outil mis en place par Google sur le site [material.io](https://material.io/resources/color/#!/) choisir les différentes couleurs, pour le fond, les icônes et le texte.
* Pensez à modifier le nom des variables dans les fichiers colors et theme lors de la copie des données récupérées via le site material.io.
### Le logo
* Choix d'un icône sur le site [flaticon.com](https://www.flaticon.com) ou sur le site [icones8.fr](https://icones8.fr)
* Télécharger le PNG, en 512x512px, ajuster les couleurs de l'icône choisi en fonction de la charte graphique
  1 - Insérer le fichier en PNG pour différentes tailles
  * Utiliser le plugin [Android Drawable Importer](https://github.com/Skeaner/android-drawable-importer-intellij-plugin/releases/download/0.8/ADI-hack-0.8.zip)
    pour retailler le PNG dans les différentes tailles écrans Android et le placer dans les bons dossiers
  2 - Convertir le fichier en vecteur pour une utilisation en mode responsive
  * Convertir le PNG en SVG avec [onlineconvertfree.com](https://onlineconvertfree.com/fr/convert/png/)
  * Convertir le SVG en vecteur avec [svg2vector.com](https://svg2vector.com)
* Le fichier xml du vecteur servira pour les différents appels du logo et cela pour toutes les tailles écrans 
***

## Authentification
Cette application nécessite l'authentification de l'utilisateur et donc l'utilisation de l'outil Authenticator, pour une authentifaiction compléte il faut plusieurs activités :
- Création d'une activité pour se connecter : LoginActivity
- Création d'une activité pour créer un compte : SignUpActivity
- Création d'une activité pour réinitialiser son mot de passe : ResetPassword

## Profil utilisateur
A cela il faut ajouter activité pour la gestion du profil avec la possibilité de
-De modifier ou supprimer l’image de l’avatar (via un menu)
-De modifier le mot de passe
-De modifier le nom de l’utilisateur
*** 

## Splash screen
Ajout d'une page avec une animation pour l'ouverture de l'app
....




