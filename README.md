# Auto Addon Updater - Blender Add-on

Automatically zip selected addon source path and reinstall it in just 1 click.

Select your add-on source folder path, and press "Update addon" button. It will zip and install it automatically.

Support for Blender 4.2 + (Only Extensions)

- Zip and install selected path automatically.
- Recent Addons list interface. Once you succesfully process an add-on it will show up in Recent Addons list, from there you can zip and reinstall it again with just 1 click.

## Why I created AAU?

For Blender Add-ons developers, the task to test each code change is kind of tedious.
After saving modified files, the folder must be compressed to a ZIP file, and then reinstalled in Blender. While now (Blender 4.2) we can drag and drop the zip into Blender directly, for a developer is a waste of time.

## How to use it?

1. Press "Select source path" button and select your add-on's path. 
2. A Info section appears, with the add-on name, the selected source path and the target zip file.
3. You can change the target file, by default it will create the zip in the same folder where Source path folder is in.
4. Press "Update selected addon" button to start the process.
5. In "Recent addons" list a new item is created with all the info. Just select the add-on you want, and press "Update addon" button to zip and reinstall it again.
6. "Recent addons" will show up after closing and opening Blender again, so you can start the process again without selecting source path again, with just 1 click.

Thats all!

## How to install this addon:

- Download the zip file.
- Open Blender and go to Edit - Preferences
- Go to Get Extensions Tab.
- Click the arrow next to "Repositories", press "Install from disk" button, and search for the downloaded zip file.
- Select it and press Install

Enjoy it!!!


