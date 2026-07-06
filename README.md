Objectives
This assignment introduces you to professional tools used by developers to track, save, and collaborate on code. You’ll learn Git version control and GitHub hosting by creating your own function journal and recording meaningful changes through Git commits.

Tasks
Create and configure a GitHub account and repository
Set up Git on your local machine
Track code changes using Git commits and messages
Push code to GitHub using the command line
Reflect on your learning using markdown files
Repository Setup
GitHub Repo Name: cs81-module3a-github

Add a short description
Choose public
Initialize with a README file
Git & GitHub Tutorial
Step 1: Install Git
Download Git from git-scm.com/downloads and follow installation instructions.

git --version
Step 2: Configure Git
git config --global user.name "Your Full Name"
git config --global user.email "your@email.com"
Step 3: Create GitHub Repo
Go to GitHub.com
Click “+” → “New repository”
Repo name: cs81-module3a-github
Add a description and README file
Step 4: Clone to Computer
git clone https://github.com/your-username/cs81-module3a-github.git
cd cs81-module3a-github
Step 5: Make Your First Commit
touch journal.js
Edit journal.js:

// Greet a user by name
function greet(name) {
  return "Hello, " + name + "!";
}
Then run:

git add journal.js
git commit -m "Add greet() function to journal"
git push
Assignment Requirements
Task	Details
GitHub Repo	cs81-module3a-github created and cloned
journal.js	Contains at least 5 unique functions
README.md	Describes each function’s purpose
REFLECTION.md	Learning experience summary
Git Commit History	Minimum of 3 meaningful commits
Commit Requirements
One new change per commit
A descriptive message (e.g., "Add isEven() function")
Reflection Prompts (REFLECTION.md)
What did you learn about using Git and GitHub?
What was most confusing or frustrating?
Why do you think developers use Git?
How might this help with larger projects in the future?
Submission
Submit your public GitHub link to cs81-module3a-github. Ensure your repo contains:

journal.js
README.md
REFLECTION.md
At least 3 commit entries
Need Help?
Git Book: git-scm.com/book/en/v2
