## Create a basic tile

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Use the **cube** object to create a basic tile shape.
</div>
<div>
Image, gif or video showing what they will achieve by the end of the step. ![](images/image.png){:width="300px"}
</div>
</div>

--- task ---

Open Blender. Click outside the **splash screen** to close it. 

![Splash screen popup.](images/blender-first.png)

A **Cube** object has been created for you. The cube has an orange border to show it is the selected object.

![A 3D cube shown in the Object view. The Cube object is also highlighted in the Scene Collection window.](images/starter-cube.png)

--- /task ---

--- task ---

Zoom into your cube so that it 

**Change** your view to see the cube from different angles and distances. Find a view you are happy with. 

--- collapse ---
---
title: Changing your view in Blender
---

**Tip:** To navigate Blender using a computer mouse with a middle scroll button:
+ Hold the middle-button down and drag the mouse around to rotate the view
+ Scroll the middle-button forward and backward to zoom in and out of the view

![An animation showing the view rotating around the cube.](images/navigate-cube.gif)

**Tip:** If you do not have a computer mouse with a middle-button you can use the navigation icons. Place the mouse over the **zoom** or **move** icons to see the cursor change to 4 arrows. Hold the left mouse button down then drag the mouse around to change the view. 

![An animation showing the navigation icons being used to zoom in and out and rotate around the cube.](images/navigate-mouse.gif)

--- /collapse ---

--- /task ---

--- task ---

Click on the 'Object properties' icon to open the Object properties pane. 

Within the **Transform** settings, find **Scale** and change the Z (up-down) axis property to `0.3`:

![A screen capture of the Blender editor. The Object properties icon is highlighted, it is an orange square with corners highlighted. In the Object properties window,  the Scale Z property is highlighted showing the number is '0.3'.](images/object-properties.png)

**Tip:** In the coordinates system used by Blender the **Z axis** points up. You might have used other software such as Unity that uses the Y axis to point up. 

--- /task ---

--- task ---

Click on the 'Modifier properties' icon to open the Modifier properties pane. 

![A screen capture of the Blender editor. The Modifier properties icon is highlighted, it is blue wrench.](images/modifier-properties.png)

--- /task ---

--- task ---

Click on the 'Add modifier' dropdown then choose **Bevel**. 

![A screen capture of the Modifier properties pane with Bevel highlighted in the list of modifiers.](images/bevel-modifier.png)

**Notice:** The edges of the cube now have a bevel effect.

![The 3D cube with a bevel effect on all edges.](images/bevel-effect.png)

--- /task ---

--- task ---

Change the number of segments to `20`. This gives a smoother edge. 

![A screen capture of the 3D cube with smooth edges. The number in the Segments property is 20.](images/bevel-segments.png)

--- /task ---

--- task ---

Click on the Bevel dropdown arrow and select **Apply** 

--- /task ---

--- task ---

**Save** your project using 'File' -> 'Save As'. Name your file 'floor.blend'. 

![File save window with the name floor dot blend.](images/blender-save-as.png)

--- /task ---

**Tip:** You can reopen an existing Blender project using 'File' -> 'Open'. 