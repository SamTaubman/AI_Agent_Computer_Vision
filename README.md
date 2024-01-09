# Note
The repository containing the actual implementation of this agent is private per Georgia Tech Policy. Let me know if you need to see the code for this project.

# Ravens_Agent
Ravens_Agent is an AI Agent designed to be able to solve Raven's Progressive Matrices IQ Test (https://en.wikipedia.org/wiki/Raven%27s_Progressive_Matrices). Raven's Progressive Matrices is a non-verbal test of general human intelligence where participants must identify the missing element that completes a pattern.

Ravens_Agent combines the computer vision methods of dark pixel ratio (DPR), intersection pixel ratio (IPR), and shape recognition by contour approximation with more general AI concepts like generate and test and learning by recording cases. Ravens_Agent utilizes the openCV, Pillow, and NumPy libraries. 

To run Ravens_Agent run RavensProject.py. To edit which problems Ravens_Agent solves you can modify ProblemSetList.txt. Main Ravens_Agent implementation is stored in Agent.py.

# Use Case
Shown below is an example Raven's Progressive Matrices problem that can be solved using Ravens_Agent. Correct answer is 1.
![Basic Problem D-04](https://github.com/SamTaubman/Ravens_Agent/assets/109553302/dd90245e-a39c-49c3-87d1-bf35992b47be)

# References
Georgia Tech CS 7637: Knowledge-Based Artificial Intelligence - Cognitive Systems
https://omscs.gatech.edu/cs-7637-knowledge-based-artificial-intelligence-cognitive-systems

