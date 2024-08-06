1. Initialize Git in Your Project:
  1.1. First, ensure you are in your project directory: cd path/to/your/project
  1.2. git init
2. Create a GitHub Repository
	2.1.	Go to GitHub and log in to your account.
	2.2.	Click on the “New” button to create a new repository.
	2.3.	Enter a repository name, description (optional), and choose the visibility (public or private).
	2.4.	Click “Create repository”.
3. Link Your Local Repository to GitHub
   git remote add origin https://github.com/yourusername/your-repo-name.git
4. Add and Commit Your Initial Code
  4.1. Add all your files to the staging area: git add .
  4.2. Commit the changes: git commit -m "Initial commit"
  4.3. Push the changes to GitHub: git push -u origin main
5. Configure VSCode for Git. Ensure you have the Git extension installed in VSCode. This extension usually comes pre-installed, but you can 
   verify by going to the Extensions view (Ctrl+Shift+X) and searching for “Git”.
6. Check-In/Check-Out Workflow in VSCode
  6.1. Cloning the Repository: git clone https://github.com/yourusername/your-repo-name.git
  6.2. Working on a Branch: git checkout -b feature-branch-name
  6.3. Make your changes, then add and commit them:
       git add .
       git commit -m "Your commit message"
  6.4. Push the branch to GitHub: git push origin feature-branch-name
7. Opening a Pull Request
  7.1.	Go to the GitHub repository in your browser.
	7.2.	You will see a prompt to open a pull request for your recently pushed branch. Click on it, or navigate to the “Pull requests” tab 
        and click “New pull request”.
	7.3.	Compare your branch with the master (or main) branch and create the pull request.
	7.4.	Provide a meaningful description of the changes you have made and submit the pull request.

8. 
    
