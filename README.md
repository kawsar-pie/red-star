# red-star
### Description:
When the game begins, two stars appear and start moving down the screen. The player needs to click on the red star before the stars reach the bottom of the screen.Each time the red star is clicked, the game moves on to the next level. With each level, more green and blue stars are added and they move faster than before. If the player clicks on any star other than the red one, or if the stars reach the bottom of the screen,the game ends.

![image](https://user-images.githubusercontent.com/79654190/171040356-e56d4623-4452-4f36-b043-4e7f78bb479d.png)

### Stars
This game uses three colors for the star Actors—red, blue, and green.
The program uses Pygame Zero’s animate() function to move the stars down the screen. You can adjust the duration of the animation to make the game more interesting. The stars can fall as slowly or as quickly as you like!


![image](https://user-images.githubusercontent.com/79654190/171039755-f0c1674b-1a56-4d6b-9260-fb58006ba083.png)

This game uses the draw() and update() functions to display the stars on the screen. Each time the draw() function is called, the program clears everything on the screen and redraws the stars. The update() function checks if the player has clicked on a star.
