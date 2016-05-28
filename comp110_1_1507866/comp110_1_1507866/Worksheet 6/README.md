#Worksheet 6

##Flowchart  
The flowchart below shows the process that leads to the characters in the game changing between the idle, wandering and moving to user set destination states.
![Flowchart](https://raw.githubusercontent.com/MaddieK19/comp110-coding-task-2/master/Worksheet%206/WS6%20-%20Flowchart.png)

##Pseudocode  
The pseudocode below outlines part of the process that takes place when the character is in a room with low or no oxygen. The character class will have a function that creates a list of nearby cells, it will then check those cells to see if any of them are not oxygenated and the character will move away and the characters speed will be reduced.

```
Function: Get list of neighbour cells ( current cell/cell the character is on ):
  above cell = current cell's Y + cell size
  below cell = current cell's Y - cell size
  right cell = current cell's X + cell size
  left cell = current cell's X - cell size
  Add them all to a list of neighbour cells
  return the list
End of function  


For each cell in neighbour cells list:
  If cell is not oxygenated 
   character state = suffocating
   return cell 
End of for each

While character state = suffocating
  If oxygen level < 50
    character speed = suffocating speed
  If oxygen level < 30
    character speed = suffocating speed
    health = health - 1
  If oxygen level < 30
    health = health - 2
End while

```
  

##UML Diagrams: 
####Use-case diagram
![Use case diagram](https://raw.githubusercontent.com/MaddieK19/comp110-coding-task-2/master/Worksheet%206/WS6%20Use%20Case.png)  


####Class diagram  
![Class diagram](https://raw.githubusercontent.com/MaddieK19/comp110-coding-task-2/master/Worksheet%206/WS6%20Class%20diagram.png)

####State diagram  
![State diagram](https://raw.githubusercontent.com/MaddieK19/comp110-coding-task-2/master/Worksheet%206/WS6%20State%20Machine.png)

####Sequence diagram
![Sequence diagram](https://raw.githubusercontent.com/MaddieK19/comp110-coding-task-2/master/Worksheet%206/WS6%20sequence%20diagram.png)
