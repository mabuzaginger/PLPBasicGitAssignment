PLPBasicGitAssignment - Steps and Commands
Task 1: Repository Setup
1. GitHub Repository Creation
Log in to GitHub.
Create a new repository named PLPBasicGitAssignment.
Initialize it with a README file.
Task 2: Local Setup
2. Local Folder Setup
Create a new folder on your local machine:
bash
Copy code
mkdir PLPBasicGitAssignment
Navigate to the created folder:
bash
Copy code
cd PLPBasicGitAssignment
3. Git Initialization
Initialize a new Git repository in your local folder:
bash
Copy code
git init
Task 3: Connecting to GitHub
4. Connecting to GitHub
Link your local repository to the GitHub repository:
bash
Copy code
git remote add origin https://github.com/yourusername/PLPBasicGitAssignment.git
Task 4: Making Changes
5. Create a File
Create a new text file named hello.txt:
bash
Copy code
echo "Hello, Git!" > hello.txt
6. Committing Changes
Stage the changes:
bash
Copy code
git add hello.txt
Commit the changes:
bash
Copy code
git commit -m "Add hello.txt with a greeting"
Task 5: Pushing to GitHub
7. Pushing to GitHub
Push the committed changes to your GitHub repository:
bash
Copy code
git push -u origin main
Task 6: Verification
8. Verify on GitHub
Visit the GitHub repository in a web browser to verify that the hello.txt file and commit message are visible.
