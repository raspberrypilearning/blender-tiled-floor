## Make a tiled floor

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
In Blender you can quickly create multiple copies of an object and place them in a pattern.
</div>
<div>
![](images/tiled-floor.png){:width="300px"}
</div>
</div>

### Create one row of 8 tiles

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
An <span style="color: #0faeb0">**array modifier**</span> creates copies of an object that can be placed at a distance to create a pattern of repetative objects. An Architect could use an array modifier to create a staircase for a home from just one step. Or when designing a model for an office building they could use an array modifier to place trees along a path.

![A highlgihted stair object that has been duplicated and offset to create a staircase.](images/stair-array.png){:width="300px"}

</p>

--- task ---

Click on the ‘Add modifier’ dropdown then choose **Array**:

![The modifier menu with Array highlighted.](images/array-modifier.png)

The Array modifier automatically creates a second tile.

**Tip:** you might need to zoom out to see both tiles:

![Two tiles side by side. In the modifier pane the count is '2'.](images/two-tiles.png)

--- /task ---

--- task ---

Change the value in the **Count** property to `8`. 

This creates a row of 8 tiles side by side:

![Eight tiles side by side. In the modifier pane the count is '8'.](images/eight-tiles.png)

--- /task ---

--- task ---

The tiles are offset by `1.000` this means they are placed next to each other with no gap. 

Change the value in the **Factor X** property to `1.100` to increase the offset placement distance and create a small gap between tiles:

![In the modifier pane the Factor X property is highlighted showing '1.100' the tiles have a small gap between them in the row.](images/offset-tiles.png)

--- /task ---

--- task ---

Click on the Array dropdown arrow and select **Apply**: 

![The Array dropdown expanded with top menu item `apply` highlighted.](images/apply-array1.png)

--- /task ---

### Create 8 rows of 8 tiles

--- task ---

Click on the ‘Add modifier’ dropdown then choose **Array** to create a second array modifier:

![The modifier menu with Array highlighted.](images/array-modifier.png)

The Array modifier automatically creates a second row of 8 tiles that are also offset on the X axis.

**Tip:** you can see where the second row starts because it has an offset of `1.000` so there is no gap:

![Two tiles side by side. In the modifier pane the count is '2'.](images/two-rows.png)

--- /task ---

--- task ---

To create an 8 by 8 grid of tiles, the offset placements needs to be along the **Y axis**. 

Change the value in the **Factor X** property to `0.000`. Change the **Factor Y** property value to `1.100`:

![The offest values in the Array modifier have been updated and two rows of 8 objects have been created.](images/offset-y.png)

--- /task ---

--- task ---

Change the value in the **Count** property to `8`. 

This creates 8 row of 8 tiles:

![Eight rows of eight tiles. In the modifier pane the count is '8'.](images/8by8tiles.png)

--- /task ---

--- task ---

Click on the Array dropdown arrow and select **Apply**: 

![The Array dropdown expanded with top menu item `apply` highlighted.](images/apply-array1.png)

--- /task ---

--- save ---