# Application de Gestion des Employés

Une application web complète pour la gestion des employés, développée avec Laravel. Ce projet permet de gérer efficacement les informations des employés (ajout, modification, consultation, suppression) avec une interface intuitive et sécurisée.

## Fonctionnalités

- **Authentification sécurisée** : Système de connexion et d'inscription pour les administrateurs
- **Gestion complète des employés** :
  - Ajout de nouveaux employés
  - Modification des informations
  - Consultation de la liste des employés
  - Suppression d'employés
  - Recherche et filtrage des employés
- **Validation des données** : Contrôle des informations saisies
- **Interface responsive** : Adaptation à tous les écrans (ordinateur, tablette, mobile)
- **Sécurisation des routes** : Accès protégé selon les rôles

## Technologies Utilisées

- **Backend** : Laravel (PHP)
- **Frontend** : HTML5, CSS3, JavaScript, Bootstrap
- **Base de données** : MySQL
- **Système de templates** : Blade
- **Authentification** : Système natif Laravel
- **Sécurité** : Protection CSRF, validation des formulaires, hash des mots de passe

## Structure du Projet

gestion-employes/
├── app/
│ ├── Http/
│ │ ├── Controllers/
│ │ │ ├── Auth/
│ │ │ │ └── LoginController.php
│ │ │ ├── RegisterController.php
│ │ │ └── EmployeController.php
│ ├── Models/
│ │ └── Employe.php
│ └── ...
├── database/
│ ├── migrations/
│ │ └── create_employes_table.php
│ └── seeders/
├── resources/
│ └── views/
│ ├── auth/
│ ├── employes/
│ └── layouts/
└── routes/
└── web.php
