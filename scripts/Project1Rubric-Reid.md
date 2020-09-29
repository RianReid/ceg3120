# Project 1:

## Score:
22.8 / 25

### Repository Layout (4 points total): 4 / 4
* Repo created & instructor added: 1 pt
* Resources page includes 1 or more sites / credits to project success: 1 pt
    * TODO: make this just a .md file and take out of resources folder
* README page includes description / usage of Project 1 script: 1 pt
* Script folder contains at least a script for the project: 1 pt

### Repository usage requirements (2 points total): 2 / 2
* Instructor can clone the repository and run the script: 1 pt
* At least one commit / push was made to the repository: 1 pt

### Script functionality requirements (19 points total): 16.8 / 19
1. PATH requirement (4 points total): 4 / 4
* Adds the path to the script(s) to the PATH via the `.profile`: 1 pt
* Checks an existence condition (2 pt) of either:
    * checking if command exists
    * checking if script directory is in path / exists
* Outputs message to user to `source .profile`: 1 pt

2. `motd` requirement (2 points total): 2 / 2
* Removes one or more default messages: 1 pt
* Adds one or more custom messages: 1 pt

3. `vim` requirement minimum expectations (3 pts total): 3 / 3
* Modifies `.vimrc`: 1 pt
* Adds plugin directory (2 pts) by either:
    * Having the plugin in the repository and copying it for installation
    * Downloading / cloning the plugin to its installation location

4. `alias` requirement (6 points total): 6 / 6
* Adds aliases to `.bashrc`: 1 pt
* Checks existence of aliases before appending to `.bashrc`: 2 pts
* Aliases to add: 
    * `alias` called `aws-ssh` that contains command to ssh to system: 1 pt
    * second `alias` of choice: 1 pt
* Output message to user to `source .bashrc`: 1 pt

5. help option requirement (2 points total): 1.8 / 2
TODO: for help alias, do your command -help.  Otherwise it will only match for -help typed  
TODO: likely also need echo in front of your print statement
* Running command with at least one of `help` / `-help` / `h` / `-h` does a thing: 1 pt
* Output message of what the script does 1 pt

6. All requirements above are neatly wrapped up in functions: 0 / 2
TODO: need function wrappers

### Extra Credit (10%)
* Scrape a daily message off a website for the `motd`
* Create a user interface with tput
   * https://ryanstutorials.net/bash-scripting-tutorial/bash-user-interface.php
* Create a menu for the script
   * https://www.shellscript.sh/tips/getopts/ 
   * Minimum of –i (dash i) for install & -h (dash h) for help / usage