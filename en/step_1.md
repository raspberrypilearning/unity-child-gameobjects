In Unity, a parent GameObject can have **child GameObjects** that move, rotate, and scale with it. This is really useful for positioning the child objects in relation to their parent. A parent can have many child GameObjects, but a child can have only one parent:

![The Hierarchy window showing a Cube with two cylinder child GameObjects. In the Scene view, it shows this forms a section of wall that can be moved and rotated as one.](images/wall-panel.png)

Models can be added to a scene as child GameObjects by dragging them from the Project window and placing them underneath the parent GameObject in the Hierarchy window. The child GameObject will be indented in the Hierarchy window structure:

![The Hierarchy window with Rat model GameObject and the Shield model as a child GameObject of the Rat.](images/shield-child.png)

![The Scene view showing the Shield GameObject positioned with the Rat GameObject.](images/shield-scene.png)

You can also right-click on the parent GameObject and create a new GameObject from a 3D shape. The new 3D shape GameObject will automatically be added as a child GameObject:

![The Hierarchy window showing a Cube with its right-click menu extended and the 3D Object 'Sphere' highlighted.](images/right-click-child.png)
