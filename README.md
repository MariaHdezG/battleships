#Battleship in Python
###Battleship in Python is a Python terminal game, wich runs in the Code Institute mock terminal on Heroku.

Here are the live version of my project




#How to play  this game
The players can try to beat the computer by finding all the five randomly created battleships in the computer with just 10 tries.

Each ship occupies 1 space that must be hitten by the player using the right coordination of the letters in the columns (A-H) and the numbers in the row (1-8).

Every try is registered and the computer counts how many tries the player has left.
Every hit on the board is also registered and will return with a message.
The message for a hit looks like this: 'Congratulations you have hit the battleship'
The message for missing looks like this: 'Sorry,You missed'
The message for repeating the coordination looks like this: 'You already guessed that'
The meddage for had sunken all the battleships looks like this: 'Congratulations you have sunk all the battleships'

And when the player succeds to sink all the five ships. the player winns this game.

The game will tell the player to choose first a letter from A to H and if the player do so, the next text is so the player can choose a number fron 1 to 8 and when doing so, the game will show the bord with the sign of miss: "-" or the sign of hit "X".

In case the player choose a letter out of range, the game will remind the player the right range of letters to choose and the same when the player chooses a number out of range, the game will remind the player wich numbers are in the range of this game. 

The game will always tell the player how many turns remaning the player still have. 

#Features

Random board generatio
  Ships are randomly placed on the computers board but can not  een seen by the player





  Play against the computer

  Accepts the players input

  Mantains scores






  Input validation and error-checking
  You can not enter coordinates outside the size of the stipulated range
  You must enter numbers in range
  You must enter letters in range
  You can not enter the same guess twice





  #Testing

  I have manually tested this project by doing the following:

  Passed the code through a PEP8 linter and confirmed there are no problems
  Given invalid inputs: strings when numbers are expected, out of bounds inputs, same input twice
  Tested in my local terminal and the Code Institute Heroku terminal

  #Bugs

  ###Solved Bugs

  When I wrote the project, I was getti

  #Remaining Bugs


  #Validator Testing
  PEP8
  No errors were returned from PEP8online.com

  #Deployment

  This project was deployed using Code Institute´s mock terminal for Heroku.

  Steps for deployment:

  Fork or clone this repository
  Create a new Heroku app
  Set the buildbacks to Python and NodeJS in that order
  Link the Heroku app to the repository
  Click on Deploy

  #Credits

  Code Institute for the deployment terminal
  ("https://copyassignment.com/battleship-game-code-in-python/") where I found explanations and codes and also ("https://www.youtube.com/watch?v=tF1WRCrd_HQ")








## Reminders

* Your code must be placed in the `run.py` file
* Your dependencies must be placed in the `requirements.txt` file
* Do not edit any of the other files or your code may not deploy properly

## Creating the Heroku app

When you create the app, you will need to add two buildpacks from the _Settings_ tab. The ordering is as follows:

1. `heroku/python`
2. `heroku/nodejs`

You must then create a _Config Var_ called `PORT`. Set this to `8000`

If you have credentials, such as in the Love Sandwiches project, you must create another _Config Var_ called `CREDS` and paste the JSON into the value field.

Connect your GitHub repository and deploy as normal.

## Constraints

The deployment terminal is set to 80 columns by 24 rows. That means that each line of text needs to be 80 characters or less otherwise it will be wrapped onto a second line.

-----
Happy coding!