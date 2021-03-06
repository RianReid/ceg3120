# ceg3120

### Project 1

USE IN THE UBUNTU AWS

Goal: Create a script that, once run, will configure your server and user directory to your custom preferences. This script will be the only thing to run on a new system. Internal to the script should be any service restarts needed - a user should not need to do any additional action.
- For the VIM plugin, NERDTree https://github.com/preservim/nerdtree.git

### Project 1-2

Goal: This project will be using your script from Project 1 to create & resolve issues via GitHub
- Create issues associated with the feedback given on the rubric.
- Create a git usage guide called Git-Guide.md in the main folder of your repository
     
### Project 2-1

Goal: The primary deliverable for this project is a changelog that includes the components listed below. You may do this by using GitHub Projects in your class repository or by manually keeping track of changes. Since we will be building from this project, your log should include a date and/or time implemented. You may choose to break up the tasks into their own changelogs. I would get templating then check with me if you have concerns about your changelog. Changelog management includes:
- A record of changes made over time
- Justifications
- Resources used as a template for your installation / configuration
- Screenshot of the result

### Project 2-2

Goal: Your goal is to create a Cloud Formation template, a file that creates a VPC and the minimum servers so far 
- (one git server, one openldap server). 

The CEO has convinced a few developers to join in on the fun! Since the directory service isn't ready for deployment, you are going to write a script that creates users, groups, and gives those users access to certain places.

- Uses the users-script and users.txt files in the scripts direcrory. Script is run with ./users-script users.txt

### Project 2-3

Goal: Create a load balancer with HAProxy, and then implement continuous deployment (CD)

Part 1: 
- Stand up proxy server (HAProxy)
- Stand up two apache or nginx servers
- Place a different index.html page on each server
- Create a private / public key and put public key on each server (don't override the AWS key), also put private key on the proxy
- Security groups should be changed

Part 2: 
- For this part, your goal is to have a main site and update all (in this case, 2) webservers at once. You may use a simple template, such as index-main.html that is in the project folder, or something complex, such as a personal site or site created in another class. Just make sure you are familar enough that you can make simple changes to the site to test your hooks.
