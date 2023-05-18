## Set the centre point

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
In Blender, objects move around an origin point. You can move the origin point of an object.
</div>
<div>
![](images/centered-origin.png){:width="300px"}
</div>
</div>

### Move the origin point to the centre of your floor

The origin point is set to the centre of your original cube tile. The x- and y-axis lines meet at this point:

![The whole tiled floor with the origin point marker shown in the top left-hand tile. The x- and y-axis lines are shown meeting at the origin point.](images/original-origin.png)

--- task ---

Go to the Scene Collection pane and click on the **Cube** object:

![The Scene Collection pane with the Cube object highlighted.](images/select-cube.png)

--- /task ---

--- task ---

Go to the **Object** menu and select **Set Origin** > **Geometry to Origin**.

The origin point marker will move to the centre of the tiled floor, and the x- and y-axis lines will meet at this point:

![The whole tiled floor with the origin point marker shown in the centre of the floor. The x- and y-axis lines are shown meeting in the centre at the origin point.](images/centered-origin.png)

--- /task ---

### Separate the grid into 64 separate tile objects

The 8-by-8 grid of tiles is still one object. This object can be separated into 64 independent tile objects.

--- task ---

Click on the **Mode** drop-down menu and select **Edit Mode**:

![The Mode drop-down menu open in the top left-hand corner of the editor, with 'Edit Mode' highlighted.](images/edit-mode.png)

--- /task ---

--- task ---

Right-click on the highlighted tiles and select **Separate** > **By Loose Parts**:

![The object right-click menu with 'Separate' then 'By Loose Parts' highlighted.](images/loose-parts.png)

There are now 64 individual tiles each shown as a Cube object in the Scene Collection pane:

![64 individual tiles with orange outlines in the 3D view. In the Scene Collection pane, the individual Cube objects are shown in a list numbered as 'Cube.001', 'Cube.002', and so on.](images/64-cubes.png)

--- /task ---
