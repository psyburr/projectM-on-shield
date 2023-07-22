# projectM-on-shield

_A collection of projectM presets that I find work well enough in the Kodi addon for Android devices, and more specifically the Nvidia SHIELD TV._

---

## Directions for use
- Drop this repository right into the root of your SHIELD shared storage directory. This will be the share name 'internal' if accessing via SMB/Samba. On the device itself the full path is '/storage/emulated/0' but can also be accessed via symlink that is created by Android at '/sdcard' no matter what storage you may have.
-- _I personally keep a "Kodi" sub-directory in /sdcard for a variety of user controlled type files relevant to kodi that I do not want overwritten or even touched by anything within Kodi. This repo has been structured for easy installation by just copying its contents and allowing all directories to be merged and finally, overwriting the existing settings.xml file. That is the only overwrite that is done and all files copied are nested in their own new directories so as not to conflict with the addon._
- In the visualization options of the ProjectM addon, set the 'Preset Pack' option to 'User Defined Preset Folder' and navigate to where you copied the repo contents to for the second option.
-- _The defaults have been changed in the settings.xml file to automatically select this directory when acceasing the options menu (easily access it by pressing 'v' on your keyboard while visualizer is running and focused, or addon settings menus)_
- DONE :)
