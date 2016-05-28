#Worksheet 7
The code that needed refactoring is the character AI in the COMP150 group game. Previously the functions that made the character respond to its current state were separated out into the different state classes and the update function to change the states was within the character. The State design pattern could be applied to this component to improve it.

##Diagrams:
###Before:
![Before refactor](https://raw.githubusercontent.com/MaddieK19/comp110-worksheets/master/Worksheet%207/Diagram%20before%20refactor.png) 
The diagram above shows a UML class diagram of the character and its states before the refactor. The functions relating to the different states are spread out among the different state classes.  

###After:   
![After refactor](https://raw.githubusercontent.com/MaddieK19/comp110-worksheets/master/Worksheet%207/Diagram%20after%20refactor.png)  
The diagram above shows the character AI with the State design pattern applied. The update function is now in the states.
