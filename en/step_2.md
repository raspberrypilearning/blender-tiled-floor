## Create your first tile

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
In Blender, you can create 3D objects such as cubes. Cubes can be edited to create objects including dice, boxes, and tiles.
</div>
<div>
![A tile object with bevelled edges in Blender.](images/3D-tile.png){:width="300px"}
</div>
</div>

--- task ---

Open Blender. Click outside the **splash screen** to close it:

![The splash screen in Blender.](images/splash-screen.png)

A new Blender project always includes a **Cube** object. The cube has an orange outline to show it is the selected object:

![A screenshot of Blender with a 3D cube with an orange outline in the 3D view. The Cube object is also highlighted in the Scene Collection pane.](images/starter-cube.png)

--- /task ---

--- task ---

🔎 **Zoom in** and 🔄 **rotate** your view to see the cube clearly:

![The cube now appears larger in the 3D view.](images/zoomed-cube.png)

--- collapse ---
---
title: Use a mouse with a scroll wheel to zoom and rotate 
---

To navigate Blender using a computer mouse with a scroll wheel:
+ Press and hold the scroll wheel down and drag the mouse around to rotate the view
+ Use the scroll wheel to scroll forward and backward to zoom in and out of the view

![An animation showing the view rotating around the cube.](images/navigate-cube.gif)

--- /collapse ---

--- collapse ---
---
title: Use a mouse without a scroll wheel to zoom and rotate
---

If you do not have a computer mouse with a scroll wheel, you can use the navigation icons. 

Place the mouse over the **Zoom** or **Move** icon and the cursor will change to four arrows. 

Click and hold with the left mouse button and drag the mouse around to change the view.

To rotate the view, click and hold on the **Orbit** icon and drag the mouse around.

![An animation showing the navigation icons being used to zoom in and out and rotate the view around the cube.](images/navigate-mouse.gif)

--- /collapse ---

--- /task ---

--- task ---

Click on the **Object Properties** icon to open the Object Properties tab.

Go to the **Transform** settings and find **Scale**. Change the **Z** (up–down) axis property to `0.3`:

![A screenshot of Blender with the Object Properties tab open. The Object Properties icon is highlighted. It is an orange square with the corners highlighted. In the Object Properties tab, the Scale Z property is highlighted and the value is set to 0.300. In the 3D view, the 3D cube object now has a smaller height.](images/object-properties.png)

**Tip:** In the coordinate system used by Blender, the **z-axis** points up. You might have used another coordinate system; for example, in some software, such as Unity, the y-axis points up.

--- /task ---

### Add sloped edges with a Bevel modifier

--- task ---

Click on the **Modifier Properties** icon to open the Modifier Properties tab:

![A screenshot of Blender with the Modifier Properties tab open. The Modifier Properties icon is highlighted. It is a blue wrench.](images/modifier-properties.png)

**Tip:** The icons in Blender are very small. Hold your mouse cursor over them to see a tool tip with the name of the tool.

--- /task ---

--- task ---

Click on the **Add Modifier** drop-down menu, then choose **Bevel**:

![The Add Modifier drop-down menu open in the Modifier Properties tab, with 'Bevel' highlighted.](images/bevel-modifier.png)

**Notice:** 👀 The edges of the cube are now sloped:

![The cube with a bevel effect on all edges.](images/bevel-effect.png)

--- /task ---

### Create smoother sloped edges

--- task ---

Change the number of **Segments** to `20`. This gives a smoother sloped edge:

![In the Modifier Properties tab, the Segments property is highlighted and the number is set to 20. In the 3D view, the cube now has smoother sloped edges.](images/bevel-segments.png)

--- /task ---

--- task ---

Click on the **Bevel** drop-down menu arrow, then select **Apply**:

![The arrow highlighted and the Bevel drop-down menu open, with the first menu item 'Apply' highlighted.](images/apply-modifier.png)

**Notice:** 👀 The Bevel modifier has now disappeared from the Modifier Properties tab.

--- /task ---

--- task ---

Right-click on the 3D cube model, then select **Shade Smooth** to give your segments a smoother appearance: 

![The object right-click menu with 'Shade Smooth' highlighted.](images/smooth-shade.png)

**Debug:** If you do not see the **Shade Smooth** menu option, make sure you are in **Object Mode**: 

![The Mode drop-down menu open in the top left-hand corner of the editor, with 'Object Mode' highlighted.](images/object-mode.png)

--- /task ---

--- task ---

**Save** your project. Click on **File** > **Save As...**. Name your file `floor.blend`:

![The file save window with the name "floor.blend" entered.](images/blender-save-as.png)

**Tip:** To reopen a saved Blender project, you can click on **File** > **Open**.

--- /task ---