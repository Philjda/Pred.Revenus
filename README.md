# 🌍 Projet 7 – Analyse mondiale de la répartition des revenus et de la pauvreté

Ce projet vise à analyser la répartition mondiale des revenus à partir de données publiques, afin de modéliser les inégalités économiques et d’estimer le niveau de pauvreté par pays.

---

## 🎯 Objectifs

- Nettoyer et structurer des données sur les revenus distribués par déciles
- Intégrer le PIB par habitant en parité de pouvoir d'achat (PPP)
- Modéliser les inégalités avec des lois statistiques (lognormale, gamma, etc.)
- Estimer les seuils de pauvreté absolue (1.90$/jour) et relative
- Comparer les pays entre eux à partir de clusters

---

## 📁 Données utilisées

- `world_income_distribution_04-11.csv` : répartition des revenus par pays (2004–2011)
- `pays_ref.csv` : correspondance des codes ISO des pays
- PIB par habitant PPP : intégré manuellement si absent
- Sources : Banque mondiale, Our World In Data, IndexMundi

---

## 🧪 Méthodologie

- Imputation de valeurs manquantes (Kosovo, Palestine, etc.)
- Transformation des distributions en données continues
- Estimation de courbes de densité de revenus par pays
- Calcul de l’indice de pauvreté absolue (<1.90$/jour) et seuils relatifs
- Réduction de dimension et clustering de pays
- Visualisation comparative des groupes de pays

---

## 📊 Technologies utilisées

- Python 3
- pandas, numpy
- matplotlib, seaborn
- scipy, statsmodels
- scikit-learn (KMeans)
- pingouin (analyses statistiques)

---

## ✅ Résultats attendus

- Courbes de distribution des revenus pour chaque pays
- Estimation des seuils de pauvreté par pays
- Classification des pays en groupes économiques
- Mise en évidence des inégalités structurelles par région

---

## ▶️ Lancer le projet

1. Ouvrir le notebook `PROJET7OCDATA.ipynb` dans Jupyter
2. S’assurer que les fichiers `.csv` sont présents dans le même dossier
3. Lancer les cellules une par une (temps de calcul raisonnable)
4. Explorer les visualisations et résultats

---


## 📄 Contexte

Projet réalisé dans le cadre d'une formation en data science.  
Données socio-économiques publiques, manipulation avancée de statistiques, modélisation de distributions de revenus.


