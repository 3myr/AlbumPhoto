# AlbumPhoto

L’utilisateur dispose d’une interface graphique pour créer un album photo à partir d'image importer.

# Utilisation
  - Télécharger le fichier **album.jar**
  - Télécharger la bibliothèque javaFX ( https://gluonhq.com/products/javafx/ )
  - Ouvrir un terminal dans le dossier où se trouve album.jar
  - Utiliser la ligne de commande suivant : 
```bash  
java -jar --module-path [...]/lib --add-modules javafx.controls,javafx.fxml,javafx.graphics -Djdk.gtk.version=2. -Dprism.forceGPU=true album.jar
```
avec [...]/lib, l'emplacement du dossier lib de javaFX

# Fonctionnalités

  - Importer des images par Drag'n Drop dans la zone associé
  - Importer des images en cliquant sur le bouton
  - Déplacer des images importées sur des pages de l'album
  - Créer une nouvelle page dans l'album

# Aperçu

  - Général
  ![Connexion](https://nsa40.casimages.com/img/2020/11/10//201110104120144135.gif)
  
  Retrouver aussi le projet sur le site de la Faculté des Sciences et Technologiques :
  http://licence-master-informatique.formation.univ-lorraine.fr/portfolio/projet-album-photo/
