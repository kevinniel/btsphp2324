# TP

Faire un formulaire d'inscription à une newsletter. On doit retrouver : 

- 1 page permettant de s'inscrire (mail obligatoire + nom (optionnel) + prenom (optionnel))
- 1 page permettant d'afficher la totalité des inscrits. Cette page ne doit afficher le contenu QUE avec un système de protection par mot de passe (géré en GET via l'URL)


## Étapes

1. Créer la page "index.php" avec le formulaire de récupération des emails
2. Créez votre BDD pour le projet
3. Gérez sur la même page la connexion avec votre BDD
4. Gérez la récupération des informations depuis le formulaire
5. Enregistrez les infos en BDD avec PDO
6. Créez la page "admin.php" qui doit afficher toutes les adresses mail. Intégrez un formulaire pour saisir le MDP
7. Intégrez la condition qui permet de n'afficher les résultats QUE si le MDP choisi est bon ($_GET)
8. Gérez la connexion BDD sur la page admin.php
9. Récupérez les contenus depuis la BDD sur les inscrits à la newsletter
10. Afficher les résultats dans un tableau