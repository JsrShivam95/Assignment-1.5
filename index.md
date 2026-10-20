Step 1: Create a New Public Repository on GitHub
Go to GitHub and log in to your account.

In the top-right corner, click the + icon and select New repository.

Name your repository web-development-practice (or matching your local folder name).

Select Public.

Important: Do not initialize the repository with a README, .gitignore, or license (since you already have a local git repository with existing commits).

Click Create repository.

Step 2: Connect Your Local Repository to GitHub
Open your terminal inside your local project folder (web-development-practice) and run the commands provided on your GitHub repository page (replace your-username with your actual GitHub username):

Bash
git remote add origin https://github.com/your-username/web-development-practice.git
git branch -M main
Step 3: Push Your Files to GitHub
Push your existing commits up to your remote GitHub repository:

Bash
git push -u origin main
Note: If prompted, log in with your GitHub credentials or a Personal Access Token.

Step 4: Add a New File and Push the Second Commit
To fulfill the requirement of adding a new file and making/pushing a subsequent commit:

Create a README.md file in your project folder (or add any new file like about.html).

Run these terminal commands to stage, commit, and push the new file:

Bash
git status
git add README.md
git commit -m "docs: add README.md file with project description"
git push
Step 5: Verify on GitHub
Refresh your repository page on GitHub.

Verify that all your files (index.html, style.css, script.js, and README.md) are visible, and check the Commits tab to confirm your commit history.

🔗 Submission Requirement:
Copy and share your public repository link for your assignment submission:

[https://github.com/your-username/web-development-practice](https://github.com/your-username/web-development-practice)