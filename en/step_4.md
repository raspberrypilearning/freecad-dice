## Adding pips to one face

Now that you have the 3D shape of the dice, it's time to add the pips that represent the numbers.

This can be done by sketching shapes onto the surface of the dice and then creating pockets in the surface.

To do this you are going to need to change which workbench you are using.

--- task ---
Switch to the **Part Design** workbench

![part-design](images/part-design.png)
--- /task ---

--- task ---
Make sure that your **Common** object is selected and then click on the *Create a new body and make it active* icon.
![PartDesign_Body_Create_New](images/PartDesign_Body_Create_New.png)

Clicking on the **Model** tab you should see that your **Common** object is greyed out.

![create-new-body](images/create-new-body.png)
--- /task ---

--- task ---
Next, select the face of the dice that your first set of pips will be added to and then click on the *Create a new sketch* icon.

![Sketcher_New_Sketch](images/Sketcher_New_Sketch.png)

Your perspective on your dice should change, and you the tab will switch to the **Tasks** tab.
--- /task ---

To make sure that the pips are all placed accurately you will need to create a construction sketch to begin with. This sketch is a little like a guide, helping you to accurately place the remaining sketch.

--- task ---
Click on the drop down arrow next to the *Create a regular polygon in the sketcher* icon.

![Sketcher_CreateHexagon](images/Sketcher_CreateHexagon.png)

Then choose the *Create a square by its center and by one corner* icon.

![Sketcher_CreateSquare](images/Sketcher_CreateSquare.png)
--- /task ---

You can place the square in two ways. The first is to carefully place your cursor over the central dot you can see in the cube and then click and drag out.

The second way is to draw the square anyway, and then use a constraint to place it in the centre of the dice.

--- task ---
Place the square in the centre of the dice by either:

- Carefully clicking on the central dot and then dragging out to draw your square

![create_square_1](images/create_square_1.png)

or:

- Draw the square anywhere, then click the dot in the centre of the screen and while holding down the **Ctrl** key, click the dot in the centre of the square.

- Now use the *Create a coincident constraint on the selected item* icon to move the square to the centre.

![create_square_2](images/create_square_2.png)

![Sketcher_ConstrainCoincident](images/Sketcher_ConstrainCoincident.png)
--- /task ---