# -20211859--shmup-

###### The code for this game is provided in the file "곽희진(20211859 - Shumup.py". 

###### To briefly explain, I mainly used the code provided from kidscancode.org (Part 10 of shmup game), and changed up some of the codes. First, I downloaded the images and sounds from opengameart.org, and saved them into the img & snd file. This way, the program can run without having any issues because all the files are where they are supposed to be at. In each of the classes in the code, the size, rotation, and falling speed of the items are assigned, so they can be used later on. Then, I loaded all the graphics and sounds that are used in the game. As for the score, it increases when the laser collides with the mob. To make the game more interesting, "score += 50 - hit.radius" this part of the code allows a higher amount of score when a smaller mob is hit and vice versa. The player(ship) has a shield, and it decreases as it is collided with the mob. Similar with the score, the player's shield decreases more when a larger mob is hit and decreases less when a smaller mob is hit. This way, the player has a couple of chances before the game ends. 





