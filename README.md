# Note

###### 4/2
* untracked file -- 沒有被版控的 file，因為專案會有許多 project files，所以 git 不會自動 track file，要自己 `git add` 
* staging -- creating a snapshot
* commiting -- record the snapshot in the repository

###### 4/3
* `git tag -a v1.0 -m"description"` `git show v1.0`可看到 description
* reset only operate on working directory, while revert undos in commited sanpshots
* `git clean -f` -- remove untracked files
---
* `git rm crazy.html` 直接 add the crazy.html deleted，再 `git add rainbow.html` 會自動變成 rename 狀態！

###### 4/4
* Branch
    1. Create a new branch for each major addition to your project.
    2. Don't create a branch if you can't give it a specific name.
* branch type
    1. topic(long-running) -- feature
    2. hotfix
    3. record the evolution of a project -- master
* Merge
    1. Fast-forwarding
    2. 3-way merge