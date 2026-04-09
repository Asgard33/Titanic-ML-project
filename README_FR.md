# Prédire la survie sur le Titanic

## 📌 Présentation du projet

Ce projet a pour objectif d’analyser et de prédire la survie des passagers du Titanic à l’aide de méthodes statistiques et de modèles de machine learning.

L’objectif n’est pas uniquement de construire des modèles prédictifs, mais aussi de comprendre les facteurs sous-jacents ayant influencé la survie, tels que la classe sociale, le genre ou encore l’âge.

---

## 📊 Données

Le jeu de données utilisé est le célèbre dataset du Titanic, contenant des informations sur les passagers telles que :

* L’âge
* Le sexe
* La classe du passager (Pclass)
* Le prix du billet (Fare)
* Les relations familiales (SibSp, Parch)

---

## 🔍 Méthodologie

Le projet est structuré en plusieurs étapes :

### 1. Analyse exploratoire des données (EDA)

* Manipulations élémentaires des données
* Premières observations sur la distribution de la survie

---

### 2. Feature Engineering

* Création de variables groupées (tranches d’âge, tranches de prix)
* Exploration des interactions pertinentes entre variables
* Transformation des variables catégorielles

---

### 3. Modèles de Machine Learning

Plusieurs modèles ont été implémentés et comparés :

* Régression Logistique
* K plus proches voisins (KNN)
* Random Forest
* Arbre de décision (pour l’interprétabilité)

---

### 4. Évaluation des modèles

* Séparation Train/Test et validation croisée
* Comparaison des performances (accuracy)
* Analyse du compromis biais-variance
* Étude des seuils de décision et de leur impact sur les prédictions

---

### 5. Analyse statistique

* Analyse de corrélation de Pearson pour les variables numériques
* Tests du Chi² pour évaluer l’indépendance entre variables et survie
* Utilisation des p-values pour mesurer la significativité statistique
* Coefficient de Cramér pour mesurer la force d’association entre variables catégorielles

---

## 📈 Résultats principaux

* **Sex et Pclass** sont les variables les plus influentes pour la survie
* **Fare** est fortement lié à la survie, reflétant le statut socio-économique
* **Age** joue un rôle plus complexe et non linéaire, mieux capté par les modèles basés sur des arbres
* Le seuil de classification par défaut (0.5) n’est pas optimal — des seuils plus bas permettent un meilleur équilibre entre survivants et non-survivants
* Les méthodes statistiques sont utiles mais limitées, car elles ne capturent pas les interactions complexes entre variables

---

## 🧠 Enseignements clés

Ce projet met en évidence l’importance de combiner :

* Analyse statistique → pour comprendre les relations entre variables
* Machine learning → pour capturer des structures plus complexes

Il souligne également les limites de certaines métriques simples, comme la corrélation, dans des contextes réels.

---

## ⚙️ Technologies utilisées

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

## 👤 Auteur

Ce projet a été réalisé avec un fort accent sur la compréhension du comportement des modèles et des relations entre les données.

---

