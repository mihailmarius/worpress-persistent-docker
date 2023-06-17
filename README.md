# WordpresPersistent with docker-compose

### English:

Short project description.

## Overview
This project contains a Docker Compose configuration to run a WordPress development environment with MySQL and phpMyAdmin. It also includes a custom php.ini configuration file.

## Setup
Make sure you have Docker and Docker Compose installed on your machine.
Clone this project to your local machine.

## Usage Instructions
Navigate to the cloned project directory.
Copy the php/configuration/php.ini.example file to php/configuration/php.ini.
Edit the php/configuration/php.ini file to add/configure your desired PHP settings.
Run the command docker-compose up -d --build to start the Docker containers.
Access the WordPress application through the browser at http://localhost.
Access phpMyAdmin at http://localhost:8080 to manage the MySQL database.

## Customization
If you want to add/modify WordPress plugins or themes, you can copy the respective files to the php/www/wp-content/plugins or php/www/wp-content/themes directory before running docker-compose up -d --build. They will be available in your WordPress installation.

## Contribution
Contributions are welcome! If you have suggestions for improvement, issues to be resolved, or the desire to contribute with code, please open an issue or a pull request.

# WordpresPersistent cu docker-compose
### Romana:

Descriere scurtă a proiectului.

## Prezentare generală

Acest proiect conține o configurație Docker Compose pentru a rula un mediu de dezvoltare WordPress cu MySQL și phpMyAdmin. Acesta include și un fișier de configurare `php.ini` personalizat.

## Configurare

1. Asigură-te că ai instalat Docker și Docker Compose pe mașina ta.
2. Clonează acest proiect pe mașina locală.

## Instrucțiuni de utilizare

1. Navighează în directorul proiectului clonat.
2. Copiază fișierul `php/configuration/php.ini.example` în `php/configuration/php.ini`.
3. Editează fișierul `php/configuration/php.ini` pentru a adăuga/configura setările PHP dorite.
4. Rulează comanda `docker-compose up -d --build` pentru a porni containerele Docker.
5. Accesează aplicația WordPress prin intermediul browserului la adresa `http://localhost`.
6. Accesează phpMyAdmin la adresa `http://localhost:8080` pentru a gestiona baza de date MySQL.

## Personalizare

Dacă dorești să adaugi/modifici module sau teme WordPress, poți copia fișierele respective în directorul `php/www/wp-content/plugins` sau `php/www/wp-content/themes` înainte de a rula `docker-compose up -d --build`. Acestea vor fi disponibile în instalarea WordPress.

## Contribuție

Contribuțiile sunt binevenite! Dacă ai sugestii de îmbunătățire, probleme de rezolvat sau dorința de a contribui cu cod, te rugăm să deschizi un issue sau un pull request.


# WordpresPersistent avec docker-compose
## French:
Description courte du projet.

## Aperçu

Ce projet contient une configuration Docker Compose pour exécuter un environnement de développement WordPress avec MySQL et phpMyAdmin. Il inclut également un fichier de configuration php.ini personnalisé.

## Configuration

Assurez-vous d'avoir Docker et Docker Compose installés sur votre machine.
Clonez ce projet sur votre machine locale.

Instructions d'utilisation

Accédez au répertoire du projet cloné.
Copiez le fichier php/configuration/php.ini.example dans php/configuration/php.ini.
Modifiez le fichier php/configuration/php.ini pour ajouter/configurer vos paramètres PHP souhaités.
Exécutez la commande docker-compose up -d --build pour démarrer les conteneurs Docker.
Accédez à l'application WordPress via le navigateur à l'adresse http://localhost.
Accédez à phpMyAdmin à l'adresse http://localhost:8080 pour gérer la base de données MySQL.

## Personnalisation

Si vous souhaitez ajouter/modifier des plugins ou des thèmes WordPress, vous pouvez copier les fichiers respectifs dans le répertoire php/www/wp-content/plugins ou php/www/wp-content/themes avant d'exécuter docker-compose up -d --build. Ils seront disponibles dans votre installation WordPress.

## Contribution

Les contributions sont les bienvenues ! Si vous avez des suggestions d'amélioration, des problèmes à résoudre ou le désir de contribuer avec du code, veuillez ouvrir une issue ou une pull request.



