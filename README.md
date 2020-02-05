# Drill-Bot
This project consists of a drillbot that can traverse through a grid of nxm dimensions collecting materials along the way while avoiding walls(4 premade maps have already been made for traversal). When the drill bot has traversed through every part of the grid it will return to its initial position. This is in the file maze_drillbot.py.

The drill bot can be ran in console.

Initially displayed is a set of 4 premade maps that are available for travesal. The user is prompted for their selecion.
![CaptureDrill1](https://user-images.githubusercontent.com/56989215/73799913-40b44580-4785-11ea-85d4-67c93a3a184a.jpeg)


Next is printed out the starting point on the map(which is always the first element of the first nested list). Along with adjacent tiles and a legend for each type of object that can exist on the map. The user is prompted to start the drill bot.
![CaptureDrill2](https://user-images.githubusercontent.com/56989215/73809803-61d75f00-47a2-11ea-9be6-3e53e45dcf61.PNG)  
Printing each step the bot takes of the map.
![CaptureDrill3](https://user-images.githubusercontent.com/56989215/73810065-44ef5b80-47a3-11ea-9175-08aa0a2a2c7a.PNG)

Finally the objects collected thought traversal are printed and the user is prompted if they want to run the bot again.
![CaptureDrill4](https://user-images.githubusercontent.com/56989215/73810137-7d8f3500-47a3-11ea-99fc-d98ca26f0b27.PNG)



Also included in this repository is a maze game where the player must reach the end goal in a grid of nxm dimensions. There is also a 2 player version included where the player can play with another player or with a computer. These are in the files maze_1player.py and maze_player2.py.




# To Add Custom Maps

To add more maps for the DrillBot to traverse, initialize a list variable directly under the first while loop in under the conditional "if __name__ == "__main__":" and follow the format where each row is represented by a nested list and individual tiles are elements of the nested list (the number of tiles within each row must be the same). 
![maplocatio](https://user-images.githubusercontent.com/56989215/73807924-16ba4d80-479c-11ea-87ab-72c22edd7468.JPG)

The tiles are string objects that follow the format "(_)", the underscore representing an empty space for which the DrillBot can traverse and where also specific letters can be instead inserted that represent different objects that the DrillBot will interact with. 

The letters correspond to values according to this legend:  
'_' is just dirt  
'x' is an impassable wall  
'r' is a ruby  
's' is a saphhire  
'e' is an emerald  
'd' is a diamond  

Following the initialization of the list variable you must create a map object, print out the name you want the map to be recognized by and then print the string represantation of the map.
![image](https://user-images.githubusercontent.com/56989215/73808370-af9d9880-479d-11ea-9019-32fc125b6b7c.png)

Finally include an if statement that recognizes the user input as the selected map.
![CaptureIfstatementsection](https://user-images.githubusercontent.com/56989215/73809520-7cf59f00-47a1-11ea-99c3-0df396d883ab.JPG)


