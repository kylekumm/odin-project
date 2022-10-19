# Git Cheatsheet
<b>Commands related to remote repo:</b><br>
git clone git@github.com:USER-NAME/REPOSITORY-NAME.git --> clones repo from GitHub <br>
git push --> pushes from local to GitHub <br>
<b>Workflow commands:</b> <br>
git add .  --> adds changes to local staging area (period indicates all files with changes made) <br>
git commit --> commits local changes to staging (will open new tab to add commit message) <br>
git commit -m "A message describing what you have done to make this snapshot different" --> same as normal commit but message flag included <br>
<b>Commands to check status or log history:</b><br>
git status --> view status of repo (staging, commits,outstanding files etc) <br>
git log --> view history of previous commits <br>
<br>
<b>Basic Git syntax is program | action | destination</b><br>
<b>Config commands:</b><br>
git config --global core.editor "code --wait" --> opens a new tab to add a commit message when -m flag is left out of commit command