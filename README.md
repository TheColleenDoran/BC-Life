# BC-Life
An Apple Swift iOS "choose your own adventure" game based on your freshman year at Benedictine College.

Program Functionality
This project is a choose your own adventure style game created for mobile iPhones. It is fully functional, containing most features this kind of game would have– an autosave and load feature, (including the ability to load in in a previous part of the game, so you can try a different path), extensive content, animations to help the flow of the story, multiple endings, and a final score.

When starting the game, a Navigation Controller is used to first display the homepage view controller, which contains buttons to start and load the game, as well as a tableview to store saved game information. The main Controller used for this game, however, is called the StartGameViewController. After pressing on a saved game or making a new game, the StartGameViewContoller loads the entire story onto a linkedlist object, and then runs the game. All scenes in the game take place on a single view contained in this controller. 

Data Sources
The SQLite extension on Studio Code was used to create the initial database for this game. It contains the user’s name, intelligence (the game's point value), and timestamp. A database class was created on swift to get and set data for this already created database.

