# Reward Modelling

In this section, I'll be demonstrating how to implement reward modelling (related to reward learning via human feedback) using Unsloth. Two different reward modelling policy methods are used within seperate google colab environments.

## ORPO (Optimistic Reward Propogation Optimization)

This method is useful in scenarios where the reward signal is sparse or delayed, helping the agent to learn more effectively by prioritizing promising states.

## DPO (Direct Policy Optimization)

This method is useful in environments where the policy can be directly influenced by the reward signals, allowing for potentially faster convergence to an optimal policy.