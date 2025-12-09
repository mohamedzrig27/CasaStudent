🏡 Student Housing Agency – Multi-Platform Application
Web • Desktop • Mobile
Symfony • JavaFX • Flutter
📌 Description du Projet

Ce projet propose une solution complète et moderne pour la gestion d’une agence immobilière destinée aux étudiants.
L’objectif est de fournir une plateforme capable d’offrir :

Une interface Web pour l’administration et la gestion interne des biens.

Une application Desktop pensée pour les agents de l’agence.

Une application Mobile pour les étudiants, leur permettant de rechercher, consulter et réserver des logements facilement.

Le système repose sur une architecture centralisée et cohérente, avec un backend robuste et des interfaces ergonomiques adaptées à chaque environnement.

🎯 Objectifs

Fournir une plateforme intuitive dédiée aux logements étudiants

Centraliser la gestion des biens, réservations et étudiants

Offrir une solution disponible sur Web, Desktop et Mobile

Utiliser des technologies performantes et modernes

Garantir une synchronisation fluide entre toutes les plateformes

🛠️ Technologies Utilisées
Backend & Web

Symfony (PHP)

Twig / API Platform (si applicable)

MySQL / PostgreSQL

Desktop

JavaFX

Maven / Gradle (selon ton setup)

Mobile

Flutter

Dart

Autres

REST API

Authentification (JWT/oauth selon implémentation)

Git / GitHub

🧱 Architecture Générale du Projet
/project-root
│
├── backend/                     # Application Symfony
│   ├── config/
│   ├── src/
│   ├── public/
│   ├── migrations/
│   └── ...
│
├── mobile/                      # Application Flutter
│   ├── lib/
│   ├── assets/
│   ├── android/
│   ├── ios/
│   ├── web/
│   └── ...
│
├── desktop/                     # Application JavaFX
│   ├── src/
│   │   ├── main/java/
│   │   └── main/resources/
│   └── ...
│
├── docs/                        # Documentation, schémas, UML, etc.
│
└── README.md                    # Documentation principale

🚀 Fonctionnalités Principales
Côté Étudiant (Mobile)

🔍 Recherche de logement

🏠 Consultation de fiches détaillées

❤️ Gestion des favoris

📅 Demande de réservation

👤 Espace utilisateur et gestion du profil

Côté Agence (Desktop + Web admin)

➕ Ajout et modification de logements

🗂️ Gestion des catégories et quartiers

👥 Gestion des étudiants

📝 Validation / suivi des réservations

📊 Tableau de bord et statistiques (si applicable)

⚙️ Installation et Lancement
📌 1. Backend – Symfony
cd backend
composer install
php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate
symfony server:start

📌 2. Mobile – Flutter
cd mobile
flutter pub get
flutter run

📌 3. Desktop – JavaFX
cd desktop
mvn clean install
mvn javafx:run


(ou Gradle selon ton projet)

🌐 API & Communication

Les applications Desktop et Mobile communiquent avec le backend Symfony via une API REST.
Typiquement disponible sur :

http://localhost:8000/api/


Les échanges sont réalisés en JSON.

🧪 Tests
Symfony
php bin/phpunit

Flutter
flutter test

📚 Documentation

Toute la documentation complémentaire (UML, diagrammes, captures d’écran, spécifications...) peut être placée dans le dossier :

/docs

👨‍💻 Auteur

Projet développé par :
Mohamed Zrig
