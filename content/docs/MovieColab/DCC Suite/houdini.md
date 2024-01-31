+++
title = 'Houdini'
date = 2024-01-19T13:26:29+05:30
draft = false
+++
Movie Collab Plugin can be opened as pane inside of houdini
![Alt text](/MovieCollab/DCC/houdini/plugin_houdini_01.png)

## Installation Process

### _Step 0. Prerequiste:_
- Make sure the standalone app has been installed.
- Make sure you have already downloaded the [Movie Colab Dependencies](mc_dependencies) and copied it to `C:\Users\<user>\Documents\MovieColab`\
This is same for all the dcc so if you have downloaded and copied it you are good to go.

### _Step 1. Download:_ 
- Close Houdini if its running
- Download the release for houdini and unzip it
- copy `Plugin_Houdini` folder to `C:\Users\<user>\Documents\MovieColab\Plugins`

### _Step 2. Setup:_
- Copy `MovieCollabShelf` folder to your houdini's preference folder under `toolbar` at
`c:/Users/<username>/Documents/houdini20.0/toolbar/`
- Copy `MovieCollab.pypanel` file to your houdini's prefernce folder under `pythonpanel`
`c:/Users/<username>/Documents/houdini20.0/python_panels/`
- TODO [STARTUP SCRIPT]

### _Step 3: Initialize:_
- Add Movie Colab Tab to the shelf tray
![Alt text](/MovieCollab/DCC/houdini/add_shelf.png)
![Alt text](/MovieCollab/DCC/houdini/houdini_shelf.png)

- You can also open Movie Colab inside a panel in houdini. Refer screenshot bellow
![Alt text](/MovieCollab/DCC/houdini/add_panel.png)
