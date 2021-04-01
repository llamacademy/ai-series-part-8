# Navmesh AI Tutorial 8 - Adding Bullet Mechanics to Ranged Enemies
The below video is the tutorial that **ENDS** where this project is. If you would like to follow along, check out the [7 How to Make a Ranged Attacking Enemy](https://github.com/llamacademy/ai-series-part-7) 

[![Youtube Tutorial](./Video%20Screenshot.png)](https://youtu.be/KobCxX7NZM4&ref=github)

In this project we have:
1. Simple click to move.
2. An enemy that follows the player
3. NavMeshLinks to allow the player and enemy to jump from one platform to another, and on top of some walls.
4. AgentLinkMover to control how NavMeshAgents will traverse NavMeshLinks
5. Animated 3D Model based on NavMeshAgent's movement
6. Dynamically spawned enemies at random points on the NavMesh
7. 2 Enemy types, configured via a ScriptableObject, that path differently based on Agent Configuration
8. Enemies and Player attack the other when they near each other, until dead.
9. Ranged Attacking Enemies
10. Configurable Homing Bullet Mechanics for Ranged Enemies

## Requirements
* Requires Unity 2019.4 LTS or higher. 
* Utilizes the [Navmesh Components](https://github.com/Unity-Technologies/NavMeshComponents) from Unity's Github.
