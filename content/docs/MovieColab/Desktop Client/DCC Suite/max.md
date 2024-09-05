+++
title = 'Max'
date = 2024-01-19T13:26:29+05:30
draft = false
+++

Movie Collab Plugin docked as panel inside of 3DS Max.
![Alt text](/MovieCollab/DCC/max/plugin_max_01.png)

### _Step 0. Prerequiste:_
- Make sure the standalone app has been installed.
- Make sure you have already downloaded the [Movie Colab Dependencies](mc_dependencies) and copied it to `C:\Users\<user>\Documents\MovieColab`\
This is same for all the dcc so if you have downloaded and copied it you are good to go.

### _Step 1. Download:_ 
- Close Max if its running
- Download the release for maya and unzip it
- copy `Plugin_Max` folder to `C:\Users\<user>\Documents\MovieColab\Plugins`

### _Step 2. Setup:_
- Copy the `ENU` Folder to your 3DS Max `ENU` Directory inside of `AppData` which can be found at 
`C:\Users\<username>\AppData\Local\Autodesk\3dsMax\<version>- 64bit\ENU`
- To Load the MovieColab Workspace - Toolbar and Menubar: 
 
### _Step 3. Load workspace(Toolbar and Menubar):_
- MenuBar > Customize > Load Custom UI Schema
- Navigate to `Workspace` folder available inside of `Plugin_Max` folder
- Select `MovieColabWorkspace` and 3dsMax would prompt asking for a restart

You can fnd Movie Collab Toolset being shown in Menu as well as shelf.
![Alt text](/MovieCollab/DCC/max/max_shelf.png)