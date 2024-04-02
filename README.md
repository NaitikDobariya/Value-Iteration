# Value-Iteration

This repository presents an implementation of Value Iteration from scratch.

### About the Project

The script focuses on solving a deterministic grid world environment where an agent learns to navigate while considering obstacles and the cost associated with each step. By implementing the value iteration algorithm, the project aims to generate optimal value functions that guide the agent to reach the goal while minimizing the number of steps and maximizing rewards.

The algorithm iteratively updates value functions until convergence, ensuring that the agent learns to efficiently reach the goal while considering the environmental constraints.

### Pseudocode Reference

The pseudocode utilized in this implementation was extracted from the book authored by Barto and Sutton. Please refer to the provided picture for a visual representation of the pseudocode.

![image](https://github.com/NaitikDobariya/Value-Iteration/assets/113834773/6d1fda6f-77f2-409d-a650-0bda12f881a2)


### Results

The algorithm successfully learns to navigate the environment, reaching the goal in the minimum number of steps. Below are the visual results of the algorithm's performance:

- Goal Reach in Minimum Steps: ![value iteration 2](https://github.com/NaitikDobariya/Value-Iteration/assets/113834773/3e4eef3f-756b-4fc1-9429-578e6dae4063)

- Maze Traversal: ![value iteration](https://github.com/NaitikDobariya/Value-Iteration/assets/113834773/a6a7d6c7-6afa-4bc1-b5ca-78a491a09ff2)


The letters represent; O: Obstacle, G: Goal, U: Up, D: Down, L: Left, R: Right

Thank you for your interest, feel free to suggest any changes.
