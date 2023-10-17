In Unity kan een bovenliggend GameObject **onderliggende GameObjects** hebben die meebewegen, roteren en schalen. Dit is echt handig voor het positioneren van de onderliggende (child) objecten ten opzichte van hun bovenliggende (parent) objecten. Een bovenliggend object kan veel onderliggende GameObjects hebben, maar een onderliggend object kan slechts één bovenliggend object hebben:

![Het Hierarchy venster met een Kubus met twee onderliggende cilinder GameObjects. De Scèneweergave toont dat dit een deel van de muur vormt die als één geheel wordt verplaatst en gedraaid.](images/wall-panel.png)

Modellen kunnen als onderliggend GameObjects aan een scène worden toegevoegd door ze vanuit het venster Project te slepen en ze onder het bovenliggende GameObject in het Hierarchy venster te plaatsen. Het onderliggende GameObject wordt ingesprongen in de structuur van het Hierarchy venster:

![De Hierarchy window met Rat-model GameObject en het Shield-model als een onderliggend GameObject van de Rat.](images/shield-child.png)

![De Scèneweergave met het Shield GameObject gepositioneerd met het Rat GameObject.](images/shield-scene.png)

Je kunt ook met de rechtermuisknop op het bovenliggende GameObject klikken en een nieuw GameObject maken vanuit een 3D-vorm. Het nieuwe 3D GameObject wordt automatisch toegevoegd als een onderliggend GameObject:

![Het Hierarchy venster toont een Kubus met het snelmenu en het 3D Object 'Sphere' gemarkeerd.](images/right-click-child.png)
