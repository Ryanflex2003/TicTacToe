#Tic-Tac-Toe

##Description
 This application will output the results of a tic-tac-toe game
##
####Assumptions
#####The board comes in the form of a 3×3 array where:
    0 if the spot is empty
    1 if it is an X
    2 if it is an O
#####The board passed in is valid in the context of a game of Tic-Tac-Toe

## To Do:
##### Write functions that
    Return -1 if the board is not solved yet
    Return 1 if X won
    Return 2 if O won
    Return 0 if it’s a cat’s game (i.e. a draw).
##### 

##### Write tests for functions validating results are intended

## Example 1    
    [[0,0,1],
    [0,1,2],
    [2,1,0]]
#### Returns 0

## Example 2
    [[1,1,1],
    [1,2,2],
    [2,0,0]]
#### Returns 1