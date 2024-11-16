### GIT CONFIG 
it links over account from git to github 

### MKDIR 
creates a new folder in the current repo

### CD
open a given folder in the current repository 

### GIT INIT 
 initialize our local folder into repo 

 ### ECHO 
 it makes a new file which we want with a line that we can add while creating it 

 ### GIT ADD 
 it adds the change in staging area where it is not changed on the github repo but is complete 

 ### GIT COMMIT 
 it updates the changes in the staging area to the git hub repo online 

 ### GIT STATUS 
 it compares the both the local and the github repo and tell us which file is different and which file is left to update 

 ### 


# Git Task Commands and Explanations

## Task 1: Install and Configure Git

1. **Set username globally:**
   ```bash
   git config --global user.name "Your Name"
   ```
   Sets the global username for all your Git commits.

2. **Set email globally:**
   ```bash
   git config --global user.email "your-email@example.com"
   ```
   Sets the global email address for all your Git commits.

3. **View Git configuration:**
   ```bash
   git config --list
   ```
   Displays all the current Git configuration settings.

---

## Task 2: Initialize a Repository

1. **Create a new project folder:**
   ```bash
   mkdir MyProject
   ```
   Creates a new directory called `MyProject`.

2. **Navigate to the project folder:**
   ```bash
   cd MyProject
   ```
   Changes the current directory to `MyProject`.

3. **Initialize Git repository:**
   ```bash
   git init
   ```
   Converts the directory into a Git repository by adding a hidden `.git` folder.

---

## Task 3: Create a File and Make Multiple Commits

1. **Create a new file with content:**
   ```bash
   echo "My First Project" > README.md
   ```
   Creates a `README.md` file with the text "My First Project."

2. **Stage the file:**
   ```bash
   git add README.md
   ```
   Adds `README.md` to the staging area.

3. **Commit the file:**
   ```bash
   git commit -m "Initial commit: Added README.md"
   ```
   Records the changes to the repository with a commit message.

4. **Modify the file:**
   ```bash
   echo "Added a description" >> README.md
   ```
   Appends "Added a description" to `README.md`.

5. **Stage the modified file:**
   ```bash
   git add README.md
   ```
   Prepares the modified file for the next commit.

6. **Commit the changes:**
   ```bash
   git commit -m "Updated README with a description"
   ```
   Saves the changes with a message explaining the update.

---

## Task 4: Check Status and Log

1. **Check repository status:**
   ```bash
   git status
   ```
   Shows the status of the working directory and staging area.

2. **View commit history:**
   ```bash
   git log --oneline --graph --decorate
   ```
   Displays a compact, detailed commit history with branch and graph information.

---

## Task 5: Create and Clone a Repository

1. **Clone a repository:**
   ```bash
   git clone http://codinggita.com/example-repo
   ```
   Downloads a Git repository to your local machine.

---

## Task 6: Understanding the Git Workflow

1. **Create a workflow file:**
   ```bash
   echo "Workflow example" > workflow.md
   ```
   Creates a file `workflow.md` with the text "Workflow example."

2. **Stage the file:**
   ```bash
   git add workflow.md
   ```
   Adds `workflow.md` to the staging area.

3. **Commit the file:**
   ```bash
   git commit -m "Added workflow example"
   ```
   Saves the changes to the repository with a description.

---
