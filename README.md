# Wprawki z git

git add .
git commit -m "init"

git log

git show

git show @^^

## conflict

```
	<<<<<<< HEAD
	## conflict

=======
## konflikt 2 
>>>>>>> dadca9cb8a14c0fd89efcefbc18ddd21ec216493
```

<<<<<<< Updated upstream

## Jak uzywac git stash
=======
## niepewna zmiana
>>>>>>> Stashed changes

```
Karina@DESKTOP-1P1P0RJ MINGW64 ~/Desktop/projekty ALX/kurs_powtorkowy/wprawki_z_git (master)
$ git stash
Saved working directory and index state WIP on master: 5e46ece merger with origin master

Karina@DESKTOP-1P1P0RJ MINGW64 ~/Desktop/projekty ALX/kurs_powtorkowy/wprawki_z_git (master)
$ git pull origin master
From https://github.com/LukaszOziomek/k09042022_wprawki_git
 * branch            master     -> FETCH_HEAD
Updating 5e46ece..7a15730
Fast-forward
 README.md | 5 ++++-
 1 file changed, 4 insertions(+), 1 deletion(-)

Karina@DESKTOP-1P1P0RJ MINGW64 ~/Desktop/projekty ALX/kurs_powtorkowy/wprawki_z_git (master)
$ git stash
No local changes to save
g
Karina@DESKTOP-1P1P0RJ MINGW64 ~/Desktop/projekty ALX/kurs_powtorkowy/wprawki_z_git (master)
$ git stash pop
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
On branch master
Unmerged paths:
  (use "git restore --staged <file>..." to unstage)
  (use "git add <file>..." to mark resolution)
        both modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
The stash entry is kept in case you need it again.

Karina@DESKTOP-1P1P0RJ MINGW64 ~/Desktop/projekty ALX/kurs_powtorkowy/wprawki_z_git (master)
$ git status
On branch master
Unmerged paths:
  (use "git restore --staged <file>..." to unstage)
  (use "git add <file>..." to mark resolution)
        both modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

Karina@DESKTOP-1P1P0RJ MINGW64 ~/Desktop/projekty ALX/kurs_powtorkowy/wprawki_z_git (master)
$ git add .
```


## konflikt 2
