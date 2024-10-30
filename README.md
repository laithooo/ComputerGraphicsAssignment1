# ComputerGraphicsAssignment1


LINK TO VIDEO PRESENTATION 
https://www.youtube.com/watch?v=q6Dsusii47w

Computer graphics assignment 1 report
Laith Ghannam 100895645 (solo project)​

Working Game with Shader Implementation

Main Premise Of Game
-The game I've built is a game that was inspired by the look of the early "DOOM" games with the mechanics of any "Hitman" game​

-Main objective is to either kill all enemies without dying, or to destroy the enemy radio tower.​

-What this means is that the game is a first person shooter with a focus on completing an objective by either stealth or eliminating every enemy​

-The style of the game I've went with is going to be a pixel game with some elements of realism




-The game revolves around a few main scripts

​
-The Scripts: Player, Shoot, Health, bullet all belong to the Player gameObject where the person who controls the object will be able to move while having the ability to shoot and possibly die.​

-The player script also contains coding to be able to rotate the camera while shooting and having the classic "DOOM" inspired camera feel to it.​

-The script for the camera will be referenced in the next two slides. The justification of this is that I needed to have a camera that suited the style of the game "DOOM" in order to really fit in with the art style of the rest of the game and to give perspective of how powerless the main character can be vs enemies. However the code was heavily remodified to be able to fit into the game scene 




The rest of the scripts revolve around the enemies or the win/loss conditions:​

-The enemy was scripted with 3 phases a patrol command which makes them move in random directions on a NavMesh, a chase command that transforms their positions towards the player gameObject, and finally an attack command that kills the player instantly and takes them to the Loss Menu.​

-The win and loss menus were coded using Unity's built in SceneManagement which lets you make win/loss conditions very easily. As soon as an event happens it will instantly take you to a new scene that shows you the result of the action you've done.


REFERENCES FOR CODING

The only scripts that I have used references for are the camera movement scripts inside Player script and the NavMeshAgent section of the enemy script.​

-The rest of the coding was coding that I have coded specifically for this assignment.​

Sections that used references:​

Player.Camera:​

​

​

​

Justification: Needed a camera that followed the "DOOM" style but also modified it by adjusting the numbers using [SerializeField]​

Enemy: Needed a smarter AI for the enemies due to the fact that it is a stealth game and needed assistance on making them detect Players.​

Modified by making own code for enemies to shoot and die


Rest is covered in the video, I go over using the diffuse, ambient, specular


then I go over using Rim shader and Transparent Shader


Lastly, I talk about the limited time constraints and how that has affected this project.







