#Worksheet 7
The code that needed refactoring  is the finite state machine for the character AI in the COMP150 group game. Previously the functions that made the character respond to it's current state were seperated out into the seperate state classes and the update function to change the states was within the character. I'm going to apply the State design pattern to the code.

##Diagrams:
###Before refactor
![Before refactor](https://raw.githubusercontent.com/MaddieK19/comp110-worksheets/master/Worksheet%207/Diagram%20before%20refactor.png) 
The diagram above shows a UML class diagram of the character and it's states before the refactor. The functions relating to the different states are spread out among the the different state classes.  

###After refactor  
![After refactor](https://raw.githubusercontent.com/MaddieK19/comp110-worksheets/master/Worksheet%207/Diagram%20after%20refactor.png)  
The diagram above shows the refactored code in a class diagram
