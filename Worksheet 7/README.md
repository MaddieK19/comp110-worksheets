#Worksheet 7
The code I've decided to refactor is the finite state machine for the character AI in the COMP150 group game. Previously the functions that made the character respond to it's current state were seperated out into the seperate state classes and the update function to change the states was within the character. I'm going to apply the State design pattern do the code.

##Diagrams:
![Before refactor](https://raw.githubusercontent.com/MaddieK19/comp110-worksheets/master/Worksheet%207/Diagram%20before%20refactor.png)  
The diagram above shows a UML class diagram of the character and it's states before the refactor. 
![After refactor](https://raw.githubusercontent.com/MaddieK19/comp110-worksheets/master/Worksheet%207/Diagram%20after%20refactor.png)
