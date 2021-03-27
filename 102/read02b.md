version control: its a system allows to revisit various version of file or set file and there is more than one type of it:

-Local Version Control: it entails one database on your hard disk that stores changes to files.
-Centralized Version Control: it entails a single server storing all changes and file versions, which can be accessed by 
 various clients and its allow to programmer to know about the other.
-Distributed Version Control:allows clients to create mirrored repositories to make a back up for the original data.

Git properties: 
-Snapshots
-Local Operations
-Tracking Changes
-less Loss of Data

Files state in git:
-Committed
-Modified
-Staged

Installed ways of Git:
-install as a package
-install via another installer
-download and compile the source code.
for windows download we can download it from Git Website (http://git-scm.com/download/win) or GitHub (http://windows.github.com).

Initial Customization:
-Configuration of Variables by the tool (git config).
-Identity Setting by typing the following into terminal 
((git config --global user.name "Jane Smith")

 (git config --global user.email "example@email.com")).

Default Text Editor: to achive this we have to type the following in terminal($ git config --global core.editor emacs).

Check Settings by this command (git config --list).

we can getting help by the following commands:(git help command, git command --help, man git-command).

Setting up a Git Repository:
-Importing: 
1-Switch to the target project’s directory Example: $ cd test (cd = change directory)
2-Use the git init command $ git init.
3- o start tracking these repository files, perform an initial commit by typing the following: $ git add *.c, $ git add LICENSE, $ git commit -m “any message here”

Cloning: its mean creating acopy of an existing git repository by this command ($ git clone https://github.com/test) also to clone with another name we using 
this command ($ git clone https://github.com/test mydirectory).

Local Repository Structure:
-Working Directory: The actual files reside here.
-Index: The area used for staging.
-Head: Points to the most recent commit.

Saving Changes: the files in a project are tracked or untraced.

The Life Cycle of File Status:
-After you edit a file, Git flags it as modified because of changes made after the previous commit.
-You stage the modified file.
-Then, you commit staged changes.

we can checking the file statuse by this command ($ git status).

Tracking and Staging a New File:
-Single File: by (git add filename).
-All Files: by ($ git add *).

Committing a File: by ($ git commit -m “made change x,y,z”).
Committing All Changes: by ($ git commit -a).

Pushing Changes: by ($ git push origin master).
Stashing Changes:by (git stash) to continue we use (git stash apply).