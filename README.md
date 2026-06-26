# SNHU Computer Science Portfolio
**Rimon Hamo**  
Bachelor of Science in Computer Science – Southern New Hampshire University

This repository contains selected coursework, projects, and reflections from my Computer Science degree at SNHU. It showcases my growth in programming, artificial intelligence, and problem-solving.

---

## Project Two: Pirate Intelligent Agent (Deep Q-Learning)

### Project Overview
In this project, I built an intelligent agent that learns to navigate a grid-based maze to find treasure using **Deep Q-Learning**. The agent (a pirate) must reach the treasure while avoiding obstacles and penalties.

I was given:
- The `TreasureMaze.py` environment (the maze and game logic)
- The `GameExperience.py` class (for storing past experiences)
- A starter Jupyter Notebook with a skeleton `qtrain()` function

I created:
- The full Deep Q-Network implementation using **Keras/TensorFlow**
- The neural network architecture for Q-value approximation
- Experience replay buffer and mini-batch training
- Epsilon-greedy exploration strategy with decay
- Target network for training stability
- Complete training loop and evaluation/visualization code

The agent achieved a **100% win rate by epoch 187**, demonstrating effective learning of optimal navigation policies.

### What I Learned

This project gave me hands-on experience with core reinforcement learning concepts, including the exploration-exploitation tradeoff, the Bellman equation, experience replay, and neural network function approximation. I gained a much deeper understanding of how intelligent agents learn through trial and error rather than being explicitly programmed.

### Connection to Computer Science

**What do computer scientists do and why does it matter?**  
Computer scientists design algorithms and systems that solve complex problems at scale. This matters because these systems power everything from autonomous robots and logistics optimization to recommendation engines and scientific discovery.

**How do I approach a problem as a computer scientist?**  
I break problems down into states, actions, and rewards (especially useful in reinforcement learning). I focus on defining clear objectives, designing appropriate models, managing training stability, and rigorously evaluating performance through iteration and experimentation.

**What are my ethical responsibilities to the end user and the organization?**  
I have a responsibility to build systems that are transparent, fair, and safe. In reinforcement learning, poorly designed reward functions can lead to unintended behaviors. I must consider the broader impact of autonomous systems, prioritize robustness and explainability where possible, and ensure technology augments human decision-making rather than creating hidden risks.

---

## Files in This Repository

- `Rimon_Hamo_Project_Two.ipynb` — Full Jupyter Notebook for the Pirate Intelligent Agent project
- `README.md` — This file (project reflections)

---

**Note:** This repository is part of my academic portfolio for SNHU’s Computer Science program.

---

*Last updated: June 2026*
