# mariosworld

Factory for making pacmen

When button "Create X Mario's" is pressed function #makePac is called and set 
via function #setToRandom to a place on the screen.
There is no limit in creating "Mario's" by clicking on the button.

The button "start Game" calls the function #update, which initates the process of moving the img. of Mario around.
The single Mario's will (randomly assigned) go into several directions and with different speeds.
The function #update is called every 20ms.

Furthermore the function #checkCollisions will detect, if the img/item is hitting the window and changes the direction.
