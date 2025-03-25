# 📌 Séparation Aveugle de Sources Sous-Déterminée  

## 📖 Description  
Ce projet implémente la séparation aveugle de sources dans un contexte sous-déterminé à l'aide de deux méthodes :  

🔹 **Sparse Source Recovery via Constrained Minimization**  
🔹 **CAGCMM (Complex Angular Central Gaussian Mixture Model)**  

L'objectif est d'extraire des sources indépendantes à partir de mélanges sous-déterminés sans connaissance préalable des signaux d'origine.  

---

## 🛠️ Méthodes Utilisées  

### 🟢 Sparse Source Recovery via Constrained Minimization  
📌 Cette approche repose sur l'hypothèse de parcimonie des sources. Elle utilise une minimisation sous contrainte pour estimer les signaux sources en exploitant leur structure parcimonieuse.  

### 🔵 CAGCMM (Complex Angular Central Gaussian Mixture Model)  
📌 Cette méthode repose sur un modèle de mélange gaussien complexe angulaire central pour effectuer la séparation aveugle des sources. Elle ne présuppose pas de structure particulière des fichiers audio.  

---

## 🔧 Prérequis  
Avant d'exécuter le projet, assurez-vous d'installer les dépendances nécessaires :  

```bash
pip install numpy scipy matplotlib librosa cvxpy sklearn einops soundfile
```

---

## 📚 Bibliothèques utilisées  
Le projet utilise les bibliothèques suivantes :  
```txt
- numpy, scipy : Calcul scientifique et traitement du signal
- matplotlib : Visualisation des signaux
- librosa : Analyse et traitement audio
- cvxpy : Optimisation convexe pour la minimisation sous contrainte
- sklearn : Clustering (KMeans) pour l'analyse des sources
- einops : Manipulation efficace des tenseurs
- soundfile : Lecture et écriture des fichiers audio
```

---

## 📂 Structure du projet  
```bash
📂 projet_separation_sources
│── 📂 code
│   ├── 📂 sparse_source_recovery  # Code pour la méthode Sparse Recovery
│   ├── 📂 cagcmm  # Code pour la méthode CAGCMM
│── 📂 presentation  # Contient les diapositives explicatives
│── README.md  # Fichier de documentation
```

```

📌 Vous pouvez modifier les paramètres dans les fichiers de configuration pour tester différentes configurations.  



## 📊 Résultats  
✅ Visualisation des signaux originaux, mélangés et reconstruits  
✅ Comparaison des performances des deux méthodes à l'aide de métriques adaptées  

