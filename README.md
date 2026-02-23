# CS-370
Module 8
In this project, I developed a Pirate Intelligent Agent using deep Q-learning to solve a pathfinding problem in an 8x8 maze environment. The goal of the agent was to navigate from any valid starting position to the treasure while maximizing cumulative reward.

The starter code provided the maze environment, the experience replay class, the neural network architecture, and supporting methods such as reset, observe, act, and completion checks. My responsibility was to implement the deep Q-learning training algorithm. This included designing the training loop, handling exploration vs. exploitation using an epsilon-greedy strategy, storing and sampling experiences, training the neural network with batch updates, updating the target network, and determining the optimal number of epochs required to achieve a consistent 100% win rate.

I applied reinforcement learning principles including reward shaping, experience replay, neural network-based Q-value approximation, and performance evaluation.

Connection to Computer Science

This project reinforced my understanding of what computer scientists do: we design systems that solve complex problems through structured logic, algorithms, and iterative refinement. In this case, I created an intelligent system that learned from interaction rather than relying on hard-coded instructions. This reflects a broader trend in computer science where systems are built to adapt and improve based on data.

As a computer scientist, I approach problems by:
	•	Breaking them into smaller components
	•	Understanding constraints and requirements
	•	Designing an algorithmic solution
	•	Testing and refining through iteration

In this project, I applied these steps by analyzing the environment, understanding the reward structure, implementing the Q-learning loop, debugging instability, and validating performance using completion checks.

Ethical Responsibilities

This project also highlights ethical responsibilities in AI development. Reinforcement learning systems make decisions based on reward structures and data. If poorly designed, they can behave unpredictably or optimize for unintended outcomes.

As a computer scientist, I have a responsibility to:
	•	Ensure models are tested and validated properly
	•	Design reward systems carefully
	•	Consider how AI decisions affect users
	•	Prioritize reliability and transparency

Even though this project focused on a game environment, the same principles apply to real-world AI systems used in healthcare, finance, and automation. Responsible AI development requires ethical awareness.
