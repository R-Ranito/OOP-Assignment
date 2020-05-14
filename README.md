# OOP-Assignment

Rui Ranito C18753061 - DT228/2 Assignment for Object Oriented Program 
YouTube link: https://www.youtube.com/watch?v=zIYeG6qaO3w

The project is a game build entire in Java, for the project I used Eclipse IDE in the game you are a young Padawan that is the pilot of a X-Wings fight and your mission is try to survive the waves of enemies and the asteroid belt, the player is allowed to go through the border of the screen and he will appears on the other side, the same occurs with the meteors

Instructions:

Run the game press the SpaceWars jar file
Another way to Run the program is in the Package main - class Window
Press Play button to Play 
Press Height Score button to see the score from previous games the 10 higher scores will be display. 
Press Exit button to close the game 


Spaceship Control

W = the spaceship moves forward

A = the spaceship turns left

D = the spaceship turns right

Spacebar = the spaceship fire


About the construction of the game
 
The Package contains the main class it is the Class Window this class extends the class JFrame to allow to create the game window.
The constructor in this class create the parameter to the window of the game the title, the size of the window and other parameters
for the window. 
Package graphics contains the class Loader this class is used to get the images and sounds from the game.
Package GameObject is where the objects of the game are created the player, the enemy, meteors etc.
to the player move through the border the if statement position.getx() < 0 the width of the window and the get from the window.
The laser of the spaceship was created getting the position of the spaceship and add the heading *width/2    
For the meteors use the BufferedImage to load the images of the meteor. I decided to create 4 types of meteors with 
once one is destroyed a small part of it will appear.
For the enemy I decide to do the spaceship make a determined route and fire against the payer
For the score I used the format Json to store the scores from each game and organize it in and descendent way.

Achievements 

This game is an attempt to recreate the games that I used to play when I was young it is a game based on the olds
arcades and also a little tribute to a movie that I like, It is very gratifying to see that you are able to at least
create something and that it works even more if it is something that brings you good memories.
I can say that yes I am proud of my work but I also know that it could be better that the game has some bugs
but now that I have taken the first step with this world of video games I would like to improve in this area. 
As previously said, the game was a small tribute to a saga that was very much appreciated by me for that reason,
the choice of the spaceship, the sound effects and the music of the game.


Bugs: 

A Bug detected in the SpaceWars.jar file the Background image does not upload.
The same doesn’t occurs when open the file trough the Package main – class Window (the main class) 



Thanks!!!!



