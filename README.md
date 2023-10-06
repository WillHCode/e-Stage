# e-Stage
Projet Web Avancé Bac3

# Présentation
## Description de l’application
  L’application nommé « e-Stage » est une plateforme en ligne (au format web) à destination des étudiants et entreprise désireux de suivre ou proposer des stages. Sur cette plateforme il sera possible de créer un compte, voir/créer des offres de formations, communiquer par messages aux sujets des offres en ligne, réserver des entretiens, ….
Cette plateforme permettra aux deux intervenant, de structuré et rassembler les interactions en lien avec les offres de stage, sur un seul site web. 
#	Détails
##	Contraintes techniques
###	Front-End
  L’interface utilisateur sera créer en utilisant le **Framework React** avec **Typescript** en respectant une *structure MVC*
On distinguera 2 types de présentation de la page en fonction de si on est connecté en tant que client (chercheur de stage) ou d’une entreprise (proposeur de stage)
###	Back-End
  Le service web sera développer en Java utilisant le **Framework Spring Boot**. La structure devra strictement respecter **l’architecture hexagonale**.
Pour la base de données principale, elle sera au format **MySQL**. La base de données en temps réel du service de messagerie sera faite en utilisant **Firebase**. Ces 2 base de données communiqueront avec le service en utilisant une API sécurisé.
##	Fonctionnalités
###	Fonctionnalités communes
-	Création d’un compte (via formulaire web)
-	Rechercher des offres de stage (+ filtrage avec système de tag)
-	Chat en direct via messagerie
-	Système de notification
-	Modifier données personnels du compte
-	Calendrier reprenant les entretiens enregistrés
-	Récupérer un historique 
2.2.2	Client
-	S’enregistrer sur une offre de stage
-	Uploader son CV (format PDF) sur son profil
2.2.3	Entreprise 
-	Créer une offre de stage
-	Sélectionner des postulant 

##	SCRUMB
  Il ne sera pas détaillé à quel moment la base de données doit-elle être implémenté, ni autre services ou détails trop précis, la liberté est laissée au bon sens des développeurs. 
L’ordre des priorités trivial est le suivant :
1.	Fonctionnalité Communes
2.	Client & Entreprise
   
L’ordre détailler de développement suggérer de manière chronologique est le suivant :
1.	Création d’un compte & Login
2.	Modification de données personnels
3.	Création d’un formulaire Web pour les inscription et login
4.	Création d’offre de stage
5.	Enregistrement pour un stage
6.	Rechercher un stage (système de filtre peut-être implémenter plus tard en fonction de l’avancement du projet)
7.	Upload du CV au format PDF
8.	Création/Récupération d’un historique
9.	Sélectionner des postulant
10.	Notification & mail
11.	Chat en direct
12.	Calendrier
    
**A NOTER :**
-	Les fonctionnalités 1 -> 5, sont **primordiales** afin d’avoir le minimum requis pour un semblant d’application fonctionnel.
-	Les ordres des autres fonctionnalités sont globalement Inversible, cette liste n’est qu’une suggestion. Il est également possible que certaines de ces fonctionnalités ne soient pas développées en fonction des délais à respecter.
