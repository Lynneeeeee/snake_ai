# snake_ai
An AI snake training game based on Deep Q Network.

1. Snake_human.py is a simple game for human, including classes of directions, snake, foof, wall and game, and methods for initializing the game state, handling collisions, etc..
2. Snake_env.py is similar to snake_human but includes methods for determining rewards or penalties. It provides the necessary functionality to simulate and interact with the Snake game.
3. Snake_agent.py is the agent that interacts with the Snake environment. It can observe the current state of the game (such as the positions of the Snake and the food) and choose the best action to maximize its performance through training. 
4. Snake_ai.py utilizes reinforcement learning to train an AI agent to make optimal decisions in the game. And it learns from the interaction between the agent and the environment, gradually improving its performance through trial and error.
5. The main function in snake_ai.py is what you need to run if you want to train your snake(train()) or play the game by existing training results(play()). 
