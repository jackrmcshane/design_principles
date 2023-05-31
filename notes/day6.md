# Day 6 Notes
## Lecture Notes/Thoughts

### REINFORCEMENT LEARNING

Critic network takes current state/observation and an action and outputs Q-value

Actor network tells the model what the ideal action would be. Takes in observation/current state

obs -> ACTOR -> action -> CRITIC -> Q
|---------------------------|


backprop through the CRITIC network to update the ACTOR network

trying to maximize the Q value (reward)
