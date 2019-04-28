# Git Command Reference

1. Always clone off master.
2. Create a development branch to work on changes. Merge all sub-branches into development branch, merge into master when complete (post beta testing).
3. Version control - a.b.c where a is a working release version/major update (ie alpha, beta), b is a feature update and c is a bug fix.
4. `git branch -a` (displays all branches)
5. `git branch -d <branchname>` (deletes branch)
6. `git checkout <branchname>` (switches current head)
7. `git add <file>` (update what will be commited)
8. `git commit <branch>` (commits branch locally)
9. `git push` (pushes current branch)
10. `git clone <repository link>` (clones repository)
11. `git checkout -b <newbranchname> <origin/branchtoclonefromremote>` (creates new branch locally called newbranch name which is a clone of the remote branch)
12. `git merge <otherbranch>` (merges current branch with otherbranch)
13. start <file> (opens file with default editor)
14. `git fetch` (alternative to git pull where it only dowloads the changes and commits from remote but does not merge anything conflicting)
15. `git rebase <otherbranch>` (changes the base of a branch to the HEAD of <otherbranch>)
