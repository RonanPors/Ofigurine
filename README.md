# 🛒 oFig 🚚

Ce projet a été réalisé dans le cadre d'un challenge de développement où l'objectif était de créer une page avec un formulaire de livraison pour un site e-commerce nommé **oFig**. Le défi consistait à concevoir une interface utilisateur claire et fonctionnelle, en respectant des consignes précises. J'ai développé l'intégralité du projet à partir de zéro, ce qui m'a permis d'explorer et de m'amuser avec différentes techniques, notamment la création d'un **spinner** en utilisant les animations CSS avec les `keyframes`.

## 🎯 Objectif du Challenge

L'objectif principal était de concevoir une page avec un formulaire de livraison complet. Ce formulaire devait inclure :

- ✏️ Des **champs de texte** pour saisir les informations personnelles (nom, adresse, etc.).
- 📦 Des **boutons radio** pour sélectionner les options de livraison.
- ✅ Des **cases à cocher** pour des options supplémentaires.

J'ai également ajouté une section bonus pour présenter le contenu du panier sous forme de tableau, avec une personnalisation CSS pour griser une ligne sur deux.

## 💻 Réalisation du Projet

### 1. 📋 Formulaire de Livraison

J'ai utilisé **HTML** et **CSS** pour structurer et styliser le formulaire de manière sémantique, en veillant à respecter les bonnes pratiques pour l'accessibilité et la compatibilité entre les navigateurs.

### 2. 🛍️ Tableau pour le Panier

Pour la section **"Votre panier"**, j'ai implémenté un tableau **HTML** en ajoutant des styles **CSS** qui grisent une ligne sur deux en utilisant la propriété `nth-child()`. Cela améliore la lisibilité du tableau pour l'utilisateur.

### 3. 🎡 Animation avec Spinner

Pour explorer davantage les **animations CSS**, j'ai ajouté un **spinner** personnalisé. J'ai utilisé les `@keyframes` pour créer une animation fluide qui tourne en boucle, offrant ainsi un indicateur visuel lors des chargements potentiels.

## 🚀 Comment utiliser ce projet ?

### Étapes d'installation

1. **Cloner le dépôt avec le lien SSH**

2. **Accédez au répertoire du projet** :

   ```bash
   cd ofig-panier
   ```

3. Lancer le script de prévisualisation :

   ```
   npm run preview
   ```

4. Ouvrir le navigateur et se rendre sur `http://localhost:4173`.

Vous pourrez alors visualiser la page avec le formulaire de livraison, explorer la section "Votre panier", et admirer l'animation du spinner.
