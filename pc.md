## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? Git is a distributed version control system (VCS) designed for tracking changes in source code during software development.
2. What is the difference between Git and GitHub? GitHub is a web-based Git repository hosting service that builds upon Git’s functionality.
3. Why do we create a branch? Isolate development work: Branches allow you to work on new features, bug fixes, or experiments without affecting the main codebase in the main branch 
4. What is the purpose of a Pull Request?  propose a set of changes made to the codebase by a developer. These changes are typically developed in a separate branch, isolated from the main codebase.
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.  git  CHECKOUT
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do? Use git fetch to stay updated on remote changes without modifying your local branch.
Use git merge to carefully integrate changes from a specific branch into your current branch.
Use git pull (cautiously) for convenience when you want to fetch updates and immediately merge them into your current branch.
7. What is a merge conflict? 


Two developers modify the same lines of code in different branches without knowing about each other's changes.
One developer deletes a file while another developer modifies the same file in another branch.
Changes made in one branch might introduce formatting or style inconsistencies compared to the other branch.
8. How do you resolve a merge conflict?
Resolving a merge conflict involves a few steps:

Identify the conflicting files: Git will typically list the files with conflicts and mark the conflicting sections with special markers like <<<<<<<, =======, and >>>>>>>.
Open the conflicted files in a text editor and examine the conflicting sections.
Manually edit the conflict markers: Choose the desired changes from each branch and remove the markers.
Stage the resolved file: Use git add to stage the modified file with your chosen changes.
Commit the changes: Use git commit to create a new commit that incorporates the resolved merge conflict.
Here are some additional tips for resolving merge conflicts:

Communicate with other developers: If the conflict arises due to overlapping changes from different developers, discuss the conflict and collaborate to find the best solution.
Use a merge conflict resolution tool: Several visual tools can help you compare changes and resolve conflicts more easily.
Commit frequently: Smaller, more frequent commits can help isolate conflicts and make them easier to resolve.
