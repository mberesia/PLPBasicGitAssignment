# PLPBasicGitAssignment
$ cd Downloads

~/Downloads (master)
$ cd PLPBasicGitAssignment

~/Downloads/PLPBasicGitAssignment (master)
$ git status

~/Downloads/PLPBasicGitAssignment (master)
$ git add README.md
git commit -m "create README.md"

~/Downloads/PLPBasicGitAssignment (master)
$ git status
On branch master
nothing to commit, working tree clean

~/Downloads/PLPBasicGitAssignment (master)
$ git remote add origin https://github.com/mberesia/PLPBasicGitAssignment.git

~/Downloads/PLPBasicGitAssignment (master)
$ git push -u origin (master)

~/Downloads/PLPBasicGitAssignment (master)
$ touch hello.txt

~/Downloads/PLPBasicGitAssignment (master)
$ nano hello.txt

~/Downloads/PLPBasicGitAssignment (master)
$ git commit -m " Add hello.txt with a greeting"

~/Downloads/PLPBasicGitAssignment (master)
$ git add hello.txt
warning: in the working copy of 'hello.txt', LF will be replaced by CRLF the next time Git touches it

~/Downloads/PLPBasicGitAssignment (master)
$ git commit -m "Add hello.txt with a greting"


~/Downloads/PLPBasicGitAssignment (master)
$ git push -u origin master
