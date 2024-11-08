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

| **Catégorie**               | **Tâches**                                                                                                                                                       | **Statut**                                                                                                                                                                  |
|-----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Configuration Git**       | - Installer Git<br> - Créer et ajouter une nouvelle clé SSH (local + GitHub)<br> - Ajouter Git Bash                                                             | <span style="color:green">Terminé</span><br> <span style="color:green">Terminé</span><br> <span style="color:green">Terminé</span>                                         |
| **Docker**                  | - Installer Docker Desktop<br> - Lire la documentation Docker<br> - Lancer un conteneur `hello-world`<br> - Créer et configurer un conteneur "host"<br> - Synchroniser un dossier entre le conteneur et le PC<br> - Créer un snapshot du conteneur pour faciliter le rebuild  | <span style="color:green">Terminé</span><br> <span style="color:orange">À faire</span><br> <span style="color:orange">À faire</span><br> <span style="color:orange">À faire</span><br> <span style="color:orange">À faire</span><br> <span style="color:orange">À faire</span> |
| **PHP**                     | - Installer PHP<br> - Configurer un débogueur                                                                                                                    | <span style="color:orange">À faire</span><br> <span style="color:orange">À faire</span>                                                                                     |
| **Éditeur de Code VSCode**  | - Installer les extensions Docker et PHP<br> - Configurer un thème PHP<br> - Configurer le compilateur PHP<br> - Ajouter un linter                               | <span style="color:orange">À faire</span><br> <span style="color:orange">À faire</span><br> <span style="color:orange">À faire</span><br> <span style="color:orange">À faire</span> |
| **Laravel**                 | - Installer Laravel dans le conteneur Docker<br> - Installer les dépendances (Composer, WSL, Node.js, npm)<br> - Configurer Laravel                             | <span style="color:orange">À faire</span><br> <span style="color:orange">À faire</span><br> <span style="color:orange">À faire</span>                                        |
| **JavaScript** *(optionnel)*| - Ajouter JavaScript si besoin                                                                                                                                   | <span style="color:orange">À faire</span>                                                                                                                                    |
| **Démarrage du Développement** | Une fois toutes les étapes de configuration terminées, commencer le développement 🚀                                                                        | <span style="color:orange">À faire</span>                                                                                                                                    |

<!--
À faire : <span style="color:orange">À faire</span>
En cours : <span style="color:blue">En cours</span>
Terminé : <span style="color:green">Terminé</span>
-->
