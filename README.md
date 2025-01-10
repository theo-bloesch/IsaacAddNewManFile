I use this urdf file:

[cobotta_pro_900.urdf](cobotta_pro_900/cobotta_pro_900.urdf)

 located at :

```/home/theobloesch/.local/share/ov/pkg/isaac-sim-4.2.0/extscache/omni.importer.urdf-1.14.1+106.0.0.lx64.r.cp310/data/urdf/robots/cobotta_pro_900```

that I copied in another folder easier to reach.

Then I followed the step provided in this tutorial:
https://docs.omniverse.nvidia.com/isaacsim/latest/advanced_tutorials/tutorial_advanced_adding_new_manipulator.html

1. copy the urdf assets (cobotta_pro_900.urdf, cobotta_pro_900_visualization and onrobot_rg6_visualization) under a new folder *URDF_Folder_Path/cobotta_pro_900*. These assets could be found at **/extscache/omni.importer.urdf-*/data/urdf/robots/cobotta_pro_900**
2. Launch Omniverse Isaac Sim using the launcher.
3. Open the **URDF Importer** through *Isaac Utils > Workflows > URDF Importer*
4. In the extension window, choose the URDF file under *Import > Input File*, check *Create Physics Scene* and *Fix Base Link*, choose the Joint Drive Type to be *Position*, and uncheck the *Parse Mimic Joint tag*.
5. Click on *Import* in the extension window.

Which gave me this usd file:

[cobotta_pro_900.usd](cobotta_pro_900.usd)

