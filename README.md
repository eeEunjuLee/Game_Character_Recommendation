> **Project Period: May 27 - June 19, 2025**
>
> This work is a domain-driven **Toy Project** aimed at exploring Graph Neural Networks (GNNs) via a **RPG/MMORPG Character Recommendation Problem.**
---
# Title: Game Character Recommendation using Graph Neural Networks (GNNs)
> **A Domain-Driven Toy Modeling Project with Link Prediction**


---
## Overview

This project explores a character recommendation problem in the online RPG *MapleStory*, 
with a focus on supporting long-term player engagement in a multi-character growth environment.
In *MapleStory*, players are encouraged to develop multiple characters over time. 
However, as the game world has continuously expanded since its release in 2003, 
the number of available classes, factions, and storylines has grown substantially. 
As a result, both new and returning players often struggle to decide which class to play next.

In such an environment, recommending the next character is a structurally delicate problem.
Recommending a class that is too similar to a previously played one may feel repetitive,
while recommending a completely unrelated class may break narrative and gameplay continuity.
We therefore frame recommendation failure as the inability to balance **familiarity and novelty**.

Based on this observation, the project reformulates character recommendation as the following question:

* How can we structurally model the balance between familiarity and novelty ?
* How can we design a recommendation system that reflects this balance using domain knowledge alone,
  without relying on user behavior logs or interaction data?

To address this, we model inter-class relationships using a graph constructed from 
game-specific domain knowledge (e.g., role similarity, narrative background, stat compatibility).
A Graph Neural Network (GNN) is then used to learn class embeddings and perform link prediction,
interpreting character recommendation as a problem of predicting plausible transitions 
between character classes.

This project is designed as a **domain-driven Toy Modeling study**, 
emphasizing problem re-formulation, structural modeling, and interpretability 
over large-scale performance optimization.
