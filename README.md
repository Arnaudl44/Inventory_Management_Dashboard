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

## 🌐 Accès au projet

- [Visualiser le tableau de bord en ligne (Power BI Service)](https://app.powerbi.com/view?r=eyJrIjoiZTkzMTI2YTAtZTUxZS00Y2M4LWIyNzYtNDgyNWQ2NjlmNDk0IiwidCI6IjI1Y2UwMjYxLWJiZDYtNDljZC1hMWUyLTU0MjYwODg2ZDE1OSJ9)
- [Télécharger le fichier Power BI (.pbix) via Google Drive](https://drive.google.com/file/d/1vaRWcdGoD5P08_xOhTaNhTT5WIpzOTic/view?usp=sharing)

---

## 🛠️ Approche technique et fonctionnalités

- **Formules DAX personnalisées** pour calculer :
  - Les écarts entre le stock actuel et le point de commande.
  - Les délais moyens de réapprovisionnement par fournisseur.
  - Le taux de rotation des stocks.

- **Utilisation des paramètres de champs** pour créer des visualisations dynamiques :
  - Sélection interactive entre différentes mesures (stock actuel, stock minimum, stock maximum).

- **Mise en évidence des écarts critiques** :
  - Mises en forme conditionnelles pour alerter sur les produits en sous-stock ou en risque de rupture.

- **Navigation fluide et intuitive** :
  - Tableau de bord organisé par **onglets** clairs et ergonomiques.

- **Design professionnel** :
  - Palette de couleurs cohérente, priorisation visuelle des insights critiques, respect des bonnes pratiques UX.

---

## 📥 Fichiers inclus
- **Tableau de bord Power BI** : `Inventory_Management_Dashboard.pbix`
- **README.md** : Ce fichier de présentation.
- **Dossier images/** : Contient les captures d’écran du tableau de bord.
- **Dossier data/** : Contient un fichier `.gitkeep` (aucune donnée réelle partagée pour des raisons de confidentialité).

---

## 🧠 Insights et recommandations
- Prioriser le réassort des produits proches du point de commande pour éviter les ruptures.
- Anticiper les commandes fournisseurs ayant un délai long.
- Optimiser la répartition des stocks entre entrepôts pour lisser les écarts de disponibilité.

---

## 🚀 Publication
Projet réalisé dans le cadre du **FP20 Analytics Challenge 25**.
