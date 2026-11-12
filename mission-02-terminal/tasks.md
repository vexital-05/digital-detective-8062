# MISSION 2 - Become comfortable with the Terminal

## Task 2.1 – Explore basic Terminal operations

| Operation | Command name | What it does? | Observations |
| --- | --- | --- | --- |
| Display Current-Directory	| pwd | Displays where the current pointer is located | This command shows the entire path starting from the root folder to the current working directory |
| Directory Listing | ls | Lists all the files and folders that are present in the current working directory | This command lists only the files and folders present in the current directory, not its child directories |
| Detailed Listing | ls -l | Lists all the files and folders in a detailed manner | This command shows the permissions of that folder/file, its owner, the size of the folder and the date and time of modification |
| Change Directory | cd | Changes the location of the pointer to the path provided as an argument | It requires atleast 1 argument to work |
| Create Directory | mkdir | Create a directory where the pointer is located | The name of the directory is taken as an argument |
| Create empty file | touch | Creates an empty file where the pointer is located | The name of the file is taken as an argument along with its extension |
| Copy file | cp | Copies the file from one location to another without deleting it from the original location | The source path and the destination path are two arguments that are required for this command to work successfully |
| Move / Rename file | mv | Moves the file from one location to another or changes the name of the file | The source path and the destination path are two arguments that are required for this command to work successfully (For renaming, just set the new name of the file along with its extension as the destination path) | 
| Display file contents | cat | Displays the contents of the file in the terminal window itself | It takes the path of the file that is supposed to be displayed as an argument |

---

## Task 2.2 - Practice file changes safely

#### 1. Replacing the file's contents will delete all the content thats already existing in the file and replace it with the new text thats supposed to be added to the file. Adding text to the end of the file will keep the content of the files and add the new text below the already existing text in the file.

#### 2. Copying a file will not delete the file from the source location after the operation is done whereas moving the file will indeed delete the file from the source location.

#### 3. The current-directory display provides the entire path starting from the root folder to the current working directory.

#### 4. The directory-listing operation is useful because in certain commands you need to enter the name of the file as an argument, and to state that, we need to know the exact name of the file or else the command will fail to run. Also its important to know what all files are present in your working directory.

---

## Task 2.3 - Understand flags and pipes

#### A flag or option's main objective is to modify how the command works. For example taking the command ls. Some of its flags are -l, -a, -R and -lh. The base command ls will only display the non-hidden files and folders present in the current directory. The -l flag will display the same files and folders with detailed information, i.e. its size, permissions and the owner of the file/folder. The -a flag will display all the files and folders along with the hidden files/folders that are present in the current directory. The -R flag will recursively show all the files and folders along with the files and folders of its child folders. The -lh flag will show display an information chart similar to the -l flag but the sizes will be human readable. These tags can be also be comined with one another by writing the flags together.

#### The pipe symbol is a special operator that is mainly used in bash for sharing the output of one command to another. For example, the command ls -l | grep ".txt" will first perform the command on the left that is list all the files in a detailed format and thereby forward the output of that command to the command on the right, that is the grep command, which will output the lines which contain the .txt line, thereby creating a flow that works unidirectionally from left to right.

---

## Task 2.4 - Understand package managers

#### Package managers are useful because they act as a singular place where you can install multiple tools and utilities directly from your terminal instead of going to the individual tool/utility's website. It also checks if the dependencies of that particular tool is installed and if not installed, it will prompt to install them for the tool to work correctly and manages the updates of the tool.

#### If a package manager is not installed on the device, there won't be much of a difference in the tools that already exist, but the installing of tools will be a manual approach. The user will be responsible to find and install the .dmg file of the tool and thereby also install the dependencies of that tool.