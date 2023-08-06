1. `git --version`                                 : Git's version
2. `git config --global user.name "Mona Lisa"`     : To Add userName
3. `git config --global user.name`                 : TO Check Name 
4. `git config --global user.email "YOUR_EMAIL"`   : To Add userEmail
5. `git config --global user.email`                : TO Check Email
6. `git config --list`                            : To check basic credentials

7. `git add .`  ->  `git commit -m "message"` ->  `git push -u origin master`  : To upload files on github using git.

8. `cd "path/toOpen/Repository"`
9. `mkdir "folderName"`                  : To Create Folder
10. `touch "testFile.extension"`         : To Create any File
11. `cat "testFile.txt"`                 : To Read content of File
12. `ls`                                 : To List down all the Files & Folders
13. `git init`                           : To initialise a git repository in that folder.
14. `rm -rf .git`                        : To Abort git repository, and remove access of git over this folder
15. `git add "fileName.ext"`             : To move file from working area to staged area
16. `git rm --cached "FileName"`         : To move file from staged area to working area
17. `git commit`                         : To Commit
18. `git commit` -> `i`                    : To enter commit message 
19. `git commit` -> `{"Esc + : " + wq}`    : To exit Vim
20. `git log`                            : List downs all the commits of the repository. If you want to exit out of git log prompt press q.
21. `git restore "fileName"`             : It removes all files changes from the staging area to be committed. 
22. `git restore --staged "fileName"`    : To restore back to previous committed versions, if current changes are staged. Brings that file back to Working Area.
23. `git remote add <name of remote> <link of the remote>` : To link GitHub Repo and Git Repo
24. `git remote add origin git@github.com:djWhoCodes-DJ/Second_Repo.git`
25. `git remote rm <name of remote>`     : This command deletes a remote connection
26. `git remote rename <oldName> <newname>` : This command renames the remote connection
27. `git pull <remote name> <branch name>` : Downloads latest changes from the branch of the mentioned remote in your local repo.
28. `git push -u origin master`           : To push git initialised repo on github
