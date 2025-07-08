# SPACE INVADER

How To Play
Space Bar is for Firing the Bullet and Left and Right arrow are for movement of Spaceship and as you hit the Enemy the Score will be updated

SET UP SECTION
Firstly we imported math , random , mixer and pygame then using init we initialize the game and created the screen of dimension (800,600) for changing the caption we used pygame.set_caption and similarly for icon pygame.image.load and we changed the background colour using RGB value then we defined a set of coordinates for different objects like enemy,bullet,spaceship and in bullet section we defined ready and fire and we created different function according to the need of the game and we also used screen.blit for image to appear on screen
and for the game to continue we created the while loop and used pygame.event and for quiting the game we changed the value to False in while
and we defined the event.type to identify which keybutton is pressed and according to which we define the change in their respective coordinates by defing change and we have certain rule if they go out of the screen by fixing the coordinate we can bring back or anything we want to do and we also created the isCollision function which determine whether the collision have happened or not
and for creating multiple enemies we started for loop for executing multiple enemy by creating empty list and adding them using append and we also upadate the game score using function and by using font.render
and when the enemies reaches the y coordinate which is equal to the y coordinate of spaceship then game gets over.
for adding music we used mixer.music and we used three types of music in game
![Screenshot 2025-07-06 221832](https://github.com/user-attachments/assets/f0ada73b-f9c7-4fac-84fb-3f397ae7b7d8)
