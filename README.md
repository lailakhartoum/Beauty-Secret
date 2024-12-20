# Beauty Secret: Site E-Commerce

## Description du projet
Beauty Secret est un site e-commerce créé avec WordPress et WooCommerce. Il est spécialisé dans la vente de produits de beauté naturels et traditionnels du Maroc, tels que l'huile d'argan, le savon noir et le henné. Ce projet reflète l'élégance des traditions marocaines alliée à une expérience utilisateur moderne.


## Fonctionnalités principales
- Gestion de catalogue produits : ajout, modification et suppression.
- Système de panier d'achat et paiement en ligne.
- Recherche avancée avec filtres par ingrédients, catégories et prix.
- Pages essentielles : Accueil, Boutique, À propos, Contact, Panier.
- Design responsif pour mobile et tablette.

## Prérequis
1. **Environnement local** : [XAMPP](https://www.apachefriends.org/index.html)
2. **WordPress** : CMS open source
3. **WooCommerce** : Plugin e-commerce
4. **Git** : Pour la gestion du dépôt

## Instructions d'installation

### 1. Mise en place de l'environnement local
1. Installer [XAMPP](https://www.apachefriends.org/index.html).
2. Démarrer les modules **Apache** et **MySQL**.
3. Accéder à `http://localhost/phpmyadmin` pour créer une base de données nommée `wordpress`.

### 2. Installation de WordPress
1. Télécharger [WordPress](https://wordpress.org/download/).
2. Extraire les fichiers dans le dossier `C:\xampp\htdocs\wordpress`.
3. Accéder à `http://localhost/wordpress` et suivre les étapes pour configurer WordPress.
4. Utiliser les informations suivantes pour la connexion à la base de données :
   - **Nom de la base** : `wordpress`
   - **Utilisateur** : `root`
   - **Mot de passe** : (vide par défaut)

### 3. Importation de la base de données
1. Accéder à `http://localhost/phpmyadmin`.
2. Sélectionner la base `wordpress`.
3. Importer le fichier `wordpress.sql` disponible dans le dépôt.

### 4. Configuration du projet
1. Cloner ce dépôt :
   ```bash
   git clone https://github.com/lailakhartoum/Beauty-Secret.git
   ```
2. Copier les fichiers dans le dossier `C:\xampp\htdocs\wordpress`.
3. Accéder à `http://localhost/wordpress` pour voir le site en action.

### 5. Identifiants administrateur
- **URL d'administration** : `http://localhost/wordpress/wp-admin`
- **Nom d'utilisateur** : `laila`
- **Mot de passe** : `laila2003000`

## Instructions pour collaborer
1. Forker le dépôt sur GitHub.
2. Créer une nouvelle branche pour vos modifications :
   ```bash
   git checkout -b nouvelle-fonctionnalite
   ```
3. Apporter vos modifications et les committer :
   ```bash
   git commit -m "Ajout d'une nouvelle fonctionnalité"
   ```
4. Pousser vos changements :
   ```bash
   git push origin nouvelle-fonctionnalite
   ```
5. Créer une Pull Request pour intégrer vos modifications.

---
**Beauty Secret**

