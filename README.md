# Régression Linéaire "From Scratch" sur le Dataset Advertising

Ce projet implémente une **régression linéaire simple avec descente de gradient** pour analyser l'impact des dépenses publicitaires sur les ventes d'un produit. Il a été développé en Python en utilisant `numpy`, `pandas`, `matplotlib` et `seaborn`.

## 📌 Objectif du projet
L'objectif est de **prédire les ventes** (`Sales`) en fonction des dépenses publicitaires dans :
- 📺 Télévision (`TV`)
- 📻 Radio (`Radio`)
- 📰 Journaux (`Newspaper`)

Nous allons créer trois modèles de régression linéaire "from scratch" pour chaque variable explicative et comparer leurs performances.

---

## 📂 Contenu du projet

- `advertising_regression.ipynb` : Notebook contenant l'implémentation du modèle.
- `Advertising.csv` : Dataset utilisé pour l'entraînement et l'évaluation.
- `README.md` : Ce fichier explicatif.

---

## 🚀 Installation & Utilisation
### 1️⃣ Prérequis
Assurez-vous d'avoir **Python 3.x** et les bibliothèques suivantes installées :
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### 2️⃣ Exécuter le projet
1. Clonez le dépôt GitHub :
```bash
git clone https://github.com/Labrini-Ouiam/R-gression-Lin-aire-From-Scratch-sur-le-Dataset-Advertising.git
cd R-gression-Lin-aire-From-Scratch-sur-le-Dataset-Advertising
```
2. Ouvrez le notebook et exécutez les cellules :
```bash
jupyter notebook advertising_regression.ipynb
```

---

## 🛠️ Explication de l'implémentation
### 🔹 Étapes principales
1. **Chargement et exploration des données** 🔍
2. **Visualisation des corrélations** 📊
3. **Normalisation des données** 📉
4. **Implémentation de la régression linéaire "from scratch"** 🏋️
5. **Séparation en train/test et entraînement du modèle** 📚
6. **Évaluation et comparaison des modèles** ⚖️

### 🔹 Résultats attendus
- Calcul des paramètres `θ` pour chaque variable (`TV`, `Radio`, `Newspaper`)
- Graphiques illustrant la régression
- Évaluation des performances avec l'erreur quadratique moyenne (MSE)

---

## 🏆 Contributions
Les contributions sont les bienvenues ! Pour proposer des améliorations :
1. Forkez le projet 🍴
2. Créez une branche `feature-votre-nom` 🔀
3. Faites vos modifications et ouvrez une pull request 📥

---

## 📜 Licence
Ce projet est sous licence **MIT**.

