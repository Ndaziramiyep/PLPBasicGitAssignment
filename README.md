# PLPBasicGitAssignment

Hello, Git!

<h3>Steps to Upload a Repository to GitHub from Local</h3>
This guide outlines the steps and commands to upload a local repository to GitHub.

Prerequisites
Install Git: Ensure Git is installed on your local machine. You can download and install it from git-scm.com.
GitHub Account: Make sure you have a GitHub account. Sign up at github.com.

<h3>Steps</h3>
Create a Repository on GitHub:

1. Go to GitHub.

Click on the "+" icon in the top right corner and select "New repository".
Enter a repository name and description (optional).
Choose to make the repository public or private.
Click "Create repository".

2. Initialize a Local Repository:

Open your terminal or command prompt and navigate to your project directory. Run the following commands:

git init

3. Add Files to the Repository:
Add the files you want to include in your repository:

git add .

4. Commit Changes:
Commit the files with a descriptive message:

git commit -m "Initial commit"

5. Add Remote Repository:

Link your local repository to the remote repository you created on GitHub. 
Replace YOUR-USERNAME with your GitHub username and YOUR-REPOSITORY with the name of your GitHub repository:

git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git


6. Push Changes to GitHub:
Push your local repository to GitHub:

git push origin main

