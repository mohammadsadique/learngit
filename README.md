I write these document according to my knowledge if you saw mistake please let me know. 

GIT DOCUMENT
Simpliest way to learn Git
Instaul Git Git Download After instaulling Git: left click on mouse and you saw two option Git GUI Here Git Bash Here. click on `Git Bash Here` to open terminal and check version of Git.

View online document: Click this link
https://celisoftware.github.io/learngit/


USE THESE COMMAND:

Check Git Version
git --version

Add Your Name
git config user.name `yourname` ( Specific Project )
git config --global user.name `yourname` ( Every Project )

Add Your Email
git config user.email `example@example.com` ( Specific Project )
git config --global user.email `example@example.com` ( Every Project )

Initialize git
git init

Untracked File
git status

Staged Area
git add index.html (For Single Page)
git add -A (For all pages)
Other Ways
git add . (Staged new and modified files without deleting files)
git add -u (Staged modified and delete files without new files)

Commit Files
git commit
It open screen for type comment using i button on keyboard
For exit from open screen press Esc + : + w + q and enter
Esc : w q , Esc : W Q both work.

git commit -m "Write message here"
git commit -a -m "Write message here"

Status
git status
If all goes fine it says: nothing to commit, working tree clean


