# Devops-Note

## 1] Find 20 Top command of git ? 

-->  

1] git config :- This command sets the author name and email address respectively to be used with your commits.

        Usage: git config –global user.name “[name]”
        Usage: git config –global user.email “[email address]” 

2] git init :- This command is used to start a new repository.

        Usage: git init [repository name]

3] git clone :- This command is used to obtain a repository from an existing URL.

        Usage: git clone [url]  

4] git add :- This command adds a file to the staging area.

        Usage: git add [file]  
 This command adds one or more to the staging area.

        Usage: git add *  

5] git commit :- This command records or shapshots the file permanently in the version history.

        Usage: git commit -m “[ Type in the commit message]”
        
This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.

         Usage: git commit -a  

 6] git diff :- This command shows the file differences which are not yet staged.

         Usage: git diff  

This command shows the differences between the files in the staging area and the latest version present.

        Usage: git diff –staged 

This command shows the differences between the two branches mentioned.

        Usage: git diff [first branch] [second branch]  

7] git reset :- This command unstages the file, but it preserves the file contents.

        Usage: git reset [file]  

This command undoes all the commits after the specified commit and preserves the changes locally.

        Usage: git reset [commit]  
        
This command discards all history and goes back to the specified commit.

        Usage: git reset –hard [commit] 

8] git status :- This command list all the files that have to be committed.

        Usage: git status

9] git rm :- This command deletes the file from your working directory and stages the deletion.

        Usage: git rm [file]  

10] git log :- This command is used to list the version history for the current branch.

        Usage: git log  

This command lists version history for a file, including the renaming of files also.

        Usage: git log –follow[file]
        
11] git show :- This command shows the metadata and content changes of the specified commit.

        Usage: git show [commit] 

12] git tag :- This command is used to give tags to the specified commit. 

        Usage: git tag [commitID]  

13] git branch :- This command lists all the local branches in the current repository.

        Usage: git branch  
        
This command creates a new branch.

        Usage: git branch [branch name]  

This command deletes the feature branch.

        Usage: git branch -d [branch name]  

14] git checkout :- This command is used to switch from one branch to another.

        Usage: git checkout [branch name]
        
This command creates a new branch and also switches to it.
        
        Usage: git checkout -b [branch name]  
        
15] git merge :- This command merges the specified brach's history into the current branch.

        Usage: git merge [branch name]

16] git remote :- This command is used to connect your local repository to the remote server.

        Usage: git remote add [variable name] [Remote Server Link]

17] git push :- This command sends the committed changes of master branch to your remote repository.

        Usage: git push [variable name] master 

This command sends the branch commits to your remote repository.

        Usage: git push [variable name] [branch]

This command pushes all branches to your remote repository.

        Usage: git push –all [variable name]  

This command deletes a branch on your remote repository.

        Usage: git push [variable name] :[branch name]  

18] git pull :- This command fetches and merges changes on the remote server to your working directory. 

        Usage: git pull [Repository Link]  

19] git stash :- This command temporarily stores all the modified tracked files.

        Usage: git stash save  

This command restores the most recently stashed files.

        Usage: git stash pop  

This command lists all stashed changesets.

        Usage: git stash list

This command discards the most recently stashed changeset.

        Usage: git stash drop        
        
## 2] Difference between Git Fetch and Git pull and Git clone ?

--> 

1] Git Fetch :-

1. Used to fetch all changes from the remote repository to the local repository without merging into the current working directory.
2. Repository data is updated in the .git directory.
3. Review of commits and changes can be done.
4. No possibility of merge conflicts.
5. Command for Git fetch is git fetch<remote>
6. Git fetch basically imports the commits to local branches so as to keep up-to-date that what everybody is working on.

2] Git pull :- 

1. Brings the copy of all the changes from a remote repository and mergens them into the current working directory.
2. The working directory is updated directly.
3. updates the changes to the local repository immediately.
4. Merge conflicts are possible if the remote and the local repositories have dodne chages at the same place.
5. Command for Git Pull is git pull <remote><branch>.
6. Git Pull basically brings the local branch up-to-date with the remote copy that will also updates the other remote tracking braches.

3] Git clone :-









## 3] Difference between revert and restore ?

--> 

1] Revert :- 





        
        











        


  
