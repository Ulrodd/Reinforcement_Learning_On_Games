# Reinforcement Learning – Q-Learning & Baselines (OpenAI Gym)

Ce dépôt propose deux notebooks démontrant des usages concrets du Reinforcement Learning avec OpenAI Gym :  
- Implémentation manuelle du Q-learning
- Utilisation de frameworks standards du domaine (Stable-Baselines3)

---

## Contenu

- **Renforcement Learning Example 1.ipynb**  
  Implémentation from scratch du Q-learning sur FrozenLake (environnement Gym discret).  
  Points montrés :
  - Exploration/exploitation, structure de la table Q
  - Fonction de simulation pour l’analyse empirique des politiques
  - Visualisation et debug du processus d’apprentissage

- **Renforcement Learning Example 2.ipynb**  
  Introduction à l’utilisation de `stable-baselines3` sur d’autres environnements Gym.
  Points montrés :
  - Setup rapide et reproductible d’agents RL prêts à l’emploi
  - Baselines pour comparaison/benchmark de modèles RL
  - Modularité pour tests sur différents environnements, adaptation facile

---

## Stack technique

- Python ≥ 3.8
- `gym[Box2D]==0.25.1` (environnements RL OpenAI)
- `stable-baselines3[extra]` (librairie standard d’agents RL)
- numpy, matplotlib, pyglet, pygame, tqdm, ipywidgets

```bash
pip install gym[Box2D]==0.25.1 stable-baselines3[extra] numpy matplotlib pyglet==1.5.27 pygame tqdm ipywidgets
