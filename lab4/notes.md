Q1. --global means the Git setting applies to all repositories for my user account. If I leave it out, the setting applies only to the current repository.

Q2. ls -a shows a hidden .git directory that does not appear in a normal ls. It contains Git's internal data, including the repository's history, configuration, objects, and references.

Q3. Git lists the files and folders inside coding-cafe that are currently untracked. The exact number depends on the contents of my folder; entries inside .venv/ are generated third-party files rather than code I wrote.

Q4. After creating .gitignore, the files inside .venv/, __pycache__/, and matching .pyc and .DS_Store files disappeared from the untracked list. Git now knows to ignore those files.

Q5. Yes, .gitignore should be committed. It is part of the repository's configuration and tells Git which files should be ignored, so other people using the repository get the same rules.

Q6. README.md moved from Untracked files to Changes to be committed. In the three-places model, it moved from the working directory to the staging area after git add README.md.

Q7. Git printed information about the new commit, including its commit ID, branch, commit message, and a summary of the files changed. The exact number of changed files should be taken from my terminal output.

Q8. The first seven characters are the short form of the commit's hash, which identifies that commit. They make it easier to refer to a particular commit without typing the entire hash.

Q9. The four steps are edit, check the status or diff, stage the changes, and commit them. This cycle is repeated whenever I make a new logical change.

Q10. README.md has a special name because GitHub automatically displays it as the main documentation for the repository. It is normally placed in the repository's root directory so visitors can immediately see it.

Q11. gh auth login authenticates my GitHub account through GitHub CLI and stores authentication credentials. Git can then use those credentials when pushing, so I do not need to enter my GitHub password each time.

Q12. The GitHub front page shows README.md rendered as formatted text. GitHub does this automatically because README.md is conventionally used as the main introduction and documentation for a repository.

Q13. No, git push did not change my local commit history. It copied my existing local commits to the remote GitHub repository.

Q14. A private repository exists on GitHub but its contents are restricted to the owner and people who have been given access. If a repository does not exist on GitHub, there is no remote repository there to access or collaborate on.
