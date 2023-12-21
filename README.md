# Lab-authentification-standard

## Travail a faire
L'objectif est de mettre en place un système d'authentification utilisateur avec une interface utilisateur AdminLTE intuitive et visuellement attrayante.

## Prérequis
Avant de commencer, assurez-vous d'avoir ce qui suit :

- Composer installé sur votre système. Sinon, vous pouvez [installer Composer](https://getcomposer.org/).
- Laravel installé globalement ou localement. Vous pouvez créer un nouveau projet Laravel avec la commande suivante :

  ```bash
  composer create-project laravel/laravel=10 .
  ```

## Démarrage
Suivez ces étapes pour créer un système d'authentification en utilisant l'interface utilisateur AdminLTE :

1. **Installer InfyOm Generator :**
   Exécutez la commande suivante pour installer le package InfyOm Generator, qui simplifie le processus de création de composants.

   ```bash
   php artisan vendor:publish --provider="InfyOm\Generator\InfyOmGeneratorServiceProvider"
   ```

2. **Installer Laravel UI AdminLTE :**
   Installez le package Laravel UI AdminLTE, qui intègre l'interface utilisateur AdminLTE dans votre projet Laravel.

   ```bash
   composer require infyomlabs/laravel-ui-adminlte
   ```

3. **Générer l'authentification avec AdminLTE UI :**
   Utilisez la commande Artisan pour générer le système d'authentification avec l'interface utilisateur AdminLTE.

   ```bash
   php artisan ui adminlte --auth
   ```

4. **Installer les dépendances et construire les assets :**
   Installez les dépendances de Node.js et construisez les assets pour votre projet.

   ```bash
   npm install
   npm run dev
   ```

5. **Lancer le serveur de développement Laravel :**
   Démarrez le serveur de développement Laravel pour prévisualiser votre application.

   ```bash
   php artisan serve
   ```

6. **Accéder à l'application :**
   Ouvrez votre navigateur Web et accédez à [http://localhost:8000](http://localhost:8000) pour accéder à l'application Laravel avec l'authentification de l'interface utilisateur AdminLTE.

## Notes supplémentaires
- Personnalisez les vues d'authentification situées dans le répertoire `resources/views/auth` pour correspondre au design de votre application.
- Explorez la documentation d'AdminLTE pour les options de personnalisation et les fonctionnalités supplémentaires : [Documentation AdminLTE](https://adminlte.io/docs/3.2/).

N'hésitez pas à me contacter si vous rencontrez des problèmes ou si vous avez besoin d'une assistance supplémentaire. Bon codage !
