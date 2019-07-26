## Export your dice

Now it's time to export your dice model for printing. There are a lot of different types of 3D printers, but most of them accept `.stl` files or `.gcode` files. It is easiest to export your model as an `.stl` file and then use this file in another software program to create a `.gcode` file.

--- task ---
In the **Model** tab, select the body.

Click on **File** and then on **Export**.

In the **Files of type** drop-down menu, click on the `.stl` option.

Give your file a name, and then click on **Save**.

![export](images/export.png)
--- /task ---

If your 3D printer requires `.gcode` files, use another software program to convert the `.stl` file into a `.gcode` file. The instructions below are for [the software Cura](https://ultimaker.com/en/products/ultimaker-cura-software).

--- task ---
Open Cura from you application menu.

![Cura1](images/cura1.png)
--- /task ---

--- task ---
Go to the **File** menu and open your `dice.stl` file.

![Cura2](images/cura2.png)
--- /task ---

--- task ---
Use the settings menu on the right-hand side to choose your **material**, **profile**, **infill**, and any **support** you might need.

In the example:
* The material is PLA
* The profile is set to **High Detail**
* The infill is set to **60%** to give the dice a bit of weight.

![Cura3](images/cura3.png)

Once the settings are correct for your 3D printer, use the menu in the bottom left-hand corner to save your `.gcode` file.
--- /task ---
