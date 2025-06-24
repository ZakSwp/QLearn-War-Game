This project was prepared in the context of the Operational Research II course at Ecole Polytechnique de Tunisie.

The goal of this project is to implement one of the algorithms seen in the course to solve an adequate real life problem.

This code is a simulation of a  simplified adversarial scenario where two agents start at opposite nodes of a procedurally generated graph and compete to capture the enemy team's source node. 

# Game Rules
The environment is represented as a finite undirected procedurally generated graph. Each team starts from designated base node located at opposite ends of the graph. The network structure allows multiple traversal paths with a chance of having dead ends.

**Objective:** Navigate the network while avoiding crossing path with the enemy team, ultimately reaching the enemy base node.
In the case of crossing an enemy team's path (contested node), both teams receive penalties. The attacking team is penalized twice to simulate defender's advantage.

**Victory Condition:**
- Capturing the enemy base (or obtain a higher score if ran out of moves)

![[Pasted image 20250624194405.png]]


