# Conservative Safety Critics (CSC) - Toy Implementation

This repository contains a toy implementation of the **Conservative Safety Critics (CSC)** algorithm, as proposed by Bharadhwaj et al. (2021). CSC is an online actor-critic reinforcement learning approach that balances **safe exploration** with task performance. The algorithm uses a **conservative safety critic** to avoid entering dangerous states with high probabilities of failure.

## Features
- **CSC Algorithm**: Implements a safety critic to guide safe exploration while learning.
- **PPO Comparison**: Includes PPO training for performance comparison.
- **Custom Networks**:
  - Safety Critic Network
  - Policy Network
  - Value Network
- **Metrics**: Tracks rewards and catastrophic failures during training.
