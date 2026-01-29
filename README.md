# 📊 Analyse d’un Portefeuille d’Assurance – Snowflake & Power BI

Ce projet présente la construction complète d’une solution analytique pour un portefeuille d’assurance.  
L’objectif est de montrer comment des données brutes (CSV) peuvent être transformées, modélisées et visualisées grâce à **Snowflake** et **Power BI**, afin d’aider les équipes métier à prendre de meilleures décisions.

---

## 🧭 Objectif du projet

Les entreprises d’assurance manipulent de nombreuses données : contrats, bénéficiaires, typologies, dates, statuts…  
Ce projet simule un cas réel où l’on souhaite :

- Centraliser les données dans un entrepôt moderne (**Snowflake**)  
- Nettoyer et structurer les données  
- Construire un modèle analytique  
- Créer un dashboard interactif dans **Power BI**  
- Fournir des KPIs utiles aux équipes métier  

Ce projet est conçu pour être **simple à comprendre**, **facile à reproduire**, et **professionnel** pour un portfolio.

---

## 📁 Structure du projet

data/
snowflake/
powerbi/
README.md


### **data/**
Contient les fichiers CSV bruts :
- contrats  
- bénéficiaires  
- typologies  
Ces données servent de base au chargement dans Snowflake.

### **snowflake/**
Contient les scripts SQL :
- création des tables  
- chargement des données  
- transformations (jointures, nettoyage, normalisation)  
- préparation du modèle pour Power BI  

### **powerbi/**
Contient :
- le fichier `.pbix`  
- les visuels du dashboard  
- les mesures DAX utilisées  

### **README.md**
Documentation complète du projet (ce fichier).

---

## ❄️ Snowflake – Modélisation & Pipeline

Snowflake est utilisé comme entrepôt de données.  
Le pipeline comprend :

### **1. Création du schéma**
Définition des tables : contrats, bénéficiaires, typologies.

### **2. Chargement des données**
Import des CSV depuis le dossier *data*.

### **3. Nettoyage et transformation**
- suppression des doublons  
- normalisation des champs  
- jointures entre tables  
- création de colonnes dérivées (ex : statut, durée, catégories)

### **4. Modèle final**
Un modèle propre, clair, optimisé pour Power BI.

---

## 📊 Power BI – Dashboard Assurance

Le dashboard permet d’explorer le portefeuille d’assurance grâce à :

### **KPIs principaux**
- Nombre total de contrats  
- Nombre de bénéficiaires  
- Répartition par type de contrat  
- Répartition par statut  
- Évolution temporelle  

### **Visualisations**
- Graphiques en barres  
- Diagrammes circulaires  
- Courbes temporelles  
- Tableaux interactifs  

### **Objectif métier**
Aider les équipes assurance à :
- comprendre la composition du portefeuille  
- identifier les segments importants  
- suivre l’évolution des contrats  
- détecter des tendances  

---

## 🏗️ Architecture du pipeline
CSV (data/)
↓
Snowflake (chargement + transformations SQL)
↓
Modèle analytique propre
↓
Power BI (visualisation + KPIs)

Cette architecture reproduit un workflow réel utilisé dans les entreprises d’assurance.

---

## 🎯 Compétences démontrées

- Manipulation et modélisation de données dans **Snowflake**  
- SQL avancé (CTE, jointures, transformations)  
- Construction d’un pipeline analytique complet  
- Création d’un dashboard professionnel dans **Power BI**  
- Structuration d’un projet pour un portfolio  
- Documentation claire et orientée métier  

---

## 👤 Auteur

Projet réalisé par ** SERGE BOGO**  
Aspirant Data Analyst spécialisé assurance & banque.  
Passionné par la data, la BI et les solutions cloud modernes.



