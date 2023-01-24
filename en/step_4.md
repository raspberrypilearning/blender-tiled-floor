## Set the centre point

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Move the origin point so that it is at the center of your tile floor.
</div>
<div>
![](images/tiled-floor.png){:width="300px"}
</div>
</div>

### Centre the origin point

The origin point is set to the centre of your original tile. The X and Y axis lines will meet in this point:

![View of the whole dance floor with the origin point marker shown in the top-left corner. The X and Y axis lines are shown meeting in the origin point.](images/original-origin.png)

--- task ---

Go to the **Scene Collection** pane and click on the 'Cube' object:

![The Scene Collection pane with the 'Cube' object highlighted.](images/select-cube.png)

--- /task ---

--- task ---

Go to Object -> Set Origin -> Geometry of origin.

The origin marker will move to the centre and the X and Y axis lines will meet in this point:

![View of the whole dance floor with the origin point marker shown in the centre of the whole dance floor. The X and Y axis lines are shown meeting in the centre at the origin point.](images/centered-origin.png)

--- /task ---

### Separate the grid into 64 separate tile objects

--- task ---

Click on the mode dropdown menu and select 'Edit Mode':

![Edit mode selected from the mode dropdown in the top left corner of the editor.](images/edit-mode.png)

--- /task ---

--- task ---

Right-click on the highlighted tiles and select 'Separate' -> 'By Loose Parts':

![The object right-click menu with 'By Loose Parts' highlighted.](images/loose-parts.png)

There are now 64 individual tiles each shown as a Cube object in the Scene Collection:

![64 individual tiles shown by an orange border around each. Each cube is shown in a list of numbered cube objects in the scene collection shown as 'Cube 001', 'Cube 002' etc.](images/64-cubes.png)

--- /task ---