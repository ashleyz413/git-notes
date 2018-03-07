
# git-notes

These are notes from the Software Carpentry class on March 6th, 2018 by Chris Deboever on github

Create repository online and clone to local repository (dont use shared folder like Dropbox, etc):
git clone <link from github>

add or change files in repository, then sequence to commit:
git add -> tells git to track files in repository
git commit -m "notes" -> commits edits to files or new files with comments
git push -> syncs with github

combined add/commit for tracked files:
git commit -m "notes" myfile.txt

if stuck in VIM: 
:qw! (if super stuck!)

Note:
dont store large files in git, just the notes!  will take over git repo 

to ignore certain large data files in a repo, add them to:
<.gitignore> file 

This file should be in the parent repo folder


