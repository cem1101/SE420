# SE 420 - Artificial Intelligence and Expert Sys.
======

    Numaranızı isterseniz ekleyin.
    


AI Project 2021-2022
------

Rules of Game:
1. The initial and goal states will be given by user.
2. The tiles can be moved up, down, right, or left.
3. The game will begin by the move of Tile #1 (ifrequired) and go on with the moves of other tiles inorder.

For example:
- 1st step: move Tile #1
- 2nd step: move Tile #2
- 3th step: move Tile #3
- 4th step: move Tile #1
- 5th step: move Tile #2
- 6th step: move Tile #3

4. Distance(cost) between two neighboring states will be measure based on the move costs as given below

Tile #1      | Tile #2 |  Tile #3       
------------ | ------------- | -------------
right or left move -> cost =2 | right or left move -> cost =1 | right or left move -> cost =3  
up of down move -> cost =1 | up of down move -> cost =2 | up of down move -> cost =4

5. User will choose one of the searching strategies: uniform cost and A* search (use Manhattan distance as heuristics).
6. The expansion will go on till 20th expanded node. The program will print out each expanded state and compare it with given goal state.
7. You are free to use any programming language for implementation. 

## Lecturer

 - Assoc. Prof. Senem KUMOVA METİN


## Team Members
 - Fidan ÇELENK 
 - Ercan ACAR    
 - Mustafa ALAN
 - Ayşegül MERCAN
 - Cem ÖZCAN