# CS216 Final Project
Final project for the Spring 2023 CS216 class

# Git stuff
Cloning the remote repo:
    - Cd to desired directory
    - Copy the HTTPS link using the green "Code" button
    - type this into terminal: git clone (link you just copied)

Committing changes
    - checking general status of git stuff: git status
    - cd to the directory your local repo is in
        - for example, cd Desktop/cs_216project/
    - Add the file you modified: git add filename.ipynb
    - Commit changes: git commit -m "a message saying what you did"
    - Push changes to remote: git push

Pulling existing changes
    - Pull: git pull
    - IMPORTANT: DO THIS REGULARLY: When multiple changes have occurred since you have committed, it is best to do the following to get all remote changes: (two commands, one after the other)
        - git fetch origin 
        - git reset --hard origin/main
    - AGAIN IMPORTANT: the above 2 commands RESET ALL LOCAL CHANGES. Do not use this if you have existing changes that need to be pushed. To avoid overwriting existing changes, save your changes (could be elsewhere or just in a separate file), pull or fetch remote changes, put YOUR local changes back AFTER you've pulled, THEN push.