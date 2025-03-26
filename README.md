# Projet d'Apprentissage par Renforcement 🚀

Ce dépôt regroupe une série d'exercices et de travaux pratiques réalisés dans le cadre du module d'apprentissage par renforcement. Chaque fichier — du **devoir.ipynb** aux TP (**TP1**, **TP2**, **TP3** et **TP4**) — illustre une progression pédagogique, combinant théorie, implémentation et analyse des résultats pour aboutir à des solutions de plus en plus complexes. 🌟

## Contenu du Dépôt

### 1. devoir.ipynb 📚  
**Objectif :**  
Poser les fondations théoriques de l'apprentissage par renforcement.  
**Contenu et Réalisations :**  
- **Introduction aux concepts clés :** Processus de décision markovien (MDP), dilemme exploration/exploitation et interactions fondamentales entre agent et environnement.  
- **Première simulation :** Mise en place d'une simulation simple servant de socle pour les travaux pratiques suivants.  

---

### 2. TP1.ipynb 🎮  
**Objectif :**  
Se familiariser avec les outils essentiels du Reinforcement Learning, notamment OpenAI Gym.  
**Contenu et Réalisations :**  
- **Interagir avec l'environnement :** Configuration et prise en main d’un environnement RL via OpenAI Gym.  
- **Premières actions et retours :** Exécution d’actions dans l’environnement avec observation des réactions, posant ainsi les bases pour un apprentissage itératif.  

---

### 3. TP2.ipynb 🤖  
**Objectif :**  
Implémenter l'algorithme **Q-Learning** dans un contexte pratique.  
**Contenu et Réalisations :**  
- **Implémentation progressive du Q-Learning :** Application sur l'environnement *FrozenLake* d'OpenAI Gym pour illustrer l'apprentissage par mise à jour itérative d'une Q-table.  
- **Stratégies d'exploration et exploitation :** Analyse de l'impact des stratégies d'exploration (comme l’epsilon-greedy) sur la convergence des valeurs Q, avec des visualisations démontrant l'amélioration de la prise de décision de l’agent au fil des épisodes.  

---

### 4. TP3.ipynb 🚦  
**Objectif :**  
Optimiser la gestion des feux de circulation en explorant deux approches d'apprentissage.  
**Contenu et Réalisations :**  
- **Double approche :** Implémentation de **Q-Learning** et **SARSA** pour apprendre une politique optimale dans un environnement simulé de gestion du trafic.  
- **Comparaison détaillée :** Utilisation de graphiques 📊 et d’évaluations quantitatives pour comparer les performances des deux méthodes, mettant en lumière leurs avantages et limites respectifs.  

---

### 5. TP4.ipynb 🚕  
**Objectif :**  
Se familiariser avec l'implémentation d'algorithmes avancés, ici le **Proximal Policy Optimization (PPO)**.  
**Contenu et Réalisations :**  
- **Approche avancée avec PPO :** Conception d'une table de politiques et mise à jour des valeurs des états pour entraîner un agent à résoudre le problème de transport de passagers dans l'environnement *Taxi-v3*.  
- **Optimisation par politiques :** Passage à des techniques d'apprentissage par renforcement plus sophistiquées pour aborder des problèmes complexes.  

---

## Conclusion ✨

Ce dépôt illustre un parcours complet en apprentissage par renforcement, allant des bases théoriques jusqu'à des implémentations avancées :  
- **Début théorique et expérimental :** Le fichier *devoir.ipynb* pose les fondations de la discipline.  
- **Premiers pas pratiques :** Le TP1 permet de se familiariser avec l'environnement RL et ses outils.  
- **Approfondissement par le Q-Learning :** Le TP2 montre comment un agent peut apprendre via la mise à jour itérative de sa Q-table.  
- **Comparaison d'algorithmes :** Le TP3 compare Q-Learning et SARSA dans un contexte réel d'optimisation de trafic.  
- **Approche avancée avec PPO :** Le TP4 ouvre la voie à des techniques modernes pour résoudre des problèmes complexes.

