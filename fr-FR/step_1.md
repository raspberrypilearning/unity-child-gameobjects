In Unity, a parent GameObject can have **child GameObjects** that move, rotate, and scale with it. This is really useful for positioning the child objects in relation to their parent. A parent can have many child GameObjects, but a child can have only one parent:

![La fenêtre Hierarchy montre un Cube avec deux GameObjects cylindriques enfants. In the Scene view, it shows this forms a section of wall that can be moved and rotated as one.](images/wall-panel.png)

Les modèles peuvent être ajoutés à une scène en tant que GameObjects enfants en les faisant glisser depuis la fenêtre Project et en les plaçant sous le GameObject parent dans la fenêtre Hierarchy. Le GameObject enfant sera indenté dans la structure de la fenêtre Hierarchy :

![The Hierarchy window with Rat model GameObject and the Shield model as a child GameObject of the Rat.](images/shield-child.png)

![The Scene view showing the Shield GameObject positioned with the Rat GameObject.](images/shield-scene.png)

Tu peux aussi faire un clic droit sur le GameObject parent et créer un nouveau GameObject à partir d'une forme 3D. Le nouveau GameObject de forme 3D sera automatiquement ajouté en tant que GameObject enfant :

![The Hierarchy window showing a Cube with its right-click menu extended and the 3D Object 'Sphere' highlighted.](images/right-click-child.png)
