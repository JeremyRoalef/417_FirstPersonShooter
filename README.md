This lab aims to develop a system for enemy pathfinding and attacking. The lab will show completeness of a transitioning state machine to handle enemy logic. It will also explore the setup of nav meshes to handle ai movement in a 3D space.

Feature Checklist:
1)Behaviour completeness
2)Design Clarity & Justification
3)Robustness & Readability
4)Polish
5)Version Control Quality

While this lab aims to develop an intuitive system for enemy pathfinding and state machines, there is much that may be expanded upon that wasn't included. To start, a health UI for the player may be added. Second, the player may attack back at the enemy. Third, the player's weapon could become a real wepaon that deals damage back to the player. Finally, improvements to the visuals and audio may be improve significantly.

Here is a simple setup for the damage and attacking events for the player. This controls the logic for dealing damage to the player and determining the attack delay of the enemy.
<img width="1197" height="815" alt="image" src="https://github.com/user-attachments/assets/19076ccd-aa10-4e6f-b54a-62ae26b9ab3c" />

Here is the logic for enemy's state machine. Currently, it only supports the chase state sequence. In the future, this system can be expanded to support many states.
<img width="1306" height="587" alt="image" src="https://github.com/user-attachments/assets/c6618d40-033a-47e1-8d78-4db5441b8d93" />

A custom enemy AI controller was created to handle the enemy logic. This AI controller does a simple check to see if the player is visible to the enemy based on the AI controller criteria (i.e., distance, cone of view, etc).
<img width="1329" height="741" alt="image" src="https://github.com/user-attachments/assets/d6d9a987-d0f6-4f9f-880e-0e0c0acef7ab" />

Controls:
-WASD to move forward, left, back, and right, respectively
-left click to shoot


Video:

![CITA+417+-+Lab+2 (1)](https://github.com/user-attachments/assets/28d8ef92-4df7-44b8-9686-4d37cb9f3a14)

