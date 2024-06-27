# Basic-Git-And-GitHub-Workflow

Task 1: Repository Setup
1. GitHub Repository Creation:
Logged in to my GitHub account.
Created a new repository on GitHub named "Basic-Git-And-GitHub-Workflow".
Initialized it with a README file.

Task 2: Local Setup
2. Local Folder Setup:
Created a new folder on my local machine named "Basic Git and GitHub Workflow".

Opened a terminal and navigated to the created folder.

cd path/to/Basic Git and Github Workflow

3. Git Initialization:
Initialized a new Git repository in the local folder.


code
git init

4. Connecting to GitHub:
Linked the local repository to the GitHub repository created in Task 1.

code
git remote add origin https://github.com/AbbyGikunju/Basic-Git-And-GitHub-Workflow.git

Task 3: Making Changes
5. Create a File:
Inside the local folder, created a new text file named hello.txt.

Added a simple text message to the file.

code
echo "Hello, Git!" > hello.txt

6. Committing Changes:
Staged the changes.


code
git add hello.txt
Committed the changes.

code
git commit -m "Add hello.txt with a greeting"
Task 4: Pushing to GitHub

7. Pushing to GitHub:
Pushed the committed changes to the GitHub repository.

code
git push -u origin main
