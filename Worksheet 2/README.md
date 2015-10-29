#1: Fading to Black
###Flowchart
![Flowchart](http://i68.tinypic.com/2pz0kyp.png)

The flowchart above shows the process I plan to use to make images fade to black. In my program an image will fade to black before transitioning  to the next image. 

###Pseudocode
SHOW Image
CREATE Timer

SET timer = 1

IF timer is greater than 20  
  >SELECT first pixel in image  
  GET red green and blue values  
  MULTIPLY red value by 0.95  
  MULTIPLY green value by 0.95  
  MULTIPLY blue value by 0.95  
  ADD 1 to timer  

END IF  

ELSE  
  SET colour to black   
END ELSE    
REFRESH image  

![Pseudocode image](http://i65.tinypic.com/34q48xg.png)

