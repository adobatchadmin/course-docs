Git Basics and .NET Website Assignment
Objective
To understand and practice the basics of Git, create a simple .NET website from scratch, initialize a local Git repository, and push the project to GitHub.

PART A: Installing Git

Task: Install Git on your machine.

Windows users: Download the installer from Git for Windows - Link https://git-scm.com/downloads
macOS users: Install using Homebrew: brew install git.
Linux users: Use the package manager for your distribution (e.g., apt-get install git for Ubuntu).

To Verify:

Run the command git --version in your terminal or command prompt.
Submission: Screenshot of the output.

PART B: Setting Up Git
Task: Configure Git with your personal details.

Commands:
 git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"

To Verify:

Run the command git config --list.
Submission: Screenshot showing your name and email configuration.


To Verify:

Run the command git config --list.
Submission: Screenshot showing your name and email configuration.

PART C: Create a Simple .NET Website
Task: Install the .NET SDK (if not already installed) from the .NET Download Page https://dotnet.microsoft.com/en-us/download .

Task: Generate a new .NET web application.

Command:

dotnet new webapp -o MyWebApp


To Verify:

Navigate to the MyWebApp directory.
Run the command dotnet run.
Access the site via a web browser at http://localhost:5000.
Submission: Screenshot of the running website.

PART D: Initialize a Local Git Repository
Task: Inside the MyWebApp directory in your terminal or command prompt, initialize a Git repository.

Commands:

git init
git add .
git commit -m "Initial commit"


To Verify:

Run the command git log.
Submission: Screenshot of the commit history.


To Verify:

Run the command git log.
Submission: Screenshot of the commit history.

PART E: Push the Project to GitHub
Task: Create a new repository on GitHub.

Task: Link your local repo to the GitHub repository and push.

Commands:

git remote add origin [URL_TO_YOUR_GITHUB_REPO]
git push -u origin master

To Verify:

Navigate to your repository on GitHub.
Submission: Link to your GitHub repository and screenshot of the files on GitHub.