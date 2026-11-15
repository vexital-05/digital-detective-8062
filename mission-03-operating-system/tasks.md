# MISSION 3 - Understand the operating system

## Task 3.1 - Explore your operating system

| Information explored | What it tells you | Your observation |
| --- | --- | --- |
| Operating system / system details | It tells you the operating system your computer is currently runnning on and the version of the same. It also shows the Kernel version of the operating system, the local time and the details of your processor such as its architecture | The command `uname -a` is used to show all this information on the terminal |
| Current account identity | It tells you which user is currently logged in | The command `whoami` is used to show the username on the terminal |
| Available and used storage | It shows all the disks and its partitions that are currently installed on your computer, its filesystem type, the available storage and also the used storage and where the particular partition is mounted on | The command `df -h` is used to display this information on the terminal |
| System activty snapshow | This command will show you the entire information of all the processes that are currently running on your computer which can be sorted either in an ascending or a descending order based on the CPU Usage, Time, Memory Usage, etc. | The command `top` is used to show this information on the terminal. We can hit `q`, to exit from the command. |

---

## Task 3.2 - Understand processes

#### A process can be defined as a program that is currently running on your commputer. The PID column when the command `top` or `htop` is run represents the _Process ID_ number. This is helpful to identify when we need to kill some process with the help of its PID. Some examples of processes that are currently running on my computer along with their PID are : Terminal - PID 32449; Code (Visual Studio Code) - PID 31679; Music (Apple Music) - PID 729; AirDrop - PID 24328.

---

## Task 3.3 - Understand paths and permissions

#### Absolute path can be defined as the complete path of a file/folder from the **root folder**, whereas the relative path can be defined as the path of a file/folder from the **current working directory**. For example, the absolute path of this file is `/Users/vexital05/Projects/digital-detective-8062/mission-03-operating-system/tasks.md`, meanwhile the relative path of this file when working in the digital-detective-8062 folder will be `digital-detective-8062/mission-03-operating-system/tasks.md`.

---

## Task 3.4 - Explain operating-system responsibilites

| OS Responsibility | Your explaination | Example |
| --- | --- | --- |
| Process Management | This is a core OS responsibility handling the creation, schedule, execution and termination of programs in memory such that the OS runs smoothly while being able to multitask | **Time slicing** is an example of process management |
| Memory Management | This repsonsibility of the operating system handles the RAM of the computer such that the processes have enough space on the RAM to run simultaneously. | **Caching** is an example of memory management |
| Device Management | To be able to recognize and ensure that the devices that are connected to the computer perform in the way they were designed and engineered to perform, this responsibility handles that. | **Managing device drivers** is an example of device management |
| File Management | The responsibility of the OS that organizes, stores and retrieves data on secondary storage devices like the SSD and HDD is called file management | **Saving files** is an example of file management | 
| User Interface / Shell | This repsonsibility acts as a bridge between the computer system and the human user such that the user can be able to control the system | **Graphical User Interface** is an example of this | 
| Security and Permissions | Not every file is supposed to be accessible to every user that uses the computer, this reponsibility is taken care by the operating system by catagorizing permissions for files and folders that are stored on the computer system | **File and folder permissions** such as read, write and execute are an example of this | 