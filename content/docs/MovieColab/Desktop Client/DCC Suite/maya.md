+++
title = 'Maya'
date = 2024-01-19T13:26:29+05:30
draft = false
+++

Movie Collab Plugin docked as panel inside of Maya.
![Alt text](/MovieCollab/DCC/maya/plugin_maya_01.png)

## Installation Process

### _Step 0. Prerequiste:_
- Make sure the standalone app has been installed.
- Make sure you have already downloaded the [Movie Colab Dependencies](mc_dependencies) and copied it to `C:\Users\<user>\Documents\MovieColab`\
This is same for all the dcc so if you have downloaded and copied it you are good to go.

### _Step 1. Download:_ 
- Close Maya if its running
- Download the release for maya and unzip it
- copy `Plugin_Maya` folder to `C:\Users\<user>\Documents\MovieColab\Plugins``

### _Step 2. Setup:_
Copy the `userSetup.py` to startup folder inside of your maya's preference folder under `script` folder.
`C:\Users\<user>\Documents\maya\<version>\scripts`
 
### _Step 3. Intialize (Every Time):_
run `import moviecolab` this in python bar in maya which is present at the bottom

You can find Movie Collab Shelf and Movie Collab Menu bar loaded at the top. 
![Alt text](/MovieCollab/DCC/maya/maya_shelf.png)

{{< callout type="info" >}}
The Above step ie, Step 3. has to be repeated everytime when maya opens.
We are working to automate this step with a future release. 
{{< /callout >}}

When you open the ShotPathSubmitter or AssetPathSubmitter for the first time; It would take couple of seconds to initialize and may feel unresponsive.

## TroubleShoot
- Inside maya: In windows > settings/preferences > preferences, in the security section, check if execute userSetup.py is enabled.