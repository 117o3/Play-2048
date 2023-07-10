# Play-2048
Data Structures Assignment: _2D Arrays Based Project_

The objective of the game is to merge tiles with numbers until you reach a tile with a value of 2048. When two tiles with the same number touch, they combine to form a new tile with double the value. 

--------------------------------------------------------------------------
Files implemented: _all in Board.java_

  updateOpenSpaces()
  addRandomTile()
  swipeLeft()
  mergeLeft() 
  transpose()
  flipRows() 
  makeMove() 
  

to compile: javac -d bin src/game/*.java

to execute: java -cp bin game.AnimatedDriver OR java -cp bin game.TextDriver

--------------------------------------------------------------------------
Programming Skills Utilized: _only mentioning new skills_

updateOpenSpaces()
  - Object-Oriented Programming (OOP): create & initalize instance variables
  - Array Manipulation: initilize instance variables
  - ArrayList Handling: import class & use its methods
  - understanding of Class & Instance variables

addRandomTile()
  - Random Number Generation: StdRandom.uniform()
  - Looping & Conditionals
  - Accessing & Modifying elements in an array
  - Understanding probability: 90% chance of a 2 value, 10% chance of 4 value

swipeLeft()
  - Looping & Iteration: rows & columns
  - Conditionals & Comparisions: check & compare adjacent tiles to determine if they can merge or move
  - Temporary Variables: maintain order of tiles and prevent data loss
  - Logic & Algorithm Design: devise strategy ensuring no zero tiles are present between nonzero tiles, whiling mainting original order
  - Problem-Solving & Debugging

mergeLeft()
  - Basic Arithmetic Operations
  - Indexing & Acessing Elements

transpose()
  - Copying 2D Array
  - Swapping Elements

flipRows()
  - iteration to Reverse Rows

makeMove()
  - Method Calling
  - Logical Operations
  - Algorithmic Thinking
  - Code Organization
  - Familiarity with Game/Application Framework
