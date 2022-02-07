## Setup

- set a name that is identifiable for credit when review version history    

```
git config --global user.name “[firstname lastname]”  
```

- set an email address that will be associated with each history marker  
  
  ```
  git config --global user.email “[valid-email]”
  ```

## Init

- initialize an existing directory as a Git repository  
  
  ```
  git init
  ```

- retrieve an entire repository from a hosted location via URL

```
git clone [url] 
```

## Stage & Snapshot

- show modified files in working directory, staged for your next commit
  
  ```
  git status  
  ```

- add a file as it looks now to your next commit (stage)  
  
  ```
  git add [file]  
  ```

- unstage a file while retaining the changes in working directory  
  
  ```
  git reset [file]  
  ```

- diff of what is changed but not staged  
  
  ```
  git diff  
  ```

- diff of what is staged but not yet committed  
  
  ```
  git diff --staged  
  ```

- commit your staged content as a new commit snapshot
  
  ```
  git commit -m “[descriptive message]”  
  ```

## Branch & Merge

- list your branches. a * will appear next to the currently active branch  
  
  ```
  git branch  
  ```

- create a new branch at the current commit  
  
  ```
  git branch [branch-name]  
  ```

- switch to another branch and check it out into your working directory  
  
  ```
  git checkout  
  ```

- merge the specified branch’s history into the current one  
  
  ```
  git merge [branch]  
  ```

- show all commits in the current branch’s history
  
  ```
  git log  
  ```
