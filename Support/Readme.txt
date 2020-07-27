Generic Module Library Documentation (Last Updated: December 4th 2019)

To create a new module, 
1. Open LabVIEW and save a new LabVIEW project. 
2. Once the LabVIEW project has been saved on disk, add the Generic Module Library.lvlib to your project.
(It is recommended to first pull down the Generic Module Library repository on to your PC and copy the files from this repository into your projects location).
3. Once the library is added to the project, right click on the "Add_Module.vi" and select "Run". 
4. LabVIEW will ask you to give your new module a name and then will create your module and add it to your saved project. 
5. Expand your new module .lvlib in your LabVIEW project explorer and find the class named "Rename.lvclass".
6. Right click "Rename.lvclass" and select Rename. 
7. Give the module class a name that reflects the name of the module you created in step 4.
8. (Optional/Recommended) Change the .lvlib template icon to reflect the name of your new module and apply the new icon template to all files in the library.
9. (Optional/Recommended) Change the .lvclass template icon to reflect the name of your new module and apply the new icon template to all files in the class.

December 20th 2019:
Fixed an issue with the Command Template.vit and the Broadcast Template.vit. Needed to add proper clusters back to these VIs after a few small changes.
Errors at start are shown to the user. Also added a prompt when closing panel to indicate that the module would stop as well.

December 4th 2019:
This is the first release of the Generic Module Library.
This library serves as a starting point for LabVIEW module development. It was developed in LabVIEW 2017 but can be saved for previous version back to LabVIEW 2015 SP1.
