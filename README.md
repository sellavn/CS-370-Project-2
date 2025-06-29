# CS-370-Project-2 Reflection

## Code Provided
For this project, I was given a full codebase that formed the treasure hunt game environment. This includes the two Python files, TreasureMaze.py, and GameExperience.py.
TreasureMaze.py represented the game environment, including the maze implementation, state management, reward calculation, and game status tracking. 
GameExperience.py implemented the experience replay mechanism for deep Q-learning, such as the memory storage, neural network prediction, and data sampling.
Finally, there was the actual notebook itself, TreasureHuntGame.ipynb. The notebook was setup to import the relavant libraries, mainly TensorFlow, establish the 8x8 maze matrix definition, and a visualization function to display the maze, pirate and treasure. 
### My contributions
My contribution served as implementing the Q-training algorithm, within the Q-train function. The designed the main training loop that iterates through epochs, managing the balance between exploration and eploitation - using an epsilon-greedy strategy with inverse decay. 
Another aspect I implemented was the decision making process that chooses between random exploration and exploitation which was based on the neural network Q-value predictions. This ensured that only valid actions are selected based on maze constraints. 
Ultimately, while I had improvements from my milestone, I was not able to reach a 100% finish rate. 

## Connection to Computer Science
### What Computer Scientists Do, and Why it Matters
Computer scientists are the people who fill the role of solving complex problems by design, researching and creating algorithms, systems and technologies that transform how we view the world. This specific project applies ML and AI principles to create an agent that is supposed to learn optimal strategies through experience. There are several real-world applications such as autonomous navigation systems for vehicles and robots, or decision support systems for healthcare and finance.
This work is very important as computational thinking is key to understanding how today's world works, as solving through other means is impractical or impossible in most scenarios currently. 
### Approaching Problems as a Computer Scientist
Computer scientists embrace computational thinking - the ways I did so in this project are by problem decomposition, iterative development, and performance analysis.
Problem decomposition is one of the first things taught in CS for good reason - learning to break down a complex challenge into manageable components helps each aspect become better understood, implemented and tested. The components in this care are the environment interaction, action selection, experience storage and learning mechanisms.
Next is iterative development. We started with a milestone, and multiple iterations between the projects conclusion had to be done - systematic debugging, examining variable scope, tracing execution flow, and testing solutions incrementally. 
Lastly is performance analysis. Learning to evaluate the algorithm performance, in terms of the convergence speed, efficiency and scalability helped somewhat in establishing what needed changes in between each iteration, and where my changes were going.

## Ethical Responsibilities
## End Users
The project as well as the coursework throughout this class highlighted important ethical considerations to end users such as transparency, fairness/bias, safety and reliability. 
AI systems have had some trouble with transparency. The systems in place should be interpretable and explainable - while the agent I created has learned some effective strategies, users deserve to understand how decisions are made. This is especially important in high-stakes contexts such as law-enforcement, finance and medical fields.
Fairness/Bias is another aspect that AI has struggled with at times. The training process could potentially learn biased strategies if the maze configurations or reward structures inadvertently favor certain paths or approaches. We must ensure AI systems perform equitably across different scenarios.
Lastly, safety/reliability must be considered as well. The agent must perform predictably and safely. In real world application, such as autonomous vehicles, unpredictable behavior can have serious consequences.
## Organizations
All of the aspects above should ideally translate to organizations as well, but they also possess different responsibilities.
A solid channel of communication must be established to accurately represent the capabilities and limitations of AI systems. Overstating performance or understating risks can lead to inappropriate deployment scenarios. 
Next, resources must be used in a responsible manner. Deep learning requires significant computational resources - this has a large environmental and financial impact. 
Another aspect which is part of the iterative development is continous improvement. AI systems require ongoing monitoring and updates - the responsibility lays with us to design systems that are able to be maintained and improved overtime.
Lastly, risk assessment should be considered when communicating with stakeholders. This includes edge cases or anomolies where the AI might fail or behave in an unexpected manner.
