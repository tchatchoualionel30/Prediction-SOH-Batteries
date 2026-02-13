# 🔋 Prédiction du Vieillissement (SOH) des Batteries Li-ion par Deep Learning

Ce dépôt contient le code source d'un projet de Machine Learning visant à estimer la capacité résiduelle (State of Health - SOH) de batteries Lithium-ion. Le modèle repose sur l'analyse de séries temporelles issues du jeu de données public de la **NASA Prognostics Center of Excellence**.

## 📌 Objectifs et Approche
La dégradation d'une batterie est un processus non linéaire complexe. Ce projet utilise un **Réseau de Neurones Récurrents (LSTM)** pour capturer la dynamique temporelle du vieillissement à travers les cycles de charge/décharge. Le dataset (`metadata.csv`) est inclus pour une exécution immédiate.

## 🚀 Performances
Après une phase d'optimisation (Fine-Tuning de l'architecture, Batch Size et Learning Rate) :
* **Cible :** Erreur Quadratique Moyenne (MSE) de 0.012.
* **Score Final Obtenu :** MSE de **0.0034** 🏆

## 🛠️ Technologies Utilisées
* **Langage :** Python 3
* **Machine/Deep Learning :** TensorFlow / Keras, Scikit-Learn
* **Manipulation & Visualisation :** Pandas, NumPy, Matplotlib, Seaborn
