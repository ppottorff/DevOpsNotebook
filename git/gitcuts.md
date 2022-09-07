## Squash commits, clean up history. 
1. Create an alias you can use across repos: git config --global alias.squash-commits '!f(){ git reset $(git commit-tree HEAD^{tree} -m "${1:-New Beginning}");};f'
2. Switch to a repo, use it: git squash-commits
3. Push it to origin: git push -f
4. Delete local copies of repos, pull a fresh copy.
