# PLPBasicGitAssignment

**1. how to create repository in github**
a. In the upper-right corner of any page, select , then click New repository.
b. Type a short, memorable name for your repository. For example, "PLPBasicGitAssignment".
c. Optionally, add a description of your repository. For example, "My first repository on GitHub."
d. Choose a repository visibility either private or public.
e. Select Initialize this repository with a README.
f. Click Create repository. 


**2. Local Folder Setup:**
a. creating a new folder in my local machine (personally i choose desktop).
b. right click and choose new then new folder
c. give it a name of your choice "PLPBasicGitAssignment kelvin"
d. I opened terminal "git bash" and i navigated to the folder i had just created"


**3. Git initialization**
a. by using git bash I used command "git init" to initialize a new git repository in my local folder.

**4. How to make changes in the file created**
a. inside the file created create another file in This is an example of simple text. format and name it any name eg "hello kelvin"
b. there after commit changes by add command in git bash
c. "git add hello kelvin
d. then type the following command "git commit -m "Add hello kelvin.txt with a greeting"


**5. Connecting to GitHub:**
a. Open Git Bash.
b. Change the current working directory to your local project
c. Use the command "git remote add origin REMOTE-URL" ->To add the URL for the remote repository where your local repository will be pushed,(**Replace REMOTE-URL with the repository's full URL on GitHub**) 
d. To verify that you set the remote URL correctly, run the following command "git remote -v"
e. To push the changes in your local repository to GitHub.com, run the following command "git push origin main"