# ECE344-Shell-Commands
Shell commands for the lazy ECE344 student

## Setup
1. Copy the bin directory into your user directory.
2. Add the bin directory to your path. 
3. Backup your .cshrc file. Next, open the .cshrc file and paste the following 2 lines:
```
#Shell Scripts:
set path = ( ~/bin $path)
```
4. Logout and login once more.
5. Test that the shell commands work. Open a terminal and enter `suhayb344`.
   * If you encounter an permissions denied error, give yourself execution rights by the following:
   `chmod -R 700 bin`
6. This should display an output of all the available shell commands, and how to use them. 
7. Open VSCode and create a new build task:
   1. Click 'Configure Tasks...' from the 'Terminal' menu.
   2. Select 'Create tasks.json file from template entry' from the dropdown menu.
   3. Since we want to write our own custom task, select 'Others' from the list.
   4. This should open a pre-made `Tasks.json` file. Replace its contents with the one provided in this repo.
   5. Notice the value `ASST3` as the argument to various commands. Replace that value with the current assignment #. This is case-sensitive!
8. Now you should be able to directly click `Ctrl+Shift+B` to run the default build task (currently set to 'Build OS'). You can change the default build task to any task you wish by changing the 'isDefault' key to a 'true' value.
9. That's it.



For more information: https://code.visualstudio.com/docs/editor/tasks
