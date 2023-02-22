## drop commit

- Step 1 : Create a new branch, add some files and commit changes. \
![create branch](drop-commit-ss/17.png) \
After the commits made, the history is as follow:
![history](drop-commit-ss/18.png)

- Step 2 : Drop the commit using `git reset --hard HEAD^` command. The history displays thats the commit has been dropped: \
![drop commit](drop-commit-ss/19.png)