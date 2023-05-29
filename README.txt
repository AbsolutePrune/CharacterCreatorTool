READ ME

SETUP:
Download the zip file from the drive link
Extract the zip and place the four folders inside your projects package folder
(you can open the package folder by right clicking packages in the unity inspector -> show in explorer)
Return to unity which should update its package list
You can choose to use the example scene in Packages>CharactorCreator>PackageResources>Scenes>samplescene
or
You can create a character by making a gameobject with rigidbody + animator + characterscript components
Give the gameobject a camera as a child and attach the camera script to the camera

ABILITIES:
When creating an ability the ability window will only extend if you select a valid ability these are in:
Packages>CharactorCreator>Runtime>Scripts>AbilityScripts
The list of valid abilities is:
Primary Fire
Shield
Dash 
Healthpack

If you use the projectile primaryfire make sure that whatever you use for the bullet has the bullet script
attached. The bullet prefab in the package comes with this by default but can be applied to similar gameobjects


BUGS/ERRORS
Creating, inspecting and then destroying a gun causes some errors to appear in the console logs which only
go away after restarting the project, these errors do not affect functionality but can be annoying if they 
build up

When destroying a gun use the destroy gun button associated with that gun as deleting it manually in the hierarchy 
does not update the script which will then error trying to access the deleted gameobject