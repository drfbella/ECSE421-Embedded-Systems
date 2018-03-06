Whenever you work on the project, make sure to run the load_from_file.vi instrument before doing anything. 
You should select the weights CSV then the output CSV, in the right order, when running it. 
It will populate the shared variable weights that the model uses to predict anything.

To run this, open up the project file Lab3" and click the run button in the taskbar. Then see the front panel window in test.vi, LED0, LED1, and LED2 and enjoy the show.



The roll and pitch were calculated using the fact that there is a point of reference that is always 1g, such that pitch = arcsin(g_y) and roll = arcsin(g_x). This was implemented using the built-in arcsin block.

Raquel Charron 260588791

Marc Cataford 260517747

Drifa Bellache 260587257


Link to video: https://drive.google.com/open?id=1SUbQ8GpT71O_DyC5R8fO6BVVWHeOMa6q