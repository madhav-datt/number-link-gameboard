# Numberlink/Flow Gameboard Generator
This C++ program creates a random game board for the popular puzzle game **Numberlink**. 

## About Numberlink

Numberlink is a type of logic puzzle involving finding paths to connect numbers in a grid.

The player has to pair up all the matching numbers on the grid with single continuous lines (or paths). The lines cannot branch off or cross over each other, and the numbers have to fall at the end of each line (i.e., not in the middle).

## Generating a game board

### Downloading the program

    $ wget https://github.com/madhav-datt/number_link_gameboard/archive/numberlink-v3.0.zip
    $ unzip numberlink-v3.0.zip
    $ rm -f numberlink-v3.0.zip
    $ cd numberlink-v3.0.zip/src

### Generating a new board

    $ make
    & ./numberlink
Enter grid size (n)

## Using the program

* The code builds the puzzle board on a grid whose size is entered by the user.
* It generates the maximum possible number of paths and numbers them.
* It then shows the puzzle/gameboard generated. 
* The program also gives a possible solution for the generated puzzle.

## Known Issues

* Board print formatting is a bit off for 2-digit and above grid size values.

*Please do report issues in case of a bug.*
