# GIT COMMANDS
1. git init: Initializes a new Git repository in the current directory.
2. git clone <repository>: Clones a repository into a new directory.
3. git add <file>: Adds a file to the staging area.
4. git add .: Adds all changes in the working directory to the staging area.
5. git commit -m "message": Records changes to the repository with a descriptive message.
6. git commit -am "message": Adds and commits changes in one step.
7. git status: Displays the status of the working directory and staging area.
8. git diff: Shows the differences between the working directory and the staging area.
9. git diff --staged: Shows the differences between the staging area and the last commit.
10. git push: Pushes changes to a remote repository.
11. git push -u origin <branch>: Sets the upstream branch and pushes changes.
12. git pull: Fetches changes from a remote repository and merges them into the current branch.
13. git pull --rebase: Fetches changes and rebases the current branch onto the fetched branch.
14. git branch: Lists all branches in the repository.
15. git branch <branch>: Creates a new branch.
16. git branch -d <branch>: Deletes the specified branch.
17. git checkout <branch>: Switches to the specified branch.
18. git checkout -b <branch>: Creates a new branch and switches to it.
19. git merge <branch>: Merges the specified branch into the current branch.
20. git merge --abort: Aborts the current merge operation.
21. git rebase <branch>: Reapplies commits on top of another base tip.
22. git cherry-pick <commit>: Applies the changes introduced by the specified commit to the current branch.
23. git log: Displays the commit history.
24. git log --oneline: Displays the commit history in a condensed format.
25. git log --graph: Displays the commit history as a graph.
26. git tag <tag_name>: Creates a lightweight tag at the current commit.
27. git tag -a <tag_name> -m "message": Creates an annotated tag with a message.
28. git fetch: Fetches changes from a remote repository.
29. git fetch --all: Fetches changes from all remotes.
30. git remote: Lists remote repositories.
31. git remote -v: Lists remote repositories along with their URLs.
32. git remote add <name> <url>: Adds a new remote repository.
33. git remote remove <name>: Removes the specified remote repository.
34. git remote set-url <name> <new_url>: Changes the URL of the specified remote.
35. git config --global user.name "Your Name": Sets the global username for Git.
36. git config --global user.email "your.email@example.com": Sets the global email address for Git.
37. git reset: Resets the current HEAD to a specified state.
38. git reset --hard: Resets the working directory and staging area to match the specified commit.
39. git reset --soft <commit>: Resets the HEAD to the specified commit without changing the working directory or staging area.
40. git revert <commit>: Reverts a commit by creating a new commit.
41. git stash: Stashes changes in the working directory for later use.
42. git stash list: Lists all stashed changes.
43. git stash apply: Applies the most recently stashed changes to the working directory.
44. git stash apply <stash>: Applies the specified stashed changes to the working directory.
45. git stash drop: Removes the most recently stashed changes.
46. git stash drop <stash>: Removes the specified stashed changes.
47. git clean -n: Shows a list of untracked files that would be removed by git clean -f.
48. git clean -f: Removes untracked files from the working directory.
49. git blame <file>: Displays the revision and author of each line in a file.
50. git bisect: Finds the commit that introduced a bug by performing a binary search.
51. git gc: Cleans up unnecessary files and optimizes the local repository.
52. git archive --format=zip --output=<zipfile> <branch>: Creates a zip archive of the specified branch.
53. git reflog: Records when the tips of branches and other references were updated in the local repository.
54. git help: Displays help information for Git commands.