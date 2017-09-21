# Comprendre par l'expérience le modèle MVC
* Compétence visée: 6- Développer des pages web en lien avec une base de données
* Organisation:
  * Travail en pair programming
  * Un repository GIT
  * A chaque étape une branche sera créée au début et mergé à la fin pour permettre à chacun de redémarer sur des bonnes bases à chaque début d'exercices
* Préalable:
  * Avoir la base de données annonces_immo
  * Savoir faire une page php avec accès au données

* Organisation

* Exercice 1: Création d'une application flat php
  * Créez une page php "annonces.php" qui renvoie une page HTML structurée avec un header une nav à gauche et une section. Le header aura un background-color bleu et contiendra un titre h1 "Affichage des annonces"
  * Ajoutez le code nécessaire pour avoir une connexion à la base, requeter la table annonces et afficher le résultat dans une table html positionnée dans la section.
  * Reproduire la page annonces.php en créant aussi les pages utilisateurs.php et rubriques.php qui afficheront respectivement les utilisateurs et les rubriques.
  * Ajoutez un menu de navigation dans la section nav pour permettre la navigation entre les pages

  * Exercice 2: Utilisez votre application sur une autre base de données
    * Immaginez qu'un client est intéressé pour utiliser votre systeme de visualisation de la base de données d'annonces immobilière mais qu'il a nommé sa base différemment. Pour cela rennomer votre base de données et reportez les modifications nécessaires pour que votre systeme fonctionne.
    * Sur combien de fichiers avez vous du intervenir pour réaliser cette adaptation?
    * Factorisez votre code pour faire en sorte que la partie connexion se trouve dans un seul fichier
    * Présentation de solutions en live programming

  * Exercice 3: Modifier la structure de votre page HTML
    * Le client de votre application souhaite que le menu de navigation ne soit plus à gauche mais en haut pour avoir plus d'espace visuel en largeur. Modifier donc votre application pour répondre à cette demande.
    * Sur combien de fichiers avez-vous du intervenir pour réaliser cette adaptation?
    * Factorisez votre code: extraire toute la structure HTML et la déplacer dans un seul fichier.
    * Testez maitenant d'autres modifications structurelles ou de mise en forme et vérifiez la bonne répercussion sur l'ensemble des pages.
    * Présentation des solutions en live programming

  * Exercice 4: L'administrateur de votre base de données a besoin d'effectuer une maintenance sur le serveur de base de données qui sera indisponible pendant toute une nuit. Il faut donc permettre de rediriger pendant ce temps toutes les pages vers une page qui explique à l'utilisateur que le site va être indisponible pendant ce temps.
  * Sur combien de fichiers avez-vous du intervenir pour réaliser cette nouvelle demande?
  * Afin de pouvoir controler tout accès à une page et éventuellement permettre des controles ou traitement préalable à l'affichage de la page faites en sorte que toute page ne soit accessible qu'en passant par index.php ( vous passerez le nom de la page en parametre )
  * Testez la nouvele architecture

  * Exercice 5: A partir de votre expérience et de ce que vous pouvez imaginer répondez aux questions suivantes:
    * Quand peut-on déceller une opportunité de factorisation?
    * En quoi consiste la factorisation?
    * Recherchez ce que signifie les lettres MVC dans le modèle MVC
    * Faites l'association entre chaque fichier créé et sa couche dans le modèle MVC.
    * Qu'est-ce qu'un controleur Frontal? quel fichier opère se role dans votre projet?


