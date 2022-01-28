# Assignment-Git-and-GitHub-week-2-
 
# 1-How do you see the files changed within each commit from git log?

You may use git log command to check the changes within the project. This command will display a list of the most recent commits. Git log -p command provides the same list but also shows whether a file have been added/modified/removed and  the actual changes within that commits. git log --raw command also shows the changes that was made.  In order to access a more simplified version of the changes of the commits one can use git log —oneline command. Git log —stat command provides a list of the commits with the relevant information of the commit but also the files that were involved in each of the commits. It is possible to view its pathways, as well as the relative changes, indicated by a + and - symbol, for content additions and deletions. There are many other variations of git log command, as well. 

# 2-How do you see the contents of what changed within each file from the git log?

git log --follow -p -- path-to-file command would list the entire changes made within a spesific file including its renamed versions.


# 3-What does HEAD refer to in the context of git?

When using Git, users can only check out one branch at a time, which is known as the "HEAD" branch. This branch is also described as the "active" or "current" branch. Git keeps track of the current branch in a file called.git/HEAD in the Git repository.

