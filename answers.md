ANSWER 1
git version 2.31.1.windows.1

ANSWER 2 
the command shows me the username, email and core editor (VS code) i had set in the last 3 lines
user.name=Chinonso Ugwumadu
user.email=cu884120@ohio.edu
core.editor="C:\Users\ugwum\AppData\Local\Programs\Microsoft VS Code\Code.exe" --wait

ANSWER 3 
git add --help took me to a webpage with info on add, while git --help gave me a list of commands and flags git uses.

ANSWER 4
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .README.md.un~
        .answers.md.un~
        README.md
        README.md~
        answers.md

ANSWER 5

On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .README.md.un~
        .answers.md.un~
        README.md~
        answers.md
here i noticed that a new file was recorded as ReadME.md but not commited yet.

ANSWER 6

On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .README.md.un~
        .answers.md.un~
        README.md~

    answer.md is recorded as new file as wellbut not commited yet

ANSWER 7

AFTER git commit -m 'Initial commit"

[master (root-commit) f0ab4ad] Initial commit
 2 files changed, 11 insertions(+)
 create mode 100644 README.md
 create mode 100644 answers.md

 AFTER git status

 On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .README.md.un~
        .answers.md.un~
        README.md~

nothing added to commit but untracked files present (use "git add" to track)

ANSWER 8

commit f0ab4ad03eb3b38a0a1f242c18fa946db34e82cf (HEAD -> master)
Author: Chinonso Ugwumadu <cu884120@ohio.edu>
Date:   Wed May 12 10:24:42 2021 -0400

    Initial commit

ANSWER 9

On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   answers.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .README.md.un~
        .answers.md.un~
        README.md~

no changes added to commit (use "git add" and/or "git commit -a")

ANSWER 10
No change recorded on README.md

ANSWER 11
An error occured 

To https://github.com/49n3r/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/49n3r/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.


ANSWER 12::
the class infomation has been updated on my local machine

ANSWER 13::

USING gci
Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         5/12/2021  11:17 AM            302 .gitignore
-a----         5/12/2021  11:17 AM             11 README.md

USING ls -hidden
Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d--h--         5/12/2021  11:17 AM                .git
