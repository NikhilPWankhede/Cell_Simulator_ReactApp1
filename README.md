# Cell_Simulator_ReactApp1

Implementation of this app is done using React and Typescript.

The "game" is a zero-player game, meaning that its evolution is determined by its initial state, requiring no further input. One interacts with the Cell Simulator by creating an initial configuration and observing how it evolves.

**Prerequisite**
Node JS and NPM installed on your system.

**Installation**
1. Download the zip file and extra it on your local system.
2. Open the command promp -> go to the project folder and run following commands - 
    
    npm install
    
    npm start

**Usage**
1. At initial state, User will see an empty board.
2. User can make Cells "alive".
3. User can make Cells "dead".
4. User can trigger "next generation".
5. User can trigger a "reset" to the initial state.

When the next generation is running:
-	A Cell with fewer than two live neighbours dies of under-population.
-	A Cell with 2 or 3 live neighbours lives on to the next generation.
-	A Cell with more than 3 live neighbours dies of overcrowding.
-	An empty Cell with exactly 3 live neighbours "comes to life".
-	A Cell who "comes to life" outside the board should wrap at the other side of the board.
-	Once the next generation is done, User can trigger "next generation" again.

