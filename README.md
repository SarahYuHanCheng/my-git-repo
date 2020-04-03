# Note

###### 4/2
* untracked file -- 沒有被版控的 file，因為專案會有許多 project files，所以 git 不會自動 track file，要自己 `git add` 
* staging -- creating a snapshot
* commiting -- record the snapshot in the repository

###### 4/3
* `git tag -a v1.0 -m"description"` `git show v1.0`可看到 description
* reset only operate on working directory, while revert undos in commited sanpshots
* `git clean -f` -- remove untracked files