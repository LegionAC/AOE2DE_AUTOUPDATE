A tool used for updating pirated AoE2DE copies to the latest released version.
Currently, the itch.io files online need to be updated by me manually, (this is subject to change in the future), so always keep in mind that updates may not be immediately posted.

#**HOW TO USE IT:**
1. Navigate to config.txt located in the config folder, inside you will see this: FileDestinationPath=
Directly after the =, place the path that you want the files to be copied to (the AoE2DE folder).
 Example: "FileDestinationPath=path/to/folder
3. Navigate to the update.bat file inside of the autoUpdate folder.
Execute the .bat file and answer any of the follow-up questions.
Should you encounter any issues/errors, make sure to create an issue on github and I will respond to it.

#**HOW IT WORKS:**
The functionality is quite simple, I manually update the AoE2DE files on itch.io, what the program actually does is replace any files with the same name but different data, or add any new files that have been created in the update.
Once this is done, it checks for any duplicates and then removes the older duplicate by checking which file is the same file as uploaded by me on itch.io.
It does this using butler (not created by me, created by itch.io) to pull the files off of itch.io.
Keep in mind, though, that any of the dlc's will not receive updates, or any dlc's that are added, be added to the pirated copy, as I do not own them, and only own the base legitimate copy of AoE2DE.
Should you encounter any errors throughout this process, please make sure to create an issue on github so that i can further debug/develop the program.
