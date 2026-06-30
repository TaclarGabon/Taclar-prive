TACLAR FIREBASE V34.1 - PORTAIL PAR ROLES FINAL

Correction principale :
- Firebase ne se connectait pas à cause d'une erreur dans la clé apiKey.
- Ancienne clé trouvée : AIzaSyC_JNVVCrd...
- Clé corrigée : AIzaSyC_JNVVGrd...

Fichiers inclus :
- index.html : portail principal
- client.html : accès Client
- dispatcher.html : accès Dispatcher
- chauffeur.html : accès Chauffeur
- admin.html : accès Admin
- direction.html : accès Direction
- logo_taclar.png : logo

Installation GitHub Pages :
1. Remplacer les fichiers du dépôt par ceux de ce dossier.
2. Garder index.html à la racine.
3. Vérifier que client.html, dispatcher.html, chauffeur.html, admin.html et direction.html sont à la racine.
4. Attendre 1 à 3 minutes après commit.
5. Ouvrir le lien GitHub Pages.

Installation Firebase Hosting :
1. Copier ces fichiers dans le dossier public du projet Firebase.
2. Lancer firebase deploy.
3. Ouvrir l'URL Firebase Hosting.

Important :
Cette version reste une séparation visuelle MVP par rôles.
Pour une vraie sécurité, il faudra ajouter Firebase Authentication + règles Firestore.
