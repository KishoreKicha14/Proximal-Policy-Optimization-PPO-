# Proximal-Policy-Optimization[PPO]
Proximal Policy Optimization is RL algo which uses policy gradient method(means agent learns by optimizing the policy). It constraints on the size of the Policy Update at each iteration.

# Policy Gradient Method

Aim: to find a policy that maximize the excepted reward over time.

works to optimize directly the policy function using gradient ascent.

#Advantages of surrogate function

- easy to optimize
- ensures that the new policy is not far from the old policy which prevent from large and unpredicted changes or the agent might not find a optimal policy.


