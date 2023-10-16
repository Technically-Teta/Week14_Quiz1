## Week 14 Quiz - Debugging, Git, & GitHub

You have just joined your favorite company and have been tasked with printing new data to a webpage. However, the existing files/directories are all jumbled up, and the code seems to have errors. Fix the bugs and sile structure. 

## Fixed File Commmands:

1. `git clone https://github.com/daaimah123/Week14_Quiz1.git` 

2. `rm -rf .git` --
3. `create new repo - Week14_Quiz - git init` on command line

4. in client gitignore  - `**\node_modules`   --node_modules are committed, remove them from repo on GitHub
5. in server gitignore  - `**\node_modules`   --node_modules are committed, remove them from repo on GitHub
6. `git mv client/server/ ./server`          --Correct the file architecture using command line/ Correct the server file’s directory by moving it to the appropriate directory
7.  - document errors you encountered and how you fixed them, ---  - server 8080 was already running so I did to this kill the server  -- sudo lsof -iTCP:8080 -sTCP:LISTEN
8.  - screenshot of the app's webpage:
  
    - 
      
<img width="699" alt="Screenshot 2023-10-16 at 11 18 16 AM" src="https://github.com/Technically-Teta/Week14_Quiz1/assets/52463043/ee503f86-4cf1-475b-9901-251b8afae9a9">


1. Debug the broken code so that it's working   ---- removed the typo from App.js
2. Correct the file architecture using command line
4. node_modules are committed, remove them from repo on GitHub
5. Correct the server file’s directory by moving it to the appropriate directory
6. Update README with
    - screenshot of the app's webpage, 
    - document errors you encountered and how you fixed them,
       
    - detail the git commands you used to remove the node_modules, and
    - detail the git commands you used to correct the file structure# Week14_Quiz1
