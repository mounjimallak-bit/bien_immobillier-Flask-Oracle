# Plateforme de location immobilière

bien_immobillier-Flask-Oracle est une application web de location immobilière développée avec Flask et Oracle PL/SQL.

Le projet permet aux locataires de rechercher et réserver des logements et aux propriétaires de gérer leurs annonces et réservations.


## Technologies utilisées

- Python
- Flask
- Oracle SQL
- PL/SQL
- HTML
- CSS
- Tailwind



## Fonctionnalités principales

### Locataire

- Consultation des logements
- Recherche par critères
- Réservation de logements
- Consultation des réservations

### Propriétaire

- Gestion des biens immobiliers
- Consultation des réservations
- Ajout et suppression de biens

### Base de données Oracle

- Tables relationnelles
- Vues SQL
- Procédures PL/SQL
- Triggers
- Contraintes d'intégrité



## Structure du projet
app.py

templates/

index.html

auth_login.html

auth_register.html

owner_dashboard.html

tenant_dashboard.html

property_detail.html

sql/

script_sql.sql

code_sql_pl.sql

requirements.txt


## Installation

### 1 Installation Oracle XE
Créer un utilisateur Oracle :

User :

Password :

DSN :localhost:1521/XEPDB1

### 2 Exécuter les scripts SQL
Exécuter : 
sql/script_sql.sql
sql/code_sql_pl.sql

dans Oracle SQL Developer.

### 3 Installer les dépendances
pip install -r requirements.txt

### 4 Lancer l'application
python app.py
Puis ouvrir :
http://localhost:5000



