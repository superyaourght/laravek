# 🛠️ Projet LARAVEK - Route de Développement

## 💡 Idée du Projet

Explorer les possibilités de développement en solo avec Laravel. Profiter de l'occasion pour expérimenter avec Docker et limiter l'installation de logiciels sur la machine locale, en prévision d'un déploiement sur serveur.

---

## ⚙️ Configuration de l'Environnement de Développement

### 1. Git
1. Installation de Git.
2. Création et ajout d'une nouvelle clé SSH (pour GitHub et local).
3. Ajout de Git Bash.

### 2. Docker
1. Installation du client Docker Desktop.
2. Lecture de la documentation Docker pour se familiariser.
3. Exécution du conteneur `hello-world` pour test.
4. Création d'un conteneur "host".
5. Configuration du conteneur :
   - Synchronisation d'un dossier entre le conteneur et le PC.
   - Création d'un *snapshot* du conteneur une fois configuré (comme une VM ?) pour permettre un rebuild facile.

### 3. PHP
1. Installation de PHP.
2. Configuration d'un débogueur (optionnel, selon les besoins).

### 4. Éditeur de Code : VSCode ou PhpStorm ?
   #### VSCode
   - **Extensions** :
     - Docker
     - PHP
   - **Thèmes** :
     - Choisir un thème pour PHP.
   - **Configuration** :
     - Setup du compilateur PHP.
     - Linter (optionnel).

   #### PhpStorm *(si choisi)*
   - **Installation** : Procéder à l'installation et configurer en fonction des besoins PHP et Docker.

### 5. Laravel
1. Installation de Laravel dans le conteneur Docker.
   - Dépendances nécessaires : Composer, WSL, Node.js, npm.
2. Configuration initiale de Laravel dans le conteneur.

### 6. JavaScript *(optionnel)*
   - Décider de l'ajout de JavaScript selon les besoins du projet.

---

## 🚀 Démarrage du Développement

Une fois toutes ces étapes de configuration terminées, tu pourras enfin commencer le développement ! 🎉

## Tableau des taches

| **Catégorie** | **Tâches** | **Statut** |
|---------------|------------|------------|
| **Configuration Git**          |- Installer Git<br> - Créer et ajouter une nouvelle clé SSH (local + GitHub) <br> - Ajouter Git Bash | Terminé <br> Terminé <br> Terminé |
| **Docker**                     |- Installer Docker Desktop<br> - Lire la documentation Docker<br> - Lancer un conteneur `hello-world`<br> - Créer et configurer un conteneur "host"<br> - Synchroniser un dossier entre le conteneur et le PC<br> - Créer un snapshot du conteneur pour faciliter le rebuild | Terminé<br> À faire<br> À faire<br> À faire<br> À faire<br> À faire |
| **PHP**                        |- Installer PHP<br> - Configurer un débogueur | Terminé<br> À faire |
| **Éditeur de Code VSCode**     |- Installer les extensions Docker et PHP<br> - Configurer un thème PHP<br> - Configurer le compilateur PHP<br> - Ajouter un linter | À faire<br> À faire<br> À faire<br> À faire |
| **Laravel**                    | - Installer Laravel dans le conteneur Docker<br> - Installer les dépendances (Composer, WSL, Node.js, npm)<br> - Configurer Laravel                             | À faire<br> À faire<br> À faire                                        |
| **JavaScript** *(optionnel)*   | - Ajouter JavaScript si besoin | À faire |
| **Démarrage du Développement** | Une fois toutes les étapes de configuration terminées, commencer le développement 🚀 | À faire |

