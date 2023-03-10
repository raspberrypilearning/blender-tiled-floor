## Create your first tile

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
In Blender you can create 3D objects such as cubes. Cubes can be edited to create  objects including dice, boxes or tiles.
</div>
<div>
![An image of a single tile object with bevelled corners.](images/3D-tile.png){:width="300px"}
</div>
</div>

--- task ---

Open Blender then click outside the **splash screen**: 

![Splash screen popup.](images/splash-screen.png)

A new Blender project always includes a **Cube** object. The cube has an orange outline to show it is the selected object:

![A 3D cube shown in the Object view. The Cube object is also highlighted in the Scene Collection window.](images/starter-cube.png)

--- /task ---

--- task ---

🔎 **Zoom in** and 🔄 **rotate** your view to see the cube clearly:

![The starter cube now appears larger in the Blender window.](images/zoomed-cube.png)

--- collapse ---
---
title: Use a mouse with a scroll button to zoom and rotate 
---

To navigate Blender using a computer mouse with a middle scroll button:
+ Hold the middle-button down and drag the mouse around to rotate the view
+ Scroll the middle-button forward and backward to zoom in and out of the view

![An animation showing the view rotating around the cube.](images/navigate-cube.gif)

--- /collapse ---

--- collapse ---
---
title: Use a mouse without a scroll button to zoom and rotate
---

If you do not have a computer mouse with a middle-button you can use the navigation icons. 

Place the mouse over the **zoom** or **move** icons to see the cursor change to 4 arrows. 

Hold the left mouse button down then drag the mouse around to change the view. 

![An animation showing the navigation icons being used to zoom in and out and rotate around the cube.](images/navigate-mouse.gif)

--- /collapse ---

--- /task ---

--- task ---

Click on the 'Object properties' icon to open the Object properties pane. 

Goto the **Transform** settings and find **Scale**. Change the **Z** (up-down) axis property to `0.3`:

![A screen capture of the Blender editor. The Object properties icon is highlighted, it is an orange square with corners highlighted. In the Object properties window,  the Scale Z property is highlighted showing the number is '0.3'.](images/object-properties.png)

**Tip:** In the coordinates system used by Blender the **Z axis** points up. You might have used another coordinates system, some software such as Unity uses the Y axis to point up. 

--- /task ---

### Add sloped edges with a Bevel modifier

--- task ---

Click on the 'Modifier properties' icon to open the Modifier properties pane: 

![A screen capture of the Blender editor. The Modifier properties icon is highlighted, it is blue wrench.](images/modifier-properties.png)

**Tip:** The icons in Blender are very small. Hover over them with your mouse to see a tool tip with the name of the tool.

--- /task ---

--- task ---

Click on the 'Add modifier' dropdown then choose **Bevel**: 

![A screen capture of the Modifier properties pane with Bevel highlighted in the list of modifiers.](images/bevel-modifier.png)

**Notice:** 👀 The edges of the cube are now sloped:

![The 3D cube with a bevel effect on all edges.](images/bevel-effect.png)

--- /task ---

### Create smoother sloped edges

--- task ---

Change the number of segments to `20`. This gives a smoother sloped edge: 

![A screen capture of the 3D cube with smooth edges. The number in the Segments property is 20.](images/bevel-segments.png)

--- /task ---

--- task ---

Click on the 'Bevel' dropdown arrow and select **Apply**: 

![The Bevel dropdown expanded with top menu item `apply` highlighted.](images/apply-modifier.png)

**Notice:** 👀 The Bevel modifier has now disapeared from the Modifier pane.

--- /task ---

--- task ---

Right-click on the 3D cube model then select **Shade Smooth** to give your segments a smoother appearance: 

![The Bevel dropdown expanded with top menu item `apply` highlighted.](images/smooth-shade.png)

**Debug:** If you do not see the 'Shade Smooth' menu option, make sure you are in 'Object mode': 

![The mode dropdown expanded with `Object mode` highlighted.](images/object-mode.png)

--- /task ---

--- task ---

**Save** your project using 'File' -> 'Save As'. Name your file 'floor.blend': 

![File save window with the name floor dot blend.](images/blender-save-as.png)

**Tip:** You can reopen a saved Blender project using 'File' -> 'Open'. 

--- /task ---