# 📊 Power BI – Tableau de Bord Décisionnel pour un Établissement Scolaire

## 📌 Contexte

Ce projet a été réalisé dans le cadre d'un exercice de Business Intelligence visant à concevoir un tableau de bord Power BI permettant à la direction d'un établissement scolaire d'analyser les performances académiques, l'absentéisme, la charge de travail des enseignants et l'efficacité des cours afin de faciliter la prise de décision.

---

## 🎯 Objectifs

* Analyser les performances des élèves.
* Suivre les taux de réussite et d'échec.
* Évaluer la charge de travail des enseignants.
* Mesurer le taux de réalisation des cours.
* Identifier les élèves à risque.
* Fournir des recommandations décisionnelles.

---

## 📂 Jeux de données

Le projet repose sur trois fichiers CSV :

### 👨‍🎓 students.csv

Informations sur les élèves :

* Identifiant
* Nom
* Date de naissance
* Genre
* Date d'inscription
* Niveau scolaire
* Section
* Statut
* Moyenne générale
* Nombre d'absences
* Professeur principal

### 👩‍🏫 teachers.csv

Informations sur les enseignants :

* Identifiant
* Nom
* Date d'embauche
* Matière
* Département
* Niveau enseigné
* Type de contrat
* Heures hebdomadaires
* Ville
* Note d'évaluation

### 📚 courses.csv

Informations sur les cours :

* Identifiant du cours
* Cours
* Enseignant
* Élève
* Semestre
* Année scolaire
* Heures prévues
* Heures réalisées
* Note
* Résultat (Réussi / Échoué)

---

## 🛠 Technologies utilisées

* Power BI Desktop
* Power Query
* DAX
* Modélisation relationnelle

---

## 🔄 Étapes du projet

### 1. Exploration des données

* Analyse de la qualité des données
* Détection des valeurs manquantes
* Recherche des doublons
* Vérification des types de données
* Identification des valeurs aberrantes

### 2. Nettoyage des données

* Traitement des valeurs manquantes
* Standardisation des formats
* Correction des incohérences
* Création de colonnes calculées :

  * Âge des élèves
  * Ancienneté des enseignants
  * Taux de réalisation des cours
  * Année d'inscription

### 3. Modélisation

Relations créées entre les trois tables :

* Students → Teachers
* Courses → Students
* Courses → Teachers

Création d'une table calendrier (DimDate) pour les analyses temporelles.

### 4. Mesures DAX

Principales mesures développées :

* Total Élèves
* Moyenne Générale
* Taux de Réussite
* Élèves à Risque
* Heures Moyennes par Enseignant
* Top Matières
* Évolution des Inscriptions

---

## 📈 Tableau de bord

### 📄 Page 1 — Vue Élèves

**KPIs**

* Total élèves
* Moyenne générale
* Taux de réussite
* Élèves à risque

**Visualisations**

* Répartition par niveau scolaire
* Évolution des inscriptions
* Corrélation Absences / Moyenne
* Répartition des statuts

---

### 📄 Page 2 — Vue Enseignants

**KPIs**

* Total enseignants
* Ancienneté moyenne
* Heures hebdomadaires moyennes
* Note moyenne d'évaluation

**Visualisations**

* Répartition par matière
* Répartition par contrat
* Distribution des évaluations
* Top 5 / Flop 5 enseignants

---

### 📄 Page 3 — Vue Cours & Résultats

**KPIs**

* Total cours
* Taux de réalisation
* Taux de réussite par semestre

**Visualisations**

* Réussite / Échec par matière
* Évolution des notes
* Matières avec moyenne ≥ 12

---

## 🎛 Fonctionnalités

* Slicers interactifs
* Navigation multi-pages
* Bouton de réinitialisation des filtres
* Interactions entre visuels
* Analyses temporelles

---

## 💡 Principaux insights

* Identification des matières ayant le plus fort taux d'échec.
* Détection des enseignants sous-chargés ou surchargés.
* Identification des élèves à risque selon leurs absences et leurs résultats.
* Recommandations pour améliorer la réussite scolaire et optimiser la répartition des ressources pédagogiques.

---

## 📷 Aperçu

Ajouter ici quelques captures d'écran du tableau de bord :

```
/images/page1.png
/images/page2.png
/images/page3.png
```

---

## 👤 Auteur

**Khadija**
Data Analyst | Power BI | SQL | Python | Excel
