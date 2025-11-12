Welcome to the Coding Club's Git Cheatsheet!

This repository is part of our hands-on introduction to Git and GitHub.

The goal is simple: learn the basics of collaborative development by adding your own contribution to this project.

🚀 Your Mission: Add Your Favorite Tip!

We're building a collaborative cheatsheet, and we need your help. Your mission is to add one useful item to the cheatsheet.md file. This can be:

Your favorite Git command

A useful coding resource (a website, a tool, a book)

A short coding tip or trick you've learned

🛠️ How to Contribute (The 7-Step Workflow)

Follow these steps to complete the activity. This is the same core workflow used in open-source projects all over the world!

Step 1: Fork this Repository

Click the "Fork" button in the top-right corner of this page. This will create a personal copy of this entire project in your own GitHub account.

Step 2: Clone Your Fork

Go to your forked repository (it will be at github.com/<YourUsername>/coding-club-git-cheatsheet). Click the green "<> Code" button and copy the URL.

Now, on your local machine, open your terminal (or Git Bash) and run:

git clone <paste-your-forked-repo-url-here>


This downloads your fork to your computer.

Step 3: Create a New Branch

Navigate into the new project folder:

cd coding-club-git-cheatsheet


Create a new branch to work on your changes. This keeps your work separate from the main project. Use a branch name like your-initials/my-tip.

git checkout -b your-name/my-tip


Step 4: Modify the File

Open the cheatsheet.md file in your favorite code editor (like VS Code).

Add your tip! Please create a new heading (using ###) for your entry, like this:

### [Your Name]'s Favorite Resource
My favorite resource is [link] because it helps with [...].


Save the file when you're done.

Step 5: Commit Your Changes

Go back to your terminal. First, add your changes to the "staging area":

git add cheatsheet.md


Next, "commit" those changes with a clear message describing what you did:

git commit -m "Adds [Your Name]'s coding tip"


Step 6: Push to Your Fork

Send your local commit up to your forked repository on GitHub:

git push origin your-name/my-tip


(You may have to replace your-name/my-tip with the exact branch name you created).

Step 7: Open a Pull Request (PR)

Go back to your fork on GitHub (github.com/<YourUsername>/coding-club-git-cheatsheet).

You should see a yellow banner with your branch name, asking you to "Compare & pull request". Click that button.

On the next page, give your PR a title (like "Adds [Your Name]'s tip") and click the "Create pull request" button.

🎉 You're Done!

Congratulations! You've just completed the full workflow for contributing to a collaborative project. We'll now review your PR and "merge" it into the main project.
