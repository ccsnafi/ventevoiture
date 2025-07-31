# 📊 Tableau de Bord - Ventes de Voitures

Ce rapport Power BI permet à une direction ou un comité exécutif de suivre et d’analyser les performances commerciales du secteur automobile (véhicules vendus, modèles, régions, concessionnaires, etc.).

---

## 📝 Objectifs / Besoins

- Suivre l'évolution des **ventes totales** et du **prix moyen**.
- Comparer les performances **par région**, **marque** et **modèle**.
- Identifier les **meilleurs concessionnaires**.
- Analyser les **tendances mensuelles** (MoM).
- Offrir une **vue synthétique globale**.
- Faciliter l’ajout de la **sécurité RLS (Row Level Security)** selon la structure de l’entreprise.

---

## 📁 Contenu

- `ventes voitures.pbix` : Fichier Power BI du rapport.
- `Car Sales.xlsx` : Source de données.
- Images : Un screenshot par page du rapport pour illustration.

---

## 📌 Page 1 – Reporting Global

Vue d’ensemble avec chiffres clés, répartition par type de véhicule, top marques, comparaison MoM/YoY et évolution journalière.

![](./ReportingGlobal.png)

---

## 📌 Page 2 – Analyse par Région

Analyse géographique des ventes avec carte, performances régionales et tableau détaillé des concessionnaires.

![](./Analyseregion.png)

---

## 📌 Page 3 – Analyse Marques/Modèles

Analyse des modèles, unités vendues, prix moyen par modèle. Visuels : bulles, histogrammes et tableau dynamique.

![](./Analysmodeles.png)

---

## 📌 Page 4 – Performance par Concessionnaire

Suivi de la performance de chaque dealer, avec évolution des ventes dans le temps et top 10 concessionnaires.

![](./Perfommanceconce.png)

---

## 📌 Page 5 – Évolution Temporelle

Analyse mensuelle de l’évolution des ventes, du prix moyen et de la croissance MoM.

![](./evolutiontemporelle.png)

---

🎯 Destinataires du rapport
Ce tableau de bord Power BI est principalement destiné à la direction et aux décideurs de l’entreprise, notamment :

-La Direction Générale pour un suivi global des performances

-La Direction Commerciale pour l’analyse des ventes par marque, modèle, région, et concessionnaire

-Les Responsables Régionaux pour un suivi localisé

-Les Analystes pour l’identification des tendances, comparaisons Mois/Mois (MoM) et Année/Année (YoY)


🛡️ Ce rapport peut être décliné en plusieurs vues selon les profils d’utilisateurs, en appliquant une sécurité par rôle (RLS).

## 🔐 Sécurité : Row Level Security (RLS)

La structure de données permet d’ajouter des rôles RLS :
- Par **concessionnaire** (Dealer)
- Par **région**
- Par **niveau d’utilisateur** (ex. direction, commercial, analyste)

> ℹ️ À **adapter selon la structure de l’entreprise** : on peut filtrer dynamiquement les visuels en fonction de l'utilisateur connecté grâce à USERPRINCIPALNAME() ou USERNAME().

---

## 🛠 Données & fichier source

- `ventes voitures.pbix` : rapport principal Power BI
- `Car Sales.xlsx` : source de données principale
- Images : captures de chaque page pour documentation

---

## 📦 Améliorations futures (suggestions)

- Ajout d’un filtre dynamique sur les types de clients (pro vs particulier)
- Intégration du RLS par rôle hiérarchique
- Analyse prédictive (tendance sur 6 mois)

---

## 🧠 Réalisé par  Afi TENUDA-EKLOU

Dashboard Power BI réalisé pour developper son portfolio mais possibillité de l'adapté à une entreprise
