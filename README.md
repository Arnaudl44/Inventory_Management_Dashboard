# 📦 Inventory Management Dashboard

## 📄 Contexte du projet
> Projet réalisé dans le cadre du **FP20 Analytics Challenge 25**.

Une gestion efficace des stocks est essentielle pour équilibrer l’offre et la demande tout en optimisant les coûts.  
Ce tableau de bord explore les niveaux de stock, la performance des fournisseurs, l’utilisation des entrepôts et les stratégies de réapprovisionnement.  
L'objectif est d’identifier des tendances clés et de proposer des leviers pour améliorer l'efficacité opérationnelle de la chaîne d'approvisionnement.

---

## 🎯 Objectifs principaux
- Identifier les produits à risque de rupture de stock.
- Évaluer la performance des fournisseurs (délais de réapprovisionnement).
- Optimiser les coûts de stockage et les stratégies de réassort.
- Visualiser la répartition géographique des stocks par entrepôt.

---

## 🛠️ Outils et technologies utilisés
- **Power BI** pour la création du tableau de bord interactif.
- **Excel** pour la préparation initiale du jeu de données.

---

## 📊 Aperçu des analyses réalisées

### 📦 Analyse des niveaux de stock
![Analyse des niveaux de stock](https://github.com/Arnaudl44/Inventory_Management_Dashboard/blob/main/images/Capture%20d%E2%80%99%C3%A9cran%202025-04-26_Stock_Analysis.jpg)

---

### 🔄 Cycle de vie des stocks
![Cycle de vie des stocks](https://github.com/Arnaudl44/Inventory_Management_Dashboard/blob/main/images/Capture%20d%E2%80%99%C3%A9cran%202025-04-26_Stock_Lifecycle.jpg)

---

### 🏢 Répartition des stocks par entrepôt
![Répartition des stocks par entrepôt](https://github.com/Arnaudl44/Inventory_Management_Dashboard/blob/main/images/Capture%20d%E2%80%99%C3%A9cran%202025-04-26_Warehouse_Location.jpg)

---

## 🛠️ Approche technique et fonctionnalités

- **Formules DAX personnalisées** pour calculer :
  - Les écarts entre le stock actuel et le point de commande.
  - Les délais moyens de réapprovisionnement par fournisseur.
  - Le taux de rotation des stocks.

- **Utilisation des paramètres de champs** pour créer des visualisations dynamiques :
  - Sélection interactive entre différentes mesures (ex : stock actuel, stock minimum, stock maximum).

- **Mise en évidence des écarts critiques** :
  - Mises en forme conditionnelles pour alerter visuellement sur les produits en sous-stock ou en risque de rupture.

- **Navigation fluide entre les analyses** :
  - Tableau de bord organisé par **onglets** clairs et ergonomiques.
  - Possibilité de revenir facilement à la vue d'ensemble depuis chaque page.

- **Design épuré et professionnel** :
  - Utilisation de palettes de couleurs cohérentes pour faciliter la lecture.
  - Respect des principes de visualisation : pas de surcharge, hiérarchie visuelle claire.

---

## 📥 Fichiers inclus
- **Tableau de bord Power BI** : `Inventory_Management_Dashboard.pbix`
- **README.md** : Ce fichier de présentation.
- **Dossier images/** : Contient les captures d’écran du tableau de bord.
- **Dossier data/** : Contient un fichier `.gitkeep` (aucune donnée réelle partagée pour des raisons de confidentialité).

---

## 🧠 Insights et recommandations
- Les produits proches du point de rupture doivent être priorisés pour le réassort.
- Certains fournisseurs présentent des délais de livraison longs, nécessitant une anticipation dans les commandes.
- La répartition géographique révèle des déséquilibres d’inventaire entre entrepôts, ce qui ouvre des pistes d'optimisation logistique.

---

## 🚀 Publication
Projet réalisé dans le cadre du **FP20 Analytics Challenge 25**.
