1) git init - initialise local repo.
2) git status - check which files are not tracked/ are not in the staging area ( will not be committed)
3) git add <filename> - add file/s to staging area (will commit them)
4) git restore --staged <file> - to unstage
5) git commit -m <messege> - commits staged files with a messege
6) git log - shows commits made to repo
7) git add . - adds all files in directory to staging area
8) git diff <filename> - shows difference between working directory and commited file
9) git checkout <filename> - rollback to last committed version (head)
10) git remote add origin <url> - add remote repo at url
11) git push -u <remote name - origin> <branch name - main>
12) git rm --cached -r . - removes all files from staged

13) git clone <url> . - clones a remote repo onto local repo
