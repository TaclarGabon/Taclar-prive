TACLAR FIREBASE V34 - PORTAIL PAR ROLES

Base : V33 validée.

Nouveautés :
1. index.html devient le portail principal TACLAR avec fond plus sombre.
2. client.html : accès Client uniquement.
3. dispatcher.html : accès Dispatcher uniquement.
4. chauffeur.html : accès Chauffeur avec sélection du chauffeur + code test 1234.
5. admin.html : accès Admin, rapports + outils + gestion chauffeurs.
6. direction.html : accès Direction, vue complète.

Important :
- Cette séparation est une séparation visuelle MVP.
- Pour une vraie sécurité, il faudra ensuite Firebase Authentication + règles Firestore.
- Le code chauffeur test est 1234.
