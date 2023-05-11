## Make a tiled floor

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
In Blender, you can quickly create multiple copies of an object and place them in a pattern.
</div>
<div>
![A grid of eight rows of eight tiles in Blender.](images/tiled-floor.png){:width="300px"}
</div>
</div>

### Create one row of eight tiles

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
An <span style="color: #0faeb0">**Array modifier**</span> creates copies of an object that can be placed at a distance from each other to create a pattern of repeating objects. An architect could use an Array modifier to create a staircase for a home from just one step. When designing a model for an office building, the architect could use an Array modifier to place trees along a path.

![A highlighted step object that has been duplicated and offset to create a staircase in Blender.](images/stair-array.png){:width="300px"}

</p>

--- task ---

Click on the **Add Modifier** drop-down menu, then choose **Array**:

![The Add Modifier menu open in the Modifier Properties tab, with 'Array' highlighted.](images/array-modifier.png)

The Array modifier automatically creates a second tile.

**Tip:** You might need to zoom out to see both tiles:

![Two tiles side by side in the 3D view. In the Modifier Properties tab, the Count property is highlighted and has a value of 2.](images/two-tiles.png)

--- /task ---

--- task ---

Change the value in the **Count** property to `8`.

This creates a row of eight tiles side by side:

![Eight tiles side by side in the 3D view. In the Modifier Properties tab, the Count property has a value of 8.](images/eight-tiles.png)

--- /task ---

--- task ---

The tiles are offset by 1.000. This means they are placed next to each other with no gap.

Change the value in the **Factor X** property to `1.100` to increase the offset and create a small gap between the tiles:

![In the Modifier Properties tab, the Factor X property is highlighted and has a value of 1.100. In the 3D view, the row of tiles now have a small gap between them.](images/offset-tiles.png)

--- /task ---

--- task ---

Click on the **Array** drop-down menu arrow, then select **Apply**: 

![The arrow highlighted and the Array drop-down menu open, with the first menu item 'Apply' highlighted.](images/apply-array1.png)

--- /task ---

### Create eight rows of eight tiles

--- task ---

Click on the **Add Modifier** drop-down menu, then choose **Array** to create a second Array modifier:

![The Add Modifier menu open, with 'Array' highlighted.](images/array-modifier.png)

The Array modifier automatically creates a second row of eight tiles that are also offset on the x-axis.

**Tip:** You can see where the second row starts because it has an offset of 1.000, so there is no gap:

![Two tiles side by side with no gap. In the Modifier Properties tab, the Count property has a value of 2 and the Factor X property has a value of 1.000.](images/two-rows.png)

--- /task ---

--- task ---

To create an 8-by-8 grid of tiles, the offset placements need to be along the **y-axis**.

Change the value in the **Factor X** property to `0.000`. Change the value in the **Factor Y** property to `1.100`:

![In the Modifier Properties tab, the values of the Factor X and Y properties have been updated. In the 3D view, there are now two rows of eight tiles.](images/offset-y.png)

--- /task ---

--- task ---

Change the value in the **Count** property to `8`.

This creates eight rows of eight tiles:

![Eight rows of eight tiles. In the Modifier Properties tab, the Count property has a value of 8.](images/8by8tiles.png)

--- /task ---

--- task ---

Click on the **Array** drop-down menu arrow, then select **Apply**:

![The arrow highlighted and the Array drop-down menu open, with the first menu item 'Apply' highlighted.](images/apply-array1.png)

--- /task ---

--- save ---